# w266_project
Project for W266 Fall 2017

Requirements:
Docker (preferably nvidia-docker if on PC with Nvidia GPU)        


Experiment Setup          

1. git clone https://github.com/stp8954/w266_project.git

2. sudo nvidia-docker run -d -p 6006:6006 -p 8888:8888 -v /<localdir>/w266_project:/notebooks/sharedfolder -e PASSWORD=password --name tensorflow tensorflow/tensorflow:latest-gpu-py3
3. Open https://localcalhost:8888 on web browser         
4. Login with password "password"        
5. Create a new notebook        
6. Run following to install additional packages
!pip install python-Levenshtein
!pip install fuzzywuzzy
!pip install tqdm
!pip install pyemd
!pip install h5py
!pip install graphviz


