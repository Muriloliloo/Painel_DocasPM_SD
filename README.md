# Controle de Docas SSP15 - PM, SD e SDE1

Painel web para acompanhamento operacional das ondas PM, Same Day (SD) e SDE1, alinhado a estrutura do Painel_DocasAM1.

## Recursos

- Controle de 92 docas por onda.
- Modos de visualizacao, alertas e acompanhamento de status.
- Base Operacional unica, com atualizacao cumulativa.
- Historico por rota e acompanhamento de tempos.
- Justificativas, resumo OOT, fechamento executivo e Farol da Expedicao.
- Exportacao de fechamento em imagem.
- Firebase com perfis Administrador/Leitor e sincronizacao entre dispositivos.

## Ciclos e horarios oficiais

- PM Onda 01: 13:20-13:50
- PM Onda 02: 13:50-14:15
- PM Onda 03: 14:15-14:35
- SD Onda 01: 17:10-17:30
- SD Onda 02: 17:30-18:00
- SD Onda 03: 18:00-18:30
- SDE1 Onda 01: 18:00-18:30
- SDE1 Onda 02: 18:30-19:00

## Arquivos principais

- `index.html`: painel principal publicado pelo GitHub Pages.
- `ondas-pm-sameday-dados.js`: ondas e horarios oficiais do PM/SD/SDE1.
- `firebase-config.js`: configuracao de sincronizacao; usa o documento `docas-pm-sd`.
- `html2canvas.min.js`: suporte a exportacao de imagens.
- `LEIA-ME-PM-SAMEDAY.txt`: orientacao operacional.

## Observacao operacional

A Base Aduana foi removida do editor e da logica do projeto. A Base Operacional e a fonte unica para processo, status, tempo e doca operacional.
