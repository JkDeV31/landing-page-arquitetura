# Landing Page Arquitetura — InDecor

Landing page **educacional** para simular a divulgação de um evento de design de interiores. O projeto apresenta a proposta do evento, benefícios, local ilustrativo e um formulário de inscrição **sem envio de dados**.

> **Atenção:** o evento, a data, o endereço e as inscrições são fictícios. Este site não representa um evento real nem recebe inscrições. Não informe dados pessoais reais no formulário.

**[Ver a demonstração no GitHub Pages](https://jkdev31.github.io/landing-page-arquitetura/)**

## Prévia da página

![Captura real da versão desktop da Landing Page Arquitetura InDecor, com apresentação do evento fictício, formulário demonstrativo e seções de ambientes](img/preview-desktop-arquitetura.webp)

*Captura completa da demonstração publicada. Projeto educacional: o evento é fictício e não recebe inscrições reais.*

## O que a página apresenta

- Seção de abertura com data ilustrativa e apresentação do evento fictício.
- Formulário visual de inscrição com campos de nome, e-mail, telefone e interesse. Os campos podem receber texto, mas não existe envio, backend ou armazenamento de inscrições pelo projeto.
- Seções de benefícios, localização, detalhes de decoração e chamada para visualizar o formulário.
- Layout com estilos adaptados a diferentes larguras por media queries.

## Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo.
- **CSS3** — estilização e regras de responsividade em arquivos separados.
- **Google Fonts** — tipografia carregada externamente.
- **Bootstrap Icons** — ícone de localização carregado por CDN.

Não há JavaScript nem sistema de inscrição implementado neste repositório.

## Organização

- `index.html` — conteúdo e formulário demonstrativo.
- `css/style.css` — estilos principais.
- `css/media-query.css` — estilos para diferentes larguras de tela.
- `img/` — imagens utilizadas no layout.
- `img/preview-social.jpg` — imagem de compartilhamento para links em redes sociais; reutiliza a foto já presente em `img/hrz-5.jpg`.

A página inclui metadados **Open Graph** e **Twitter Card** para apresentar título, descrição e imagem quando o link for compartilhado. A atualização das prévias em plataformas externas pode depender do cache de cada rede.

## Como executar localmente

1. Clone: `git clone https://github.com/JkDeV31/landing-page-arquitetura.git`
2. Abra a pasta do projeto.
3. Abra `index.html` em um navegador.

A tipografia e os ícones externos exigem conexão com a internet.

## Limitações e observações

- O formulário é um componente de demonstração, identificado por aviso e com botão de envio desabilitado.
- Os rótulos dos campos estão associados aos respectivos controles, e há indicação visual de foco para navegação por teclado.
- O botão da seção final agora é um link interno que leva ao formulário demonstrativo.
- A seção de benefícios apresenta temas ilustrativos de organização de ambientes, cores e materiais, móveis, iluminação e decoração. São exemplos editoriais de um evento fictício, não conteúdos de um evento real.
- Ainda não foi realizada auditoria completa de acessibilidade (WCAG), desempenho ou testes visuais em todos os dispositivos.

## Autor

Projeto educacional mantido por [JkDeV](https://github.com/JkDeV31).
