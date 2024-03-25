# Keras practice

### 1. Keras installation

* Clean up conda env

  ```shell
  conda config --set channel_priority flexible
  conda config --remove channels conda-forge
  conda config --add channels conda-forge
  conda update conda
  ```

  

* Tensorflow and keras installation

  ```shell
  conda install -c conda-forge tensorflow-gpu
  pip install --upgrade keras-cv
  pip install --upgrade keras-nlp
  pip install --upgrade keras
  ```

  

* Cuda libs installation

  * <= tensorflow 2.15 

    ```shell 
    conda install -c conda-forge cudatookit # nvidia driver and API for gpu programming
    conda install -c conda-forge cuDNN  
    ```

    

  * \>tensorflow 2.15

    ```shell 
    conda install -c conda-forge tensorflow-gpu
    pip install --upgrade keras-cv
    pip install --upgrade keras-nlp
    pip install --upgrade keras
    ```

    

### 2. Keras and tensorflow

`Earlier version of tensorflow 2, up continue 2.15 uses keras 2, tensorflow 2.16 starts to use keras 3 as the default configuration. Latest keras which was starting from keras-core, now the keras version III becoming the universal high-level machine learning API, it is available for JAX, Tensorflow, and PyTorch at the same time. `



### 3. Jupyter-notebook, ipython installation

* Download and install anaconda

  * On windows, run the executable file direclty. 
  * On Linux, run the `Anaconda.sh`

* Configure the environment variables

  ```shell
  cd ~
  vim .bashrc
  export PATH=~/anaconda/bin:$PATH
  ```

* Create conda env

  ```shell
  conda create --name env_name
  conda activate env_name
  ```

* Jupyter-notebook installation

  ```shell
  conda install -c anaconda jupyter nbconvert
  ```

* Install Jax, Tensorflow, or PyTorch, and keras

* update and others

  ```shell
  pip install --upgrade --user nbconvert
  conda update conda
  conda update anaconda
  ```


### 4. Keras III all you need to know

https://www.kdnuggets.com/2023/07/keras-30-everything-need-know.html

