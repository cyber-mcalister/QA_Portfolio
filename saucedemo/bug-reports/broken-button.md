# Bug Report - Saucedemo

# BR003

**Cenário:** Após logar com os perfis "problem_user" ou "error_user" escolher um dos seguintes produtos (Sauce Labs Onesie, Sauce Labs Bike Light, Sauce Labs Backpack) e clicar no botão "add to cart", não é possível removê-lo do carrinho usando o botão "Remove" pois esta função para este botão está desabilitada, para os demais produtos, o botão "add to cart" está totalmente desabilitado.

**Perfis Afetados:** problem_user / error_user

**Severidade:** Alta - O bug em questão impede usuários de realizarem compras e/ou remover produtos do carrinho, fazendo com que usuários saiam do site dando um impacto grande no faturamento da empresa.

**Prioridade:** Alta - O bug pode comprometer o faturamento e o propósito real do site.

**Passos:**
1. Acessar https://www.saucedemo.com/
2. Logar com o perfil "problem_user" ou "error_user"
3. Clicar no botão "add to cart" em cada produto
4. Verificar funcionalidade do botão "Add to Cart/Remove" em cada produto.

**Resultado esperado:** Após logar com o perfil "problem_user" ou "error_user" o botão "add to cart/remove" deve funcionar normalmente.

**Resultado obtido:** Após logar com o perfil "problem_user" ou "error_user" o botão "add to cart/remove" se comporta de diferentes formas: Ao clicar no botão "add to cart" para os seguintes produtos (Sauce Labs Onesie, Sauce Labs Bike Light, Sauce Labs Backpack), não é possível removê-lo do carrinho usando o botão "Remove" pois o mesmo se encontra inativo no estado "Remove", nos demais produtos o botão "add to cart/remove" está totalmente desabilitado.

**Evidência:** ![Evidência](https://github.com/cyber-mcalister/QA_Portfolio/raw/6e569e9d44584cbcb896b71903d40caebd39b41f/saucedemo/evidence/saucedemo_broken_button.png)

**Ambiente:**
- Windows 10
- Google Chrome
- url: https://www.saucedemo.com/inventory.html

