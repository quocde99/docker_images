### Docker command run 
#### docker build
docker build --tag depq-jupterlab .
#### docker run
docker run -d -p 8888:8888 -p 4040:4040 --name jupyter-lab -v $(pwd)/pyspark_jupiter:/home/jupyter depq-jupterlab
#### Spark jupiter
http://127.0.0.1:8888/
#### Spark UI
http://127.0.0.1:4040/