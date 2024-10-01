Resumo curso Engenharia de Prompts da DIO

AWS step Fundactions

Para que eu consiga trabalhar com esses serviços o primeiro passo e ter uma conta na AWS e ter acesso a todas as funcionalidades e ferramentas.

\- Ter conhecimento outras ferramentas dentro do step functions para ter mais habilidades para desenvolver qualquer serviço.

Exemplos de Implantação de um serviço utilizando as ferramentas da AWS

\- Exemplo de uma aplicabilidade:

Aplicação de uma ferramenta de pedidos de Fast Food via aplicativo Delivery.

\- Usuário realizou o pedido > (API de USER MANAGEMENT) armazenar no histórico de pedidos do usuário e cupons de desconto > Gerenciamento de Push notifications do Restaurante para o cliente > (API DELIVERY APP) API de gerenciamento de estado do pedido

OBS: mesmo que o usuário esteja utilizando apenas uma tela no celular, estão acontecendo vários processos ao mesmo tempo, cada um tomando um tipo de ação e execução – está acontecendo um FLUXO de serviço.

Serviço de mensageria – Publisher

Como se fosse o carteiro – que leva as informações de cada serviço até os usuários

Exemplo de ferramenta de Mensageria: RabbitMQ

Step Functions funciona com as aplicações apenas com clica e arrasta, todo não tendo a necessidade de criar códigos.

Benefícios do Step Functions 

\- Integração rápida

\- Automação Simples

\- Processar dados sob demanda

\- Visualização da arquitetura orientada por eventos

O Step Functons funciona para você criar processos, automatizar processos, orquestrar micro serviços e criar Pipelines de dados e machine learn

Utilizando o Step Functions 

Acesse a Plataforma da AWS 

E no menu de engrenagem> Integração de Aplicativos >  e clique no Step Functions 

Entre na Máquina de estado e crie um novo projeto – Station Machine 

Comece a criar uma nova máquina de estado> será um novo projeto – um novo FLUXO DE TRABALHO – workflow

Escolha um tipo de pré automação que você queira trabalhar

Vá na opção: execute um fluxo de trabalho com apenas cliques – executar Hello World, escolher um novo modelo ou criar um fluxo do zero.

WorkFlow Studio & ASL

Amazon Station Ianguage (ASL)

Estrutura toda organizada baseada em JSON ( toda a estrutura em códigos por trás dos blocos NOCODE )

Tudo o que for criado em fluxos, são criadas todas a linguagem de códigos baseados em JSON, podendo até editar os códigos, modificando as informações também nos blocos e qual estado ele vai estar.

Criando Meu Primeiro Projeto-

Como executar um processo

Executando um novo projeto Hello World> verifico os blocos e vou entendo quais serão as suas ações de acordo com o comando que eu informar.

Início a execução e ele vai verificar todo o fluxo para informar qual o seu status, se está fluindo de acordo com o esperado ou seguiu o fluxo contrário.

Podendo visualizar todo os processos em forma de blocos ou em código, estruturado em JSON.

Existe também a opção de Estation View  para verificar toda a árvore do processo para saber como ocorre o fluxo.

Todos os Projetos podem ser criados e excluídos caso o queira se criar um novo estado de máquina, deixando de utilizar o anteriormente criado.

Criando um assistente de Delivery com AWS Step Functions e Badrock

Crie uma nova máquina de estado e use a opção: Execute o encadeamento de prompts de IA com Amazon Bedrock 

Uso a opção de Prompts Chains  e executo os prompts fornecidos automaticamente.

Verifico quais permissões estão disponíveis para o meu usuário, e vou realizando os desbloqueios das funcionalidades que tenho disponíveis.

Quanto as execuções dos processos vão dar erro até que todas as permissões sejam desbloqueadas e que tenha permissão para serem utilizadas de acordo com a região que está sendo utilizada, não sendo possível usar todas de acordo de onde você estiver usando o portal da AWS

Utilizando um modelo de LLM para a utilização do meu projeto vou utilizado a versão do CLAUDE 3.0 HAIKU e sempre lembrando de editar e salvar todas as minhas alterações feitas no projeto e utilizada as boas práticas de criação de Prompts aprendidas anteriormente no curso.

Lembrando que sempre e necessário adicionar as permissões para se criar o projeto e solicitar acesso a linguagem do código que estará intrínseco. 

Na prática: será criado um projeto de delivery de Fast Food, onde irei usar a plataforma da AWS, irei usar o Step Functions e o Bedrock.

Redefinindo as informações dos blocos já criados na área de trabalho da plataforma, consigo ir alterando os códigos e JSON em cara bloco já determinados e ir colocando as informações do meu prompt para que tenha as respostas e IA com as informações que solicitei.

Usando essas soluções do Step Functions junto com a IA do Bedrock podemos obter todos os tipos de resultados somente com clique e arrasta dos módulos.


