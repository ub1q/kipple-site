---
layout: default
title: Impressum / Contact
permalink: /impressum/
---

{% if site.commercial %}
<div lang="de" markdown="1">

# Impressum

## Angaben gemäß § 5 DDG

{{ site.owner.name }}<br>
Half Batch<br>
{{ site.owner.street }}<br>
{{ site.owner.city }}<br>
{{ site.owner.country }}

## Kontakt

E-Mail: [{{ site.owner.email }}](mailto:{{ site.owner.email }})

## Verantwortlich für den Inhalt

{{ site.owner.name }}, Anschrift wie oben.

</div>

---

## Legal notice (English)

Half Batch and its apps, including kipple, are provided by {{ site.owner.name }}, {{ site.owner.street }}, {{ site.owner.city }}, {{ site.owner.country }}. Contact: {{ site.owner.email }}.
{% else %}
# Contact

Half Batch is a private, non-commercial project. The apps are free, with no in-app purchases, ads or tracking.

Email: [{{ site.owner.email }}](mailto:{{ site.owner.email }})

<div lang="de" markdown="1">

## Impressum

Half Batch ist ein privates, nicht-kommerzielles Projekt ohne Gewinnabsicht. Die Apps sind kostenlos, ohne In-App-Käufe, Werbung oder Tracking.

Kontakt: [{{ site.owner.email }}](mailto:{{ site.owner.email }})

</div>
{% endif %}
