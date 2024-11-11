# EXAMEN DAW 
## INDECE
  1-Motivación.  
  2-Palabras clave.  
  3-Actividades realizadas.  
  4-Conclusión.  

### MOTIVACIÓN  
  El aprobar este examen es la mayor motivación que tengo, también el aprender cada dia algo nuevo.  

### PALABRAS CLAVE  
  * SSH  
  * MarkDown  
  * DAW  
  * Apache  
  * Virtual Host  

### DOCUMENTACION EJERCICIO 2.  

**1. Primero he accedido al servidor mediante el comando ssh usuario@192.168.0.185**  
![imagen](https://github.com/user-attachments/assets/59e85444-35da-4af7-9846-66fe75831aac)  

**2. Hacemos un touch para creamos un .text dentro del Escritorio.**  
![imagen](https://github.com/user-attachments/assets/77af3686-a2db-495f-884e-22b8ec5725c0)  
![imagen](https://github.com/user-attachments/assets/acbffac7-f2a9-4c05-8699-02620bbe3aeb)  

**3. Después ponemos el comando whoami y vemos el resultado.**  
![imagen](https://github.com/user-attachments/assets/eb87950a-131e-4bae-85d5-3a294998a57a)  

**4. Tambien ponemos el comando who comando necesario para saber quién está conectado a la máquina.**  
![imagen](https://github.com/user-attachments/assets/4774485f-8c84-4835-97a7-b9b862979297)  

**5. Unimos la respuesta 3 y 4 en el .text.**  
![imagen](https://github.com/user-attachments/assets/a565b989-d6b4-4f21-8677-887f0de87e96)  


## DOCUMENTACION EJERCICIO 3.  
**1. Instalamos apache.**  
![imagen](https://github.com/user-attachments/assets/1e01c9e4-6926-458d-8caf-c8a09d914e8b) 

**2. Hacemos un sudo apt update**  
![imagen](https://github.com/user-attachments/assets/c33ba595-d20d-46d2-a023-852162f99f83)    

**3. En /home/practica creamos una carpeta llamada miWeb.**  
![imagen](https://github.com/user-attachments/assets/50f5ef53-715b-437d-a284-516b24936046)    

**4. Luego con un nano vamos a /var/www/miWeb/index.html y pegamos el html.**  
![imagen](https://github.com/user-attachments/assets/28edd904-0c0d-4000-ab1e-8a0b39e0a09c)  

**5. Despues con un cd accedemos a /etc/apache2 y luego a sites-available**  
![imagen](https://github.com/user-attachments/assets/2c78ab6f-c924-463a-b5f5-6efb5739a6bd)  

**6. Un ls para hacer un cp del default**  
![imagen](https://github.com/user-attachments/assets/0d991ff7-4962-4d4e-b4d7-d0a6fcb038ee)  

![imagen](https://github.com/user-attachments/assets/0b1e61e9-cf15-4e5d-b61b-15483d7ee4e8)  

**7. A continuación entramos con un sudo nano a miWeb.conf**  
![imagen](https://github.com/user-attachments/assets/26241a81-183d-4eb7-b0ad-4efa88f56131)  

**8. Dentro del .conf desmarcamos del ServerName y ponemos el nombre de nuestro dominio, en Admin ponemos nuestro correo y en DocumentRoot quitamos donde pone html y ponemos miWeb**  
![imagen](https://github.com/user-attachments/assets/b5f6671d-7e32-4355-86af-782c8dcab25b)  

**9. Por ultimo accedemos a /etc/hosts con un sudo nano, dentro ponemos nuestra ip y el dominio que queremos acceder**
![imagen](https://github.com/user-attachments/assets/eb23e77f-b11a-497b-852e-ff89bdca9284)

### CONCLUSIÓN  
En resumen, este examen me ayudó a reforzar habilidades como conectarme al servidor con SSH, configurar Apache y crear un Virtual Host. Fue una buena práctica para entender cómo funcionan estos servicios y seguir aprendiendo.  

### BIBLIOGRAFIA  
Apuntes de clase.  

















