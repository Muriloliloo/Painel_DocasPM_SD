# Controle de Docas SSP15 - PM e SD

Painel web para acompanhamento operacional das ondas PM e Same Day (SD), alinhado à estrutura do Painel_DocasAM1.

## Recursos

- Controle de 92 docas por onda.
- Modos de visualização, alertas e acompanhamento de status.
- Bases Operacional e Aduana com atualização cumulativa.
- Histórico por rota e acompanhamento de tempos.
- Justificativas, resumo OOT, fechamento executivo e Farol da Expedição.
- Exportação de fechamento em imagem.
- Firebase com perfis Administrador/Leitor e sincronização entre dispositivos.

## Ciclos e horários oficiais

- PM Onda 01: 13:20–13:50
- PM Onda 02: 13:50–14:15
- PM Onda 03: 14:15–14:35
- SD Onda 01: 17:10–17:30
- SD Onda 02: 17:30–18:00
- SD Onda 03: 18:00–18:30

## Arquivos principais

- `index.html`: painel principal publicado pelo GitHub Pages.
- `ondas-pm-sameday-dados.js`: ondas e horários oficiais do PM/SD.
- `firebase-config.js`: configuração de sincronização; usa o documento `docas-pm-sd`.
- `html2canvas.min.js`: suporte à exportação de imagens.
- `LEIA-ME-PM-SAMEDAY.txt`: orientação operacional.

O armazenamento local usa a chave exclusiva do PM/SD e o Firebase utiliza um documento separado do AM1, evitando mistura de dados entre os painéis.
