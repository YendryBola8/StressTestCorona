# StressTestCorona

Instalar python
#
sudo apt-get install python

Instalar pip
#
sudo apt-get install python-pip

Si ya has instalado pip pero deseas actualizarlo a su última versión, deberás ejecutar lo siguiente:
#
sudo pip install -U pip

Para instalar locustio
#
sudo pip install locustio



Para ejecutar el archivo
#
locust -f locust_files/my_locust_file.py --host=http://example.com

abrir un navegador y apuntarlo a http://127.0.0.1:8089 (si está ejecutando Locust localmente)
