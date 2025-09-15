+++
title="Ръководство"
weight = 3
+++

# Използване на бележки

Цветовете могат да бъдат конфигурирани във файла `color.sass`.

{% note(type="ok", display="block", markdown=true) %}
*Примерна* бележка "ok". С изглед "block"  
И **markdown** съдържание.
{% end %}

{% note(type="ok") %}
Бележка на един ред с икона и фон
{% end %}

{% note(type="ok", display="icon", markdown=true, size="large") %}
Много дълга бележка  
с голяма икона  
и без фон  
{% end %}

{% note(type="ok", display="icon") %}
Бележка на един ред "ok"
{% end %}

---

{% note(type="ok") %}
Бележка на един ред "ok"
{% end %}

{% note(type="warning") %}
Бележка на един ред "warning"
{% end %}

{% note(type="error") %}
Бележка на един ред "error"
{% end %}

{% note(type="info") %}
Бележка на един ред "info"
{% end %}

{% note(type="neutral") %}
Бележка на един ред "neutral"
{% end %}

{% note(type="other") %}
Бележка на един ред "other"
{% end %}
