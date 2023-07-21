# ExpressAndMongoDB
Docker compose mariadb and phpmyadmin


## Como rodar a aplicação
### Crie um .env e ajuste as variaveis como no .env.example
#### set the version of pgadmin image
PGADMIN_TAG=latest
#### set the version of postgres image
POSTGRES_TAG=latest
#### email pgadmin
PGADMIN_DEFAULT_EMAIL=pgadmin4@pgadmin.org
#### password pgadmin
PGADMIN_DEFAULT_PASSWORD=admin
#### postgres user
POSTGRES_USER=postgresusr
#### postgres password
POSTGRES_PASSWORD=postgrespwd

#### Na raiz do projeto rode:
docker-compose up -d

### Endereços e portas

<table>
  <tr>
      <td>Aplicacao</td>
      <td>Portas</td>
  </tr>
  <tr>
      <td>Mariadb</td>
      <td>3306</td>
  </tr>
   <tr>
      <td>Phpmyadmin</td>
      <td>127.0.0.1:8080</td>
  </tr>
</table>
