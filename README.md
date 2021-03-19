# jupyter

`jupyter` is a docker container version of jupyter notebook.
1. Build the docker image with:
    ```bash
    docker build --tag jupyter:latest .
    ```
1. Run docker:
    ```bash
    docker run -it -p "8888:8888" --rm -v $PWD:/app jupyter
    ```


#docker run -p "8888:8888" -v "${PWD}:/home/jovyan/work" jupyter/minimal-notebook


# https://www.offerzen.com/blog/how-i-use-jupyter-notebooks-as-a-sandbox-for-building-visualisations