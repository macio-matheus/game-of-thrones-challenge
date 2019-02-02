
## Data Analysis Game Of Thrones, DataCamp
<p>This dataset constitutes a network and is given as a text file describing the <em>edges</em> between characters, with some attributes attached to each edge. Let's start by loading in the data for the first book <em>A Game of Thrones</em> and inspect it.</p>
<p><img src="https://s3.amazonaws.com/assets.datacamp.com/production/project_76/img/got_network.jpeg" style="width: 550px"></p>


### Usage
First of all, build the container using docker-compose and then you can 
access the Jupyter that is ready to be used.

#### Run with docker compose
```sh
cd game-of-thrones-challenge
docker-compose up -d
```

#### Accessing Jupyter
```sh
http://<your-ip>:8888/tree
```

#### Ports
```sh
    - 8888 => Jupyter
```

### DockerHub
```sh
https://hub.docker.com/r/maciomatheus/jupyter_notebook_data_science/
```