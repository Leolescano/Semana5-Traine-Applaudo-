Tarefa da Semana #5

Vamos criar uma aplicação Spring Boot. Para facilitar, usaremos o Spring Initializr para criar nossa aplicação Spring Boot. Para este projeto, utilizaremos Spring Web, Spring Data e H2 como banco de dados; tenha isso em mente ao gerar o projeto com o Spring Initializr.

O que precisamos alcançar?

Vamos desenvolver um processo de cadastro com as seguintes funcionalidades:

Criar um usuário:

Precisamos ser capazes de criar novos usuários em nosso repositório de dados (H2).
As informações que precisam ser capturadas são:
Email: um email válido e único.
Primeiro nome: obrigatório e com comprimento máximo de 50 caracteres.
Sobrenome: obrigatório e com comprimento máximo de 50 caracteres.
Número de telefone: valor opcional que deve seguir o padrão +503 #### ####.
Se o usuário já existir, um erro precisa ser retornado com a seguinte mensagem: “O usuário já existe com a conta de email fornecida”.
Se os dados não forem consistentes, um erro deve ser retornado indicando quais campos têm erros.
Atualizar um usuário:

Precisamos ser capazes de atualizar as informações do usuário em nosso repositório.
As únicas informações que podem ser atualizadas são:
Primeiro nome
Sobrenome
Número de telefone
Obter uma conta de usuário:

Precisamos ser capazes de localizar um usuário pelo email.
Precisamos retornar as seguintes informações quando o usuário for encontrado com o email fornecido:
Primeiro nome
Sobrenome
Número de telefone
Se o usuário não for encontrado, um erro deve ser reportado ao nosso consumidor indicando: “Não conseguimos encontrar um usuário com o email fornecido”.
Notas:

Lembre-se de seguir as melhores práticas que aprendemos nas últimas semanas.
Siga as melhores práticas ao nomear recursos e projetar seus endpoints.
Use uma estrutura bem organizada para o projeto, pacotes, classes e DTOs.
