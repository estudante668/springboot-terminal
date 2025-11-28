\# Spring Boot Hello World 🚀



Este é um projeto simples em \*\*Spring Boot\*\* que demonstra como criar uma aplicação web mínima \*\*pelo terminal\*\* usando apenas o \*\*Notepad\*\* como editor de texto, sem IDEs sofisticadas.  

O foco é compreender conceitos fundamentais de \*\*arquivos, empacotamento, versionamento e código-fonte\*\*.



---



\## 📌 Conceito de Build e Maven



\*\*Build\*\* é o processo de transformar o código-fonte (`.java`, `.xml`, `.properties`) em um \*\*artefato executável\*\* (`.jar`, `.war`, etc.).  

Esse processo inclui:



\- \*\*Compilação\*\* → converte `.java` em bytecode `.class` que a JVM entende.  

\- \*\*Testes\*\* → executa testes unitários e de integração para validar o código.  

\- \*\*Empacotamento\*\* → junta `.class`, recursos e dependências em um único arquivo (`myproject-0.0.1-SNAPSHOT.jar`).  



O \*\*Maven\*\* é o motor que organiza, compila e empacota o projeto Spring Boot.  

Com comandos simples como `mvn package` ou `mvn spring-boot:run`, ele cuida de todo o ciclo de vida da aplicação.



---



\## 📂 O papel do `pom.xml`



O `pom.xml` é o \*\*Project Object Model\*\*, um arquivo XML que funciona como a \*\*receita do projeto\*\*.  

Ele descreve:



\- Nome e versão do projeto (`groupId`, `artifactId`, `version`).  

\- Dependências externas (bibliotecas necessárias).  

\- Plugins e configurações de build.  



Com ele, o Maven sabe como compilar, empacotar e executar sua aplicação.



---



\## ▶️ Como rodar



1\. Clone o repositório:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/estudante668/springboot-terminal.git

&nbsp;  cd spring-hello



