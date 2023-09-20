💡 Projeto Docker-Nginx
✔ Executar um container do nginx com site do api cep (https://viacep.com.br/exemplo/jquery/)

✔Executar o container com docker run Com imagem do Nginx

✔ Mapear um volume para adicionar index.html

💻 Comando utilizado para a criação do container
✔ docker run -d --name webserver -p 8080:80 -v C:\Users\raphaelsiston\Curso_docker\Projetos\Docker:/usr/share/nginx/html nginx