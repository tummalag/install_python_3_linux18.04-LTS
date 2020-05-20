# install_python_3_linux18.04-LTS

This tutorial is for installing python3 using pip  in Linux 18.04 LTS

This is for the system without python, pip installed

Initially, system should be updated

    sudo apt update
    
if there are any upgrades pending they also need to be upgraded with the following command

    sudo apt upgrade
    
Once the system is upto date, its time to install all the dependencies that are used to build python modules

    sudo apt install python3-pip
    
Then, its time to check the version

    pip3 --version
    
output
    pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)
    
    
To upgrade pip

        pip3 install --upgrade pip


## pip module names

In general, to install any module you just need to know the module name (exceptions apply), here we will discuss the genreal syntax of the pip install command

        pip3 install <module>
        
Few examples are here

Open CV
        pip3 install opencv-python
        
Pandas
        pip3 install pandas
        
Tensor Flow
        pip3 install tensorflow
        
        
        
       

