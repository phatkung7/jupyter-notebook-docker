# jupyter-notebook-docker
Use Jupyter Notebook On docker
<ol>
<li>1.Clone This Repo</li>
<li>2.Run : docker compose up -d</li>
<li>3.Run : docker ps and Select CONTAINER_ID</li>
<li>4.Run : dokcer exec -it CONTAINER_ID bash</li>
<li>5.Run :jupyter server list</li>
<li>6.Copy : Result at 5. on word ?token=[here] and input your token</li>
<li>7.Enjoy !!!</li>
</ol>

How to Install Package
1.Run : docker ps and Select CONTAINER_ID
2.Run : dokcer exec -it CONTAINER_ID bash
3.Run : pip install package_name


Ref : [link](https://jupyter-server.readthedocs.io/en/latest/operators/public-server.html)
