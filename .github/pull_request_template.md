<!--
Para o agente que abre este pull request: preencha cada seção com frases simples.
Escreva "nenhum" numa seção que não se aplica. Nunca deixe uma seção vazia.
Mantenha o corpo no que o revisor não lê no diff. Não liste arquivos e não repita o diff.
Não narre a execução: sem registro da execução, sem "ninguém acompanhou", sem link de sessão e sem Co-Authored-By.
Apague todos os comentários, inclusive os das seções, antes de abrir o pull request.
-->

## O que muda para quem integra

<!-- Uma ou duas frases, nas palavras do título do pull request. Cite o endpoint, o campo ou o código de erro. -->

## Por quê

<!-- O motivo que o revisor não enxerga no diff. -->

## Pull request correspondente e ordem de merge

<!-- Cite o pull request do `mypcards` que muda a API e diga se já está em produção. Mesclar este pull request publica a documentação na hora, então ele só entra depois. Sem pull request par, escreva "nenhum". -->

## Quebra a integração?

<!-- Diga "aditiva" ou "quebra". Caminho removido, campo removido do schema e código de erro removido quebram quem integra. Para uma quebra, diga o que a pessoa que integra precisa fazer. -->

## Fica de fora

<!-- O que um revisor esperaria ver nesta mudança e não vai encontrar. Cite também cada problema ou ideia que esta execução achou e não registrou. Sem nada, escreva "nenhum". -->

## Olhe primeiro

<!-- Um ou dois pontos em que um erro custaria mais, como um schema, a enum `Jogos` ou o texto de autenticação. -->

## Verificações

- Lint: <!-- `npx @redocly/cli lint swagger.yaml`: erros e avisos, e se os avisos são os mesmos da `main`. -->
- Produção: <!-- A resposta descrita foi conferida com uma chamada real à produção? Diga sim ou não. -->
- Não verificado: <!-- Cada verificação que você não rodou, como a renderização no Swagger UI. Escreva "nenhum" só quando rodou tudo de que esta mudança precisa. -->
