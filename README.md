# Aplicação de Blog Simples utilizando o Azure para fazer a integração da aplicação

Este repositório contém uma aplicação web simples de blog, desenvolvida como parte do curso Microsoft Azure Cloud Native. A aplicação permite a criação, visualização e remoção de posts.

## Funcionalidades

* **Criar Novo Post:** Adicione novos posts ao blog com um título e conteúdo.
* **Visualizar Posts:** Exibe uma lista de todos os posts criados.
* **Comentários:** Após o post criado pode ser inseridos comentários no mesmo.
* **Remover Post:** Selecione e remova posts existentes.

## Demonstração

### Primeiro Post Criado

Após criar o primeiro post, a tela principal do blog exibe-o.

![Primeiro blog criando](https://github.com/user-attachments/assets/5ae443b6-3fb7-4e22-bd83-b4ee18f8baff)

### Lista de Posts Criados

Com mais posts, a lista na página principal do blog se expande.

![Lista dos posts criados](https://github.com/user-attachments/assets/6c472a10-f6c9-4aa0-9ef2-b3395dc6effa)

### Inserindo comentários no post criado

Post "teste 2" inserindo comentários  

![Inserindo comentário no post teste 2](https://github.com/user-attachments/assets/32948ac7-c4dc-4807-8373-3e27bd97689e)

### Opção de Seleção para Remover Post

Ao clicar em "Remover Post Criado", é possível selecionar qual post será removido a partir de uma lista suspensa.

![Opção de seleção para remover post](https://github.com/user-attachments/assets/2af21e45-6c94-42d2-b707-11e9233ae50c)

### Informação de Remoção com Sucesso

Após a remoção de um post, uma mensagem de confirmação é exibida. Neste exemplo, o "TESTE 2" foi removido.

![Selecionado Teste 2 para remover](https://github.com/user-attachments/assets/453a4408-3524-4fe6-bed9-af70feb68cb3)

![Informação de remoção com sucesso](https://github.com/user-attachments/assets/8329bbf1-1fdf-4e50-8deb-b53c99cae350)

### Post "TESTE 3" Removido com Sucesso

Confirmação da remoção do post "TESTE 3".

![Selecionado teste 3 para ser removido](https://github.com/user-attachments/assets/df90e5a3-26be-4e33-927a-21db7b8a76b6)

![Post teste 3 removido com sucesso](https://github.com/user-attachments/assets/cfc9c244-5e7c-46b5-b053-8e23449ae946)

### Lista de Posts Criados (somente "TESTE" restante)

Após as remoções, a lista de posts é atualizada, mostrando apenas os posts que não foram removidos.

![Lista de post criados somente o post teste](https://github.com/user-attachments/assets/9208c37f-458e-4fe1-a28b-5c561c0492a0)

## Insights e Possibilidades

Durante o desenvolvimento desta aplicação de blog, aprendi e reforcei vários conceitos importantes:

* **Fundamentos de Desenvolvimento Web:** A estrutura básica de uma aplicação web, incluindo HTML para a estrutura, CSS para o estilo e JavaScript para a interatividade.
* **Interação com o Usuário:** Como criar formulários e elementos de interface que permitem ao usuário interagir com a aplicação (criação e remoção de posts).
* **Persistência de Dados (Simplificada):** Embora esta aplicação possa estar usando uma abordagem simplificada (talvez armazenamento local ou em memória para os fins do curso), ela introduz o conceito de como os dados são mantidos e manipulados. Em uma aplicação real, isso foi feito utilizando o azure para armazenamento na cloud.
* **Fluxo de Navegação:** Gerenciamento de diferentes "páginas" ou estados dentro da aplicação (página principal, página de remoção).
* **Comentários:** Adicionado um sistema de comentários para cada post já criado.
* **Feedback ao Usuário:** A importância de fornecer feedback claro ao usuário, como a mensagem de "Post removido com sucesso!", para indicar que uma ação foi bem-sucedida.
* **Implantação (Deployment):** Configurei a aplicação para ser implantada em serviços de nuvem (como Azure App Service) para torná-la acessível publicamente. Caminho do projeto Blog criação de posts https://blog-anderson-app.greenrock-68d2521b.eastus.azurecontainerapps.io

### Possibilidades Futuras

Esta aplicação simples pode ser expandida de diversas maneiras:

* **Backend Robusto:** Integrar um backend real com um banco de dados (SQL, NoSQL) para persistência de dados mais duradoura e escalável.
* **Autenticação e Autorização:** Adicionar funcionalidade de login para que apenas usuários autenticados possam criar, editar ou remover posts.
* **Edição de Posts:** Implementar a capacidade de editar posts existentes.
* **Categorias/Tags:** Organizar os posts por categorias ou tags para facilitar a navegação.
* **Paginação:** Para blogs com muitos posts, implementar paginação para melhorar o desempenho e a experiência do usuário.
* **Melhorias na Interface do Usuário (UI):** Utilizar frameworks CSS mais avançados (como Bootstrap, Tailwind CSS) para um design mais responsivo e moderno.
* **Frameworks JavaScript:** Migrar para um framework JavaScript moderno (React, Angular, Vue.js) para uma arquitetura mais organizada e escalável, especialmente para aplicações mais complexas.
* **Testes:** Adicionar testes unitários e de integração para garantir a robustez do código.
