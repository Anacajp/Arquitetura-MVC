# Arquitetura-MVC

Antigamente, ao desenvolver software, as estruturas de código eram confusas e não tinham uma orientação clara, o que resultava em baixo reaproveitamento de código, aumento de bugs e dificuldades para outros programadores entenderem e dar continuidade ao programa. 

Para resolver esse problema, foi definido o padrão MVC, uma arquitetura baseada em três camadas: [model, view e controller](https://drive.google.com/file/d/1WvG34rT4zH6xZZbqt4eH53f6MNl324cq/view?usp=sharing). Essas camadas definem como o software deve se comportar de acordo com as solicitações do usuário, facilitando o entendimento passo a passo de sua execução ideal.


![MVC6](https://github.com/Anacajp/Arquitetura-MVC/assets/159061342/9c5fac8c-288b-4587-96bb-ddf31be86883)


CLIENTE

O primeiro contato que o usuário possui com o sistema é por meio do Browser (navegador/cliente), que atua permitindo o acesso do usuário à internet. O Chrome é o navegador presente no modelo de MVC apresentado, mas há diversos outros navegadores como Opera, Mozilla Firefox, Safari, entre outros.

CONTROLLER

Dentro do padrão MVC, o Controller é uma parte essencial responsável por facilitar a comunicação entre o Modelo e a Visualização. Ele atua como um intermediário que recebe as entradas dos usuários e encaminha essas requisições para o Modelo ou a Visualização conforme necessário. 

MODEL

Após receber a requisição do Controller, o Model atua para buscar os dados solicitados no banco de dados. Uma vez que os dados são recuperados com sucesso, o Model os entrega ao Controller, que pode então proceder com as próximas etapas do fluxo da aplicação.

VIEW

Após o Controller receber os dados do Model, ele os encaminha para o View, que é responsável por traduzir esses dados em elementos visuais compreensíveis para o usuário. O View é a camada de apresentação da aplicação, onde são definidas a interface gráfica e a forma como as informações serão renderizadas ao usuário final.

INFRAESTRUTURA

No processo de desenvolvimento do software, faremos uso de diversas ferramentas, incluindo Sails, Node.js, JavaScript, Render, HTML e CSS. Essa seleção de tecnologias não apenas proporciona uma construção rítmica e concisa da aplicação, mas também oferece uma base sólida para garantir sua eficiência.

SAILS

O Sails é projetado para facilitar o desenvolvimento rápido de aplicações web, é especialmente útil para criar APIs e é usado para deixar o sistema escalável para lidar com grandes volumes de dados.

NODE.JS

O Node.js tornou-se uma escolha dominante na construção de back-ends com o modelo JavaScript, proporcionando uma plataforma robusta e eficiente para desenvolver aplicativos web escaláveis e de alto desempenho.

HTML

Linguagem de marcação baseada em hiperlinks, utilizada para a estruturação base de um site. Com ela, há a possibilidade de incrementar imagens, arquivos, links, etc.

CSS 

Com o CSS, os desenvolvedores podem criar recursos visuais esteticamente agradáveis, definindo cores, fontes, espaçamento, layout e outros aspectos visuais de uma página.	



