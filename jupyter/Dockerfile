FROM jupyter/scipy-notebook
COPY ./requirements.txt /home/jovyan/
WORKDIR /home/jovyan
RUN pip install -r requirements.txt
RUN pip install -U lyft_dataset_sdk
RUN jupyter labextension install @jupyterlab/plotly-extension