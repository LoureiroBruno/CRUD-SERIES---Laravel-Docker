## como subir a aplicação

### clonar o repositorio 
- git clone https://github.com/LoureiroBruno/curso_laravel_forms_sessoes_relacionamentos.git
### acessar o repositorio clonado 
- cd curso_laravel_construindo_APIS-DOCKER/
### baixar as dependency
- composer install
- criar arquivo env
- cp .env.example .env
### criar banco sqlite
- database.sqlite
### rodar as migrações 
- php artisan migrate
### gerar a key projeto
- php artisan key:generate
### subir a aplicação
- php artisan serve
