# Desafío Wireshark
---

https://elearning.securityblue.team/home/courses/free-courses/introduction-to-network-analysis#content#analysis-with-wireshark#introduction-to-wireshark#activity-wireshark-challenge

---
En esta actividad, pondrás a prueba tus nuevos conocimientos de Wireshark analizando dos PCAP, cuya dificultad aumenta. Podrás completar ambos desafíos utilizando los conocimientos adquiridos en las lecciones anteriores del curso.

Preguntas sobre la actividad de Wireshark
 
---

PCAP 1
¿Qué protocolo se utilizó en el puerto 3942?
¿Cuál es la dirección IP del host al que se le hizo ping dos veces?
¿Cuántos paquetes de respuesta de consulta DNS fueron capturados?
¿Cuál es la dirección IP del host que envió la mayor cantidad de bytes?

---

PCAP 2
¿Cuál es la contraseña de WebAdmin?
¿Cuál es el número de versión del servidor FTP del atacante?
¿Qué puerto se utilizó para obtener acceso al host Windows de la víctima?
¿Cuál es el nombre de un archivo confidencial en el host de Windows?
¿Cuál es el nombre del archivo de registro que se creó a las 4:51 a. m. en el host de Windows?

---

## PCAP 1 – Pregunta 1  
**Protocolo en puerto 3942:** SSDP  
[![A‑1](Imagenes/A1.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A1.jpg)

---

## PCAP 1 – Pregunta 2  
**Host ping‑eado dos veces:** 8.8.4.4  
[![A‑2](Imagenes/A2.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A2.jpg)

---

## PCAP 1 – Pregunta 3  
**Respuestas DNS capturadas:** 90 paquetes  
[![A‑3](Imagenes/A3.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A3.jpg)  
[![A‑4](Imagenes/A4.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A4.jpg)

---

## PCAP 1 – Pregunta 4  
**IP con mayor volumen de bytes:** 115.178.9.18  
[![A‑5](Imagenes/A5.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A5.jpg)

---

## PCAP 2 – Pregunta 1  
**Contraseña de WebAdmin:** sbt123  
[![A‑6](Imagenes/A6.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A6.jpg)  
[![A‑7](Imagenes/A7.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A7.jpg)  
[![A‑8](Imagenes/A8.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A8.jpg)

---

## PCAP 2 – Pregunta 2  
**Versión del servidor FTP (atacante):** pyftpdlib 1.5.5  
[![A‑9](Imagenes/A9.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A9.jpg)

---

## PCAP 2 – Pregunta 3  
**Puerto usado para acceder al host Win:** 8081  
[![A‑10](Imagenes/A10.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A10.jpg)

---

## PCAP 2 – Pregunta 4  
**Archivo confidencial extraído:** Información_del_empleado_CONFIDENCIAL.txt  
[![A‑11](Imagenes/A11.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A11.jpg)

---

## PCAP 2 – Pregunta 5  
**Archivo log creado 04:51 AM:** LogFile.log  
[![A‑12](Imagenes/A12.jpg)](https://raw.githubusercontent.com/nicosotomayor/Wireshark-Challenge/main/Imagenes/A12.jpg)
