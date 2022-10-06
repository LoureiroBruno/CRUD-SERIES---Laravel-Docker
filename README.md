# Passo a passo 

# 1.0 - Clone Repositório
### git clone https://github.com/LoureiroBruno/curso_laravel_construindo_APIS-DOCKER.git

# 2.0 - Acessar o Repositório Via Terminal
### respositorio baixado/ curso_laravel_construindo_APIS-DOCKER

# 2.1 - Crie o Arquivo .env
### cp .env.example .env

# 2.2 - Instalar o compose
### composer install

# 2.3 - Gerar a key do projeto Laravel
### php artisan key:generate

# 2.4 - Criar arquivo SQLite: 
### cd database
### cat database.sqlite

# 4.0 - Subir os containers: 
### docker-composer up -d 

# 5.0 - Acessar o container da image series:
### docker exec -it id_container bash 
### php artisan storage:link 





