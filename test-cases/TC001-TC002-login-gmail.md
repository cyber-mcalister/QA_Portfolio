# Test Cases — Login Gmail

## TC001
Título/Cenário — Digitar um e-mail, válido, digitar uma senha válida e clicar em logar.
Pré-condições — Usuário deve ter conta cadastrada no Gmail. Os campos de login/email, senha e o botão de login devem estar na tela

Steps
Step 1 - Digitar um e-mail válido
Step 2 - Digitar uma senha válida
Step 3 Clicar em logar

Resultado esperado — Logar com sucesso
Resultado obtido — Login efetuado com sucesso respeitando os parâmetros do cenário.
**Status:** Passou ✅

## TC002
Título/Cenário — Tentar logar sem digitar um e-mail ou senha
Pré-condições — Os campos de login/email, senha e o botão de login devem estar na tela, porém as abas devem estar em branco. 

Steps
Step 1 - Deixar os campos de e-mail e senha vazios.
Step 2 Clicar em logar

Resultado esperado — Login recusado e mensagem de erro aparece na tela
Resultado obtido — Login negado, mensagem de erro aparece na tela informando que se deve digitar um e-mail e senha válidos.
**Status:** Passou ✅
