
# Template Readme para Arquitetura MVC em Markdown
- Nome do Projeto: MVC-WEB CULTURE;
- Descrição: MVC para organizar e planejar site que tem como princípio organizar ;feedback entre alunos e professores no jogo "Cesim Game";
- Arquitetura: MVC (Model-View-Controller);
- Ferramenta de Diagramação: draw.io;

### Modelos (Models):
-   Usuário: O usuário interage com a aplicação através do cliente;

    Cliente: Representado pelo ícone do navegador, é a interface pela qual o usuário interage com a aplicação;

- Users estarão ultilizando os produtos;

### Controladores (Controllers):
-   USUÁRIOS: Gerencia operações LADP (Listar, atualizar, deletar, procurar) para usuários;

    PRODUTOS: Gerencia operações LADP (Listar, atualizar, deletar, procurar) para proutos;

- LADP:
Listar- fornece e mostra infos.
atualizar- atualiza infos.
deletar- apaga infos armazenadas.
procurar- encontrar informações.

- Controlador: Recebe e interpreta as entradas do usuário, solicitando informações ao modelo ou instruindo a view a se atualizar.

Modelo: Fornece dados ao controlador e reage às instruções do controlador para alterar esses dados.

Visão: Exibe os dados ao usuário e muda sua apresentação conforme instruído pelo controlador, baseando-se nas informações fornecidas pelo modelo.

### Views (Views):
- Home: Inclui componentes como a barra de navegação e membros do grupo.

Login: Local onde o usuário vai poder "imputar" suas informaçoes no navbar, tendo um dropdown que leva pro resto do site.

Feedback: Contém elementos para questões, envio e visualização de feedbacks.

### Infraestrutura:

- PostgreSQL: Sistema de gerenciamento de banco de dados onde as informações dos modelos são armazenadas e gerenciadas.

- No MVC, o modelo é responsável pela lógica de dados, que inclui armazenar, recuperar, e manipular informações do banco de dados. PostgreSQL, sendo um SGBD robusto e altamente confiável, gerencia esses dados.


### Justifique as escolhas feitas e como elas impactam o projeto.
#### Implicações da Arquitetura:
Descreva as implicações da arquitetura em termos de escalabilidade, manutenção, testabilidade e outros aspectos importantes.

É uma arquitetura relativamente simples e já q somos desenvovolvedores iniciantes isso é extremamente positivo. A manutenção está em meio a propria arquitetura já que é um sistema baseado no imput/output de dados. A testabilidade é positivamente facil, pois por não ser um sistema complexo temos acesso com facilidade ao erros que podem eventualmente ocorrer


