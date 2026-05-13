<h1 align="center">𓆩⚜𓆪 403 Bypass 𓆩⚜𓆪</h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/403_bypass.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNm5uNHl6eW5sMXB6Y25obnRpeG52Mm12dmtkNTk2dGFyYjVyejl0bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/B6zEPouWkkekb8exj3/giphy.gif" width = 75px>  </picture> 403 Bypass

<br>

 "403 Bypass" es el arte de acceder a recursos restringidos que devuelven un error 403 Forbidden, lo cual suele esconder paneles de administración, archivos de configuración o datos sensibles, Comparto esta lista que reuní tras leer y analizar en detalle cada informe que uno puede encontrarse sobre reportes de 403 Bypass en bug bounty.<br><br>

Es la colección de informes más completa que pude lograr, buscando en diferentes rincones de Internet.<br><br>

<b>Tip:</b> en caso de que FreeMedium esté caído, casi siempre aparece algún mirror o alternativa similar.<br><br>

Las técnicas y patrones generales de cada informe me los reservo, al menos hasta el momento de publicar mi tool web, anteriormente llamada <b>Excalibur</b> y hoy en día llamada <b>Lanza del Cielo Invertida</b>.<br><br>

Saludos.


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHg3dThzazNwN2lrYjVscGdwMmRyN2xlb2NrcWJsamUwMXFjbXM5YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/1CoTS8bsIdPaRNS7fs/giphy.gif" width = 80px>  </picture> Informes de bug bounty de 403 bypass

<br><br>

**“En esta sección encontrarás 70 informes reales sobre análisis de 403 bypass que leí, estudié y guarde en mi gestor de informes para bug bounty personal.”**
<br><br>


