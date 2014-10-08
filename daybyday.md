---
layout: page
title: Day by day
permalink: /day-by-day/
---

14.09.2014
==========

[http://www.trzeciakawa.pl/?p=1179 Dlaczego Scrum nie działa?]

Wnioski:

Surum nie jest dla wszystkich, niektrzy lepiej wykonuja zadania pracujac samotnie
usi trafic na wlasciwych ludzi



13.09.2014
==========

* RammbitMQ vs Redis

> Redis
> 
> - przeznaczony dla operacji w których strata danych nie 
> - bardzo szybkie
> - brak dispachera
> - operacjie tymczasowe mało istone z biznesowego punktu widzenia
> 
> RammbitMQ 
> 
> - dla operacji w których ważne jest bezpieczeństwo wykonania operacji
> - zaawansowane sterowanie zdarzeniami
> - wolniejszy
> - wysyłanie maili, ważne operacje biznezowe


* Brakuje czegoś takiego jak "Awsome angular"

* "wymagania biznesowe to całościowe spojrzenie na biznes i cele biznesowe - 
wymagania wobec oprogramowania to dopiero wymagania wobc rozwiązania"


12.09.2014
==========

* Powrót do Angular'a

Exmaple: https://github.com/angular-app/angular-app.git

Narzędzia Jasmine


Strurktura:

	/client
	  /dist - skompilowane źródła
	  /src - źródła
	    /app
	      /dashboard/ - kontrolery, szablony, routing
		    /app.js
	    /common
	      /resourcers - modele resource np Project, Task
	      /directives 
	      /service - np breadcrumbs, nitifications
	      /less
	      /assets - obrazki
	  /test
	    /config
	    /unit/
	      /apps
	      /common

`Lib angular mock?`

* grunt plugin html2js kompiluje szablony (project.tpl.html) do javascriptu do jednego pliku
(Compiles Angular-JS templates to JavaScript).

Przykładowe zadanie grunta

	html2js: {
	  app: {
	    options: {
	      base: 'src/app'
	    },
	    src: ['<%= src.tpl.app %>'],
	    dest: '<%= distdir %>/templates/app.js',
	    module: 'templates.app'
	  }
	}	

* react-php - websocket 
* ratcher php - websocket

Przykład
https://github.com/phpmasterdotcom/LukasWhite-LiveScores.git


11.09.2014
==========
	 - Czym jest "Legacy code"?
	 - Kod bez testów
	 `Książka: Legacy code`
