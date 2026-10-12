# Daily Danish

Aulas estáticas de dinamarquês. Abra `index.html` ou uma página em `lessons/` no navegador. Sem instalação, build ou dependências.

## Publicar no GitHub Pages

Em Settings → Pages → Build and deployment, escolha **Deploy from a branch**, branch **main**, pasta **/(root)** e salve.

## Estrutura

- `index.html`: índice das aulas.
- `lessons/YYYY-MM-DD.html`: uma página independente por dia, com CSS e JavaScript incorporados.

## Áudio

Botões reproduzem Google Translate TTS na página. A política `no-referrer` é definida no documento e antes do src do áudio. Erros e bloqueios oferecem síntese do navegador, se houver uma voz dinamarquesa instalada. Um áudio por vez; botão Parar; nenhuma chave ou dependência. O serviço Google é externo e pode ficar indisponível.

Respostas continuam manuscritas e enviadas no chat. Não há campos de resposta, correção automática, rastreamento ou armazenamento de dados do aluno.
