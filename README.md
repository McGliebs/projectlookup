# GDS Helper

*Developed by Steven Faria.*

**🌐 Language / Idioma** — click a section below to expand:

<details open>
<summary><b>🇬🇧 English</b></summary>

<br>

Official **release host** for **GDS Helper** — the desktop app that finds
outbound + return flights and returns them in the compact GDS format.

This repository stores the published builds and the update manifest. The app
checks here and **updates itself automatically** — as an end user you don't need
to do anything in this repo.

### Get the app

Download the latest installer from the **[Releases](../../releases/latest)**
page and run `GDS Helper.exe`.

### First launch — connect Duffel

The first time you run the app, a **setup wizard** opens to connect it to
**Duffel**, the source of the flight data:

1. **Create a free Duffel account** — <https://duffel.com/> (no card required).
2. **Open the developer dashboard** — <https://app.duffel.com/tokens>.
3. **Create a token** and copy it — it starts with `duffel_test_…`.
4. **Paste** the token into the wizard and click **Test connection** to confirm
   it works against the real Duffel API.
5. **Done** — the token is stored securely in the **Windows Credential Manager**,
   never in plain text and never in a file.

You can skip the wizard and set the token up later from
**⚙ Settings → Configure Duffel API**. The test token (`duffel_test_`) gives
access to real airline data and is enough to look up availability.

### Update channels

- **Stable** — the recommended build, delivered to everyone.
- **Beta** — pre-release builds (marked *pre-release*) for early testing.

Each download's integrity is verified (SHA-256) before it is installed.

</details>

<details>
<summary><b>🇵🇹 Português</b></summary>

<br>

**Alojamento oficial das releases** do **GDS Helper** — a aplicação de
secretária que localiza voos de ida + regresso e os devolve no formato compacto
do GDS.

Este repositório guarda as versões publicadas e o manifesto de atualização. A
aplicação consulta-o e **atualiza-se automaticamente** — como utilizador final
não precisa de fazer nada aqui.

### Obter a aplicação

Descarregue o instalador mais recente na página de
**[Releases](../../releases/latest)** e execute `GDS Helper.exe`.

### Primeira abertura — ligar à Duffel

Na primeira vez que abre a aplicação, aparece um **assistente de configuração**
que a liga à **Duffel**, a fonte dos dados de voos:

1. **Criar uma conta Duffel gratuita** — <https://duffel.com/> (sem cartão).
2. **Abrir o painel de programador** — <https://app.duffel.com/tokens>.
3. **Criar um token** e copiá-lo — começa por `duffel_test_…`.
4. **Colar** o token no assistente e clicar em **Testar ligação** para confirmar
   que funciona contra a API real da Duffel.
5. **Concluído** — o token fica guardado em segurança no **Gestor de Credenciais
   do Windows**, nunca em texto simples e nunca num ficheiro.

Pode ignorar o assistente e configurar o token mais tarde em
**⚙ Definições → Configurar API Duffel**. O token de teste (`duffel_test_`) dá
acesso a dados de companhias aéreas reais e é suficiente para consultar
disponibilidade.

### Canais de atualização

- **Stable** — a versão recomendada, entregue a todos.
- **Beta** — versões de pré-lançamento (marcadas como *pre-release*) para
  testes antecipados.

A integridade de cada descarga é verificada (SHA-256) antes da instalação.

</details>
