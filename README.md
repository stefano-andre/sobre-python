# Sobre Python
Estos apuntes de Python fueron probados sobre Ubuntu 20.04 en una máquina virtual con 4 cores y 4 GB de RAM

## Antes de clonar

Actualizar:

```
sudo apt update
```

En caso no tenga instalado pipenv, lo puede instalar con el siguiente comando:

```
sudo apt install pipenv
```

Para probar el cuaderno de ctypes, requiere nasm y gcc:

```
sudo apt install gcc
sudo apt install nasm
```

## Luego de clonar

Dentro del directorio clonado, ejecute el siguiente comando para sincronizar las dependencias:

```
pipenv sync
```

Para activar el entorno:

```
pipenv shell
```

Por ejecutar el cuaderno de `jupyter`:

```
pipenv run jupyter notebook
```

Por salir del entorno de `pipenv`:

```
exit
```

Vista previa de los cuadernos:
  * [Apuntes de Python](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/python-general.ipynb)
  * [Apuntes de Numpy](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/numpy-general.ipynb)
  * [Apuntes de Pandas](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/pandas-general.ipynb)
  * [Apuntes de Matplotlib](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/matplotlib-general.ipynb)
  * [Apuntes de Time y Timeit](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/python-timing.ipynb)
  * [Apuntes de Ctypes](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/python-ctypes.ipynb)
      * [Optimizaciones de GCC](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/gcc-optis.ipynb)
  * [Problema de los N-cuerpos](https://nbviewer.jupyter.org/github/stefano-andre/sobre-python/blob/main/euler-nbprob.ipynb)
