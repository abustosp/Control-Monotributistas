# Control de Monotributistas

Progrmama/Script para realizar masivamente el control de la facturación de los monotributistas en base a los archivos de Mis Comprobantes emitidos y un Excel con las Escalas de Facturación.

---

El licenciamiento es bajo PL (es decir que no se puede distribuir comercialmente, solamente GRATIS). y si se utiliza este el código, sus derivados también debne ser distribuidos de manera abierta y gratuita. 

---

## Ejecución del Programa

1. Instalar el .exe correspondiente a la versión que se quiera utilizar. Existen actualmente 2 versiones del Programa:

    - V 1.0 : requiere que los archivos de Mis Comprobantes tengan un formato de nombre específico:

        `Fin de CUIT - MCE  - Periodo (en formato AAAAMM) - CUIT (sin guiones) - Nombre .xlxs`

        Ejemplo : `0 - MCE - 202304 - 20374730429 - Agustin Bustos.xlsx`

    - V 1.0.1: No requiere nombres específicos pero requiere que existe la primer fila donde dice "Mis Comprobantes Recibidos - CUIT XXXXXXXXXXX" 

2. Una vez instalado el programa se debe ejecutarlo, para lo cual es importante:

    - Actualizar el Excel de "Categorias.xlsx" con las categorías de monotributo vigentes y el periodo a analizar

    - Completar un Excel con la lista de los archivos a analizar (existe un ejemplo donde se encuentra el instalado el programa llamado "Ejemplo de Lista.xlsx")

        - En caso de no tener listados los Excels con sus ubicaciones Existe el Boton de "listador" que genera "Archivos.txt" con la lista de los archivos de Excel en la carpeta seleccionada. Luego hay que depurar los archivos de Excel que no sean de Mis Comprobantes.

---

### Opción 2: Ejecutar el Script

Los pasos para ejecutar el Script suele ser el siguiente:

1. Descargarse Python (https://www.python.org/downloads/)

2. Instalar Python (https://www.python.org/downloads/)

3. Descargar/Clonar el Script:
    - Descargar el ZIP o
    - Clonar el repositorio con el comando en la consola/terminal:

    ```
    git clone https://github.com/abustosp/Control-Monotributistas.git
    ```

4. Crearse un entorno virtual. Generalmente se hace con el comando:

    Python en windows:
    ```Python en Windows
    python -m venv NombreDelEntornoVirtualaCrear
    ```
    Python en Linux/Mac:	
    ```Python en Linux
    python3 -m venv NombreDelEntornoVirtualaCrear
    ```

5.  Activar el entorno virtual (depdende del sistema operativo):

        - Windows: EntornoVirtual\Scripts\activate

        - Linux: source EntornoVirtual/bin/activate 

6. Instalar las dependencias/Librerías del proyecto (generalmente se hace con el comando):

    ```Python	
    pip install -r requirements.txt
    ```

    - Si no se tiene el requirements.txt, se puede instalar cada librería con el comando:

    ```Python
    pip install NombreDeLaLibreria1 NombreDeLaLibreria2==version NombreDeLaLibreria3>=version NombreDeLaLibreriaN<=version
    ```

        (generalmente suelo utilizar las siguientes librerias: pandas, numpy, lxml, customtkinter, matplotlib, seaborn , openpyxl, openai , PIL o pillow)


---
## Aclaraciones

El uso del Programa/Script se ejecuta bajo la responsabilidad de quien lo utiliza. No me hago responsable de los daños que pueda ocasionar el uso indevido del mismo.

Si lo compartís debes hacelo gratis bajo los lineamientos de PL, adicionalmente podés mencioname también para que mas personas conozcan en el mundo de la programacion/automatización con Python/RPA y/o mostrale mis videos para que vean que cosas pueden hacer.

---

### Links de Interés:

- Link de invitación al grupo de RPA en Discord: https://discord.gg/KVYyryvAcD

- Link de invitación al grupo de RPA en WhatsApp: https://chat.whatsapp.com/IekktfvfTNLCkdIagO6xz3

- Tutorial de Descarga de Bots desde Uipath: https://youtu.be/hD5BH7YzABw

- Tutorial de Instalación y descarga de Repositorios con Git: https://youtu.be/ujk27tRdA80

---

Cualquier cosa pueden contactarme en:

    https://www.linkedin.com/in/agust%C3%ADn-bustos-piasentini-468446122/

    https://www.youtube.com/user/agustinbustosp

    whatsapp al https://wa.me/+5493764224695

<br/>

## 💰 Acepto donaciones para mantener el proyecto libre y gratuito
<br/>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/agustinbustosp) <!-- [<img src="http://ketekipo.com.ar/wp-content/uploads/2020/05/mercado-pago.png" alt="Image" height="30" width="100\">](https://paypal.me/paypal.me/agustinbustosp) -->

<!-- [![Cafecito](https://img.shields.io/badge/-Cafecito-9cf?style=for-the-badge)](https://cafecito.app/abustos) -->

<!-- [<img src="https://santanderpost.com.ar/wp-content/uploads/2022/02/Cafecito-.jpg" alt="Image" height="30" width="65\">](https://cafecito.app/abustos) -->

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_5.svg)](https://cafecito.app/abustos)

<br/>
 
## 💰 Y También en Pesos Argentinos

<br/>

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20100-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2JBdGez)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20500-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2CwfjKE)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%201.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/21Xvpig)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%205.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1s4D4mM)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%2010.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1n9cimr)
