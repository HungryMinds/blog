---
layout: post
title: "5 minutos para iniciar un proyecto de Angular 4"
description: "Custom written post descriptions are the way to go... if you're not lazy."
category: Angular
tags: [sample post, readability]
<!--imagefeature: ../images/leonardo/angular2.png-->
share: true
author: Leonardo Mendoza
---

Esta es la forma más rápida para poner generar un proyecto que funciona inmediatamente y que sigue las mejore practicas dictadas por Angular. Con solo instalar algunos paquetes y correr unas lineas de comando usted podrá tener su primer proyecto de Angular funcionando en los próximos minutos. 


# Es más rapido con Angular-cli

Normalmente iniciar un proyecto en angular es un proceso lento y tiene una variedad de opciones que pueden tornar un poco confuso y tedioso el inicio de un proyecto a un usuario principiante. Pero en este post voy a presentar como iniciar con Angular de la manera más rápida usando angular-cli


## Instalando Angular-cli

 Primero es necesario instalar Node 6.9.0 o superior, junto con NPM 3 o superior

**1 - Node** (Un entorno de ejecución para JavaScript)

>La forma más rápida de instalar node es descargando el instalador según el sistema operativo que se este usando desde la pagina oficial  [Descargar Node](https://nodejs.org/es/download/)


**2 - NPM** (El manejador de paquetes para JavaScript) 
>Node viene con una version de npm, y con el siguiente comando se puede actualizar 

{% highlight bash linenos %}
npm install npm@latest -g
{% endhighlight %}


Para revisar la versión de NPM que se esta usando se puede usar 

{% highlight bash linenos %}
npm -v
{% endhighlight %}


**3 - angular-cli** (Command Line Interface para Angular)
>se instala corriendo la siguiente linea de comando

{% highlight bash linenos %}
npm install -g @angular/cli
{% endhighlight %}


## Generar un proyecto en 2 lineas

Una vez que se tiene instalado @angular/cli se puede generar un proyecto con solo ubicarse en la carpeta donde se quiere generar y corriendo los siguientes comandos 

{% highlight bash linenos %}
ng new PROJECT_NAME
cd PROJECT_NAME
{% endhighlight %}


## Ver el projecto localmente

Ahora para poder ver el proyecto funcionando solo hace falta correr la linea de comando 

{% highlight bash linenos %}
ng serve
{% endhighlight %}

Y listo, ahora desde la dirección [http://localhost:4200](http://localhost:4200) se puede ver el proyecto funcionando.

![localhost](../images/leonardo/localhost-angular-cli.png)



