---
icon: house-blank
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

# Create a Facility

{% hint style="info" %}
The first step to make a Living Wage Gap Calculation is to create a Facility.&#x20;
{% endhint %}

#### Guidance for multi-site facilties

The general ruel is to create a Facility for each production site.

Multiple sites can only be combined into one single Facility when ALL the sites are run under the same payroll system AND:

* they all produce the same products, and
* wages or payment rates per units are the same, and
* the average number of units worked for a given timeframe are the same (no major variances in productivity), and
* bonuses and in-kind benefits schemes are the same, and
* they are all located in the same region and share the same living wage estimate.

#### How to create a Facility

Go to the _Facilities_ view and click on the _+ Create Facility_ button on the top right corner.

{% hint style="info" %}
The top horizontal menu shows you what step you are on and the status of each stage of the process.
{% endhint %}

{% stepper %}
{% step %}
### Location information

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.21.01.png" alt=""><figcaption></figcaption></figure>

You will first be asked to provide information on the location of the Facility by selecting a _Country_ and a _Region_ from the drop-down lists. This information will allow the tool to propose the right living wage estimates.

Entering the city or town name is optional.

Click _Next_ to go to Step 2.
{% endstep %}

{% step %}
### Facility Information

The next step is to enter the Facility name and choose the currency.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.22.58.png" alt=""><figcaption></figcaption></figure>

The _Currency_ drop-down list will allow you to select the local currency or USD. It is highly recommended to select the local currency since this is the one used to calculate the living wage estimates. Choosing a different currency will reduce the accuracy of your calculations due to the impact of variable exchange rates.

You also have the option to include any additional information that you find relevant in the field _Description_. For example, you may want to note here that some workers in the payroll are shared with another Facility.

Note that once saved, information from Step 1 and 2 cannot be modified to maintain data integrity.

Click _Next_ to go to Step 3.
{% endstep %}

{% step %}
### Sector and products

Next, you will be asked to choose a _Sector_ from a drop-down list. If you don't find your sector in the list, select _Other_. Please note that once saved, you will not be able to change the sector.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.24.34.png" alt=""><figcaption></figcaption></figure>

To enter products manufactured at the facility, type the product name, select the product from the drop-down list, and press _Enter_ or the _+ Add_ button on the right. You can include as many products as you like.

{% hint style="info" %}
The _Product_ drop-down list is only available after you have selected a _Sector._
{% endhint %}

Once you have entered your products click _Next_ to go to Step 4.
{% endstep %}

{% step %}
### Overview

You will see an _Overview_ of the information entered so far. Please review the information carefully since, once you save the facility, most details cannot be modified to maintain data integrity. You will only be able to edit the _Product_ list and the _Description_.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-01-23 a les 10.33.37.png" alt=""><figcaption></figcaption></figure>

Click _Save Facility_ to create the Facility.

Once the Facility is created a menu will appear with an overview of the data entered and three buttons on the top right corner, allowing you to _Edit_ or _Delete_ the facility or to _Create a living wage gap calculation_.

&#x20;
{% endstep %}
{% endstepper %}
