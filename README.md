<h1 align="center"> SMBauth </h1> <br>

<p align="center">[  !  ] El script requiere la instalación de paquetes. Una vez ejecutado, estos pueden ser visualizados en el código de SMBauth.py. </p>

<hr/>

<picture> <img align="right" src="https://i.pinimg.com/originals/6c/2b/b8/6c2bb8b7405d465a581a957944dbb8a3.gif?raw=true" width = 250px> </picture> <br> 

**Algunas de sus funcionalidades:**

1 - Verificación de un dominio y subdominio al ingresar las credenciales. <br>
2 - Conexión por selección de recursos en una mini interfaz, entablando una mini shell. <br>
3 - Conexión por terminal mediante argumentos, entablando una mini shell. <br>
4 - Visualización de recursos en una red. <br> 

<br> <br> <h1 align="center"> ¿Cómo funciona? </h1> <br>

Primeramente, ejecutamos el script con el argumento -t, ingresando las credenciales donde se requiere: <br> <br> 
 
1. Dominio → No obligatorio. <br>
2. Subdominio → Obligatorio. <br>
3. Usuario → Obligatorio. <br>
4. Contraseña → Obligatorio. <br> <br>

A continuación, se mostrará un ejemplo, pero se debe tomar en cuenta que se deben eliminar los signos de mayor que (<) y menor que (>) junto con el contenido que se encuentra dentro de ellos (por ejemplo, <Usuario>), dejando tal cual los signos que sean indiferentes a estos:

```bash
python3 SMBauth.py -t 
```
  
  

