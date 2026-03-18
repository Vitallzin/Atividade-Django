## Etapa 1 - Respostas

### 1. Por que o arquivo .env não deve ser versionado?
O arquivo .env não deve ser versionado porque ele armazena informações sensíveis, como chaves secretas, senhas e tokens de acesso. Se esses dados forem expostos em um repositório público, 
podem comprometer a segurança da aplicação.

---

### 2. Qual a função do pip freeze no contexto de desenvolvimento em equipe?
O comando pip freeze serve para listar todas as dependências instaladas no projeto, permitindo gerar um arquivo requirements.txt. Isso facilita que outros desenvolvedores instalem exatamente 
as mesmas versões das bibliotecas, garantindo que o projeto funcione corretamente em diferentes ambientes.

---

### 3. O que pode acontecer se a SECRET_KEY for exposta?
Se a SECRET_KEY for exposta, a segurança da aplicação pode ser comprometida. Um atacante pode manipular sessões, falsificar autenticações e executar ações maliciosas dentro do sistema.

---

### 4. Qual o papel do .gitignore em projetos colaborativos?
O .gitignore serve para impedir que arquivos desnecessários ou sensíveis sejam enviados para o repositório, como arquivos temporários, ambiente virtual e o próprio .env, mantendo o projeto 
organizado e seguro.
