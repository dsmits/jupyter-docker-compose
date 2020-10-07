# jupyter-docker-compose
A simple template for running jupyter notebook in a docker-container.

Apart from running the `jupyter/minimal-notebook` notebook image it will make sure the dependencies from
 `requirements.txt` are installed.
 
 ## How to use
 Make sure the required dependencies are in `requirements.txt`.
 Then open a terminal and run:
 ```bash
docker-compose up 
```

After the requirements are installed the jupyter server will be started. When ready it will provide you the url to
 the notebook webinterface.