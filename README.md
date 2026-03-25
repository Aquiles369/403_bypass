<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"403 Bypass"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="35" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"> </h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/403_bypass.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNDltMTlyZXgzaWExd3dzNGcwNGFhc2kyenpqeWx2ZHhnZ2Rwd3c1bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/JmUYzs2dIvMw4EBFx4/giphy.gif" width = 75px>  </picture> 403 Bypass

<br>

 **"403 Bypass" es el arte de acceder a recursos restringidos que devuelven un error 403 Forbidden, lo cual suele esconder paneles de administración, archivos de configuración o datos sensibles.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/defi_js.gif"/>
</p>


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>


### <picture> <img src =   "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExc2d2a2l4NWpuNThydWE4eDlsYmF4aG92ZzJ6ZWJlZ2t1Y3loeGQ4dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/UVXnlKaR2fHc0b70MU/giphy.gif" width = 75px>  </picture> Problema que resuelve<br><br>
**Su objetivo es detectar fugas de información y superficies de ataque ocultas tras errores 403 Forbidden antes de que un atacante externo las explote.** 

<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWszdnRxemtoaG41Y3k3dGxpY3l3b20zZ3AxcGpoNnVreWQyaHluOCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/iIRyg2WRR8WJTNyTNk/giphy.gif" width = 75px>  </picture> Qué aporta y cómo beneficia <br><br>
**• Permite descubrir endpoints no documentados o restringidos.<br><br>
  • Facilita encontrar parámetros vulnerables a XSS, IDOR, SSRF o RCE.<br><br>
  • Ayuda a identificar claves duras en el código (AWS, Firebase, API keys).<br><br>
  • Revela lógica de validación en el cliente que puede ser manipulada o saltada.<br><br>
  • Amplía el mapa de ataque incluso sin autenticación.** 


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2gzOGF3Z2tqMWM3YzJ1ODE4aGhhaGgzbXlpbGMzbzBrMm40aDBrcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/5OJLBp60agyioEwpJf/giphy.gif" width = 80px>  </picture> Índice 
<br><br>

