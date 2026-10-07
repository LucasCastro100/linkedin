# 🧩 LinkedIn — Seção "Projetos" (pronta pra colar)

> **Como adicionar:** LinkedIn → **Ver perfil** → **Adicionar seção** → **Projetos**
> → preencha **Nome**, **Tipo: Pessoal**, **Início/Fim**, **Descrição** e **Link**.
>
> ⚠️ Os projetos marcados com 🔒 têm repositório **privado**: **não preencha o campo
> de link** (vamos apenas listar o projeto). Os demais têm link público.

---

## 1. Ideias.dev.br — Plataforma multi-sistema
- **Tipo:** Pessoal · **Período:** jul/2025 – atual
- **Link:** https://github.com/LucasCastro100/ideias_dev

```
Plataforma multi-sistema hospedando 22 sistemas de gestão independentes (financeiro,
escolar, advocacia, clínicas, PDV, loja virtual, marketplace, CMS, e-commerce, eventos...)
dentro de um único codebase Laravel 12 + Livewire 3 + Jetstream.

Cada módulo tem rotas, models, migrations e telas próprias, isolados por usuário —
sem virar monolito ingovernável.

Métricas: 75 tabelas | 90 rotas | 86 componentes Livewire | 66 models Eloquent |
~39.500 linhas de código.

Stack: Laravel 12 · Livewire 3 · Jetstream · Tailwind CSS · Chart.js · DomPDF · SQLite
```

---

## 2. Clubset — Marketplace de permuta audiovisual
- **Tipo:** Pessoal · **Período:** em andamento
- **Link:** 🔒 *sem link — repositório privado*

```
Marketplace de permuta (barter) para o mercado audiovisual, com matches, livro-razão
de créditos, disputas, assinaturas e checkout via Stripe.

Segurança forte: 2FA por TOTP e login por Passkey (WebAuthn).

Métricas: 68 rotas | 35 tabelas | 48 migrations | 26 controllers | 38 páginas React |
78 componentes React.

Stack: Laravel 13 · React 19 · Inertia · TypeScript · Tailwind · Stripe · 2FA · Passkeys
```

---

## 3. Control School — Gestão escolar full-stack
- **Tipo:** Pessoal · **Período:** jun/2026 – atual
- **Link:** https://github.com/LucasCastro100/control-school-back

```
Sistema de gestão escolar full-stack: turmas, alunos, professores, horários e
financeiro.

API REST em Laravel 13 com autenticação Sanctum e frontend em Next.js 16 (App Router).

Métricas: 19 endpoints | 15 models | 23 tabelas | 119 arquivos TypeScript/TSX no front.

Stack: Laravel 13 · Sanctum · Next.js 16 · TypeScript · Tailwind CSS
```

---

## 4. OdontoPro — SaaS odontológico
- **Tipo:** Pessoal · **Período:** set/2026 – atual
- **Link:** https://github.com/LucasCastro100/odontopro

```
SaaS para clínicas odontológicas: agendamento, pacientes, prontuários e painel
administrativo.

Métricas: 9 models Prisma | 7 páginas | ~20.500 linhas de código.

Stack: Next.js 16 · Prisma 7 · PostgreSQL · Auth.js · TypeScript
```

---

## 5. Neuro Comunicação — Plataforma EAD/LMS
- **Tipo:** Pessoal · **Período:** em andamento
- **Link:** 🔒 *sem link — repositório privado*

```
Plataforma de ensino a distância com 3 painéis (admin, professor e aluno),
matrículas, avaliações, pagamentos via Stripe e certificados emitidos em PDF.

Métricas: 113 rotas | 19 models | 26 tabelas | 28 migrations | ~22.000 linhas.

Stack: Laravel 11 · Blade · DomPDF · Stripe · SQLite
```

---

## 6. Calendário Unificado — Agendas externas em um só lugar
- **Tipo:** Pessoal · **Período:** em andamento
- **Link:** 🔒 *sem link — repositório privado*

```
Aplicação que unifica agendas externas numa única visão. O backend Laravel expõe a
API e faz a integração por OAuth (Socialite) com calendários de terceiros; o frontend
Next.js renderiza dia, semana, mês e lista com FullCalendar e TanStack Query.

Métricas: 15 rotas de API | 11 tabelas.

Stack: Laravel 12 · Sanctum · Socialite · Next.js 16 · FullCalendar · TanStack Query
```

---

## 7. register-students — Automação de cadastro em paralelo
- **Tipo:** Pessoal · **Período:** em andamento
- **Link:** 🔒 *sem link — repositório privado*

