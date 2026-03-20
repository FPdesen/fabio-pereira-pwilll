<!-- 1.O que é o Laravel ? -->
- O Laravel é um framework para aplicações web com sintaxe expressiva e elegante.

<!-- 2.Por que o Laravel ? -->
- O Laravel oferece ferramentas robustas para injeção de dependência , testes unitários , filas , eventos em tempo real e muito mais. O Laravel é otimizado para a construção de aplicações web profissionais e está pronto para lidar com cargas de trabalho corporativas.

<!-- Instalação -->
1.Requisitos:
- PHP (versão 8.1 ou superior)
- Composer (para instalar as dependências)

2.Formas de instalação
1. Via Laravel Installer 

Instale o instalador globalmente:

<!-- </>Bash -->

<!-- composer global require laravel/installer -->

Crie um novo projeto:

<!-- </>Bash -->

<!-- laravel new nome-do-projeto -->

2. Via Composer

Alternativa direta sem o installer:

<!-- composer create-project laravel/laravel nome-do-projeto -->

*Executando o projeto

Entre na pasta do projeto:

<!-- </>Bash -->

<!-- cd nome-do-projeto -->

Inicie o servidor local:

<!-- </>Bash -->

<!-- php artisan serve -->

A aplicação ficará disponível em:

<!-- http://localhost:8000 -->

*Configuração inicial

Copie o arquivo de ambiente:

<!-- </>Bash -->

<!-- cp .env.example .env -->

Gere a chave da aplicação:

<!-- </>Bash -->

<!-- php artisan key:generate -->

Configure o banco de dados no arquivo .env (se necessário).

🗄️ Banco de dados (opcional)

Execute as migrations:

<!-- </>Bash -->

<!-- php artisan migrate -->
