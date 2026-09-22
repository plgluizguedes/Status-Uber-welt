# Über-Welt · Status Dashboard

Dashboard de status ao vivo do servidor Minecraft **Über-Welt**, mostrando Java Edition e Bedrock (via Geyser/Floodgate) lado a lado.

🔗 **Demo ao vivo:** _(cole aqui o link do GitHub Pages depois de publicar)_

## O que ele mostra

- Status online/offline de Java e Bedrock em tempo real
- Jogadores online / máximo, com anel de porcentagem
- Versão, protocolo, software (Paper, etc.) e MOTD
- IP, porta e hostname com botão de copiar
- Lista de jogadores conectados (quando o servidor permite)
- Histórico visual das últimas checagens (online/offline)
- Atualização automática configurável (padrão: 60s)

## Como configurar

Clique no ícone de engrenagem no canto superior direito da página para abrir o painel de configurações e ajustar:

- Nome do servidor e frase de boas-vindas
- Endereço e porta do Java
- Endereço e porta do Bedrock/Geyser
- Intervalo de atualização (em segundos)

As configurações ficam salvas no navegador de cada visitante (localStorage) e não afetam os outros.

## Tecnologia

Arquivo único (`index.html`), sem build e sem dependências além de duas fontes do Google Fonts. HTML, CSS e JavaScript puro. Os dados vêm da API pública [mcstatus.io](https://mcstatus.io), sem necessidade de chave de API.

## Publicar alterações

1. Edite `index.html` direto pelo GitHub (ícone de lápis) ou localmente
2. Faça commit das mudanças
3. O GitHub Pages republica automaticamente em cerca de 1 minuto

## Embutir no Notion

Depois de publicado, copie o link do GitHub Pages e cole dentro de um bloco `/embed` no Notion.

---

Feito para o servidor **Über-Welt** · dados via [mcstatus.io](https://mcstatus.io)