```
Automação que lê uma planilha Excel, abre vários navegadores Chrome em paralelo
(ThreadPoolExecutor), preenche o formulário de cadastro e gera um cartão de login
por aluno em PDF, com lock para evitar conflito de escrita no Excel.

Stack: Python 3 · Selenium · pandas · python-dotenv · ThreadPoolExecutor
```

---

## 8. pyton-projects — Automações e análise de dados
- **Tipo:** Pessoal · **Período:** em andamento
- **Link:** 🔒 *sem link — repositório privado*

```
Suíte de automações e análises: raspagem e preenchimento de formulários com Selenium,
dashboards interativos em Streamlit/Plotly (análise de livros e peças automotivas com
PCA/CAP/BAP), geração de recibos em PDF, consumo de APIs e GUI com PySide6.

Stack: Python 3 · Pandas · Streamlit · Plotly · Selenium · FPDF · PySide6
```

---

## 9. Style Hub — Hub de bibliotecas UI
- **Tipo:** Pessoal · **Período:** set/2026
- **Link:** https://github.com/LucasCastro100/style-hub

```
Diretório de bibliotecas e ferramentas de UI com sandbox de componentes e previews
interativos — feito para acelerar a escolha de componentes em novos projetos.

Métricas: 14 componentes React documentados.

Stack: Next.js 16 · React · Framer Motion · Tailwind CSS
```

---

## 10. App Finanças — Gestão financeira pessoal
- **Tipo:** Pessoal · **Período:** ago/2026
- **Link:** https://github.com/LucasCastro100/app-financas

```
Dashboard de receitas e despesas com gráficos e resumo mensal.

Métricas: 42 componentes React | ~4.700 linhas.

Stack: Next.js · Recharts · shadcn/ui · Tailwind CSS
```

---

## 11. Base Next.js — Template de projeto
- **Tipo:** Pessoal · **Período:** ago/2026
- **Link:** https://github.com/LucasCastro100/base-nextjs

```
Template base com Next.js (App Router), shadcn/ui, validação com Zod, gráficos com
Recharts e tema claro/escuro — ponto de partida para novos projetos.

Stack: Next.js · TypeScript · shadcn/ui · Zod · Recharts
```

---

## 12. Cola Componente — Referência de componentes
- **Tipo:** Pessoal · **Período:** set/2026
- **Link:** https://github.com/LucasCastro100/cola-componente

```
Coleção de guias prontos para "colar e usar" de componentes React/Next.js —
referência rápida de padrões de UI no dia a dia.

Stack: Next.js · React · Tailwind CSS
```

---

## 13. pyton — Fundamentos de Python
- **Tipo:** Pessoal · **Período:** jan/2025 – atual
- **Link:** https://github.com/LucasCastro100/pyton

```
Repositório didático de Python organizado por tópico: intro, POO, coleções,
manipulação de arquivos, MySQL e MongoDB, decorators, módulos, automações e
análise de dados.

Métricas: 81 scripts | ~2.000 linhas só em fundamentos.

Stack: Python 3 · Tkinter · MySQL · MongoDB · Matplotlib · Requests
```

---

## 14. LinkedIn Toolkit — Guias de otimização de perfil
- **Tipo:** Pessoal · **Período:** out/2026
- **Link:** 🔒 *sem link — repositório privado*

```
Pacote de guias, checklists e textos prontos para montar perfil no LinkedIn:
título, "Sobre", experiência, habilidades, destaques e métricas reais extraídas
do código.

Stack: Markdown
```

---

## ⚡ Versão curta (se o campo limitar caracteres)

Use só as 3 primeiras linhas de cada descrição acima.

---

## 📌 Ordem sugerida (maior impacto primeiro)

1. Ideias.dev.br
2. Clubset
3. Control School
4. OdontoPro
5. Neuro Comunicação
6. Calendário Unificado
7. register-students
8. pyton-projects
9. Style Hub
10. App Finanças

> Dica: os **4 primeiros** já bastam se você quiser um perfil mais enxuto.

---

## 🔗 Quem leva link e quem não leva

**✅ Preenche o campo Link (repo público):**

`ideias_dev` · `control-school-back` · `control-school-front` · `odontopro` ·
`style-hub` · `app-financas` · `base-nextjs` · `cola-componente` · `pyton`

**🔒 Lista o projeto mas deixa o campo Link VAZIO (repo privado):**

`clubset` · `calendario-unificado` · `neurocomunicacaobrasil` ·
`register-students` · `pyton-projects` · `linkedin`

> Motivo: um link que dá 404 no perfil do candidato passa impressão de "projeto
> inexistente". Melhor listá-lo sem link — a descrição com métricas já faz o trabalho.

**Se um dia quiser liberar o link:** GitHub → repo → **Settings** → **Danger Zone** →
**Change repository visibility** → **Make public**.
