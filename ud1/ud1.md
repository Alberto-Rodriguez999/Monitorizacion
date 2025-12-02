# PROCESOS ![Monitorizacion | Ud1](https://img.shields.io/badge/Monitorizacion-Ud1-brightgreen?style=flat&labelColor=brightgreen&color=white)

## 🛠️Comando 1: Muestra procesos con formato extendido
```bash
ps au
```
![Captura 1](./img/captura1.png)

---

## 🛠️Comando 2: Muestra todos los procesos con detalles
```bash
ps aux
```
![Captura 2](./img/captura2.png)

---

## 🛠️Comando 3: Muestra procesos de un usuario específico
```bash
ps -u nombre_usuario
```
![Captura 3](./img/captura3.png)

---

## 🛠️Comando 4: Visualización interactiva de procesos
```bash
top
```
![Captura 4](./img/captura4.png)

---

## 🛠️Comando 5: Ejecuta top en modo batch y muestra 3 actualizaciones consecutivas de los procesos.
```bash
top -b -n 3
```
![Captura 5](./img/captura5.png)

---

## 🛠️Comando 6: Muestra un monitor interactivo de procesos con información en tiempo real.
```bash
htop
```
![Captura 6](./img/captura6.png)

---

## 🛠️Comando 7: Lista los 6 primeros procesos mostrando usuario, PID, uso de CPU y comando.
```bash
ps -eo user,pid,%cpu,comm | head -n 6
```
![Captura 7](./img/captura7.png)

---

## 🛠️Comandos 8: Genera carga artificial en la CPU lanzando dos procesos de alto consumo en segundo plano para monitorizar inmediatamente con atop cómo reacciona el sistema bajo estrés.
```bash
for i in {1..2};do yes > /dev/null & done
```
```bash
atop
```
![Captura 8](./img/captura8.png)

---

## 🛠️Comando extra: Fuerza la finalización inmediata y drástica del proceso con ese identificador (PID) usando permisos de administrador, sin permitirle guardar datos ni cerrarse correctamente.

```bash
sudo kill -9 [PID]
```

[![VOLVER](https://img.shields.io/badge/VOLVER-lightgrey?style=for-the-badge)](../)








