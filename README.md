# Passo a passo 

# 01 - Clone Repositório
git clone https://github.com/LoureiroBruno/curso_laravel_construindo_APIS-DOCKER.git

# 02 - Acessar o Repositório Via Terminal
respositorio baixado/ curso_laravel_construindo_APIS-DOCKER

# 03 - Crie o Arquivo .env
cp .env.example .env

# 04 - Instalar o compose
composer install

# 05 - Gerar a key do projeto Laravel: php artisan key:generate

# 06 - Subir os containers: 
docker-composer up -d 

# 07 - Subir os containers: 
docker-composer up -d 

# 08 - Acessar o container da image series:
docker exec -it id_container bash 
php artisan storage:link 





