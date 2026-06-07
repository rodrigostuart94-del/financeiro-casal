# Manual Financeiro · Rodrigo & Esther

Painel de gestão financeira e investimentos do casal — diagnóstico, saúde financeira,
controle de receitas/despesas, metas, reserva de emergência, viagens, investimentos,
aportes, dividendos e relatórios mensais.

É uma aplicação **estática** (um único HTML + CSS + JavaScript, sem dependências de build).

## Como acessar

O site é publicado gratuitamente pelo **GitHub Pages**:

> **https://rodrigostuart94-del.github.io/financeiro-casal/**

## Como usar localmente

Basta abrir o arquivo [`index.html`](index.html) no navegador (duplo clique).

## Onde os dados ficam salvos

Os lançamentos são gravados no **`localStorage` do navegador** de cada pessoa.

> ⚠️ **Importante:** por enquanto os dados **não são sincronizados** entre dispositivos
> ou entre Rodrigo e Esther — cada navegador guarda a sua própria cópia. O site fica
> acessível para os dois, mas o que um digita não aparece para o outro.
>
> Para ter **dados compartilhados em tempo real** (mesma base para os dois), o próximo
> passo é conectar um banco online gratuito (ex.: Supabase). É só pedir.

## Estrutura

- `index.html` — aplicação (página servida pelo GitHub Pages)
- `manual_financeiro.html` — cópia idêntica com o nome original do arquivo

## Tema

Layout em **azul** com detalhes em **dourado**, tipografia Fraunces + Manrope.
