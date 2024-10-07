# Sistema de Biblioteca

Este é um sistema de gerenciamento de biblioteca desenvolvido em Python utilizando a biblioteca Tkinter para a interface gráfica e SQLite como banco de dados. O sistema permite adicionar autores, livros e gerenciar empréstimos.

## Funcionalidades

- Adicionar autores com nome e nacionalidade.
- Adicionar livros com título, autor, ano de publicação e gênero.
- Registrar empréstimos de livros, incluindo informações sobre o usuário e as datas de empréstimo e devolução.
- Visualizar todos os livros e empréstimos registrados.
- Buscar livros pelo título.

## Requisitos

- Python 3.x
- Tkinter (geralmente incluído com a instalação do Python)
- SQLite (geralmente incluído com a instalação do Python)

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/sistema-biblioteca.git
   cd sistema-biblioteca
Execute o script principal:
python seu_script.py
Substitua seu_script.py pelo nome do seu arquivo Python.

Estrutura do Banco de Dados
O banco de dados biblioteca.db contém as seguintes tabelas:

Autores

AutorID (chave primária)
Nome
Nacionalidade
Livros

LivroID (chave primária)
Titulo
AutorID (chave estrangeira)
AnoPublicacao
Genero
Emprestimos

EmprestimoID (chave primária)
LivroID (chave estrangeira)
DataEmprestimo
DataDevolucao
NomeUsuario
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto é licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.