- [Tabla de CWE , CVE , CAPEC , RFCs , OWASP , NIST , ASVS , MITRE ATT&CK](#1)
- [ Checklist , análisis de archivos .js](#2)
- [ Investigación propia](#3)
- [ Dónde buscar funciones / ejemplos](#4)
- [ “Palabras claves y Dorks”](#5)
- [182 Informes diferentes](#6)
- [Hardening / mitigation](#7)
- [“Recursos img entre otros”](#8)
- [“Las tools que armé son 3”](#9)   

 

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNW9qZDE2NG00dmdxMzBvbzJmOHJycnplYWZwZmNrZTdpcTVyNXM5biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/eyjs7st5OcMXSw7mjV/giphy.gif" width = 80px>  </picture> Investigación propia

#  3

**En esta sección se encuentra un breve resumen de la investigación que realicé, de la cual aprendí mucho conocimiento que desconocía anteriormente y quiero compartirlo, ya que me ayudó a comprender mucho mejor y tener una base sólida para poder leer luego los 200 informes de análisis de JavaScript y entenderlos más rápido.
Además, me permitió identificar en qué áreas me faltaba más conocimiento o debía repasar.<br>
La parte relacionada con herramientas y sitios web la dejaré en la sección de informes, y todo lo que aprendí leyendo esos 200 informes lo dividiré en tres categorías: texto, tips/consejos y herramientas (tools).**<br><br>



## 

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2NxY2JzdWxmeHVqeWtxenp5dTIybWxlMWZ6dnRmcTZsemNwYW4zYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/0Q6VlwzeMhuL7xFCKG/giphy.gif" width = 80px>  </picture> 182 Informes diferentes

#  6

**“En esta sección encontrarás 182 informes reales sobre análisis de .js que leí, estudié y anoté. Podés copiarlos directamente, importarlos en JSON con mis notas o cargarlos masivamente en tu gestor.”**
<br><br>


## Lista de informes link directo
```yam

```

<br><br>


## Lo que aprendí leyendo de esos informes:



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzhwcjVwbmRsazd6cTh3M3l2cmh1eTIxYmh3YmF6Yzk3c2ZuZzBvMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/uRoZBofy2cTCvz18we/giphy.gif" width = 80px>  </picture> “Recursos img entre otros”

#  8

**En esta sección encontrarás imágenes, recursos adicionales, herramientas y mucho más, todo relacionado con el análisis de JavaScript.**
<br><br>

## IMG


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-092744.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251025-133825.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-134719.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-141930.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-143940.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150204.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150212.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150219.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150419.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-153145.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-155123.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-155913.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-161537.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221442.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221528.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221729.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-224251.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-224614.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-232001.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-232056.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-003902.png"/>

<br><br>



<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-004753.png"/>

<br><br>



<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-004853.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251028-112615.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251022-235403.png"/>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-005230.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-075353.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-082626.png"/>



<br><br>

## Recursos

https://www.youtube.com/watch?v=VpDmOjDqmh8
 — Interesante metodología bastante completa de análisis de JS con sus tools.<br><br>
https://www.youtube.com/watch?v=djCNhYMo3eE
 — Está bueno, habla sobre análisis de JS y análisis de diferentes cosas como React, Angular, etc. También trata algo básico de regex, pero está bien.<br><br>
https://www.youtube.com/watch?v=CiIyaZ3x49c
 — Súper bueno, reglas regex; explica cómo funciona la lógica según la biblioteca, muy interesante.<br><br>
https://www.youtube.com/watch?v=AIZh0MDk3lI
 — Bueno para mirar, en español (audio), cursito.<br><br>
https://blogs.jsmon.sh/100-regex-patterns/
 — Recurso interesante: más de 100 regex para análisis de JS.<br><br>
https://www.youtube.com/watch?v=ArwTbZAlZSA
 — Ocultar source.map.<br><br>
https://www.youtube.com/watch?v=FIYkjjFYvoI
 — Bueno para mirar, explica qué es source.map; interesante compilación sobre TypeScript y los compiladores de Vite, etc.<br><br>
https://www.youtube.com/watch?v=SkUcO4ML5U0
 — Uso de DevTools para análisis completo de source.map, cómo ocultarlo, limitaciones, etc.<br><br>
https://www.youtube.com/watch?v=qWDwHRZfbDo
 — Cómo funciona realmente source.map con Webpack, muy interesante.<br><br>
https://www.youtube.com/watch?v=uzRbPp4rC4M
 — Decodificación de VLQ para source.map, súper recomendado; incluye herramienta web.<br><br>
 https://www.youtube.com/watch?v=oVcv3QZiXNM Super recomendado sobre Análisis en profundidad de los mapas de origen - Nicolò Ribaudo | JSHeroes 2024
  <br><br>
 https://www.youtube.com/watch?v=FqnSAa2KmBI — Metodología del cazador de bugs: análisis de aplicaciones | Jason Haddix minuto 35:13 js interesante
 <br><br>
 https://www.youtube.com/watch?v=FTeE3OrTNoA&t=8s — Hacker101 - JavaScript for Hackers (Created by ‪@STOKfredrik‬) no esta mal  me encanto la manera de como lo expresa y aprendi algunas revisiones manules mediante la consola como ver todos las llamdas de evento que tiene ese sub-domain como tambien las llamadas de api ajax que hace hacia afuera en xhr etc y otra cosa mas para el rastreo de variables pueden cambiar el nombre funciones concatenacion de cadenas y contruccion en tiempo real aparte estudia y busque recursos sobre devtool sobre su uso completo tips avanzado comando general que no sabia que tenia la devtool muy bueno y puntos de quiebre entres otros , entender cuando un archivo esta minificado cuando esta ofuscado y encontre tools para deteccin de tanto minificados como ofuscados y que tool tengo que usar para aplicar embellecer y desofuscar por la terminal y tambien como existen tool para los sourcemap y su contruccion analisis etc.
 <br><br>
 https://www.youtube.com/watch?v=nkznsNxDM5k — ¡Buscando Javascript! Bug Bounty, scripthunter, jsmon, getjswords y más , muy bueno tools interesante para ffuf con los archivos js y monitoreo avanzado de js interesante.
 <br><br>
 https://github.com/NobleSiXSS/getjswords.py_fork — Tool de python para extraccion de palabras claves de los archivos js etc para armar un diccionario especializado para fuerza bruta se podria mejorar bastante la tool ejemplo agregar mas palabras claves y mejorar la deteccion como la regla regex entres otros pasarle a GPT si queres mejorar en mi caso estoy armando algo de mi gusto.
 <br><br>
 https://github.com/al-sultani/url-tracker — ¡ Tool interesante no la probe aun segun el repo esta bastante bien echa y pulida ux etc interesante y mas pulida vs https://github.com/robre/jsmon en cambio en esta esta algo mas limita para mi la primera es mas completa. 
  <br><br>
 https://github.com/003random/getJS — ¡ Tool para descargar todos los archivos etc de las url que le pases ejemplo de js etc muy bueno.

 <br><br>
 https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html — ¡ Interesante hardering de secretos manejo , rotacion , muy bueno.
 <br><br>
 https://owasp.org/www-project-wrongsecrets/ — ¡ Ctf interesante mas de 50 ejercicios.
 <br><br>
 https://cheatsheetseries.owasp.org/cheatsheets/Third_Party_Javascript_Management_Cheat_Sheet.html#introduction — ¡ algo basico pero aun sirve algunas medidas de proteccion ejemplo iframe de sandbox otras protecciones menores pero imporante.
 <br><br>
 Books📓:
1. The Joy of JavaScript— By Luis Atencio , click to Download the The Joy of JavaScript
 <br><br>
2.Eloquent Javascript: A Modern Introduction to Programming -By Marijn Haverbeke , Click to Download Eloquent Javascript: A Modern Introduction to Programming.
 <br><br>
3.JavaScript For Impatient Programmers — By Dr. Axel Rauschmayer , Click to Download JavaScript For Impatient Programmers.
 <br><br>
4.Simplifying JavaScript: Writing Modern JavaScript with ES5, ES6, and Beyond — By Joe Morgan , Click to Download Simplifying JavaScript: Writing Modern JavaScript with ES5, ES6, and Beyond.
<br><br>
Podes descargarlo cada uno mediante este sitio web , https://welib.org/md5/daaecc43eef120737ebaea63ffe494e9 y otra tips de libro un invetigador que trabaja para la empresa Portswwiger.net tiene un libro de js bastante bueno para comenzar esta bien y tambien mira mis informes leidos con sus notas de informes de bug  bounty sobre javascrypt.
<br><br>
https://www.youtube.com/watch?v=CiIyaZ3x49c .Muy bueno me , ayudo mucho a comprender sobre regex como funciona y el por que funciona de manera distinta entre lenjuages de programacion y tambien otra cosa que descubri por expericencia propia incluso por tipo de shell y html etc ayudo mucho saber que existia lo del regex101 que con eso pude mejorar mis regex complejas con un automata ripgrep etc y gpt etc interesante , el tipo tiene un sitio web intereasante sobre como algunos caracteres o meta caracteres a ascii etc.

 


<br><br>

## Tools

https://urlquery.net/
 — Mirar endpoints interesantes, muy buen sitio web.<br><br>
https://obf-io.deobfuscate.io/
 — Para JS ofuscado, excelente sitio web.<br><br>
https://sokra.github.io/source-map-visualization/
 — Sitio web para analizar archivos source.map.<br><br>
https://regex101.com/
 — Interesante para probar reglas regex, permite test unitarios y varía según lenguaje o biblioteca. Súper útil.<br><br>
https://www.youtube.com/watch?v=AIZh0MDk3lI&list=PLFF93FRoUwXF-Lq9Bm55osmcg2dZrythY
 — Curso de 10 lecciones sobre regex, muy bueno.<br><br>
https://es.scribd.com/document/775345095/JavaScript-for-Hackers
 — Libro JavaScript for Hackers de Gareth Heyes, altamente recomendado (gratuito).<br><br>
https://cyscan.io/
 — Sitio web para escaneo rápido con captura de scripts, estilos, etc.<br><br>
https://github.com/0xacb/recollapse
 — Tool regex muy interesante.<br><br>
https://sploitus.com/?query=React#exploits
 — Interesante sitio web para buscar exploits relacionados con React.<br><br>
  https://www.youtube.com/watch?v=vUrx113ZtEw — Tool JSParser interesante , esta bueno html.
 <br><br>
 https://www.youtube.com/watch?v=JQspeMI1UX4 — MHE  es tipo quiere crear en go el motor de reglas regex etc sin entender y saber que ya existe algo asi y super pulido en C y Rust que soporta todas las extensiones llamado ripgrep y con pcre2 -_- pero bueno se agredece compartir.
  https://www.youtube.com/watch?v=LXS8k06v61c — Tool  interesante , esta bueno extension del navegador.
 <br><br>
 https://www.youtube.com/watch?v=pPgRMP-bRro — Tool LinkFinder interesante , esta bueno html mismo de jsparser.
 <br><br>
 https://www.youtube.com/watch?v=yT_IqBMwLFg — Tool extension de burp suite interesante , esta bueno algo basico.

<br><br>


## Las tools que armé son 3:<br><br>

#  9

**En esta sección encontrarás las herramientas que desarrollé:
La primera tool contiene más de 300 reglas Regex integradas con ripgrep.
La segunda tool agrupa 49 categorías diferentes, cada una con alrededor de 400 palabras clave específicas, además de 10 categorías adicionales dedicadas a las permutaciones de nomenclaturas usadas para nombrar endpoints (un total de 7 esquemas de nomenclatura).
La tercera tool utiliza IA, a la cual se le proporcionan los tres PDF correspondientes a este repositorio —dividido en tres secciones— para que aprenda y asimile el concepto general del proyecto, funcionando como guía de referencia durante el análisis de código JavaScript.**



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Cada .js es un mapa oculto: si sabés leerlo, encontrás el tesoro.”
<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
