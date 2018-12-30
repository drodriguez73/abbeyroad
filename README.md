# abbeyroad
Home Page for Abbey Road program

## Guia tecnologica sobre el desarrollo y herramientas que se utilizaron para construir

Desde el arranque se penso en un sitio responsive que pueda verse sin problemas desde cualquier dispositivo, que sea facil de desarrollar utilizando alguna libreria que facilite las cosas al maquerador y que a su vez sea lo suficientemente aceptada y utilizada para que cualquier otro maquerador pueda colaborar con el proceso.
Sin lugar a dudas recurrimos a la version mas actual de Bootstrap que a ese momento fue https://getbootstrap.com/docs/4.1/getting-started/introduction/


### Principios

No reiventar la rueda, es decir, utilizar todo lo que bootstrap provee.

### Beneficios

1. Desarrollo mas rapido
2. Desarrollo reutilizable
3. Codigo a super probado, y si algo falla, la comunidad probablemente lo descubra antes que nosotros
4. Codigo compatible con la mayoria de los navegadores y dispositivos mobiles


#### Tips para el maquetador

La pagina principal y completa es el index.html
Solo a efectos de hacer mas facil el testing desagremamos al index.html en los siguientes archivos para que fuera mas sencillo el testeo
-- corousel.html
-- destacado.html
-- findus.html
-- menu.html
