# FullCycle
   Sobre o Sistema<br>
   Code Pix - Transações de um banco para o outro gerenciadas pelo goLang.
<hr>
   
   # Tecnologias Utilizadas;
   
   nest.js no backend <br>
   next.js no frontend

   golang

   gRPC <br>
   apahce Kafka

   DDD - Domain Drive Director (Domain / Model) Coração da Apliacação e Suas Regras de Negocios.<br>

   Aplicação<br>
   factory - instancia "objetos" com muitas dependencias;<br>
   grpc - servidor e servicos disponibilizzados via GRPC<br>
   kafka - Consunmo e Processamento de Transacoes com Apache Kafka <br>
   model - Estrutura dos objetos que receberao as requisicoes externas via Apache ou GPRC (DDD); <br>
   usecase - Executa o fluxo de operacoes acordo com a regra de negocio. 

   CMD - comando registrados para iniciar a aplicacao e seus servicos (CLI)
   
   Infrastructure <br>
   db - Realiza a configuracao do ORM e a iunterface com o banco de dados;<br>
   repository -  Realiza a persistencia de dados. Normalmente sao chamados pelos usecases;