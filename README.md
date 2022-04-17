# Desafio 01-NodeJS
## Nome: Luiz Emanuel j. Boldrindi

## Perguntas:

### **1.Para que serve o método Scrum?**
É uma metodologia ágil que é utilizada para gestão e organização de projetos que são complexos em que não se conhece todas as etapas ou necessidades. Tem como foco a distribuição de tarefas por etapas, em que o time de desenvolvimento realiza processos mais simples e claros, tendo em nota todo o caminho que foi percorrido.

### **2.Como funciona o método Scrum?**
Ele se inicia quando um projeto precisa de três fatores principais; transparência, Inspeção e Adaptação:
 * A transparência é quando todos os participantes têm   conhecimento dos requisitos de entrega do projeto, ou seja, o'que tem de ser entregado.
 * É feito inspeções ao longo de todo o projeto, seja nas reuniões diárias(daily) ou nos reviews.
 * Já a adaptação pode ser feita de duas formas; o produto que está sendo realizado pode sofrer alterações constantes, conforme as mudanças vem acontecendo, ou desde que preserve as características do do método scrum, pode ser adaptado de acordo com a realidade da empresa.

### **3.O que é Git?**
É um programa que, através dele, pode ter um controle das versões em que seu projeto vem a ser utilizado ou realizadas. Podendo ser compartilhado com outras pessoas, sem perder uma versão que você ou outra pessoa realizou anteriormente.
 * De forma mais simples, é um ambiente em que sem tem o histórico do seu projeto e que se pode voltar para qualquer alteração anterior.

### **4.O que é um scrum Product Owner?**
Mais conhecido como P.O. Tem o papel de ser o representante do cliente no time. É ele quem senta com o cliente e entende oque ele está buscando e, com isso, chegar em funcionalidades que façam sentido para o projeto. O P.O. tem como objetivo criar, alimentar e atualizar o *product backlog*.
 * Conjunto de trabalho ou processos que tem de ser realizados em um determinado tempo.

### **5.Qual o comando para criação de um novo repositório no Git?**
Utiliza-se o comando `git init`.

### **6.O que é o HTTP?**
HTTP(HyperText Transfer Protocol) é um protocolo de comunicação com conjunto de regras para a comunicação, que devem ser realizados pelo o usuário(mais especificamente pelo navegador) ou pelo desenvolvedor web.

### **7.Como funciona o HTTP?** 
 Ela é quem faz a "mediação" entre o cliente e o servidor, fazendo a comunicação entre os dois, onde o cliente pede uma resposta de busca para o servidor(ex: um html ou css de uma página) e o servidor envia a resposta do que foi solicitado, comumente conhecida com requisição.
 * Cada requisição é única, em que o navegador gera uma identificação para ela e manda pro navegador. 
 
### **8.Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando?**
 Utiliza-se o comando `git add NOME_DO_ARQUIVO` para adicionar um arquivo específico e `git add .` para adicionar todos os arquivos que foram alterados.

### **9.O que é a Branch master e para que serve?**
 Fazendo uma analogia e traduzindo para ramo; é como se todo o projeto fosse uma árvore e a "branch" fosse um ramo dessa árvore.
* Onde cada ramo tem um papel único para esta árvore.
  
A branch master é o ramo em que já iniciamos quando entramos em um repositório.
* É ele que vai absorver todas as alterações feitas por outros ramos, fazendo o papel central(ou de admin dentro do repositório).

### **10.Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?**
 Utiliza-se o comando `git pull` para atualizar o repositório. Utiliza-se o comando `git merge NOME_DA_BRANCH.`

### **11.Pensando em bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas?**
[ ]MySQL = MongoDB 

[ ]PostgreSQL = Redis

[ ]Oracle = CouchDB

[x]Todas as alternativas estão corretas. 

### **12.O que é MongoDB?** 
 É um software de Banco de Dados NoSQL, em que se armazena dados do tipo JSON. Ele deixa seu banco em aberto onde pode se fazer alterações e criar outros bancos de dados em cima do outro sem problema.
 * Todas as informações estão contidas em um único documento, ficando livre de esquemas e tabelas. 

### **13.O que é o MySQL?**
 É um software de gerenciamento de Banco de Dados SQL para armazenar e manipular dados definidos em modo de tabelas, onde se tem dois papéis importantes; servidor e cliente.
 * O servidor é responsável por armazenar os dados e enviar as respostas requisitadas.
 * O cliente se comunica através da linguagem SQL com o servidor.

### **14.Qual a diferença entre git e github?**
 Git é uma plataforma em que se pode manipular e compartilhar o código com outras pessoas se em funcionalidade. Já o GitHub é uma plataforma web em que envia o código já pronto e em funcionamento, funcionando como um portfólio dos seus projetos.
 * Em que qualquer pessoa(se deixar público), mesmo não sendo do projeto, possa visualizá-los e usá-los em seus respectivos projetos.
 * Em resumo, uma "rede social de código".

### **15.Quais os dois verbos http que podemos utilizar para realizar um update? Explique a diferença entre eles.**
O método PUT irá substituir um arquivo (ou recurso). Se não houver nenhum arquivo ou recurso lá, o método PUT cria um. Já o POST envia dados para um URI específico para manipular a solicitação. O servidor web, neste ponto, pode determinar o que fazer com os dados no contexto do recurso especificado.

### **16.Qual o status code que pode ser usado na criação de um novo usuário?**
 Status code `201(Created)`.

### **17.Quais são os três status code que podem ser utilizados para realizar o delete?**
 Para um delete bem sucedido mas ainda não foi decretada: `202-Accepted`. Se ela foi decretada e não precisa de nenhuma informação adicional: `204-No Content`. No caso da ação ter sido executada e a mensagem de resposta possuir descrição do status: `200-Ok`.

### **18.Qual a extensão ".xxx" contém as definições da tabela?** 
[ ]Commands.myi 

[ ]Commands.frm 

[x]Commands.myd

[ ]{mysqlDirectory}/data 

### **19.A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá. Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados?** 
[ ]/{database_name_folder}/{database_tables_and_files}.

[ ]C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm 

[x]C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd

[x]C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 

### **20.Qual a extensão ".xxx" que contém os dados da tabela?**
 A extensão `.ARZ`.

### **21.Qual comando usa-se para extração de arquivos em MongoDB durante a instalação?**
 Utiliza-se o comando `mongoexport`.

### **22.Para que usamos o MongoDB?**
Quando se precisa de um banco de dados livre e que seja não relacional, ou seja, livre de qualquer relação entre as tabelas que forem descritas no mongo.

### **23.Exemplifique para que serve os métodos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!** 
    1xx = Informação.
    2xx = Realizado com sucesso.
    3xx = Há uma necessidade de uma ação pelo browser.
    4xx = Erro com o cliente.
    5xx = Erro com o servidor(problema interno)

### **24.Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora:** 
 Foi muito interessante e educativo; foram disponibilizados vários cursos para entendermos que programação na web não se limita apenas a codar. Para que se possa chegar a um resultado positivo, existem vários caminhos ou trilhas para se seguir e com muitas outras pessoas(nada se faz sozinho). Espero que com esses conhecimento que foi adquirido possa me ajudar nos desafios que estão por vir e que possa retribuir da melhor forma possível, não só neste programa, mas também em futuros desafios no decorrer da vida. 
