#### To install fastai2(2020) in Anaconda (latest version), we can follow following instructions (in Ubuntu 18.04, may work with other linux kernels, can't guarantee that it will work).

**Creating a virtial conda enviroment by using conda:** <i> `conda create --name fastai2 `</i>

**Activating the virtial conda enviroment by using conda:** <i> `conda activate fastai2 `</i>

**Installing pytorch with cudatoolkit, either using conda:**
<i> `conda install pytorch torchvision cudatoolkit=10.2 -c pytorch ` </i>
**or using pip:**
<em>`pip install torch torchvision ` </em>

**Installing fastai2, either using conda:**
<em>`conda install -c fastai fastai `</em>
  
 **or using pip:** <em> ` pip install fastai `</em>
 
 **Installing jupyterlab using conda:** <i> `conda install -c conda-forge jupyterlab ` </i> 

**for more details, visit https://docs.fast.ai/**
