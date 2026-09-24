# Como adaptar esta skill ao seu estilo

As seções 1 a 8 da skill valem para quase todo texto jurídico. O que as torna suas é a
seção 9, o padrão do autor. Este arquivo explica como preenchê-la. Leve uma tarde na
primeira vez e alguns minutos por semana depois.

## 1. Junte pares "minuta × versão final"

A fonte mais confiável do seu estilo não é o que você acha que faz, é o que você corrige.
Separe de três a cinco decisões (ou petições, ou pareceres) em que você recebeu uma
minuta, da IA ou de outra pessoa, e a alterou antes de assinar. Guarde as duas versões.

Antes de mostrar esses textos a qualquer IA, retire nomes, números de processo e dados
pessoais, ou use uma ferramenta de IA autorizada pelo seu tribunal ou escritório.

## 2. Peça a comparação

Dê os pares à IA com um pedido assim:

> Compare a minuta com a versão que assinei. Liste cada alteração que fiz, agrupada em:
> (a) vocabulário e expressões; (b) estrutura dos tópicos e dos parágrafos;
> (c) formatação de datas, números, citações de lei e de súmula; (d) conteúdo que
> acrescentei ou retirei; (e) fórmulas fixas (abertura, fecho, assinatura).
> Para cada item, cite o trecho antes e depois. Não interprete ainda; só descreva.

Depois, peça uma segunda passada: "Quais dessas alterações se repetem em mais de um
par? Quais parecem regra e quais parecem ajuste do caso?"

## 3. Separe o que manter do que mudar

Duas perguntas diferentes, e as duas importam.

**O que manter** são as suas marcas, as escolhas que um revisor genérico "corrigiria"
por engano. Sem esta lista, a IA desfaz o seu estilo toda vez que revisa. Exemplos do
padrão do autor desta skill, o juiz do trabalho Jorge Araujo:

- datas por extenso ("28 de janeiro de 2026");
- numerais por extenso no corpo do texto ("quarenta por cento", "dez dias");
- "inc." antes do inciso ("art. 818, inc. I, da CLT") e espaço depois do "§";
- "item I da Súmula 463 do TST", e não "Súmula 463, I, do TST";
- cláusulas por extenso ("cláusula décima primeira").

**O que mudar** são as correções que você faz sempre. Do mesmo padrão:

- cada tópico de mérito abre com dois parágrafos, o pedido e a defesa, antes da análise;
- o pedido é nomeado pelo conteúdo, nunca pela letra da inicial;
- valores e datas exatos, tirados dos documentos;
- título do tópico pelo tema ("Compensação de jornada"), não pela pretensão
  ("Descaracterização do regime de compensação");
- o entendimento próprio do juízo, quando existe, dito como tal ("em consonância com a
  ressalva pessoal já firmada por este Juízo").

## 4. Escreva a regra com o porquê e um exemplo

Uma regra sem razão vira ritual, e a IA aplica ritual fora de hora. Compare:

- Fraco: "Nunca use a letra do pedido."
- Melhor: "Nomeie o pedido pelo conteúdo ('o pedido de diferenças de vale-transporte'),
  nunca pela letra da inicial. A letra obriga o leitor a abrir outra peça e um erro de
  letra gera contradição."

Sempre que puder, dê um exemplo real, anonimizado, do antes e do depois.

## 5. Ajuste as listas das seções 1 a 3

A lista de palavras a evitar é genérica. Você provavelmente:

- usa alguma delas com gosto (tudo bem: registre na seção 9 que ela é permitida);
- detesta outras que não estão lá (acrescente, com o substituto que você usaria).

## 6. Registre as convenções da unidade

Tudo o que é fixo e que a IA não tem como adivinhar: formato do cabeçalho, a fórmula que
abre o dispositivo ("Isto posto", "Ante o exposto", "Passo a decidir"), o cargo na
assinatura, se e como você informa o uso de IA. Se as convenções variam por unidade ou
tipo de processo, diga quando vale cada uma.

## 7. Teste

Dê à IA a skill e uma minuta nova, e peça: "Revise esta minuta aplicando a skill de
estilo. Mostre cada alteração com a regra que a motivou." Se ela aplicar uma regra de
forma errada, o problema costuma estar no texto da regra: reescreva-a com mais contexto
em vez de acrescentar "SEMPRE" ou "NUNCA" em caixa alta.

## 8. Mantenha o guia vivo

Cada vez que você corrigir algo que a skill deveria ter evitado, acrescente a regra, com
a data e o motivo. Cada embargo de declaração acolhido é uma regra que faltava. Não
apague regras antigas sem motivo: se mudar de ideia, registre a mudança e a razão, para
saber depois por que o padrão é o que é.

## Onde a skill funciona

A skill segue o padrão aberto Agent Skills (uma pasta com um arquivo `SKILL.md`), aceito
pelo Claude (no site, no aplicativo e no Claude Code) e por outras ferramentas que
adotaram o padrão. Em ferramentas que não leem skills, o conteúdo do `SKILL.md` também
funciona colado como instrução de um projeto ou de um assistente personalizado.
