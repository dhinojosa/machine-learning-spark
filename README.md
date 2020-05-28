# Machine Learning Using Spark

This repository contains the samples for my presentation on Machine Learning Using Spark

## What is included in this repository?

* Zeppelin Notebooks of the Samples
* Slides

## How do I run the examples?

```sh
docker run -p 8080:8080 --rm -v $PWD/logs:/logs -v $PWD/notebook:/notebook -v $PWD/data:/data -e ZEPPELIN_LOG_DIR='/logs' -e ZEPPELIN_NOTEBOOK_DIR='/notebook' --name zeppelin apache/zeppelin:0.8.1
```


