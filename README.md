# Proyecto BRYAN - Monitoreo de Sistemas

Este proyecto incluye un cliente de monitoreo que se puede instalar en sistemas Linux y un servidor de monitoreo que se ejecuta en Python utilizando Flask. El cliente se encarga de enviar información sobre el sistema al servidor y de escanear el sistema en busca de virus utilizando ClamAV.

## Información del Proyecto

**Creador:** Bryan  
**Año de Nacimiento:** 1995  
**Descripción:** Este proyecto tiene como objetivo proporcionar una solución de monitoreo para sistemas Linux, permitiendo a los administradores revisar el estado del sistema y detectar posibles amenazas de virus. El cliente se encarga de recolectar información del sistema y realizar escaneos periódicos, mientras que el servidor centraliza y muestra esta información en tiempo real.

## Requisitos

- **Linux:** Compatible con Kali Linux y otras distribuciones basadas en Debian.
- **Python 3:** Necesario para ejecutar tanto el cliente como el servidor.
- **ClamAV:** Herramienta de escaneo de virus para Linux.

## Instalación

### 1. Configuración del Servidor

1. **Clonar el repositorio:**

   Primero, debes clonar el repositorio desde GitHub. Abre una terminal y ejecuta el siguiente comando:

   ```bash
   git clone https://github.com/usuario/repo.git
