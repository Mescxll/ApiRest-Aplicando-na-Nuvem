# Projeto: Publicando Sua API REST na Nuvem Usando Spring Boot, Java 21 e Railway
## Figma e representação visual
O Figma foi utilizado para a abstração do domínio desta API, sendo útil na análise e projeto da solução.
Acesse a representação: [BookStore](https://www.figma.com/design/RBnvNT1wRCB1HQ6ri10mKA/Library?node-id=0-1&t=DDJ9a7llpA7zOfOs-1)
## Status
Em desenvolvimento
## Foco de aprendizagem
Spring Framework com Spring Boot, API REST, Railway e Gerenciamento com Gandle.
## Diagrama de Classe Da API em desenvolvimento - Sistema de uma Livraria
```mermaid
classDiagram
    class Bookstore {
        +string name
        +string address
        +Account account
        +list~Book~ books
        +Front front
    }
    
    class Account {
        +string name
        +int age
        +string address
        +list~Book~ purchaseHistory
        +list~Book~ cart
        +list~Book~ favorite
    }
    
    class Book {
        +string name
        +string id
        +float price
        +string genre
        +int quantityOnStore
        +int quantitySold
        +list~Book~ booksOnOffer
    }
    
    class Front {
        +Icons icons
    }
    
    class Icons {
        +string bell
        +string bookOpen
        +string search
        +string cart
        +string home
        +string profile
        +string ellipsis
        +string arrows
    }
    
    Bookstore --> Account
    Bookstore --> Book
    Bookstore --> Front
    Front --> Icons
```
## Uso e tecnologias utilizadas
A produção do projeto em questão se limita ao uso do Framework Spring, mais especificamente Spring Boot, alguma IDE (Integrated Development Environment ou Ambiente de Desenvolvimento integrado) da linguagem Java, nesse caso a IDE Eclipse e as tecnologias básicas Eclipse e Java. Ademais, utilizou-se algumas dependências naturais ou não do próprio framework.

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white" /> ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

## Contribuição
Se deseja melhorar o projeto de maneira a aprofundar o aprendizado sobre novas formas de se trabalhar a proposta Conta bancária em BackEnd Java, é possível executar as funções de Issues, Pull requests e Fork na plataforma do GitHub.

Saiba mais em: [Contribuições](https://docs.github.com/pt/get-started/exploring-projects-on-github/contributing-to-a-project)

## Conecte-se comigo
[![GitHub](https://img.shields.io/badge/GitHub-DC105D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mescxll)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-DC105D?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-campos-0a670b2a4/)
[![Gmail](https://img.shields.io/badge/Gmail-DC105D?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mariaeduardasantoscampos09@gmail.com)
