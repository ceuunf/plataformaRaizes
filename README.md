# Plataforma Raízes
Plataforma Raízes - Identificação, reconhecimento e entendimento racial.

🌍 Descrição Geral

A Plataforma Raízes é uma aplicação digital criada para promover a educação racial, o reconhecimento da identidade negra e o combate a expressões racistas por meio de questionários interativos, glossário explicativo e materiais informativos.
O sistema foi desenvolvido com integração emtre Front-end e Back-end, com o objetivo de garantir uma experiência acessível educativa e responsiva durante a Semana da Consciência Negra na faculdade Senac Recife.

🛠️ Tecnologias Utilizadas

+ Front-end: Figma (protótipo), HTML, CSS, JavaScript (para versão funcional)

+ Back-end: Python (Flask), Banco de Dados Relacional (SQLite)

+ Integração: QR Code para acesso rápido à aplicação

🎯 Objetivos

+ Promover o autoconhecimento e o reconhecimento racial.
+ Fornecer conteúdo educativo sobre termos e expressões racistas.
+ Coletar dados de forma relacional e segura para futuras análises
+ Criar uma experiência interativa e acessível durante o evento.

| Período                                    | Atividade Principal |
| ------------------------------------------ | ------------------- |
| Semana da Consciência (17–19/11)          | Divulgação e uso da plataforma
| Semana pós-feriado (24–28/11              | Exposição física do Mural
| 14/11                                     | Fixação dos QR Codes nos andares da escola

👥 Equipe Técnica

+ Front-end: Desenvolvimento da interface, design e interatividade.
+ Back-end: Infraestrutura do sistema, banco de dados e coleta de informações.

💻 2. Documentação Técnica — Front-end

O Front-end da Plataforma Raízes é responsável pela camada de apresentação, ou seja, toda a parte visual e interativa da aplicação. Ele foi projetado para garantir usabilidade, acessibilidade e coerência visual com o propósito educativo do projeto.

🎨 Principais Componentes

+ Tela inicial: nome do projeto, descrição e botão de acesso ao questionário.
+ Questionário de Identificação Racial: interface intuitiva com perguntas de múltipla escolha.
+ Pop-ups Informativos: pequenas janelas explicando termos racistas e conceitos sobre identidade racial, com base em um dicionário interativo.
+ Design Responsivo: adaptação a diferentes tamanhos de tela (desktop, tablet e mobile).
+ Sistema de Feedback: mensagem de conclusão e incentivo à reflexão.

🧠 Funcionalidades

+ Renderização de formulários dinâmicos com perguntas pré-carregadas.
+ Exibição de pop-ups com conteúdo educativo (glossário de termos).
+ Integração com o QR Code gerado pelo back-end para acesso rápido.
+ Validação básica dos campos de formulário.

⚙️ Tecnologias e Ferramentas

+ Figma: prototipagem visual e fluxos de navegação.

+ HTML5 / CSS3 / JavaScript: implementação base da interface.

🐍 3. Documentação Técnica — Back-end

O Back-end da Plataforma Raízes é responsável por gerenciar os dados, controlar a lógica do sistema e conectar o front-end ao banco de dados relacional. É a camada que vai garantir o funcionamento da aplicação e a persistência das informações dos usuários.

🧠 Funcionalidades Principais

+ Armazenamento de respostas dos questionários de forma relacional.
+ Geração de QR Code para acesso direto à aplicação.
+ Criação e gestão de uma comunidade
+ Controle de sessões e integração com o front-end.
+ Configuração de servidor local para testes (Flask).

🧩 Bibliotecas e Dependências

+ Flask: framework web principal
+ Flask-SQLAlchemy: Para banco de dados
+ Qrcode: geração de QR Codes
+ Pandas: manipulação de dados (para relatórios e análises futuras)
+ Requests / jsonify: comunicação com o front-end
