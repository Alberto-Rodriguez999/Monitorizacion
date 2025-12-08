# Tráfico de red  ![Monitorizacion | Ud3](https://img.shields.io/badge/Monitorizacion-Ud2-brightgreen?style=flat&labelColor=brightgreen&color=white)

## 🛠️Comando 1: Analizador de paquetes CLI que captura tráfico en modo promiscuo, permitiendo la inspección profunda de cabeceras y payloads para auditoría de red y troubleshooting.
```bash
sudo tcdump
```
![Captura 1](./img/captura1.png)

---

## 🛠️Comando 2: Sniffer pasivo que monitoriza el estado de las sesiones TCP en una interfaz, desglosando el ancho de banda por conexión individual.
```bash
tcptrack -i [TARJETA_DE_RED]
```
![Captura 2](./img/captura2-tcptrack_-i_tarjeta_de_red.png)

---

## 🛠️Comando 3: Utilidad basada en la librería ncurses que genera estadísticas granulares de tráfico IP/TCP/UDP en tiempo real, incluyendo conteo de bytes y flag de paquetes.
```bash
iptraf
```
![Captura 3](./img/captura3iptraf.png)

---

## 🛠️Comando 4: Monitor de ancho de banda y estimador de tasas de transferencia que visualiza la carga y saturación de las interfaces mediante gráficos ASCII y estadísticas de capa 2.
```bash
bmon
```
![Captura 4](./img/captura4bmon.png)

---

[![VOLVER](https://img.shields.io/badge/VOLVER-lightgrey?style=for-the-badge)](../)
