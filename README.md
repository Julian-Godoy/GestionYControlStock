# E-commers Control y Gestion de Stock 

## Descripción
Esta aplicación e-commerce permite a los negocios gestionar de manera eficiente el control de inventario y el procesamiento de pedidos, integrando autenticación segura mediante OAuth y PostgreSQL como sistema de base de datos. A través de esta plataforma, los administradores pueden monitorear el stock en tiempo real, recibir alertas ante inventarios bajos y ajustar cantidades disponibles, optimizando así la disponibilidad de productos. Además, el sistema de gestión de pedidos facilita a los usuarios la experiencia de compra, permitiéndoles ver el estado de sus pedidos en cada etapa. Con PostgreSQL, la persistencia de datos asegura la integridad y eficiencia en el manejo de la información de productos, clientes y transacciones, lo cual proporciona una base sólida para el crecimiento escalable de la tienda en línea.

## Colaboradores
Agradecemos a todos los colaboradores que han contribuido al desarrollo de este proyecto.
- [Emiliano Esteban Diaz](https://github.com/PerZZi)
- [Federico Val](https://github.com/fedeval98)
- [Xavier Nochelli](https://github.com/Xn0ch3)
- [Julian Godoy](https://github.com/Julian-Godoy)

## Tecnologias

### Back-End
- **Lenguajes:** Java 21
- **Framework:** Spring Boot 3.3.5
- **Empaquetador:** Gradle-Groovy

### Front-End
- **Lenguajes:** JavaScript
- **Frameworks:** React, Tailwind
- **Empaquetador:** Vite 

## Dependencias

- **Spring Web:** Para manejar las solicitudes HTTP y crear la API REST.
- **Spring Security:** Para la autenticación y autorización.
- **Spring Data JPA:** Para la integración con bases de datos utilizando JPA.
- **PostgreSQL:** Base de datos para almacenar datos en caché y otros recursos.
- **OAuth:** Para gestionar el registro de usuarios.
- **Lombok:** Para reducir el código repetitivo (getters, setters, constructores, etc.).
- **Swagger:** Para documentar los endpoints y sus respuestas.

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/Julian-Godoy/GestionYControlStock.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd GestionYControlStock
    ```

3. Compila el proyecto con Gradle:
    ```bash
    gradle clean build
    ```

4. Configura las variables de entorno o modifica el archivo `application.properties` para conectar tu base de datos PostgreSQL.

## Usage


### Endpoints

## Configuracion

### Base De Datos

Asegúrate de tener una instancia en ejecución de PostgreSQL. Configura la conexión en el archivo `application.properties` o mediante variables de entorno según sea necesario.

```application.properties
spring.datasource.url=jdbc:postgresql://localhost:5432/gcs_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un Pull Request o crea un Issue.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
