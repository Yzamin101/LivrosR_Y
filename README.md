Este é um sistema simples feito em PHP com MySQL para cadastrar e editar livros.

Pré-requisitos: Você precisa ter PHP 7 ou superior instalado, MySQL, e um servidor local como XAMPP ou WAMP.

Instalação: Crie um banco de dados chamado livros_db. Em seguida, execute a seguinte instrução SQL para criar a tabela:

CREATE TABLE livros ( id INT AUTO_INCREMENT PRIMARY KEY, titulo VARCHAR(255), autor VARCHAR(255) );

Depois, edite o arquivo config.php com os dados de acesso ao seu banco de dados. Abra o index.php no navegador para começar a usar.

Funcionalidades: Você pode listar os livros cadastrados, adicionar novos livros, e editar livros já existentes.

Esse projeto foi feito para ser direto, funcional, e fácil de entender — ideal para testes ou uso como base para algo mais avançado.
