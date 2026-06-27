 The Internet (Heroku App)

Site de prática para QA, com diversas páginas isoladas que simulam comportamentos e bugs comuns em aplicações web reais.

🔗 **URL:** https://the-internet.herokuapp.com/

## Sobre o site

O The Internet é um conjunto de páginas independentes, cada uma criada para exercitar um tipo específico de teste (formulários, autenticação, elementos dinâmicos, imagens quebradas, entre outros). Por não ter perfis de usuário, o foco aqui está em testar páginas e funcionalidades isoladas.

## Páginas testadas até agora

- `/login` — formulário de autenticação com usuário `tomsmith` (senha `SuperSecretPassword!`)
- `/broken_images` — página com imagens quebradas propositais
- `/typos` — página com erros de texto/ortografia propositais

## Conteúdo desta pasta

- `test-cases/` — casos de teste documentados
- `bug-reports/` — relatórios de bugs encontrados
- `evidence/` — prints e evidências visuais dos bugs reportados
