Tato & Nando - Agendamento de Shows

Este é um projeto front-end que facilita o agendamento de shows da dupla sertaneja Tato & Nando. O site permite que os usuários preencham um formulário para solicitar o agendamento de um show e conta com uma área restrita para administradores.
Funcionalidades

    Página Inicial: Apresenta a dupla Tato & Nando e oferece a possibilidade de agendar shows.
    Formulário de Agendamento: Os usuários podem preencher informações como nome do contratante, contato, local do evento e data para solicitar um show.
    Acesso Restrito: Uma área de login para administradores, que futuramente pode ser conectada a um banco de dados para gerenciar as solicitações.
    Entrevistas: A página contém links para entrevistas da dupla no Globo Play.
    Responsividade: O site foi projetado para ser responsivo e funcionar em dispositivos móveis e desktop.

Estrutura do Projeto

O projeto é dividido em várias páginas e arquivos de estilo e mídia:

    index.html: Página inicial com uma introdução à dupla e opção de agendar shows.
    login.html: Página de login (Acesso restrito).
    agendar.html: Formulário de agendamento de shows.
    area-restrita.html: Página de área restrita, que futuramente exibirá as solicitações de agendamento.
    styles.css: Arquivo de estilos CSS que define o layout e a aparência do site.
    Mídias: Arquivos de imagens e vídeos para a apresentação visual.

Tecnologias Utilizadas

    HTML5: Estrutura das páginas.
    CSS3: Estilização do site, incluindo responsividade.
    JavaScript (Opcional): Potencial futuro para validação do formulário no lado do cliente.

Como Utilizar

    Clone o Repositório:

    bash

    git clone https:https://github.com/beatrizborgex/front-end.git

    Abra o projeto: Navegue até a pasta onde o repositório foi clonado e abra o arquivo index.html em um navegador.

    Explorar o site:
        Use o link "Agendar Show" na página inicial para acessar o formulário de agendamento.
        O link "Acesso Restrito" leva à página de login, onde futuramente será possível gerenciar as solicitações de agendamento.

Estrutura de Arquivos

bash

├── index.html
├── login.html
├── agendar.html
├── area-restrita.html
├── favicon.ico
├── README.md
├── css
│   └── styles.css
├── midias
│   ├── 20-anos.mp4
│   ├── capa-video1.png
│   ├── capa-video2.png
│   └── foto-inicial.jpg
└── icons
    ├── instagram-icon.png
    └── youtube-icon.png

Melhorias Futuras

    Integração com Banco de Dados: Adicionar um backend para processar e armazenar as solicitações de agendamento.
    Autenticação de Usuários: Implementar um sistema de autenticação completo para proteger a área restrita.
    Validação de Formulário: Adicionar validações em JavaScript para garantir que os dados inseridos no formulário estão corretos antes de enviar.

