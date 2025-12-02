# Memoria, espacio y rendimiento de disco ![Monitorizacion | Ud2](https://img.shields.io/badge/Monitorizacion-Ud2-brightgreen?style=flat&labelColor=brightgreen&color=white)

## 🛠️Comandos 1: Muestran el estado de la memoria RAM y Swap: el comando a secas lo da en kilobytes, -h traduce las cifras a unidades legibles (MB/GB) y -s 3 actualiza los datos en pantalla cada 3 segundos.
```bash
free
```
```bash
free -h
```
```bash
free -s 3
```
![Captura 1](./img/captura1.png)

## 🛠️Comandos 2: Informan sobre el espacio disponible en las particiones montadas: -h usa unidades legibles, -hT añade la columna con el tipo de sistema de archivos (ext4, ntfs...) y -h / filtra para mostrar únicamente la información de la partición raíz.
```bash
df -h
```
```bash
df -hT
```
```bash
df -h /
```
![Captura 2](./img/captura2.png)

## 🛠️Comandos 3: Analizan el almacenamiento de forma distinta; du calcula el peso real del contenido de la carpeta, mientras que df muestra la capacidad y espacio libre de la partición del disco donde residen esos archivos.
```bash
du -h /home
```
```bash
df -h /home/*
```
![Captura 3](./img/captura3.png)

## 🛠️Comando 4: Monitoriza el rendimiento de entrada/salida del disco indicado con estadísticas extendidas (-x), refrescando la información cada 5 segundos
```bash
iostat -x nombre_disco 5
```
![Captura 4](./img/captura4.png)

[![VOLVER](https://img.shields.io/badge/VOLVER-lightgrey?style=for-the-badge)](../)









