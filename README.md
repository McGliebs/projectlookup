# GDS Helper

*Developed by Steven Faria.*

**🌐 Language / Idioma** — click a section below to expand:

<details open>
<summary><b>🇬🇧 English</b></summary>

<br>

Official **release host** for **GDS Helper** — a desktop travel app with two
modes: a simple **Traveller** flight search and a **Professional** GDS toolset
for travel agents.

This repository stores the published builds and the update manifest. The app
checks here and **updates itself automatically** — as an end user you don't need
to do anything in this repo.

### Get the app

Download the latest installer from the **[Releases](../../releases/latest)**
page and run `GDS Helper.exe`.

### Two modes

Switch anytime from the **Mode** button in the header:

- **✈️ Traveller** — a simple flight search (From/To, dates, round-trip /
  one-way / multi-city, cabin class, passengers) with easy-to-read results and
  sorting/filters.
- **💼 Professional** — the full agent toolset: GDS timetable, Amadeus sell
  commands, PNR skeleton, and more.

Both modes can export results to **Excel** or **PDF**.

### First launch — connect Duffel

The first time you run the app, a **setup wizard** connects it to **Duffel**,
the source of the flight data:

1. **Create a free Duffel account** — <https://duffel.com/> (no card required).
2. **Open the developer dashboard** — <https://app.duffel.com/tokens>.
3. **Create a token** and copy it — it starts with `duffel_test_…`.
4. **Paste** the token into the wizard and click **Test connection**.
5. **Done** — the token is stored securely in the **Windows Credential Manager**.

You can set the token up later from **⚙ Settings → Configure Duffel API**.

### Update channels

- **Stable** — the recommended build, delivered to everyone.
- **Beta** — pre-release builds (marked *pre-release*) for early testing.

Each download's integrity is verified (SHA-256) before it is installed.

### Licence

GDS Helper is **commercial, proprietary software** — licensed, not sold.
Copyright © 2026 Steven Faria. All rights reserved.

Use requires a valid licence. Redistribution, resale, rental and reverse
engineering are not permitted. The full terms are supplied with the software.

> **Important:** GDS Helper is not a live Amadeus/GDS connection. The entries it
> generates are suggestions built from third-party data and must be verified by a
> qualified travel professional in the live GDS before booking or ticketing.

### Built with AI

**The source code of GDS Helper was written entirely by artificial
intelligence**, under the specification, direction, review and testing of Steven
Faria, who defined its requirements, business rules and operating logic.

The application itself contains **no AI system**: it runs no machine learning,
generates no synthetic content, and makes no automated decisions about people.
Under **Regulation (EU) 2024/1689 (the AI Act)** it is therefore not an "AI
system" within the meaning of Article 3(1) — its results come from deterministic
rules defined by a person (Recital 12) — so the Article 50 transparency
obligations are not engaged, and this disclosure is made voluntarily.

</details>

<details>
<summary><b>🇵🇹 Português</b></summary>

<br>

**Alojamento oficial das releases** do **GDS Helper** — uma aplicação de viagens
de secretária com dois modos: uma pesquisa simples de **Viajante** e um modo
**Profissional** com as ferramentas GDS para agentes de viagens.

Este repositório guarda as versões publicadas e o manifesto de atualização. A
aplicação consulta-o e **atualiza-se automaticamente** — como utilizador final
não precisa de fazer nada aqui.

### Obter a aplicação

Descarregue o instalador mais recente na página de
**[Releases](../../releases/latest)** e execute `GDS Helper.exe`.

### Dois modos

Alterne a qualquer momento no botão **Modo**, no topo:

- **✈️ Viajante (Traveller)** — pesquisa simples de voos (De/Para, datas, ida e
  volta / só ida / multidestino, classe, passageiros) com resultados fáceis de
  ler e ordenação/filtros.
- **💼 Profissional** — todas as ferramentas do agente: horário GDS, comandos de
  venda Amadeus, esqueleto de PNR e mais.

Ambos os modos podem exportar os resultados para **Excel** ou **PDF**.

### Primeira abertura — ligar à Duffel

Na primeira vez que abre a aplicação, um **assistente de configuração** liga-a à
**Duffel**, a fonte dos dados de voos:

1. **Criar uma conta Duffel gratuita** — <https://duffel.com/> (sem cartão).
2. **Abrir o painel de programador** — <https://app.duffel.com/tokens>.
3. **Criar um token** e copiá-lo — começa por `duffel_test_…`.
4. **Colar** o token no assistente e clicar em **Testar ligação**.
5. **Concluído** — o token fica guardado em segurança no **Gestor de Credenciais
   do Windows**.

Pode configurar o token mais tarde em **⚙ Definições → Configurar API Duffel**.

### Canais de atualização

- **Stable** — a versão recomendada, entregue a todos.
- **Beta** — versões de pré-lançamento (marcadas como *pre-release*) para testes.

A integridade de cada descarga é verificada (SHA-256) antes da instalação.

### Licença

O GDS Helper é **software comercial e proprietário** — licenciado, não vendido.
Copyright © 2026 Steven Faria. Todos os direitos reservados.

A utilização exige uma licença válida. Não são permitidas a redistribuição, a
revenda, o aluguer nem a engenharia inversa. Os termos completos acompanham a
aplicação.

> **Importante:** o GDS Helper não é uma ligação em direto ao Amadeus/GDS. As
> entradas geradas são sugestões construídas a partir de dados de terceiros e têm
> de ser verificadas por um profissional de viagens qualificado no GDS antes de
> reservar ou emitir.

### Feito com IA

**O código-fonte do GDS Helper foi escrito inteiramente por inteligência
artificial**, sob a especificação, direção, revisão e testes de Steven Faria, que
definiu os requisitos, as regras de negócio e a lógica de funcionamento.

A aplicação em si **não contém nenhum sistema de IA**: não executa aprendizagem
automática, não gera conteúdo sintético e não toma decisões automatizadas sobre
pessoas. Ao abrigo do **Regulamento (UE) 2024/1689 (Regulamento da IA)** não é,
por isso, um «sistema de IA» na aceção do artigo 3.º, n.º 1 — os resultados
provêm de regras determinísticas definidas por uma pessoa (considerando 12) —
pelo que as obrigações de transparência do artigo 50.º não são aplicáveis, sendo
esta divulgação voluntária.

</details>
