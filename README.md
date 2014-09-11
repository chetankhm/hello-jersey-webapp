Projeto totalmente baseado na documentação do Jersey encontrado na URL:

https://jersey.java.net/documentation/latest/getting-started.html

Como base, usei o seguinte comando para criar o projeto:

mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-webapp \
                -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false \
                -DgroupId=com.example -DartifactId=simple-service-webapp -Dpackage=com.example \
                -DarchetypeVersion=2.12

Você pode fazer o deploy deste projeto em qualquer Servlet container: Jetty, Tomcat, Wildfly, Glassfish, ...
