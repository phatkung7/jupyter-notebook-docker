# jupyter-notebook-docker
Use Jupyter Notebook On docker
1.Clone This Repo
2.Run : docker compose up -d
3.Run : docker ps and Select CONTAINER_ID
4.Run : dokcer exec -it CONTAINER_ID bash
5.Run :jupyter server list
6.Copy : Result at 5. on word ?token=[here] and input your token 
7.Enjoy !!!

How to Install Package
1.Run : docker ps and Select CONTAINER_ID
2.Run : dokcer exec -it CONTAINER_ID bash
3.Run : pip install package_name


Ref : [link](https://jupyter-server.readthedocs.io/en/latest/operators/public-server.html)
