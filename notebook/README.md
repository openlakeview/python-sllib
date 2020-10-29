


# Windows PowerShell
From the root of python-sllib run
```powershell
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes `
-v "${PWD}/notebook:/home/jovyan/work" `
-v "${PWD}/sllib:/home/jovyan/sllib" `
-v "${PWD}/tests/sample-data-lowrance:/home/jovyan/sample-data-lowrance" `
jupyter/scipy-notebook

```