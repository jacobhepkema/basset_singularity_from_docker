Bootstrap: docker
From: lzamparo/basset

%help
    lzamparo's basset docker image
  
%labels
    Maintainer @jacobhepkema
    Version v0.1

# To allow for access 
%post
    apt-get update && apt-get install -y pip
    pip install h5py
    chmod -R 777 /root
    chmod -R 777 /opt
    chmod -R 777 /usr
