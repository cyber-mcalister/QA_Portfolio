# Test Cases — The Internet Login Page

# TC001
**Título/Cenário:** Digitar um username e senha válidos e clicar em logar

**Pré-condições**
•	Usuário tomsmith deve estar cadastrado no sistema
•	Os campos de username, senha e o botão de login devem estar na tela


**Steps**
1.	Digitar um username válido
2.	Digitar uma senha válida
3.	Clicar em logar

**Resultado esperado** — Logar com sucesso

**Resultado obtido** — Login efetuado com sucesso respeitando os parâmetros do cenário.

**Status:** Passou ✅

---
## TC002
**Título/Cenário** Tentar logar sem digitar um username ou senha.
 
**Pré-condições** 
- Os campos de username, senha e o botão de login devem estar na tela. 
- As abas devem estar em branco antes de serem preenchidas.

**Steps**
1. Deixar o campo "username" em branco 
2. Deixar o campo "senha" em branco 
3. Clicar no botão "Login"

**Resultado esperado** — Login recusado e mensagem de erro “Your username is invalid!” aparece na tela. 

**Resultado obtido** - Ao deixar os campos "username" e "senha" vazios, e clicar em login, o sistema exibiu a mensagem "Your username is invalid!" em uma caixa vermelha no topo da página, e a tela de login permaneceu visível (não houve redirecionamento). 

**Status:** Passou ✅

---

## TC003
**Título/Cenário** Tentar logar com username vazio e senha válida
 
**Pré-condições** 
- Os campos de username, senha e o botão de login devem estar na tela. 
- As abas devem estar em branco antes de serem preenchidas.
- Senha “SuperSecretPassword!” cadastrada no sistema e atribuída ao usuário “tomsmith”

**Steps**
1. Deixar o campo "username" em branco 
2. Preencher o campo "senha" com a senha válida 
3. Clicar no botão "Login"

**Resultado esperado** — Login recusado e mensagem de erro “Your username is invalid!” aparece na tela. 

**Resultado obtido** - Ao deixar os campos "username" vazio e preencher o campo “senha” com “SuperSecretPassword!” (sem aspas) e clicar em login, o sistema exibiu a mensagem "Your username is invalid!" em uma caixa vermelha no topo da página, e a tela de login permaneceu visível (não houve redirecionamento). 

**Status:** Passou ✅

---

## TC004
**Título/Cenário** username correto porém senha errada
 
**Pré-condições** 
- Os campos de username, senha e o botão de login devem estar na tela.
- As abas devem estar em branco antes de serem preenchidas. 

**Steps**
1. Preencher com o username válido.
2. Preencher com senha inválida
3. Clicar em login

**Resultado esperado** — Login recusado e mensagem de erro “Your password is invalid!” aparece na tela.

**Resultado obtido** — Ao preencher o username válido "tomsmith" com uma senha incorreta e clicar em "Login", o sistema recusou o acesso e exibiu a mensagem "Your password is invalid!" em uma caixa vermelha no topo da página. A tela de login permaneceu visível, sem redirecionamento.

**Status:** Passou ✅

---

## TC005
**Título/Cenário** username correto porém senha vazia
 
**Pré-condições** 
- Os campos de username, senha e o botão de login devem estar na tela.
- As abas devem estar em branco antes de serem preenchidas. 

**Steps**
1. Preencher com o username válido.
2. Deixar campo “senha” vazio
3. Clicar em login

**Resultado esperado** — Login recusado e mensagem de erro “Your password is invalid!” aparece na tela.

**Resultado obtido** — Ao preencher o username válido "tomsmith", deixar o campo “senha” vazio e clicar em "Login", o sistema recusou o acesso e exibiu a mensagem "Your password is invalid!" em uma caixa vermelha no topo da página. A tela de login permaneceu visível, sem redirecionamento.

**Status:** Passou ✅

---

## TC006
**Título/Cenário** Tentar logar com username inválido e senha válida
 
**Pré-condições** 
- Os campos de username, senha e o botão de login devem estar na tela. 
- As abas devem estar em branco antes de serem preenchidas.
- Senha “SuperSecretPassword!” cadastrada no sistema e atribuída ao usuário “tomsmith”

**Steps**
1. Preencher campo “username” com um usuário inválido
2. Preencher o campo "senha" com a senha válida 
3. Clicar no botão "Login"

**Resultado esperado** — Login recusado e mensagem de erro “Your username is invalid!” aparece na tela. 

**Resultado obtido** - Ao preencher o campo "username" com um usuário inválido e o campo "senha" com "SuperSecretPassword!", e clicar em login, o sistema exibiu a mensagem "Your username is invalid!" em uma caixa vermelha no topo da página, e a tela de login permaneceu visível (não houve redirecionamento).

**Status:** Passou ✅

Reorganiza test cases na pasta the-internet
