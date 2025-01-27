# README

Olá, meu nome é Rodrigo Araujo e estou concorrendo à vaga de desenvolvedor.

## Sobre o Projeto

Este projeto foi desenvolvido com as seguintes tecnologias:
- **Frontend**: Next.js
- **Backend**: C# .NET
- **Banco de Dados**: SQLite (escolhido pela praticidade para este tipo de projeto).

## Passos para a Instalação

1. **Clone o Repositório**
   - Acesse o diretório em que deseja adicionar o projeto na sua máquina.
   - Faça o clone do repositório com o comando:
     ```bash
     git clone git@github.com:Rod-S-Araujo/ProjMicroondas.git
     ```

2. **Navegue para o Diretório do Projeto**
   - Após clonar, utilize o comando:
     ```bash
     cd .\projMicroondasDocker\
     ```

3. **Inicie e Atualize os Submódulos**
   - Execute os comandos:
     ```bash
     git submodule init
     git submodule update
     ```

4. **Instale as Dependências do Frontend**
   - Navegue até a pasta do frontend:
     ```bash
     cd .\CDMicroondasFrontEnd\
     ```
   - Instale as dependências com:
     ```bash
     npm install
     ```

5. **Retorne à Pasta Raiz do Projeto**
   - Utilize o comando:
     ```bash
     cd ../
     ```

6. **Execute o Docker**
   - Suba os serviços com:
     ```bash
     docker-compose up --build
     ```

## Pré-requisitos Necessários

- **Docker**
- **Visual Studio Code (VS Code)**

---

Espero que este README seja útil para o entendimento e instalação do projeto. Obrigado pela oportunidade!
