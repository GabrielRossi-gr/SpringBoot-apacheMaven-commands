
# Spring Boot -- Apache Maven

##  🛑(em processo de desenvolvimento >> por favor reporte os erros no issues)
 
 ⭐️ Star o projeto  
 🐛 Encontrar e relatar issues

 <img alt="springboot-"  height="77" width="77" src="https://cdn.discordapp.com/attachments/819226289789075497/1042758902363734027/spring-boot-project-logo.png">   
<img src="https://cdn.discordapp.com/attachments/819226289789075497/1041844189203288075/image.png" /> 

### Dowload Apache Maven --><a href="https://maven.apache.org/download.cgi" title="site">Site</a>

### Lista de projetos Achetype --><a href="https://maven.apache.org/archetypes/" title="site">Site</a>

### Lista de Dependencias Maven --><a href="https://mvnrepository.com/" title="site">Site</a>

### Configurar Projeto Spring --><a href="https://start.spring.io/" title="site">Site</a>


# Inicializar Projeto Com Apache Maven:
```
 🔸mvn archetype:generate -DgroupId=nomeDoProjeto -DartifactId=quick-start-maven -Darchetype=maven-archetype-quickstart -DinteractiveMode=false
```

# Comandos Basicos:
```
🔸mvn compile            //Compilar Projeto
🔸mvn test               //Testar Projeto
🔸mvn package            //Empacotar Projeto --> Criar Arquivo.jar
🔸mvn clean              //Apagar Pasta Target 
🔸mvn instal             //Cria Uma Dependencia Local
```
# Comandos para dependencias Maven
```
🔸mvn dependency:build-classpath -DincludeScope=compile   //Mostrar Classpath Para o Escopo Compile
🔸mvn dependency:build-classpath -DincludeScope=test   //Mostrar Classpath Para o Escopo Test
🔸mvn dependency:build-classpath -DincludeScope=runtime   //Mostrar Classpath Para o Escopo Runtime
```

