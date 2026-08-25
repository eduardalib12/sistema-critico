Sistema Critico

Projeto pratico desenvolvido para a disciplina de Gerencia de Configuracao, utilizando Git e GitHub.

---

Objetivo

Demonstrar boas praticas de controle de versao, organizacao de branches, commits semanticos, recuperacao de alteracoes e colaboracao remota.

---

Tech Stack

- Git
- GitHub
- JavaScript
- Windows 10/11

---

Funcionalidades

Autenticacao
Implementacao inicial de autenticacao demonstrada no arquivo app.js.

Pagamento via Pix
Implementacao inicial da funcionalidade de pagamento via Pix no arquivo pagamento-pix.js.

Hotfix
Correcao emergencial do trigger do botao de compra no arquivo botao.js.

---

Estrutura do projeto

sistema-critico/
- .gitignore
- README.md
- app.js
- botao.js
- pagamento-pix.js
- .env.example

---

Como executar

Clone o repositorio:

git clone https://github.com/eduardalib12/sistema-critico.git

Entre na pasta:

cd sistema-critico

Execute os arquivos JavaScript utilizando Node.js:

node app.js
node pagamento-pix.js

---

Seguranca

Arquivos contendo credenciais e informacoes sensiveis nao devem ser versionados.

O arquivo .env esta incluido no .gitignore.

O arquivo .env.example serve apenas como modelo de configuracao e nao deve conter credenciais reais.

---

Git

Branches utilizadas no projeto:

- main
- feat/PROJ-101-pagamento-pix
- hotfix/botao-comprar

---

Tag de release:

- v1.0.0
