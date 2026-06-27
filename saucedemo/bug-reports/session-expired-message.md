# Bug Report - Saucedemo

# BR001

**Cenário:** Após a sessão expirar devido a um tempo por inatividade (15 minutos), uma mensagem de erro em formato informal contendo informação que infringe a segurança do projeto aparece na tela em vermelho. 

**Perfis Afetados:** todos os perfis cadastrados

**Severidade:** Média (a mensagem está escrita com linguagem incorreta/informal e revela informações que devem permanecer ocultas para o usuário, como o nome do arquivo HTML da página)

**Prioridade:** Baixa (apesar do bug em questão afetar a identidade profissional pela forma informal a qual foi retratada fora o fato de revelar o nome do arquivo em html, o bug não impede o usuário de realizar a compra ou explorar o site, lembrando que o bug só ocorre caso haja inatividade por um período de tempo.)

**Passos:**
1. Acessar https://www.saucedemo.com/
2. Logar com algum dos perfis
3. aguardar um período de 15 minutos em inatividade
4. Tentar ir para outra área do site (algum produto, carrinho e etc)
5. Após ser deslogado automaticamente (padrão e-commerce) se atentar a mensagem de erro em vermelho

**Resultado esperado:** Após a sessão expirar devido a um tempo por inatividade (15 minutos), uma mensagem de erro em formato profissional informa que o usuário foi deslogado e precisa fazer o login novamente para acessar as páginas do site.


**Resultado obtido:** Texto escrito de forma informal e revelando o nome do arquivo html da página

**Evidência:** ![Evidência](https://github.com/cyber-mcalister/QA_Portfolio/raw/main/saucedemo/evidence/SadFace_message_bug.png)

**Ambiente:**
- Windows 10
- Google Chrome
- url: https://www.saucedemo.com/

