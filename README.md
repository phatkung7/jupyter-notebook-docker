# jupyter-notebook-docker
Use Jupyter Notebook On docker
<ol>
<li>Clone This Repo</li>
<li>Run : docker compose up -d (Location in docker-compose.yml)</li>
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

Ref : [Running a public Jupyter Server](https://jupyter-server.readthedocs.io/en/latest/operators/public-server.html) \
Ref : [How to Run Jupyter Notebook on Docker](https://towardsdatascience.com/how-to-run-jupyter-notebook-on-docker-7c9748ed209f)
