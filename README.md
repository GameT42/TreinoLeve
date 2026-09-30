# Treino Leve — PWA

Aplicativo web instalável no Android, com funcionamento offline e dados salvos no aparelho.

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Vá em Settings → Pages.
4. Em Source, escolha Deploy from a branch.
5. Selecione `main` e `/ (root)` e salve.
6. Abra a URL publicada no Chrome do Android.
7. Menu ⋮ → Adicionar à tela inicial / Instalar aplicativo.

O app usa localStorage e Service Worker, portanto os dados ficam no dispositivo e a interface funciona offline depois do primeiro carregamento.
