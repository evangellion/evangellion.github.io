---
layout: post
title: Powrót do Angular'a
description: bardziej konkretne podejście angulara
---

## Przykładowy projekt:

[GitHub](https://github.com/angular-app/angular-app.git) - repozytorium


### Strurktura:

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


### html2js

Plugin html2js kompiluje szablony (project.tpl.html) do javascriptu do jednego pliku
(Compiles Angular-JS templates to JavaScript).

*Przykładowe zadanie grunta:*

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
