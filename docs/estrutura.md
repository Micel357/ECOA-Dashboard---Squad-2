# Estrutura do ECOA Dashboard

`src/` contém o frontend React: `componentes/` reúne peças reutilizáveis, `screens/` agrupa páginas por recurso e `assets/` contém recursos importados pelo código. `public/` guarda arquivos servidos diretamente pelo Vite. `assets/` na raiz preserva recursos originais do projeto.

`tests/` fica reservado para testes automatizados quando uma ferramenta de testes for configurada. `config/` documenta futuras configurações específicas da aplicação. `vite.config.js`, `package.json` e `package-lock.json` permanecem na raiz porque Vite e npm os procuram ali.
