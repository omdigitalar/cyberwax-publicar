# cyberwax-publicar

Robot que publica la web de Cyberwax (cyberwax.com.ar). Solo tiene los workflows de GitHub Actions: el código de la
web está en un repo privado y se baja en cada corrida con un token de solo lectura. Al ser público, Actions no consume
minutos pagos.

- **Web beta rápida**: cada 30 min (y cuando el Admin la dispara) sube solo las fichas que cambiaron.
- **Web beta**: una vez por noche, o a mano (Actions → Web beta → Run workflow), rearma y sube todo lo que cambió.
