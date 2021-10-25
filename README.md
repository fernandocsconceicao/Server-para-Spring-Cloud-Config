# Server-para-Spring-Cloud-Config
# O que é Spring Cloud?
Configurações de projetos se tornaram mais fáceis com o Spring Boot, que com o conceito de auto configuração ficam menos verbosas e centralizadas nos application.properties. Porém, como são configurações em arquivos isso acaba sendo um pouco repetitivo quando utilizadas em diversas aplicações e diversos ambientes, como na arquiteturas de microsserviços onde há várias aplicações, consequentemente várias configurações que ainda são multiplicada pela quantidade de ambientes(desenvolvimento, homologação, produção).<br> <br>
Fonte desta definição: https://emmanuelneri.com.br/2018/07/09/configuracoes-distribuidas-com-spring-cloud-config/
# Nota
1- O caminho do application.yml deve ser ajustado para o ambiente de quem utilizar. Isto pode ser feito mudando o caminho da variavel spring.cloud.config.server.git.uri em application.properties
<br>
<br>
Para mais informações acesse a documentação base:
<br>
https://cloud.spring.io/spring-cloud-config/reference/html/#custom-rest-template
