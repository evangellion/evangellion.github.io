---
layout: page
title: RammbitMQ vs Redis
description: małe porównanie, z naciskiem na przeznaczenia
links:
    - http://blog.langoor.mobi/django-celery-redis-vs-rabbitmq-message-broker/
---

Message broker - wybrane cechy programów do kolejkowania  wiadomości (zdarzeń)

### Redis


- przeznaczony dla operacji w których bezpieczeństwo danych nie jest wymagane
- bardzo szybkie
- brak dispachera
- operacje tymczasowe, mało istone z biznesowego punktu widzenia
- replikacja

### RammbitMQ

- przeznaczony dla operacji w których ważne jest bezpieczeństwo wykonania operacji
- zaawansowane sterowanie zdarzeniami
- wolniejszy
- ważne operacje biznezowe np. wysyłanie maili
- replikacja

