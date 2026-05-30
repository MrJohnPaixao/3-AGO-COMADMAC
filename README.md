# 3ª AGO COMADMAC 2026

Site oficial do projeto visual da **3ª Assembleia Geral Ordinária da COMADMAC**.
Convenção dos Ministros das Assembleias de Deus da Missão no Acre.

**📅 13 e 14 de Junho de 2026 · IEADM Acrelândia — AC**

---

## 🗂️ Estrutura

```
comadmac-2026/
├── index.html          # Página inicial (landing page)
├── banner/
│   └── index.html      # Banner horizontal — tela cheia, força landscape
└── vertical/
    └── index.html      # Versão Stories — formato 1080×1920
```

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `comadmac-2026`)
2. Faça upload da pasta inteira (ou use `git push`)
3. Vá em **Settings → Pages → Source: main / root**
4. Acesse: `https://seu-usuario.github.io/comadmac-2026/`

## 📱 Funcionamento Mobile

- **index.html** — responsivo, funciona em qualquer tela
- **banner/** — exibe overlay "Vire o celular" em portrait; em landscape ocupa tela cheia e solicita fullscreen ao toque
- **vertical/** — visualização do banner Stories no browser mobile

## ✏️ Personalização

Para atualizar nomes e cargos da mesa diretora, edite o array `ROLES` nos arquivos `banner/index.html` e `vertical/index.html`.

---

COMADMAC · 2026