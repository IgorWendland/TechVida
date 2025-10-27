# TechVida

**Projeto desenvolvido por:** Igor Wendland Venancio

**Resumo:** Plataforma web simples para ONG (tema TechVida). Implementa páginas: Início, Projetos e Cadastro. Projeto focado em acessibilidade (modo escuro), controle de versão e preparação para deploy.

## Estrutura do repositório
```
/
├─ index.html
├─ projetos.html
├─ cadastro.html
├─ css/
│  └─ style.css
├─ js/
│  └─ validate.js
├─ assets/
├─ screenshots/
├─ README.md
├─ CHANGELOG.md
└─ .gitignore
```

## Como executar localmente
1. Clone o repositório:
```
git clone https://github.com/SEU_USUARIO/TechVida.git
cd TechVida
```
2. Abra `index.html` no navegador ou use Live Server no VS Code.

## Branching e workflow (sugestão)
- main — produção
- develop — integração
- feature/* — novas features

## Acessibilidade (aplicada)
- HTML semântico, labels, landmarks, alt nas imagens.
- Contraste alto (modo escuro) e foco visível.
- Formulários com validação e feedback textual.

## Deploy
Recomendado GitHub Pages: Settings → Pages → main → / (root).
