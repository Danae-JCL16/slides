---
title: Tarea #996
layout: post
permalink: /tarea-996/
background: '#0a5'
slides:
 - title: Virtualización en TIC ☁️
   slide-data: Solución estratificada de problemas en sistemas modernos.

 - title: 1.1 Solución estratificada
   slide-data: División del sistema en capas para mejorar rendimiento, escalabilidad y organización.

 - title: 1.1.a Interpretación pura
   slide-data: Ejecuta instrucciones una por una sin compilación previa. Ejemplo: emuladores. Característica: compatibilidad alta pero bajo rendimiento.

 - title: 1.1.b Recompilación dinámica
   slide-data: Traduce instrucciones a código nativo en tiempo real. Ejemplo: QEMU. Más eficiente que la interpretación.

 - title: 1.1.c Hipervisión (Bare Metal)
   slide-data: El hipervisor corre directamente sobre el hardware. Ejemplo: VMware ESXi, Hyper-V, Xen.

 - title: Características generales
   slide-data: Virtualización permite optimización de recursos, aislamiento de sistemas y escalabilidad.

 - title: Casos de uso
   slide-data: Cloud computing, centros de datos, máquinas virtuales, servidores empresariales.

 - title: Ejemplos reales
   slide-data: AWS, Azure, Google Cloud, entornos de pruebas.

 - title: Conclusión
   slide-data: La virtualización es base de la nube moderna y permite eficiencia y flexibilidad en sistemas TIC.
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
