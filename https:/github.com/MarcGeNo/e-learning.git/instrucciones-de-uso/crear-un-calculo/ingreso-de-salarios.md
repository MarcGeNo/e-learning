---
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
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/qcqJAUZBOCLls7nRFHi9/how-to-use-the-tool/create-a-calculation/entering-wages
---

# Ingreso de Salarios

{% hint style="info" %}
Ingrese valores anuales por trabajador.

La Matriz Salarial requiere que los números se ingresen sin separadores de miles y los decimales separados por un punto. Por lo tanto, el formato correcto sería: 5000.55.

Recuerde usar la misma unidad monetaria que la unidad de la estimación de salario digno seleccionada.
{% endhint %}

{% hint style="info" %}
<mark style="color:red;">Novedad: las horas y la remuneración durante los</mark> [<mark style="color:red;">permisos personales remunerados</mark> ](#user-content-fn-1)[^1]<mark style="color:red;">deben ingresarse ahora como tiempo trabajado</mark>
{% endhint %}

<details>

<summary>Horas ordinarias trabajadas – Año laboral estándar</summary>

Introduzca el número total de horas ordinarias trabajadas por los trabajadores individuales, o la media de la categoría laboral. La herramienta calculará el porcentaje de año trabajado y ajustará los cálculos al año laboral estándar.

El número total de horas ordinarias trabajadas incluye:

* Horario laboral regular
* Horas en las que el trabajador estaba de baja personal remunerada (enfermedad, parental, duelo, días libres por antigüedad)
* Descansos durante el turno laboral
* Horas de formación obligatorias
* Tiempo de desplazamiento durante el horario laboral normal requerido para una asignación laboral, como los desplazamientos entre obras.
* Tiempo de guardia cuando los trabajadores no pueden usar su tiempo como desean.

Pero no incluye:

* Horas de vacaciones anuales remuneradas, festivos o días de descanso semanales
* Horas de licencia voluntaria no remunerada
* Horas de descanso para comer fuera del turno de trabajo

</details>

<details>

<summary> Horas ordinarias trabajadas – Semana laboral o horas anuales restringidas</summary>

Para algunos trabajadores, la jornada laboral regular legalmente permitida puede ser inferior a la jornada laboral estándar. Esto puede darse para:&#x20;

* Trabajadores con horario laboral diario restringido debido a riesgos para la salud y la seguridad (por ejemplo, fumigadores, trabajo en turno de noche o trabajadores pagados a destajo en condiciones laborales exigentes).
* Trabajadores amparados por leyes o convenios colectivos que establecen jornadas laborales regulares más cortas que la semana o el año laboral estándar.

Para evitar que la herramienta ajuste al alza la remuneración comparable de estos trabajadores hasta el año laboral estándar, son necesarios los siguientes ajustes:&#x20;

a) Si la reducción es aplicable a todos los trabajadores de la instalación:

Sume el número de horas de reducción anual (año laboral estándar a tiempo completo - año laboral reducido real) al "Número mínimo de horas de vacaciones anuales pagadas".

_Por ejemplo, si la semana laboral estándar es de 48 horas, pero la semana reducida para la instalación es de 40 horas, sume (48-40) \* 52.143 horas al Número mínimo de horas de vacaciones anuales pagadas (consistente en el número mínimo de horas de vacaciones anuales y festivos remunerados)._

Luego, ingrese los otros datos (horas, salarios, bonificaciones y beneficios en especie) como haría normalmente.

b) Si la reducción solo se aplica a ciertas categorías laborales o a trabajadores individuales,&#x20;

Las "horas ordinarias trabajadas" de los trabajadores en esa categoría laboral se ajustarán de la siguiente manera:

* Horas normales trabajadas \* Semana laboral estándar / Semana laboral restringida real&#x20;

_Por ejemplo, si la semana laboral estándar es de 48 horas, pero la semana laboral reducida para la categoría de trabajo/trabajador es de 40 horas, y las horas ordinarias trabajadas son 2000, ingrese 2000 \* 48 / 40 = 2400 horas trabajadas ordinarias._

ingrese los otros datos (salarios, primas y beneficios en especie) como normalmente haría.

</details>

<details>

<summary> Salario percibido </summary>

Introduzca aquí los salarios en efectivo percibidos los trabajadores individuales, o la media de la categoría laboral.

Esto incluye:

* Salario base ganado durante el horario laboral semanal regular o por debajo de 48 horas, lo que sea más bajo.
* Salario correspondiente a las vacaciones anuales y festivos.
* Compensación recibida durante las licencias personales remuneradas (por ejemplo, bajas por enfermedad o por paternidad), ya sean pagadas por el empleador o recibida de los sistemas públicos de seguridad social.

Esto no incluye:

* Pagos de 13º, 14º y 15º mes.
* Bonificaciones.
* Pago de horas extra.

</details>

<details>

<summary>Horas extra trabajadas</summary>

Ingrese el número total de horas extra trabajadas por los trabajadores individuales, o la media de la categoría laboral.

Esto incluye:

* &#x20;Horas trabajadas a partir de las horas regulares semanales o 48 horas, lo que sea menor.
* Las horas trabajadas durante las vacaciones anuales o festivos legales, compensadas con remuneración adicional.

{% hint style="info" %}
En el caso de que las horas extra no hayan sido remuneradas, éstas deben incluirse como horas ordinarias.
{% endhint %}

</details>

<details>

<summary>Pago percibido por horas extra </summary>

Ingrese la compensación percibida por las hora extra realizadas de los trabajadores individuales, o la media de la categoría laboral.

Esto incluye:

* Pago de horas extra por horas trabajadas a partir de las horas regulares semanales o 48 horas, lo que sea menor.
* Compensación en efectivo por las horas trabajadas durante las vacaciones anuales o festivos.

</details>

[^1]: Tiempo libre remunerado para atender circunstancias personales específicas a las que los trabajadores tienen derecho al año según las leyes laborales locales o la política de la empresa (por ejemplo, baja por enfermedad/discapacidad, cuidado familiar, baja por duelo, días de representación sindical...).
