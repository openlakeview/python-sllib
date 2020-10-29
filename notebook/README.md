


# Windows PowerShell
```powershell
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD\notebook:/home/jovyan/work" -v "$PWD\sllib:/home/jovyan/work/sllib" jupyter/scipy-notebook

```