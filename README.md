# Launch-Jupyter-notebook-on-instance-Ubuntu
Install Python, pip, Jupyter Notebook on Ubuntu and create virtual environment 


- If the port 8888 was used: 
  - Check all running servers : jupyter notebook list
  - Find the path of runtime : jupyter --paths
  - Go to folder runtime and delete all files : rm -r path of runtime/*
  - reset the instance : sudo reset
  - Launch again jupyter: jupyter notebook --ip=0.0.0.0
  - Remark: useful commands [top | grep jupyter &] then [kill [PID]]
