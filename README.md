# Spark Capstone Project

### Generate dataset

```
pip install -r bigdata-input-generator/requirements.txt
python bigdata-input-generator/main.py
```

### Run Spark locally in Docker

`PATH_TO_DIR` – full path to this directory (commands differ on Linux and Windows, so just put it manually)

```
docker run -it --rm -p 8888:8888 -v PATH_TO_DIR:/home/jovyan/work jupyter/pyspark-notebook
```

Open the link with token from command line and run `work/capstone_project.ipynb` there.