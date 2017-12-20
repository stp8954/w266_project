# w266_project
Project for W266 Fall 2017

Requirements:
Docker (preferably nvidia-docker if on PC with Nvidia GPU)        


Experiment Setup          

1. sudo nvidia-docker run -d -p 6006:6006 -p 8888:8888 -v /home/stp8954/github/w266_project:/notebooks/sharedfolder -e PASSWORD=password --name tensorflow tensorflow/tensorflow:latest-gpu-py3
2. Open https://localcalhost:8888 on web browser         
3. Login with password "password"        
4. Create a new notebook        
5. Run following to install additional packages
!pip install python-Levenshtein
!pip install fuzzywuzzy
!pip install tqdm
!pip install pyemd
!pip install h5py
!pip install graphviz


