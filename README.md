# Pyspark playground

Start up pyspark playground to create and modify parquet and csv files with the power of spark.

```
docker run -it --rm --name pyspark-lab -p 8888:8888 -p 4044:4040 --mount type=bind,source="$(pwd)",target="/home/jovyan/" jupyter/pyspark-notebook
```
- Current PWD will be mounted and the working directory for the jupyter notebook
- Link to jupyter notebook will be shown in the terminal.
- `notebook.ipynb` is a starting point with some basic examples to read/write and transform
- Execute single cells with shift-enter (so just pick what you need)
- Access spark UI on (http://127.0.0.1:4044)
- Shutdown with ctrl-c