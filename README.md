# Blog-website
Blog-website é um sistema de um blog que apresenta 4 páginas. A primeira, a página Home, responsável por exibir todos os posts carregados do banco de dados, no caso o mongoDB utilizado na aplicação, além de conter uma barra de navegação que contém 3 menus: home, para retornar à página principal da aplicação, about us, que redireciona para a rota "/about", e contact us, que redireciona para a rota "/contact". A segunda página, About, contém informações sobre o blog, que no caso são preenchidas por textos Lorem Ipsum. Já a terceira página, Contact, contém informações de contato do blog, mas que também são preenchidas por dados Lorem Ipsum. Já a última página da aplicação, é uma página secreta, que só pode ser acessada digitando a rota no navegador "/compose". Nela é possível criar novos posts, que contém um título e um conteúdo, e que serão armazenados no banco de dados para serem exibidos na página home. </br></br>
Esse projeto foi desenvolvido utilizando as tecnologias de programação HTML, CSS, JavaScript, Express e EJS, bem como o banco de dados não-relacional mongoDB, junto da ODM (Object Data Mapping) mongoose, similar ao ORM. </br></br>
## Visualização do projeto (Local hosting):
#### Página home:
Responsável por renderizar os posts do banco de dados. Cada post possui um título e um conteúdo, que é carregado seguindo a lógica que cada conteúdo é exibido até o caractere 200, caso este seja um ponto ("."), caso contrário, será exibido até o próximo ponto após o caractere 200. Após o ponto, tem-se uma anchor tag (Ler mais), que redireciona para a rota específica do post, que contém seu conteúdo completo. </br></br>
![image](https://user-images.githubusercontent.com/80121288/158444977-0c8a8e25-0eaa-47a0-814f-bec3074237f5.png) </br></br>
#### Página about:
![image](https://user-images.githubusercontent.com/80121288/158445942-2cb70fa7-70c2-4cdb-adfd-7ac61555a56c.png) </br></br>
#### Página contact:
![image](https://user-images.githubusercontent.com/80121288/158445985-c9bc5e9e-ab97-49e3-8924-8d49788014ab.png) </br></br>
#### Página compose:
![image](https://user-images.githubusercontent.com/80121288/158446064-5860205f-b83a-43a3-babb-e50d75599e1a.png) </br></br>
Ao criar um novo post, o usuário é redirecionado para a página home e poderá visualizar o novo post abaixo do post default "Home": </br></br>
![image](https://user-images.githubusercontent.com/80121288/158446368-b07301fb-cf22-41af-a6a9-1a16edc8428f.png) </br></br>
![image](https://user-images.githubusercontent.com/80121288/158446427-152519c6-b274-47f6-bf93-86538f2a8deb.png) </br></br>
Criando outro post: </br></br>
![image](https://user-images.githubusercontent.com/80121288/158446585-8f1082bc-5cb8-4d2b-9f02-5a3c7db6290a.png)
</br></br>
![image](https://user-images.githubusercontent.com/80121288/158446624-e6b8a7d0-695a-4d4f-a454-5835db337116.png)
</br></br>
Para obter o projeto em seu repositório local, execute o seguinte comando no seu terminal, dentro da pasta que deseja adicionar o projeto: $ git clone https://github.com/Thiago-Gonzalez/Blog-website.git (caso o git não esteja inicializado na pasta, $ git init)
