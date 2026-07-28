# RJ Auto Clean Automotive

Landing page desenvolvida para a **RJ Auto Clean Automotive**, empresa de estética automotiva localizada em Campina Grande - PB. O site apresenta os serviços oferecidos, galeria de trabalhos realizados, formulário de agendamento integrado ao WhatsApp e informações de contato.

## 🔗 Demonstração

Página única (single page), totalmente responsiva para desktop, tablet e mobile.

## 📋 Funcionalidades

- **Menu de navegação fixo**, com efeito de transparência ao rolar a página e menu mobile (hambúrguer) funcional
- **Seção Hero** com chamada principal e botões de ação rápida
- **Como Funciona** — passo a passo simplificado do atendimento
- **Diferenciais** — destaque dos pontos fortes do serviço
- **Sobre** — apresentação da empresa
- **Serviços** — catálogo dos serviços oferecidos
- **Serviço Diferenciado** — destaque para lavagem a domicílio, com imagens ilustrativas
- **Galeria** com efeito lightbox (clique para ampliar as imagens)
- **FAQ** — perguntas frequentes em formato acordeão
- **Agendamento** — formulário que monta automaticamente uma mensagem e a envia via WhatsApp, incluindo uma confirmação de disponibilidade (já que não há sistema de bloqueio de horários por banco de dados)
- **Contato** — endereço, WhatsApp, Instagram, horário de funcionamento e mapa incorporado do Google Maps
- **Botões fixos** de WhatsApp e "voltar ao topo"
- **Animações suaves** ao rolar a página (fade-in nas seções)
- **Favicon** configurado com a logo da empresa

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica das seções
- **CSS3** — estilização, grid/flexbox e media queries para responsividade
- **JavaScript (Vanilla)** — interatividade (menu mobile, lightbox, FAQ, scroll suave, formulário de agendamento, animações ao rolar)
- **Font Awesome** — ícones
- **Google Fonts** (Poppins e Inter) — tipografia
- **Google Maps Embed** — localização

Nenhuma dependência externa de build (sem Node.js, sem frameworks) — basta abrir o `index.html` em um navegador.

## 📁 Estrutura de pastas

```
rj-auto-clean/
├── index.html
├── README.md
└── imagens/
    ├── 1.png    → Logo (header e rodapé)
    ├── 2.png    → Imagem de fundo da seção Hero
    ├── 3.png    → Imagem da seção Sobre
    ├── 4.png    → Galeria - foto 1
    ├── 5.png    → Galeria - foto 2
    ├── 6.png    → Galeria - foto 3
    ├── 7.png    → Galeria - foto 4
    ├── 8.png    → Galeria - foto 5
    ├── 9.png    → Galeria - foto 6
    ├── 10.png   → Galeria - foto 7
    ├── 11.png   → Galeria - foto 8
    ├── 12.png   → Lavagem a domicílio - foto 1
    └── 13.png   → Lavagem a domicílio - foto 2
```

> Todas as imagens devem estar na pasta `imagens/`, na raiz do projeto, no mesmo nível do `index.html`.

## ▶️ Como usar

1. Baixe ou clone os arquivos do projeto
2. Crie a pasta `imagens/` na raiz do projeto
3. Adicione as 13 imagens numeradas conforme a tabela acima
4. Abra o `index.html` diretamente no navegador — não é necessário nenhum servidor ou instalação

## ✏️ Personalização

As informações de contato (WhatsApp, endereço, Instagram e horário de funcionamento) estão distribuídas ao longo do `index.html`, nas seções **Header**, **Contato**, **Agendamento** e **Rodapé**. Para atualizar o número de WhatsApp, basta substituir `5583993169622` em todas as ocorrências do arquivo.

## 👨‍💻 Desenvolvimento

Desenvolvido por **Kevin Ribeiro**.
