<h1 align="center">Devsbook</h1>

<p align="center">O Devsbook se trata de um site web desenvolvido em PHP para simular uma rede social de interações entre usuários, o mesmo se trata de um sistema de relações desenvolvido para praticar o conhecimento adquirido em cursos de PHP.</p>

## :camera: Demonstração

![Devsbook_ini](https://user-images.githubusercontent.com/52537183/163696046-8c359c21-1653-482b-bc16-9f45866d9e07.PNG)
![Devsbook_demo1](https://user-images.githubusercontent.com/52537183/163696050-2e44bda8-99cc-4895-9be3-8236b345c2ac.PNG)
![Devsbook_demo2](https://user-images.githubusercontent.com/52537183/163696054-270fd747-9deb-4229-97b3-8529a464e9cc.PNG)
![Devsbook_demo3](https://user-images.githubusercontent.com/52537183/163696056-70920fc9-bb5f-47f9-8ee1-eb9751ae801b.PNG)
![debsbook_demo4](https://user-images.githubusercontent.com/52537183/163696059-ec1e9a08-e7ba-4428-8e7f-63749215783a.PNG)
![Devsbook_demo5](https://user-images.githubusercontent.com/52537183/163696061-3d860b4f-b46b-4e45-9793-9361c7bff414.PNG)



# Funcionalidades

 - 1 - Login
 - 2 - Cadastro de usuário
 - 3 - Seguir usuário
 - 4 - Deixar de seguir usuário
 - 5 - Postagem de texto
 - 6 - Postagem de foto
 - 7 - Like em posts
 - 8 - Comentar em posts
 - 9 - Configuração geral de perfil
 - 10 - Trocar foto de perfil
 - 11 - Trocar foto da capa do perfil
 - 12 - Trocar informações de perfil
 - 13 - Trocar senha do usuário
 - 14 - Paginação de feed
 - 15 - Mecanismo de busca
 - 16 - Logout


# Rotas

  - 1 - $router->get('/', 'HomeController@index');

  - 2 - $router->get('/login', 'LoginController@signin');
  - 3 - $router->post('/login', 'LoginController@signinAction');

  - 4 - $router->get('/cadastro', 'LoginController@signup');
  - 5 - $router->post('/cadastro', 'LoginController@signupAction');

  - 6 - $router->post('/post/new', 'PostController@new');
  - 7 - $router->get('/post/{id}/delete', 'PostController@delete');

  - 8 - $router->get('/perfil/{id}/fotos', 'ProfileController@photos');
  - 9 - $router->get('/perfil/{id}/amigos', 'ProfileController@friends');
  - 10 - $router->get('/perfil/{id}/follow', 'ProfileController@follow');
  - 11 - $router->get('/perfil/{id}', 'ProfileController@index');
  - 12 - $router->get('/perfil', 'ProfileController@index');

  - 13 - $router->get('/amigos', 'ProfileController@friends');
  - 14 - $router->get('/fotos', 'ProfileController@photos');

  - 15 - $router->get('/pesquisa', 'SearchController@index');

  - 16 - $router->get('/config', 'ConfigController@index');
  - 17 - $router->post('/config', 'ConfigController@save');

  - 18 - $router->get('/sair', 'LoginController@logout');
  - 19 - $router->get('/ajax/like/{id}', 'AjaxController@like');
  - 20 - $router->post('/ajax/comment', 'AjaxController@comment');
  - 21 - $router->post('/ajax/upload', 'AjaxController@upload');
 
---

## 🚀 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:


- ✔️ PHP

- ✔️ MVC

- ✔️ Routes

- ✔️ MySql (PhpMyAdmin)

- ✔️ WampServer

- ✔️ Composer

- ✔️ JavaScript


## ⚙ Configuração via Composer

1- Para instalar o PHP (Mvc):
> git clone https://github.com/suporteb7web/mvc

2- Para iniciar sessão:
> Public/index.php 
       session_start();

3- Configurução do vendor:
> Composer install



Feito com 💜 por Jonathas Nunes 👋 [Veja meu Linkedin](https://www.linkedin.com/in/jonathasnunes-developer/)
<br>
