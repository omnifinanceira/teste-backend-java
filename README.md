# Desafio de Desenvolvimento Backend: Cadastro de CNPJ

## Objetivo
O objetivo deste desafio é avaliar as habilidades dos candidatos em desenvolver um sistema backend em Java utilizando Spring Boot, criando um CRUD para o cadastro de CNPJ. Além disso, é necessário garantir que o sistema tenha 100% de cobertura de testes no use case e testes de integração.

## Requisitos
### Tecnologias Utilizadas:
* Java 21 ou superior
* Spring Boot 3.2.x ou superior
* Hibernate/JPA para persistência
* Banco de dados H2

### Funcionalidades:
#### CRUD Completo:
* Criar CNPJ
* Listar CNPJ
* Buscar CNPJ por ID
* Atualizar CNPJ
* Deletar CNPJ

#### Campos do CNPJ:
* id (gerado automaticamente)
* cnpj
* razaoSocial
* nomeFantasia

#### Sócios:
* Cada CNPJ pode ter vários sócios.
* Cada sócio pode ser um pessoa física ou jurídica (outro CNPJ).

#### Campos do Sócio:
* id (gerado automaticamente)
* tipo (pessoa física ou jurídica)
* documento (CPF ou CNPJ do sócio)
* nome (nome do sócio)
* porcentagemParticipacao (porcentagem de participação no CNPJ)

#### Estrutura de Propriedade:
* Um CNPJ pode ter outro CNPJ como sócio, representando uma estrutura de propriedade complexa.

### Testes:
* **Testes Unitários:** Utilizar JUnit e Mockito para testar isoladamente o serviço e o repositório.
* **Testes de Integração:** Utilizar `@SpringBootTest` para testar a integração completa do sistema, incluindo o banco de dados.

### Documentação:
* Incluir um arquivo `README.md` com instruções sobre como executar o projeto e rodar os testes.
* Incluir decisões que foram tomadas e as suas justificativas no `README.md`
* Documentar a API utilizando Swagger.

## Avaliação
A avaliação será baseada nos seguintes critérios:

* **Funcionalidade:** O sistema deve atender a todos os requisitos funcionais descritos.
* **Cobertura de Testes:** O sistema deve ter 100% de cobertura de testes no use case e testes de integração.
* **Organização do Código:** O código deve estar bem organizado, seguindo boas práticas de desenvolvimento.
* **Documentação:** A documentação deve ser clara e útil para entender e executar o projeto.

## Instruções para Entregar o Desafio
* Crie um novo repositório no GitHub.
* Implemente o sistema conforme os requisitos acima.
* Adicione um arquivo `README.md` com as instruções para executar o projeto e rodar os testes.
* Envie o link do repositório para a avaliação.