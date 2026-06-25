# Test Cases — Login Gmail

## TC001
**Título/Cenário**: Digitar um e-mail e senha válidos e clicar em logar 

**Pré-condições**  
- Usuário deve ter conta cadastrada no Gmail. 
- Os campos de login/email, senha e o botão de login devem estar na tela

**Steps**
1. Digitar um e-mail válido
2. Digitar uma senha válida
3. Clicar em logar

**Resultado esperado** — Logar com sucesso

**Resultado obtido** — Login efetuado com sucesso respeitando os parâmetros do cenário.

**Status:** Passou ✅

---
## TC002
**Título/Cenário** Tentar logar sem digitar um e-mail ou senha.
 
**Pré-condições** 
- Os campos de login/email, senha e o botão de login devem estar na tela.
- As abas devem estar em branco antes de serem preenchidas. 

**Steps**
1. Deixar os campos de e-mail e senha vazios.
2. Clicar em logar

**Resultado esperado** — Login recusado e mensagem de erro aparece na tela.

**Resultado obtido**  
- Login negado 
- mensagem de erro aparece na tela informando que se deve digitar um e-mail e senha válidos.
  
**Status:** Passou ✅

---
## TC003
**Título/Cenário** E-mail correto porém senha errada
 
**Pré-condições** 
- Os campos de login/email, senha e o botão de login devem estar na tela.
- As abas devem estar em branco antes de serem preenchidas. 

**Steps**
1. Preencher com o e-mail válido.
2. Preencher com senha inválida
3. Clicar em login

**Resultado esperado** — Login recusado e mensagem de erro aparece na tela.



**Resultado obtido**  
- Login negado 
- mensagem de erro aparece na tela informando que se a senha está inválida.
  
**Status:** Passou ✅
