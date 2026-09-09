# Portfólio pessoal

Site estático (HTML/CSS/JS puro, sem frameworks ou dependências externas) para portfólio, currículo e materiais de ensino.

## Estrutura

```
portfolio/
├── index.html      → conteúdo do site (todas as seções)
├── css/style.css   → estilo (paleta, layout, responsividade)
├── js/main.js      → pequenos comportamentos (menu mobile, ano no rodapé)
└── assets/         → coloque aqui seu curriculo.pdf e outras imagens/arquivos
```

## Como editar o conteúdo

Abra o `index.html` e substitua os textos entre colchetes, ex: `[Seu Nome]`,
`[Nome do projeto 1]`. As seções são: Sobre, Currículo, Projetos, Disciplinas,
Publicações e Contato. Comentários HTML marcam onde escrever textos mais longos.

Para trocar as cores, edite as variáveis no topo de `css/style.css` (bloco `:root`).
O site já se adapta automaticamente a modo claro/escuro do sistema.

## Como visualizar localmente

Basta abrir `index.html` no navegador — não precisa de servidor.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `seu-usuario.github.io` para ficar na raiz,
   ou qualquer outro nome).
2. Dentro desta pasta, rode:
   ```bash
   git init
   git add .
   git commit -m "Primeira versão do portfólio"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
   git push -u origin main
   ```
3. No GitHub, vá em **Settings → Pages**, selecione a branch `main` e a pasta `/root`.
4. Em alguns minutos o site estará em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`
   (ou `https://SEU_USUARIO.github.io/` se o repositório tiver esse nome).
