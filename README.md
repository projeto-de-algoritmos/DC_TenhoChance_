# ¿ Tenho Chance ?

**Número da Lista**: 26<br>
**Conteúdo da Disciplina**: Divide & Conquer<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 19/0042532  |  Felipe Alef Pereira Rodrigues |
| 18/0145509  |  Lucas Ramon Alves De Oliveira |

## Sobre 
O TenhoChance é um sistema que lê o PDF disponibilizado pela UnB com as informações sobre os candidatos, separa os candidatos e seus respectivos cursos, os ordena de acordo com a classificação geral e, por meio de web scraping, verifica quem foi aprovado ou não no site do Cebraspe.

## Screenshots
![img](https://github.com/projeto-de-algoritmos/DC_TenhoChance_/blob/master/documentacao/tenhochance1.jpeg)
![img](https://github.com/projeto-de-algoritmos/DC_TenhoChance_/blob/master/documentacao/tenhochance2.jpeg)
![img](https://github.com/projeto-de-algoritmos/DC_TenhoChance_/blob/master/documentacao/tenhochance3.jpeg)
![img](https://github.com/projeto-de-algoritmos/DC_TenhoChance_/blob/master/documentacao/Diagrama%20sem%20nome.drawio.png)

## Instalação 
**Linguagem**: Java<br>
**Framework**: Spring e Angular<br>
Descreva os pré-requisitos para rodar o seu projeto e os comandos necessários.

<div style="display: inline_block" align="center"><br>
   <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> 
    <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> 
    <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> 
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>  
 </div> 
 
## Uso 
Pré-requisitos para executar o software "Tenho Chance":

Ter o Java versão 11 instalado: Certifique-se de ter o Java Development Kit (JDK) versão 11 instalado na sua máquina. Você pode baixar e instalar o JDK 11 a partir do site oficial da Oracle ou de um provedor de distribuição Java, como o OpenJDK.

Ter o Maven instalado: Certifique-se de ter o Apache Maven instalado na sua máquina. O Maven é uma ferramenta de automação de compilação e gerenciamento de dependências. Você pode baixar e instalar o Maven a partir do site oficial.

Modificar o arquivo application.properties: Faça a configuração adequada do arquivo application.properties, fornecendo as variáveis de ambiente específicas da sua máquina, como as configurações do banco de dados e outras configurações personalizadas.

Ter um banco de dados MySQL instalado: É necessário ter o banco de dados MySQL instalado na sua máquina. Certifique-se de que esteja configurado corretamente e acessível para o software "Tenho Chance". Se necessário, você pode baixar e instalar o MySQL a partir do site oficial.

Criar o banco de dados "tenho_chance": No terminal do MySQL ou usando uma ferramenta como o DBeaver, execute o comando CREATE DATABASE tenho_chance para criar o banco de dados necessário para o funcionamento do software.

```bash 
CREATE DATABASE tenhochance
```

Executar o Maven no diretório raiz: No diretório raiz do projeto, execute o comando mvn clean install compile para compilar e construir o software. Em seguida, execute mvn spring-boot:run para iniciar o servidor.
` 
```bash 
mvn clean install compile
```
```bash 
mvn spring-boot:run
```
Acesso ao diretório do frontend: Navegue até o diretório do frontend do projeto.

Ter o Node.js versão 16 instalado: Certifique-se de ter o Node.js instalado na versão 16 ou superior. Você pode baixar e instalar o Node.js a partir do site oficial.

Executar o comando npm install: No diretório do frontend, execute o comando npm install para instalar todas as dependências necessárias para o frontend do software.

```bash 
nvm use 16
```
```bash 
npm install
```
Executar o comando npm start: Após a conclusão da instalação das dependências, execute o comando npm start para iniciar o servidor do frontend.
```bash 
npm start
```

Acessar o software no navegador: Abra o navegador (recomendamos o Firefox) e navegue para localhost:4200 para acessar o software "Tenho Chance" e utilizá-lo para verificar as informações e chances dos candidatos.
```
localhost:4200
```
[Documentação Swagger - Backend API](http://localhost:8080/swagger-ui/index.html#/root-controller)

Ao acessar esse link em seu navegador enquanto o servidor backend estiver sendo executado localmente, você poderá visualizar e explorar a documentação da API do software "Tenho Chance" fornecida pelo Swagger. Isso permitirá entender melhor os endpoints disponíveis, os parâmetros esperados e as respostas retornadas pela API.



