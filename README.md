# Gestor de Portefólio – Pro v1.5.5 (Sync)

Esta app é um PWA para gerir portefólios (ETFs, ações, PPR, ouro, crypto) com rebalanceamento, calculadora FIRE, actualizações automáticas de preços e sincronização via GitHub Gist.

## Como publicar
1. Faça download do ficheiro .zip com a app e extraia: `portfolio_mobile_v1_5_5_sync.zip`.
2. Na página do repositório no GitHub, escolha "Upload files" e adicione os ficheiros extraídos (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`) na raiz do repositório.
3. Faça commit das alterações.
4. Em Settings → Pages, seleccione a branch `main` e a pasta root (`/`) como fonte.
5. Espere alguns minutos e aceda ao URL gerado (`https://<seu-utilizador>.github.io/portfolio-pro/`).

Para instalar no telemóvel, abra o URL no browser (Android: menu → Add to Home screen; iOS: Partilhar → Adicionar ao Ecrã Principal).

## Sincronização de dados
A app permite sincronizar os seus dados entre dispositivos através de um Gist privado no GitHub:
- Criar um token GitHub com permissão `gist`.
- No separador Definições → Sincronização, introduzir o token e premir "Criar Gist".
- Repetir nos restantes dispositivos usando o mesmo token e o ID do Gist.
