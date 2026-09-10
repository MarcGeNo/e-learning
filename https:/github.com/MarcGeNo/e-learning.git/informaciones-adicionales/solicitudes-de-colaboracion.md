---
icon: arrows-down-to-people
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
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
---

# Solicitudes de colaboración

La colaboración es crucial para lograr un salario digno para los trabajadores de todo el mundo.&#x20;

La función de _Colaboraciones_ permite compartir datos de forma segura, eliminando la necesidad de descargar y compartir los cálculos mediante flujos de trabajo externos, lo que ahorra un tiempo valioso y salvaguarda la privacidad de los datos.

Los compradores pueden iniciar invitaciones a proveedores directamente desde la herramienta. Los proveedores reciben una solicitud para conectarse y compartir sus datos solamente después de su consentimiento explícito.

<details>

<summary><strong>Privacidad de los datos</strong></summary>

Hemos desarrollado esta función con fuertes protecciones de privacidad de datos para garantizar un proceso de intercambio de datos seguro, transparente y controlado por el usuario:

* Los compradores deben proporcionar dos datos válidos, ya sea el "ID de la Instalación + el Correo electrónico del usuario", o el "ID de la Instalación + el ID de la Matriz", ambos originados por el proveedor. Si estos datos no coinciden, la solicitud no podrá enviarse, asegurando que solo se intenten las conexiones autorizadas&#x20;
* Se requiere consentimiento explícito antes de compartir cualquier dato: esta solicitud de consentimiento está integrada en la solicitud de invitación. Nunca se comparten datos en bruto sin que el usuario lo apruebe primero.
* La propiedad de los datos sigue siendo plenamente del proveedor: el usuario tiene derecho a conceder y revocar el acceso en cualquier momento, incluso después de que se dé el consentimiento inicial.

</details>

<details>

<summary><strong>Proceso de colaboración</strong></summary>

El proceso de colabración costa de cuatro pasos:

{% stepper %}
{% step %}
### Recibir invitación

Si ha sido invitado por un comprador, recibirá una notificación por correo electrónico.&#x20;

Al hacer clic en el enlace accederá a la Matriz Salarial, donde deberá iniciar sesión.&#x20;
{% endstep %}

{% step %}
### Ir a la pestaña de colaboraciones

Si ha recibido una invitación de un comprado, aparecerá un nuevo apartado _Colaboraciones_ en el panel de navegación izquierdo, incluyendo un contador con el número de nuevas solicitudes recibidas.

Haga clic en _Colaboraciones_ para ver acceder a los detalles de las solicitudes recibidas.&#x20;
{% endstep %}

{% step %}
### Verificación de la solicitud

Compruebe que el comprador forma parte de la cadena de suministro y el rango de fechas para el que han solicitado la colaboración.&#x20;

Haga clic en la flecha junto a 'Lo que verá el comprador' para acceder a los permisos incluidos en la solicitud:

* Solo visibilidad completa de datos o promedios de la instalación.
* Consentimiento para compartir con auditores solicitado o no.
* Consentimiento para compartir Datos de contribución al salario digno solicitados o no.
{% endstep %}

{% step %}
### Aprobar o rechazae

Una vez haya comprobado los detalles de la solicitud, puede seleccionar 'Aprobar' o 'Rechazar'.&#x20;

Al rechazar se solicitará una razón para dar contexto al comprador. En caso de estar de acuerdo con la solicitud general excepto en algún detalle concreto, se recomienda rechazar con motivo, para que el comprador pueda enviar una solicitud actualizada.
{% endstep %}
{% endstepper %}

</details>