## Lista de informes link directo
```yam
https://infosecwriteups.com/easy-100-bypass-403-to-200-ok-b6bc126e2f4b
https://infosecwriteups.com/how-i-turned-a-403-error-into-a-200-api-key-leak-bounty-96faba78dfc4
https://infosecwriteups.com/crack-the-403-code-turn-forbidden-errors-into-bug-bounty-wins-1f5efe98b987
https://medium.com/@iski/from-403-to-fortune-how-i-became-an-accidental-admin-through-access-control-bypasses-d76f0c707098
https://infosecwriteups.com/bypassing-403-401-errors-all-hacker-techniques-revealed-0709ddfa99af
https://medium.com/@uday637/403-forbidden-a0843052612f
https://medium.com/@remmy9/403-forbidden-no-problem-heres-a-post-xss-eba84020ff70
https://infosecwriteups.com/how-403-forbidden-bypass-got-me-nokia-hall-of-fame-hof-8acbd2c1c2c8
https://medium.com/@Cybervenom/tale-of-easy-p1-bugs-in-wild-1b7f5bf80eef
https://infosecwriteups.com/403-bypass-lyncdiscover-microsoft-com-db2778458c33
https://medium.com/@driccosec/403-forbidden-bypass-leading-to-admin-endpoint-access-b696a36665ed
https://medium.com/@damaidec/403-bypass-on-a-fortune-100-financial-institution-p3-156d33bc6ed
https://www.darkanonsys.com/blogs/E1XTCpTgVy7V5njIXVB9
https://remonsec.com/posts/getting-first-swag-SIDN/
https://medium.com/@vishnurajr/403-forbidden-bypass-accessing-config-files-using-a-header-4bd172c25ff1
https://freedium-mirror.cfd/https://infosecwriteups.com/a-story-of-another-awesome-old-school-hacking-that-lead-to-a-cool-p1-bug-f88da04b1ecf
https://sapt.medium.com/bypassing-403-protection-to-get-pagespeed-admin-access-822fab64c0b3
https://freedium-mirror.cfd/https://infosecwriteups.com/importance-of-burp-history-analysis-to-bypass-403-afc7af6c08b
https://dewangpanchal98.medium.com/403-forbidden-bypass-fc8b5df109b7
https://freedium-mirror.cfd/https://notifybugme.medium.com/unauthorized-access-to-admin-setpassword-page-by-bypass-403-forbidden-f10bbb92ab35
https://medium.com/@nuraalamdipu/xss-403-forbidden-bypass-write-up-e070de52bc06
https://infosecwriteups.com/account-takeover-using-idor-and-the-misleading-case-of-error-403-cb42c96ea310
https://observationsinsecurity.com/2020/08/09/bypassing-403-to-get-access-to-an-admin-console-endpoints/
https://freedium-mirror.cfd/https://blog.viktormares.com/unusual-403-bypass-to-a-full-website-takeover-external-pentest-4970c788c6bf
https://freedium-mirror.cfd/https://infosecwriteups.com/5-sneaky-ways-to-bypass-403-forbidden-pages-zuri-98f0f3411641
https://freedium-mirror.cfd/https://infosecwriteups.com/how-hackers-try-to-bypass-403-forbidden-pages-and-guarantee-they-find-bugs-1119828a8c29
https://freedium-mirror.cfd/https://infosecwriteups.com/forbidden-but-not-forgotten-how-an-http-403-made-me-a-superadmin-6f769c4a9952
https://freedium-mirror.cfd/https://medium.com/@iski/from-403-to-fortune-how-i-became-an-accidental-admin-through-access-control-bypasses-d76f0c707098
https://freedium-mirror.cfd/https://osintteam.blog/mastering-403-bypass-unlock-hidden-bounties-like-a-pro-bc8ee954c209
https://freedium-mirror.cfd/https://infosecwriteups.com/100-200-worth-403-bypass-techniques-e4c22064091a
https://bitpanic.medium.com/mastering-403-bypass-techniques-a-penetration-testers-guide-f3a1cb16b9a3
https://infosecwriteups.com/common-403-bypasses-part-1-a455f2a1410b
https://infosecwriteups.com/common-403-bypasses-part-2-ae89060debec
https://medium.com/@nnface/my-first-bug-gitingore-exposure-combined-with-403-bypass-5db750e211ff
https://freedium-mirror.cfd/https://infosecwriteups.com/understanding-403-bypass-a-critical-vulnerability-in-web-application-security-2b9f0318f3a4
https://infosecwriteups.com/hunting-for-hidden-treasures-unveiling-the-403-bypass-bug-bounty-adventure-%EF%B8%8F-%EF%B8%8F-c6d17a0282ac
https://medium.com/@bughuntersjournal/unveiling-the-hidden-pathways-exploring-the-403-bypass-technique-and-effective-remediation-8cbd4f0546a5
https://freedium-mirror.cfd/https://blog.viktormares.com/unusual-403-bypass-to-a-full-website-takeover-external-pentest-4970c788c6bf 
https://medium.com/@pankajk.1540/all-about-404-bypass-fedb5371335e
https://freedium-mirror.cfd/https://medium.com/bug-bounty-hunting-a-comprehensive-guide-in/403-isnt-the-end-understanding-access-control-failures-in-web-applications-dab64f79bdcb
https://freedium-mirror.cfd/https://infosecwriteups.com/the-ultimate-guide-to-403-forbidden-bypass-2025-edition-1b2e852e503e
https://v1krammm.medium.com/nahamcon-ctf-2025-the-mission-b16d4f3279e4
tecnia de bypas header doble header en uno solo
https://medium.com/@reazatih/how-i-bypassed-403-forbidden-private-method-fc066c11f90f
https://theindiannetwork.medium.com/how-i-bypassed-403-forbidden-accessed-restricted-pages-real-world-exploit-e19ccb18bbbb
https://medium.com/@sonuoffsec/403-forbidden-bypass-technique-eda321012baa
https://infosecwriteups.com/403-forbidden-bypass-leads-to-hall-of-fame-ff61ccd0a71e
https://medium.com/@xelcezeri/breaking-the-walls-techniques-for-403-forbidden-bypass-c25034b822c6
https://freedium-mirror.cfd/https://bevijaygupta.medium.com/5-ways-to-bypass-403-forbidden-pages-like-a-pro-e9ced6c30aab
https://medium.com/@shadyfarouk1986/403-forbidden-bypass-techniques-the-ultimate-guide-0072457facba
https://freedium-mirror.cfd/https://it4chis3c.medium.com/how-ai-helped-me-to-bypass-403-forbidden-06becd32b999
https://freedium-mirror.cfd/https://medium.com/@kumawatabhijeet2002/mastering-403-forbidden-bypass-techniques-4ab1482afe49
https://freedium-mirror.cfd/https://anontriager.medium.com/403-401-bypass-methods-bash-automation-your-support-5468b93599fd
https://infosecwriteups.com/methods-to-bypass-403-401-38df4cec069e
https://freedium-mirror.cfd/https://infosecwriteups.com/bypass-403-response-code-by-adding-creative-string-irsyadsec-a6472c9010d0
https://infosecwriteups.com/ways-i-followed-to-bypass-403-your-checklist-fa3fc1256d2a
https://medium.com/@mohammed199709/improper-access-control-403-forbidden-bypass-489393ea112e
https://alb-soul.medium.com/xss-with-403-waf-bypass-for-and-document-cookie-998850c02bd5
https://systemweakness.com/how-to-bypass-403-forbidden-bypass-2330acc69069
https://medium.com/@uttamgupta_/14-bypass-403-forbidden-82df3cfe5386
https://sagarsajeev.medium.com/sensitive-data-exposure-via-403-forbidden-bypass-df9b4dcd0fd
https://freedium-mirror.cfd/https://infosecwriteups.com/importance-of-burp-history-analysis-to-bypass-403-afc7af6c08b
https://freedium-mirror.cfd/https://systemweakness.com/bypass-wordpress-403-in-bank-website-f6610f045736
https://rdnzx.medium.com/bypass-waf-403-forbidden-lead-to-cross-site-scripting-xss-ca7d30e510f3
https://python.plainenglish.io/how-to-get-around-a-403-forbidden-website-a14bcdd4feec
https://freedium-mirror.cfd/https://meetcyber.net/waf-this-way-real-world-bypass-tactics-from-the-trenches-0d2eaae9e32f
https://medium.com/@remmy9/beyond-the-wall-bypassing-otp-waf-and-403-for-exploiting-a-sql-injection-97f06a3527c0
https://medium.com/@moul_cyber/access-denied-not-really-a-complete-guide-to-forbidden-page-bypass-techniques-024ee810aae0
https://medium.com/@dipanshuchhanikar/bypassing-authentication-in-a-major-api-gateway-a-path-normalization-story-5f1bea6d3f08
https://medium.com/@rupaksahoo9/403-401-forbidden-bypass-automatic-tool-87b015714770

```

<br>


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3podm1rZ3Y4amU5d3hpdmxucGhydGd3MnF1ZndudzhlenV0eWxkMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/cByts7baForf4uj0eU/giphy.gif" width = 80px>  </picture> “Cada informe asimilado de 403 bypass es camino.”<img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3podm1rZ3Y4amU5d3hpdmxucGhydGd3MnF1ZndudzhlenV0eWxkMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/cByts7baForf4uj0eU/giphy.gif" width = 80px>
<br><picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
