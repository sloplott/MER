# MER
Atividade de MER
![Diagrama sem nome drawio](https://github.com/user-attachments/assets/da635cc4-37ea-44b2-89f9-d7357f4087fe)
 Uma biblioteca solicitou a criação de um software e para realizar o planejamento para o desenvolvimento
da aplicação solicitada, foi necessário conversar com a bibliotecária e entender todos os cadastros que
realizava nas fichas manuscritas, que são:
• Livro: Representa um livro físico ou digital disponível na biblioteca.
• Usuário: Representa uma pessoa que pode pegar livros emprestados.
• Empréstimo: Representa o ato de um usuário pegar um livro emprestado.
• Autor: Representa o(s) autor(es) de um livro.
• Editora: Representa a editora que publicou um livro.
• Gênero: Representa o gênero literário de um livro.
Para cada ficha eram coletadas as seguintes informações:
• Livro:
o ISBN (Identificador único)
o Título
o Ano de Publicação
o Número de Páginas
o Edição
o Sinopse
o Capa
• Usuário:
o ID (Identificador único)
o Nome
o CPF
o Endereço
o Telefone
o E-mail
• Empréstimo:
o ID (Identificador único)
o Data de Início
o Data de Devolução
o Status (Em aberto, Devolvido)
• Autor:
o ID (Identificador único)
o Nome
o Nacionalidade
o Data de Nascimento
• Editora:
o ID (Identificador único)
o Nome
o Endereço
• Gênero:
o ID (Identificador único)
o Nome
Logo, foi necessário entender a relação entre as fichas e o funcionamento da biblioteca, tendo as seguintes
informações:
• Um Livro é escrito por um ou mais Autores.
• Um Livro é publicado por uma Editora.
• Um Livro pertence a um ou mais Gêneros.
• Um Usuário pode pegar emprestado um ou mais Livros.
• Um Empréstimo envolve um Usuário e um Livro.
