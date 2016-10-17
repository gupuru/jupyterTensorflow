# jupyterとTensorflowをいれたDockerfile

## 実行

```
docker run -itd --name jupyterTensorflow -p 8888:8888 -p 6006:6006 -v $HOME/data:/root/notebook -e PASSWORD=password gupuru/jupyter_tensorflow:1.0.0
```
