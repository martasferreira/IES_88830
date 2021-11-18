# IES_88830
##lab1



### Review Questions

### a)
 Uma Java **Servlet** é uma classe que corre no servidor e tem a função de receber, processar e responder aos pedidos do cliente. O *servlet container* é um componente do servidor responsável pela gestão dos pedidos que permite a geração de páginas dinâmicas. Este é então responsável por receber os pedidos do cliente, converte-los em chamadas às classes Java que implementam a classe Servlet e receber as respostas destas classes que depois encaminha para o cliente. É ainda responsável pela gestão da concorrência, permitindo o processamento de múltiplos pedidos em simultâneo.

### b)
O Spring usa MVC (Model, View, Controller) para servir o conteúdo da web:
-> O modelo é a camada lógica da aplicação. O framework Spring possui o org.springframework.ui.Model que permite mapear atributos para serem posteriormente renderizados nas visualizações.
-> A visualização é a camada "front-end" e geralmente é armazenada na pasta de modelos de um projeto Spring
-> O controlador aceita inputs e converte-os em comandos para o modelo ou vista. Spring tem uma anotação especial para designar uma classe como um Controlador.


### c)
As dependências iniciais permitem simplificar a construção do sistema, padronizando alguns aspectos do mesmo.


### d)
 **`@SpringBootApplication`** identifica a classe base do projeto, aplicando as configurações por defeito. ESta anotação adiciona:
-> @ComponentScan: Ativa a pesquisa pelas classes componente. Diz ao Spring para procurar outros componentes, configurações e serviços no pacote *com/example*, permitindo que ele encontre os controladores.
-> @Configuration: Permite o registo de componentes da aplicação adicionais e importa classes de configuração. Marca a classe como uma fonte de definições de bean para o contexto da aplicação.
-> @EnableAutoConfiguration: Ativa o mecanismo de configuração automática com base nos ficheiros jar gerados.Diz ao Spring Boot para começar a adicionar beans com base nas configurações do classpath, outros beans e várias configurações de propriedade.



### e).
-> Utilizar a linguaguem JSON para comunicar pois é de fácil leitura e compacta. Esta é uma das linguaguens mais conhecidas e utilizadas;
-> Ter várias versões de uma API. Uma vez que estamos em constante desenvolvimento, é seguro ter diferentes versões para que não hajam problemas no futuro com atualizações;
-> Retornar detalhes de erros no JSON ou na resposta para que seja mais fácil para o utilizador fazer o seu debug;
-> Utilizar dados em cache, em memória local, para que seja mais rápido obter a informação pretendida. Assim, não será necessário consultar sempre a base de dados;
-> Limitar o aninhamento na REST API
