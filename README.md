<h1>🧩 Pokédex Web — Projeto Front-End com React + Vite</h1>

Este projeto consiste em uma Pokédex web moderna, construída para oferecer uma experiência rápida, responsiva e intuitiva. A aplicação consome dados da PokeAPI e apresenta informações detalhadas dos Pokémon da primeira geração, incluindo imagens oficiais, atributos e recursos de filtragem.

O objetivo central é entregar uma solução escalável, bem organizada e com boas práticas de desenvolvimento utilizando React, TypeScript e Tailwind CSS.


<h2>⚙️ Tecnologias Utilizadas</h2>

React (Vite + TypeScript): Performance otimizada e DX (Developer Experience) moderna.

Tailwind CSS: Estilização rápida, utilitária e consistente.

React Router DOM: Navegação entre páginas em formato SPA.

PokeAPI: Fonte pública de dados para consumo.

Context API: Gerenciamento simplificado de estados globais.

Fetch API: Consumo de dados com implementação de camada de cache local.


<h2>📁 Estrutura do Projeto</h2>

A arquitetura foi pensada para modularidade, manutenibilidade e escalabilidade:

src/
 ├── api/        # Serviços e integração com a PokeAPI (inclui camada de cache)
 ├── components/ # Componentes reutilizáveis de UI
 ├── context/    # Gerenciamento global de estado (ex.: favoritos, filtros)
 ├── pages/      # Páginas principais (Home, Details)
 ├── routes/     # Definição centralizada das rotas
 ├── types/      # Tipos e interfaces TypeScript
 └── assets/     # Imagens, ícones e mídias estáticas


<h2>🔍 Funcionalidades Principais</h2>

✅ Listagem dos 151 Pokémon da primeira geração.

✅ Consulta de detalhes (imagem oficial, atributos, tipos, etc.).

✅ Filtragem dinâmica por nome.

✅ Navegação fluida via SPA.

✅ Cache local: Melhora a performance em requisições repetidas.

✅ Tipagem forte: Garantia de consistência de dados em toda a aplicação.


<h2>🚀 Como Executar Localmente</h2>

1. Instalar Dependências
Certifique-se de estar utilizando o Node.js (versão LTS).

Bash
npm install
# ou
yarn install
2. Rodar o Projeto
Bash
npm run dev
# ou
yarn dev
O Vite iniciará o servidor local em: http://localhost:5173

Nota: Nenhuma variável de ambiente (.env) é necessária para este projeto.


<h2>🧱 Base Técnica e Decisões de Arquitetura</h2>

Enriquecimento de Dados: A lista inicial da PokeAPI é complementada com detalhes individuais obtidos em requisições paralelas, garantindo imagens oficiais de alta resolução.

Cache Interno: Reduz o consumo da API e acelera a experiência do usuário após a primeira carga.

Componentização Estratégica: UI organizada para ser escalável e fácil de manter.

Separação de Camadas: Isolamento claro entre serviços, rotas, páginas e tipagens.


<h2>📌 Possíveis Expansões Futuras</h2>

[ ] Paginação ou Infinite Scroll.

[ ] Suporte a Tema Dark/Light.

[ ] Testes unitários (Vitest) e E2E (Cypress/Playwright).

[ ] Implementação de Debounce na pesquisa.

[ ] Migração para React Query ou SWR.

[ ] Incremento de acessibilidade (ARIA labels).


<h2>📝 Resumo Final</h2>

O projeto foi estruturado com foco em Código Limpo, Escalabilidade e Performance, unindo uma UX responsiva com uma arquitetura técnica sólida baseada em TypeScript.