# You GPS — primeira versão web

Aplicativo web estático com mapa OpenStreetMap/Leaflet e localização local do dispositivo, mediante permissão. **Ainda não compartilha localização com outras pessoas.**

## Publicar usando GitHub e Vercel
1. Crie um repositório novo no GitHub, por exemplo `you-gps`.
2. Clique em **Add file > Upload files** e envie `index.html`, `manifest.webmanifest` e `vercel.json` (não envie apenas o ZIP).
3. No Vercel, clique em **Add New > Project**, importe o repositório e selecione **Other** como framework, caso seja solicitado.
4. Deixe o comando de build em branco e o diretório de saída como raiz do projeto; clique em **Deploy**.
5. Abra o endereço HTTPS da Vercel no Android, toque em **Encontrar minha localização** e conceda permissão.

## Limitações
A versão atual não possui login, convites, servidor, banco de dados nem rastreamento em segundo plano. O mapa precisa de internet. Os serviços públicos de tiles do OpenStreetMap possuem política de uso; para escalar, contrate provedor adequado. Geolocalização depende de HTTPS e permissão do navegador. O manifesto não inclui ícones de instalação; suporte de instalação PWA pode variar.
