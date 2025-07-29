# HACKIN ETICO
##T1_Reconocimiento Activo

Manejo de Wireshark para visualizar

Comandos utilizados para la practica:
* sudo nmap.sn
* sudo smap -sS -p1-
* sudo nmap -sS -p-



<img width="921" height="383" alt="image" src="https://github.com/user-attachments/assets/284a3605-3cc0-41c3-8f40-320b3f68b2c6" />

* El trafico de SYN enviado a multiples direcciones IPs del mismo segmento.
<img width="1542" height="736" alt="Captura de pantalla 2025-07-03 121806" src="https://github.com/user-attachments/assets/dbab64fa-7ba8-4446-a425-d179b9d5ecf5" />

  
* Respuestas SYN-ACK desde hosts activos
  <img width="921" height="236" alt="image" src="https://github.com/user-attachments/assets/c630f728-f448-4fec-9910-c2cf2c90dfc9" />

* Trafico ICMP usando el scan
  <img width="921" height="319" alt="image" src="https://github.com/user-attachments/assets/069717a6-41b2-4c65-b310-07b3f0ea65e8" />

  
* Escaneos dirigidos a multiples puertos hosts.
  <img width="921" height="319" alt="image" src="https://github.com/user-attachments/assets/35f5b041-5ac9-4bef-86de-944f2f82b58e" />



##T2_ Escaneo de host en la misma red.

Escoge un host dentro de tu red y realiza un escaneo que utilice técnicas de evasión para evitar su detección por firewalls o sistemas de monitoreo. Evalúa si lograste obtener información sin generar tráfico evidente. 

En Wireshark deberían ver: 
•	Tráfico con fragmentación de paquetes TCP/IP. 
•	Uso de un puerto fuente no estándar (ej. 53, 123). 
•	Intervalos largos entre los paquetes (bajo volumen). 
•	Tráfico que no completa handshakes TCP. 



<img width="1476" height="677" alt="Captura de pantalla 2025-07-08 002258" src="https://github.com/user-attachments/assets/0d17d7f1-d87a-48ee-8fdf-8359b8d1a44a" />

<img width="1473" height="498" alt="Captura de pantalla 2025-07-08 003156" src="https://github.com/user-attachments/assets/d9eb6312-7a4d-47da-89a0-ca0cb3fa3a5d" />



##T3_ Enumeracion avanzada de servicios

Identifica un host dentro de tu red que tenga servicios web, FTP, o SSH, y utiliza técnicas avanzadas para obtener información detallada de esos servicios (como banners, versiones, métodos HTTP, etc.). 
En Wireshark deberían ver: 
•	Solicitudes hacia puertos 21, 22, 80, 443, u otros comunes. 

<img width="1452" height="580" alt="Captura de pantalla 2025-07-08 011142" src="https://github.com/user-attachments/assets/a8d5db18-0537-496c-ba11-51fbc580858c" />


<img width="1472" height="521" alt="Captura de pantalla 2025-07-08 011505" src="https://github.com/user-attachments/assets/69932d9c-a412-44b8-8dd1-d372144516f8" />

##T4_Detección de hosts sin ICMP habilitado 
Encuentra dentro de tu red aquellos hosts que no responden a ping (ICMP), pero que tienen puertos abiertos accesibles. Analiza si puedes detectarlos sin depender de ICMP. 
En Wireshark deberían ver: 
•	Escaneos TCP sin tráfico ICMP. 
•	Solicitudes TCP SYN enviadas directamente a puertos específicos. 
•	Respuestas SYN-ACK de hosts que no respondieron al ping. 


<img width="921" height="380" alt="image" src="https://github.com/user-attachments/assets/bfaf5f68-f3aa-40ba-9af3-b5999aae11d0" />



<img width="921" height="342" alt="image" src="https://github.com/user-attachments/assets/4f5f3c44-5023-47f1-86c1-1d3b9f56552c" />


<img width="921" height="469" alt="image" src="https://github.com/user-attachments/assets/7b36db68-204f-49dd-8017-a6d263ef928d" />

