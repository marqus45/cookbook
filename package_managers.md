# Enviroment management using conda and pip 
---
### Instalation of enviroment behind firewall

mkdir for project dependancies and make it current directory 
use package list or requirements file 

pip download ...

move it to server to separate folder  

on destination create enviroment for the the project
activate it
and install there pip 

```
conda create -n <enviroment_name>
source activate <enviroment_name>
conda install pip 
```

Then install packages usign pip 

```
pip install --find-links file:///home/... -no-index <top package list>  
```

### Using conda 
I was not sucessful to make it happen using only conda. 
This should be theoretically possible by combinining all files into one tar file 
this has not worked for me.

