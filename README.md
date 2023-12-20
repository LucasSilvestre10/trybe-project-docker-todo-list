# Docker Todo List

## Descrição do Projeto
Este repositório contém a implementação do projeto Docker Todo List proposto no curso da Trybe. O objetivo é conteinerizar uma aplicação full-stack de lista de tarefas, criando os arquivos de configuração para o Front-end, Back-end e um aplicativo de teste.

### Comandos Docker
1. **Crie um container interativo, sem executá-lo, nomeado como 01container, utilizando a imagem alpine na versão 3.12:**
   - ✅ Arquivo: `./docker/docker-commands/command01.dc`

2. **Inicie o container 01container:**
   - ✅ Arquivo: `./docker/docker-commands/command02.dc`

3. **Liste os containers filtrando pelo nome 01container:**
   - ✅ Arquivo: `./docker/docker-commands/command03.dc`

4. **Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele:**
   - ✅ Arquivo: `./docker/docker-commands/command04.dc`

5. **Remova o container 01container:**
   - ✅ Arquivo: `./docker/docker-commands/command05.dc`

6. **Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container:**
   - ✅ Arquivo: `./docker/docker-commands/command06.dc`

7. **Rode um novo container nginx 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para a porta 3000 do sistema hospedeiro:**
   - ✅ Arquivo: `./docker/docker-commands/command07.dc`

8. **Pare o container 02images que está em andamento:**
   - ✅ Arquivo: `./docker/docker-commands/command08.dc`

### Dockerfile
9. **Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend:**
   - ✅ Arquivo: `./docker/docker-commands/command09.dc`

    - ✅ Arquivo: `./docker/todo-app/back-end/Dockerfile`

10. **Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend:**
    - ✅ Arquivo: `./docker/docker-commands/command10.dc`

    - ✅ Arquivo: `./docker/todo-app/front-end/Dockerfile`

11. **Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests:**
    - ✅ Arquivo: `./docker/docker-commands/command11.dc`

    - ✅ Arquivo: `./docker/todo-app/tests/Dockerfile`

### Docker-compose
12. **Suba uma orquestração em segundo plano com o docker-compose para que backend, frontend e tests consigam se comunicar:**
    - Arquivo: `./docker/docker-compose.yml`
