# Site pessoal

**Aluno:** Enzo Raitz

**Disciplina:** Programação para Web 1 (UTFPR, Câmpus Dois Vizinhos)

**Site publicado:** https://raitz-enzo.github.io/SitePessoal/

Projeto incremental: o mesmo site pessoal evolui a cada etapa, mantendo o histórico das versões no Git.

## Etapa 1: HTML puro

**Objetivo:** criar a primeira versão do site pessoal usando somente HTML (sem CSS, frameworks ou JavaScript), com estrutura semântica, imagem, navegação interna, links para perfis e um formulário de contato demonstrativo.

## Etapa 2: CSS externo

**Objetivo:** transformar visualmente a página da etapa 1, separando a estrutura e o conteúdo (`index.html`) da apresentação (`estilos.css`). Sem JavaScript e sem frameworks.

**O que foi aplicado:**

- arquivo CSS externo ligado por `<link rel="stylesheet">`;
- cores, tipografia, espaçamentos, bordas e tamanhos, com variáveis CSS;
- estilização de links, do menu fixo no topo e do formulário;
- organização visual das seções no formato de landing page: apresentação com botões, formação em linha do tempo e habilidades em etiquetas;
- estados `:hover`, `:focus` e `:disabled`;
- tema claro e escuro: segue o tema do sistema (`prefers-color-scheme`) e o botão "Claro / Escuro" do menu inverte a escolha, só com CSS;
- slideshow de destaques no meio da página, com troca automática por `@keyframes`, pausa ao passar o mouse e sem animação para quem prefere menos movimento;
- responsividade básica: `max-width` em `rem`, imagem com `max-width: 100%` e uma media query para telas pequenas.
