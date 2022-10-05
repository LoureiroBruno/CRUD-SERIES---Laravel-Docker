Passo a passo 

01 - Clone Repositório: 
git clone https://github.com/LoureiroBruno/curso_laravel_construindo_APIS-DOCKER.git

02 - Acessar o Repositório Via Terminal: 
respositorio baixado/ curso_laravel_construindo_APIS-DOCKER

03 - Baixar as Dependências: 
docker-composer up -d 

04 - Acessar o container da image series:
docker exec -it id_container bash

05 - composer install

05 - Crie o Arquivo .env: cp .env.example .env

06 - Gerar a key do projeto Laravel: php artisan key:generate
