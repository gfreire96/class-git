# CLASE 01 MIÉRCOLES 14 DE AGOSTO DEL 2024 - Portafolio 1

## USO DE GITHUB Parte 1

GitHub es una plataforma que nos permite guardar repositorios de Git que podemos usar como servidores remotos y ejecutar algunos comandos de forma visual e interactiva (sin necesidad de la consola de comandos). Luego de crear nuestra cuenta, podemos crear o importar repositorios, crear organizaciones y proyectos de trabajo, descubrir repositorios de otras personas, contribuir a esos proyectos, dar estrellas y muchas otras cosas.

## COMANDOS

- **Import repository**: significa que es como tu empresa
- **New repository**: significa es como un grupo de repositorios 
- **New organization**: puedes tener dentro de una empresa
- **New project**: significa es como un grupo de repositorios que puedes tener dentro de una empresa
- **New gist**: es un pedasito de código que puedes compartir

### Creación de Repositorio
1. **New repository**
   - Ponemos el nombre: class-git
   - Descripción: Haremos un blog increible
   - Hay muchas licencias para publicar el código (NO lo hacemos ahora)

2. **Create repository**
   - Lo ponemos en privado o en Publico

### Información Importante

El README.md es el archivo que veremos por defecto al entrar a un repositorio. Es una muy buena práctica configurarlo para describir el proyecto, los requerimientos y las instrucciones que debemos seguir para contribuir correctamente.

Para clonar un repositorio desde GitHub (o cualquier otro servidor remoto) debemos copiar la URL (por ahora, usando HTTPS) y ejecutar el comando git clone + la URL que acabamos de copiar. Esto descargará la versión de nuestro proyecto que se encuentra en GitHub.

**ATENCIÓN**: ¿Por qué? Porque a través de https nos pedirá usuario(nombre perfil) y contraseña. Sin embargo, esto solo funciona para las personas que quieren empezar a contribuir en el proyecto.

### Conectar Repositorio GitHub a Documento Local

Si queremos conectar el repositorio de GitHub con nuestro repositorio local, que creamos aconsejo que al trabajar desde GitHub no utilizemos localmente el comando git init, si debemos ejecutar las siguientes instrucciones:

1. Guardar la URL del repositorio de GitHub con el nombre de origin:
```bash
git remote add origin URL
```

2. Verificar que la URL se haya guardado correctamente:
```bash
git remote
git remote -v
```

3. Traer la versión del repositorio remoto y hacer merge:
```bash
git pull origin master --allow-unrelated-histories
```

4. Guardar los cambios en GitHub:
```bash
git push origin master
```

## Autenticación en GitHub 2022

### Cambio de Rama Master a Main
1. Posicionarse en la rama a renombrar
2. Ejecutar:
```bash
git branch -M main
```

### Creación de Token de Acceso Personal

1. Ingresamos a nuestra cuenta de GitHub
2. Buscamos Settings
3. Click en Developer settings
4. Click en Personal access tokens
5. Click en Generate new token
6. Configurar:
   - Nombre
   - Fecha de expiración
   - Tildar en repo
   - Click en Generate token

## PORTAFOLIO

Vamos a ver unos videos de como avanzar en lo que es un portafolio por el Tutor:
- **Dante Nicolás Martinez**
- **Segundo Semestre Parte 1:**

### [IntroYpractica](https://drive.google.com/file/d/1yFihiQVMKXJvOXSwMdczrCesocRS9heY/view?usp=drive_link)

### [PDF](https://docs.google.com/presentation/d/10QC9Ii6zvYgTa5fbzUJGNC8z9LukEN5r/edit?usp=drive_link&ouid=103827187004520077964&rtpof=true&sd=true)

Revisar y ejecutar cada comando, hacerlo como practica: NO olvidar hacer lo requerido por el Tutor Nico, lo que sea tarea o investigación.

*Profesor Ariel Betancud*
