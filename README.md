# Projeto Sequelize(exemplo)

### O 'package.json' já tem o registro das dependências para este projeto:
```json
"dependencies": {
    "dotenv": "^16.4.5",
    "mysql2": "^3.11.0",
    "sequelize": "^6.37.3"
}
```

### Portanto, para rodar o projeto, é preciso apenas baixar e instalar as dependências:

1. Crie um diretório para colocar os arquivos deste projeto, por exemplo:
    ```
    mkdir teste_sequelize
    ```

2. Entre no diretório criado:
    ```
    cd teste_sequelize
    ```

3. Clique com o botão direito do mouse, abra o GitBash Here e digite:
    ```
    git clone https://github.com/prof-marneicardoso/teste_sequelize.git .
    ```
    * Note que há um *espaço* e um . (ponto) depois do lonk do repositório. Este ponto determina que será baixado apenas o conteúdo do repositório, sem criar um diretório. Se não colocar o ponto, será criado um diretório dentro do diretório criado manualmente, no passo 1: mkdir teste_sequelize

4. Abra o projeto no vscode.

5. No Terminal, rode o comando para instalar localmente as dependências no projeto baixado:
    ```
    npm i
    ```
    * o mesmo que: npm install

6. Rode o projeto com:
    ```
    npm start
    ```

 * Segurança das informações: Lembre-se que as configurações do arquivo .env são dados sensíveis e devem ser alterados conforme as necessidades de cada projeto. Os dados deste projeto são genéricos, usados de forma didática como exemplo. Os dados finais do .env não devem ser enviado para o repositório, para que não fiquem expostos e qualquer pessoa que acessar o repositório possa acessar a base de dados.

---
// OLD  
// Criar o package.json   
npm init -y

// Adiciona o type para import ES   
"type": 'module'

// Instalação dos dependências   
npm i sequelize mysql2 dotenv# teste_sequelize
