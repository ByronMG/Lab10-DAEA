# Lab 10 DAEA

## Descripción
Este proyecto implementa una aplicación Node.js que se conecta a una base de datos SQL Server y muestra la fecha y hora actual en un navegador web. Además, se configura un proxy inverso con Nginx utilizando Docker Swarm para manejar múltiples réplicas del servicio.

## Ejecuciones

### 1. **Construcción de la imagen de la aplicación Node.js**
   ```bash
   docker build -t mynodeapp .
