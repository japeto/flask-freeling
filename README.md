# FLASK-Freeling
Esta aplicación utiliza Freeling para realizar el analisis morfologico para español.

## Getting Started
Para ejecutar es necesario tener instalado freeling (3.1) y el wraper para python, y ejecutarlos con la instrucción.

```{r, engine='bash', count_lines}
pip install flask
python application.py
```
El ambiente Freeling, junto con este codigo se encuentra en el docker 

```{r, engine='bash', count_lines}
docker run -it --name fmweb -p 8000:8000 japeto/freeling-morpho-web /bin/bash
cd ~/flask-freeling
python application.py
```

Ver la ejecución en http://localhost:8000/

## Dependencias
[FreeLing web page](http://nlp.cs.upc.edu/freeling) 
[FreeLing repo](https://github.com/TALP-UPC/FreeLing) 



