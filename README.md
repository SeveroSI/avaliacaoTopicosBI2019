# avaliacaoTopicosBI2019
# Avaliação do 1º Bimestre 2019 - Tópícos de SI
## Especificações Técnicas
* Utilizar a API do JSONPlaceHolder 
* Cores livres, imagens livres
* Criar uma API através do NodeJS que consuma a API do JSONPlaceholder.
* Todas as rotas deverão ser criadas pelo NodeJS
* Usar o Git
* Desenvolver um frontend que comunique com a API que você criou!

## Especificações funcionais
### Tela inicial
* Esta tela terá uma lista de usuários contendo as informações (Nome, Email e Telefone) alinhados à esquerda. Alinhado a direita deverá ter um botão com o texto "Ver Álbuns". 
Quando for clicado no botão "Ver Álbuns" deverá ser redirecionado para a tela de lista de Álbuns, onde listará somente os álbuns daquele usuário.
* URL: é:  https://jsonplaceholder.typicode.com/users

### Tela de Lista de Albuns 
* Esta tela terá uma lista de álbuns com as seguintes informações: (título e ícone) e botão ("Ver fotos").
Quando o usuário clicar no título do Álbum ou no botão "Ver fotos" deverá ser redirecionado para a página Tela de Lista de Fotos.
* URL: https://jsonplaceholder.typicode.com/albuns?userID={userId}

### Tela de Lista de Fotos
Esta tela terá informações referente (Imagem da Foto, Título da Foto) ao clicar sobre o título ou a imagem deverá abrir a foto em uma nova target.
Também deverá existir 3 ícones alinhados a direita referente ao feedback do usuário sobre aquelas fotos.

* URL: https://jsonplaceholder.typicode.com/photos?albumID={albumId}


## O que será avaliado
* Organização do Projeto
* Uso do Git

## Extra
* Na tela de Lista de Fotos, os ícones que se referem ao feedback, deverá ser implementado uma algoritmo que adicione valores randômicos para cada um dos comportamentos do usuários.
* Ao clicar no link de conversas, na terceira tela deverá exibir um modal, com um texto fictício.
* Documentar através do README.md as intruções para execução do APP.
* Interface gráfica bonita


## Layout (Sugestivo)
https://www.figma.com/file/UJJvQdnEhx9Cs2rWRv0xbTg8/Avalia%C3%A7%C3%A3o-de-T%C3%B3picos-de-SI?node-id=0%3A1


## Demonstração 
[![Everything Is AWESOME](https://i.ytimg.com/vi/rgwcyH4xQww/hqdefault.jpg)](https://www.youtube.com/watch?v=rgwcyH4xQww "Vídeo de Demonstarção")









