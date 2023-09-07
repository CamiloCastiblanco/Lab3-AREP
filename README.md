# Frameworks
Programa que permite la simulacion de framworks como Spring o Spark pero usando una arquitectura propia


### Prerequisitos
Se recomienda contar con las siguientes versiones instaladas:
```
version de java: 15
version de compilador: 1.8
Apache maven: 3.6.3 
```

### Instalación
Para uso del proyecto requerimos clonar este repositorio. Siga los pasos:

1. Clonamos el repositorio con ayuda de git
```
git clone https://github.com/CamiloCastiblanco/Lab3-AREP.git
```

2. Accedemos a la carpeta donde hemos clonado
```
cd Lab3-AREP
```

3. Compilamos nuestro proyecto para generar el target
```
mvn package
```

4. Abrimos el proyecto con nuestro editor de preferencia
```
code .
```

### Corriendo las pruebas
Si queremos ejecutar las pruebas de nuestro proyecto debemos ubicarnos en la raiz del pryecto y usar el comando
```
mvn test
```

## Programa hecho con

* [Maven](https://maven.apache.org/) - Dependency Management

## Actor

* **Brayan Camilo Castiblanco** - [CamiloCastiblanco](https://github.com/CamiloCastiblanco)


## Licencia

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.txt) file for details

## JavaDoc

La documentación del proyecto la generamos con el siguiente comando 
```
mvn javadoc:javadooc
```
