# jupyter-notebook-docker
Use Jupyter Notebook On docker
<ol>
<li>Clone This Repo</li>
<li>Run : docker compose up -d</li>
<li>Run : docker ps and Select CONTAINER_ID</li>
<li>Run : dokcer exec -it CONTAINER_ID bash</li>
<li>Run :jupyter server list</li>
<li>Copy : Result at 5. on word ?token=[here] and input your token</li>
<li>Enjoy !!!</li>
</ol>

How to Install Package
<ol>
<li>Run : docker ps and Select CONTAINER_ID</li>
<li>Run : dokcer exec -it CONTAINER_ID bash</li>
<li>Run : pip install package_name</li>
</ol>

Ref : [link](https://jupyter-server.readthedocs.io/en/latest/operators/public-server.html)
