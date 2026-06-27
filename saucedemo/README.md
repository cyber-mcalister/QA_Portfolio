# SauceDemo (Swag Labs)

Site de e-commerce fictício, usado como ambiente de prática para testes manuais de QA.

🔗 **URL:** https://www.saucedemo.com/

## Sobre o site

O SauceDemo simula uma loja online (Swag Labs) e permite login com diferentes perfis de usuário, cada um com comportamentos e bugs propositais distintos — o que o torna um ambiente rico para prática de testes funcionais, exploração de bugs e técnicas de QA.

## Perfis de usuário testados

Todos os perfis usam a senha `secret_sauce`.

- `standard_user` — fluxo padrão, sem bugs propositais
- `locked_out_user` — acesso bloqueado no login
- `problem_user` — apresenta diversos bugs visuais e funcionais
- `performance_glitch_user` — apresenta lentidão proposital
- `error_user` — apresenta bugs funcionais no carrinho e checkout
- `visual_user` — apresenta bugs visuais (layout, preços, imagens)

## Conteúdo desta pasta

- `test-cases/` — casos de teste documentados
- `bug-reports/` — relatórios de bugs encontrados
- `evidence/` — prints e evidências visuais dos bugs reportados
