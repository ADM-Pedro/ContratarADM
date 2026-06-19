# 3 — Formulário de Candidatura a ADM (PÚBLICO)

Página única (`index.html`) onde quem quer ser ADM do **DK Diário Brawl** se candidata.
Sem dependências, sem build. Abre no navegador e publica em qualquer lugar.

## ⭐ Antes de publicar
Coloque o arquivo **`logo.png`** nesta pasta (já vem junto). Se faltar, o site não quebra,
só não mostra a logo.

## 🚀 Como publicar no GitHub (grátis)
1. Crie um repositório no GitHub e suba os arquivos desta pasta (`index.html` + `logo.png`).
2. Vá em **Settings → Pages**.
3. Em "Branch", escolha `main` e a pasta `/root`, salve.
4. Em 1–2 minutos o site fica no ar num link tipo
   `https://seu-usuario.github.io/nome-do-repo`.
5. **Divulgue esse link** pra galera que quer ser ADM.

## ⚙️ Configuração (dentro do `index.html`)
No início do `<script>`:

```js
var WHATSAPP_ADM = "5511998385244"; // número que RECEBE as candidaturas
```

Troque pelo WhatsApp de quem vai receber as candidaturas (só números, com DDI 55).

## Como funciona
1. O candidato preenche poucas perguntas (nome, WhatsApp, idade, experiência,
   disponibilidade — horas/dia, horários livres e dias por semana —, se é confortável
   com Pix/dinheiro, Brawl e motivo). O campo de **prova só aparece pra quem disse que
   já teve experiência** — e mesmo assim é opcional.
2. O site calcula uma **nota automática (0–100)** dele.
3. Ao enviar, abre o **WhatsApp do responsável** já com tudo escrito + um **código**.
4. O candidato te manda essa mensagem. Você cola o código no **Painel de Candidatos**
   (pasta 4) pra ver o ranking.

> Importante: como é site estático, a resposta só chega quando o candidato envia a
> mensagem no WhatsApp. Por isso o botão de WhatsApp aparece automático no final.
