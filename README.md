# escola-api

## Descrição
O projeto consiste em criar 3 serviços: Escola, Biblioteca e Autenticação. A Escola cadastra alunos, professores e turmas e interage com a Biblioteca para permitir que alunos e professores peguem mais livros emprestados. A Biblioteca empresta livros para usuários e precisa da Escola para saber se um usuário é aluno ou professor. O serviço de Autenticação armazena credenciais de login e senha e é usado pelos outros serviços para autenticar usuários. Juntos, esses serviços formam uma solução para gerenciar cadastros, empréstimos de livros e autenticação de usuários.

## Dependências
- [Composer](https://getcomposer.org/)
- [Laravel](https://laravel.com/)

## Executando o Serviço
Após instalar o Laravel, basta baixar o projeto. Uma vez com o projeto instalado na máquina, abra o terminal e digite:
```sh
composer install
```

Executar o serviço em uma porta específica:
```sh
php artisan serve --port=0000
```

Também é possível vincular a um host específica:
```sh
php artisan serve --host=0.0.0.0 --port=0000
```

Exemplos de porta:
```sh
8080
8001
8002
```
