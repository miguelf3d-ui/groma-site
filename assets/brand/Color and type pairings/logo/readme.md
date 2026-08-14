# Logótipo Backshift

- `backshift-lockup.svg` — principal, tile amarelo + palavra escura (250×64)
- `backshift-lockup-reversed.svg` — marca nua sobre fundo escuro, como no cabeçalho do site
- `backshift-appmark.svg` — favicon e ícone de aplicação (64×64)
- `backshift-wordmark.svg` — só a palavra, com a ponta sobre o k

A marca é o **k de backshift rematado por uma ponta de seta** — o mesmo elemento
que distingue o wordmark. No appmark o k é desenhado em traçados, não em texto,
porque um favicon nunca carrega uma fonte externa e um `<text>` cairia para a
fonte que o sistema tivesse à mão.

Cores: tinta `#16170F` · amarelo `#F2E7A9` · marinho `#0A1020` · texto `#EEF1F7`
Tipo: Karla 700 para a palavra.

Os lockups e o wordmark usam texto vivo, com as fontes carregadas por `@import`
— renderizam bem no browser. Para impressão, Illustrator ou qualquer uso
offline, abre cada ficheiro e converte o texto em curvas (Tipo → Criar
contornos) uma vez, e grava. Não consigo vetorizar as fontes daqui.
