# Banco API Tests 🚀
Este projeto consiste em uma suíte de testes automatizados para a [Banco API](https://github.com/juliodelimas/banco-api). O objetivo principal é validar os endpoints da API, garantindo a integridade dos dados, o comportamento esperado das regras de negócio e a conformidade dos contratos.
## 🛠️ Stack Utilizada
As seguintes tecnologias e bibliotecas foram utilizadas para estruturar este projeto:

- **Linguagem:** [JavaScript (Node.js)](https://nodejs.org/)
- **Test Runner:** [Mocha](https://mochajs.org/) - Framework de testes para Node.js.
- **Requisições HTTP:** [Supertest](https://github.com/ladjs/supertest) - Biblioteca para testar APIs HTTP.
- **Asserções:** [Chai](https://www.chaijs.com/) - Biblioteca de BDD/TDD para asserções.
- **Relatórios:** [Mochawesome](https://adamgruber.github.io/mochawesome/) - Gerador de relatórios HTML personalizados.
- **Variáveis de Ambiente:** [Dotenv](https://www.npmjs.com/package/dotenv) - Carrega variáveis de um arquivo `.env`.
## 📂 Estrutura de Diretórios
```text
.
├── test/               # Diretório contendo os scripts de teste (.js)
├── mochawesome-report/ # Relatórios em HTML gerados automaticamente
├── .env                # Configurações de ambiente (não versionado)
├── package.json        # Gerenciador de dependências e scripts
└── README.md           # Documentação do projeto

## ⚙️ Configuração do Arquivo .env
Para que os testes funcionem corretamente, é necessário configurar a URL base da API.

   1. Na raiz do projeto, crie um arquivo chamado .env.
   2. Adicione a variável BASE_URL conforme o exemplo:

BASE_URL=http://localhost:8080

(Substitua o valor acima pela URL onde a API está rodando).
## 🚀 Execução dos Testes e Relatórios## 1. Instalar dependências
Certifique-se de ter o Node.js instalado. No terminal, execute:

npm install

## 2. Rodar os testes
Para executar a suíte de testes completa:

npm test

## 3. Visualizar o relatório
Após a execução dos testes, um relatório visual será gerado automaticamente pelo Mochawesome. Para visualizá-lo:

   1. Acesse o diretório mochawesome-report/.
   2. Abra o arquivo mochawesome.html em seu navegador preferido.

## 🔗 Links para Documentação

* Mocha
* Chai
* Supertest
* Mochawesome





