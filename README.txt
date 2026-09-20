PWA - Relatório de Produção do Turno

Estrutura:
- index.html: aplicação original com suporte PWA adicionado
- manifest.json: instalação como aplicativo
- sw.js: cache e funcionamento offline do app shell
- icons/: ícones do aplicativo

Publicação recomendada:
1. Crie um repositório no GitHub.
2. Envie TODOS estes arquivos para a raiz do repositório.
3. Settings > Pages > Deploy from a branch > main > / (root).
4. Aguarde a publicação.
5. Abra a URL no Chrome do celular.
6. Use "Instalar aplicativo" ou "Adicionar à tela inicial".

Observação: o código original usa bibliotecas externas (Chart.js, html2canvas e jsPDF). O app shell fica disponível offline, mas alguns recursos podem exigir conexão na primeira utilização, dependendo do cache do navegador.
