# Copias de seguridad
Formas que ayudan en la pérdida de datos:
- Redundancia. Este método permite borrar las réplicas, luego, ante un fallo humono, no es muy eficaz. 
- Backup. Copia de seguridad. Permite guardar los datos, no solo actuales, sino históricos. 

La suma de ambas es la forma correcta. 


## 1. Interrogantes para establecer las copias de seguridad
Para guardar los datos de una organización hay que establecer una estrategia que guarde cada cierto tiempo y determinados documentos, porque no todo puede guardarse.

### 1.1. ¿Qué?
Lo que se pueda recoger de otra fuente no se guarda. Podríamos dividir en dos partes:
#### Datos: 
- /home (o directorio del usuario de Windows: Users\\) -> esto es muy grande, luego lo que se suele hacer es habilitar un directorio específico donde guardar los documentos importantes del usuario.
- /var/lib -> no completo, sino los datos de la base o bases de datos que se guardan aquí. Por ejemplo: /var/lib/ldap.
- /var/www
- logs

#### Configuración:

### 1.2. ¿Cómo?

### 1.3. ¿Cuándo?

### 1.4. ¿Dónde? 

