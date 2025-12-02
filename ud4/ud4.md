# Red y servicios ![Monitorizacion | Ud4](https://img.shields.io/badge/Monitorizacion-Ud2-brightgreen?style=flat&labelColor=brightgreen&color=white)

## 🛠️Comando 1: Muestra las conexiones TCP activas usando direcciones numéricas, detallando qué proceso las usa y sus temporizadores internos.
```bash
ss -ntop
```
![Captura 1](./img/captura1.png)

---

## 🛠️Comando 2: Lista de forma simple las conexiones TCP establecidas con IPs numéricas y el proceso responsable, sin mostrar los temporizadores.
```bash
ss -tnp
```
![Captura 2](./img/captura2.png)

---

## 🛠️Comando 3: Consulta la base de datos pública para identificar al dueño de esa IP y sus datos de registro.
```bash
whois [IP]
```
![Captura 3](./img/captura3.png)

---

## 🛠️Comando 4: Comprueba rápidamente si ese equipo está encendido (ping scan) sin intentar escanear sus puertos.
```bash
nmap -sn [IP]
```
![Captura 4](./img/captura4.png)

---

## 🛠️Comando 5: Analiza los 100 puertos más comunes del objetivo para detectar qué servicios y versiones exactas están corriendo.
```bash
sudo nmap --top-ports 100 -sV [IP]
```
![Captura 5](./img/captura5.png)

---

## 🛠️Comando 6: Muestra la tabla actual que relaciona las direcciones IP de tu red con sus correspondientes direcciones físicas (MAC).
```bash
arp -a
```
![Captura 6](./img/captura6.png)

---

[![VOLVER](https://img.shields.io/badge/VOLVER-lightgrey?style=for-the-badge)](../)
