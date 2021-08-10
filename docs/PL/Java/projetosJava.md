# :back: [README](../../../README.md#programming-languages)

<h1 align="center">
    Padrão de projeto Java
</h1> 

<br>

# Arquivos
Um projeto Java terá uma pasta com seu nome, exemplo "**meuProjeto**".

Esta pasta "meuProjeto" conterá dois arquivos inicialmente:
-   **src**
    -   Contêm o código do projeto.
-   **JRE System Library**
    - Contês as bibliotecas que serão utilizadas pelo projeto.

<br>
<br>

# src
Nesta pasta emcontraremos os packages (pacotes) do projeto, exemplo "**br.com.umPacoteQualquer**". Note que cada ponto no nome do pacote representa uma pasta, veja abaixo como ficaria esta estrutrura de pastas:
-   meuProjeto
    -   source
        -   br
            -   com
                -   umPacoteQualquer

<br>
<br>

# Ferramentas de Build (Automação de processos, compilação)

## Gradle
Usa a linguagem de programação Groovy.

Ao utilizar uma ferramenta commo po Gradle é interessante que criemos um wrapper da versão que estamos utilizando, para que todos os desenvolvedores, quando tiverem acesso ao projeto, utiliem nossa mesma versão contida no wraper gerado pelo comando `gradle wrapper` e dessa forma podemos fazer `./gradlew -v` para ver a versão do nosso wrapper.

<br>

## Maven
Baseado em XML, é mais antigo que o Gradle.

Para criar um wrapper no maven fazemos `mvn -N io.takari:maven:wrapper` e então `./mvnw -v` para checar a versão do wrapper.

<br>
<br>

# Criação de projetos em Java

## Projetos Spring
A partir do endereço https://start.spring.io/ é possível inicializar um projeto Java com Spring Boot.

<br>
<br>