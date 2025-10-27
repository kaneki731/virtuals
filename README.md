# Script de Automatización PAPI JHON v3.0 Final Pro

Automatiza la creación de entornos virtuales, instalación de dependencias, verificación de módulos Python y herramientas del sistema. Ideal para pentesters, desarrolladores y entornos de laboratorio.

##  Características

- Banner ASCII personalizado
- Instalación de módulos Python y herramientas del sistema
- Detección de dependencias en scripts `.py` y `.sh`
- Activación persistente del entorno virtual

##  Requisitos

- Python 3
- Git
- Sistema basado en Debian (para `apt`)
- Herramientas como `nmap`, `curl`, `hydra`, etc.

##  Instalación

```bash
git clone https://github.com/v1n1v131r4/virtuals.git
cd virtuals
chmod +x virtuals.sh
cp virtuals /usr/local/bin/ "Esto para ejecutar el escrip en cualquier lado del sistema"
./virtuals.sh

