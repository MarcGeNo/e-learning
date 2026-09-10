---
description: Guidance to troubleshoot the most common problems
icon: screwdriver-wrench
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/qcqJAUZBOCLls7nRFHi9/additional-informations/troubleshooting
---

# Solución de problemas

<details>

<summary>No se puede iniciar sesión</summary>

&#x20;Si no puede iniciar sesión, haga clic en "_Restablecer contraseña"_ y siga el proceso para restablecerla.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-03-11 a les 9.18.58.png" alt="" width="368"><figcaption></figcaption></figure>

Una vez que haya iniciado la sesión con éxito, haga clic en el botón "_Verificar_".

{% hint style="info" %}
Es importante que inicie la sesión de su cuenta de correo electrónico antes de acceder al enlace de inicio de sesión; de lo contrario, el sistema no podrá enviar el correo de verificación.
{% endhint %}

</details>

<details>

<summary>Fallo en la carga de datos mediante Excel</summary>

Estas son las razones más frecuentes por las que la carga del fichero Excel puede fallar y cómo corregir el problema:

<table data-header-hidden><thead><tr><th width="317" valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top"><strong>Posibles razones</strong></td><td valign="top"><strong>Solución</strong></td></tr><tr><td valign="top">Plantilla antigua </td><td valign="top">Asegúrese de utilizar la última plantilla que puede descargar desde la plataforma</td></tr><tr><td valign="top">Cambios en el formato del archivo o celdas</td><td valign="top">Asegúrese de que no haya habido cambios en el formato del archivo (columnas añadidas, duplicadas o eliminadas, páginas añadidas...) ni en las celdas (se eliminó el formato de listas desplegables).</td></tr><tr><td valign="top">Uso de enlaces a datos externos</td><td valign="top">Asegúrese de ingresar valores en los campos numéricos en lugar de fórmulas o enlaces a datos externos. </td></tr><tr><td valign="top">Archivo de Excel abierto durante la subida</td><td valign="top">Asegúrese de que el archivo de Excel no esté en uso al subir los datos</td></tr><tr><td valign="top">Símbolos en campos numéricos sin valor</td><td valign="top">Deje los campos sin valor vacíos o en 0</td></tr><tr><td valign="top">Filtrado activo de datos</td><td valign="top">Asegúrese de eliminar cualquier filtrado de datos antes de subir el archivo</td></tr><tr><td valign="top">Valores no incluidos en las listas desplegables y/o eliminados</td><td valign="top">Asegúrese de seleccionar un elemento de las listas desplegables integradas y no borre la lista al introducir los datos.</td></tr><tr><td valign="top">Área de trabajo no reconocida</td><td valign="top">El área de trabajo introducida no está incluida en la lista desplegable. Selecciona el área de trabajo en la lista desplegable. </td></tr><tr><td valign="top">Mensaje de error: El área de trabajo 'abc' no está asociada con el sector de la Instalación: 'abc'</td><td valign="top">Los valores en el archivo de Excel no coinciden con el sector de la Instalación.<br>Asegúrese de seleccionar la opción que empieza por "abc" para cada fila.</td></tr></tbody></table>



</details>
