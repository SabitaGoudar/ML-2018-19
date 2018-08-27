1. Goto the directory where you have downloaded Anaconda3-5.2.0-Linux-x86_64.sh 
2. run the following command
    $bash Anaconda3-5.2.0-Linux-x86_64.sh
3. Set the path on terminal 
    $export PATH="/home/ise/anaconda3/bin:$PATH"
4. Create environment for TensorFlow
    $conda create -n tensorflow
5. Activate the tensorflow
    $source activate tensorflow
6. Install the TensorFlow
    $pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.8.0-cp36-cp36m-linux_x86_64.whl
7. Open the jupyter notebook
    $jupyter notebook
	

