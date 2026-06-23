# Controle de Docas SSP15 - PM e SD

Painel web para controle das ondas PM e SD, com docas, rotas carregadas, rotas expedidas, justificativas, fechamento por ciclo e fechamento geral.

## Como Publicar no GitHub Pages

1. Crie um repositorio no GitHub.
2. Envie todos os arquivos desta pasta para o repositorio.
3. No GitHub, entre em **Settings > Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Clique em **Save**.
6. Aguarde alguns minutos ate o GitHub gerar o link do site.

O link ficara parecido com:

`https://seu-usuario.github.io/nome-do-repositorio/`

## Arquivos Principais

- `index.html`: painel principal. No GitHub Pages precisa ter esse nome.
- `ondas-pm-sameday-dados.js`: dados iniciais do painel PM e SD.
- `assets/logo-dhl.png`: logo DHL.
- `assets/logo-mercado-livre.png`: logo Mercado Livre.
- `LEIA-ME-PM-SAMEDAY.txt`: instrucoes de uso operacional.

## Upload dos Logos

No GitHub, os logos precisam ficar dentro da pasta:

```text
assets/logo-dhl.png
assets/logo-mercado-livre.png
```

Se os logos forem enviados fora da pasta `assets`, o painel nao vai encontrar as imagens.

## Importante

Nesta versao, os dados ficam salvos no navegador de cada computador. O GitHub Pages publica o painel online, mas ainda nao sincroniza os dados entre maquinas.

Para sincronizacao ao vivo entre varios computadores, a proxima etapa e conectar o painel a uma base em tempo real, como Firebase.

## Uso

1. Abra o link do GitHub Pages.
2. Clique em **Editar dados**.
3. Cole a **Extracao** com onda, rota, doca e transportadora.
4. Cole a **Base** com as rotas que subiram QR ou com status `Expedida`.
5. Acompanhe PM e SD no painel de docas, justificativas e fechamento.

## Ciclos

- PM Onda 01
- PM Onda 02
- PM Onda 03
- SD Onda 01
- SD Onda 02
- SD Onda 03

