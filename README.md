# Mesa_ayuda

Una aplicación para una empresa de telecomunicaciones que les permite hacer una mesa de ayuda en donde clientes puedan crear `tickets` y que eston sean asignados a técnicos para resolver dicho problema.

El sistema cuenta con roles como:

* Cliente: Que puede registrarse, logearse, crear tickets y eliminarlos, así como ver en tiempo real los cambios es los estados, prioridad y el técnico asignado.
* Técnico: Es creado por el administrador y tiene la tarea de resolver los tickets y decidir la prioridad, y cambiar el estado.
* Administrador: Gestiona técnicos y puede ver todos los tickets y usuarios, puede crear técnicos y asignarlo a un ticket. Pero no puede manjar aspectos del ticket o eliminar usuarios o tickets.

Para el desarrollo de la aplicación se usó `Python` con el framework `Flask` para todo el backend y la lógica de negocio. Para el frotend se usarón tecnologías web como HTML, CSS con Boostrap y JS vanilla.


## Instalación y ejecución

El proyecto fue realizado usando `Flask` como framework web, para ello es necesario la versión de `Python 3.12` que puedes descargar [aqui](https://www.python.org/downloads/)

Para usar el proyecto clona el repositorio y accede:

```bash
git clone https://github.com/MontoyaN1/Mesa_ayuda.git

cd Mesa_ayuda

```

Para el tema de las dependencias se recomienda crear un entorno virtual de Python:

```bash
python -m venv .venv

```

O usando:

```bash
python3 -m venv .venv

```

Y ahora accede al entorno:


```bash
source .venv/bin/activate
```

Instala las dependencias en el archivo requeriments.txt usando `pip` :

```bash
pip install -r requeriments.txt
```

Cuando veas que haya terminado la instalación correctamente, ejecuta el proyecto:

```bash
python main.py

```

O usa:
```bash
python3 main.py

```

Y ahora si vaz a `localhost:5000` ya puedes usar el programa
















