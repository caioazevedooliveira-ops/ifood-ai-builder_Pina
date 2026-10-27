# Campanha: &lt;nome&gt;

> Exemplo sanitizado. É o formulário que configura uma campanha nova.
> Os agentes leem este arquivo; campanha nova não mexe nos agentes.

## Público

Quem são as contas: tipo de empresa, região, porte.

## Lista de contas

Arquivo e colunas: onde está a lista, separador, qual coluna é o id, o nome, o site, o e-mail, o
telefone. Qual coluna define a oferta.

## Ofertas

Cada oferta: nome curto, o que é, oferta de entrada.

## Roteiro de pesquisa

O que o pesquisador levanta em cada conta e em quanto tempo. O que fica com o executor humano.

## Mensagens

- Textos: **fixos** (arquivo e seção de onde copiar) ou **livres** (dentro das regras gerais).
- Quais mensagens gerar, em que ordem e em que dia.
- O que pode ser preenchido e com quê.

## Regras extras

Além das regras gerais. Inclui bloqueios: quando não abordar a conta.

## Saída

Pasta onde gravar (uma subpasta por conta), registro de cadência (estado atual por conta) e registro
de envios (histórico).

## Envio

- **modo:** `teste` | `real`
- **Remetente:** conta de e-mail conectada.
- **Endereços de teste:** quem recebe no modo teste.
- **Registro:** caminho do histórico de envios.

## Pendências

O que falta decidir antes de rodar.
