Test Driven Development (TDD)

SEMPRE teste a cada nova alteracao

Deixar para testar tudo no final eh uma das mais perigosas armadilhas, isso lhe custara muito tempo

Tres leis do TDD:

Nao se deve criar um codigo de producao ate criar um teste de unidade de falha

Nao se deve escrever mais de um teste de unidade do que o necessario para falhar, e nao compilar eh falhar

Nao se deve escrever mais codigos de producao do que o necessario para aplicar o teste de falha atual

Os testes e os codigos de producao sao escritos juntos, com os testes um pouco mais avancados

Se vai fazer testes, faca testes que facam sentido, nao eh valido fazer um teste porco.

Ao fazer um teste porco e seu codigo passar nele, vc vai ter uma falsa impressao de que o codigo esta funcionando, porem eh seu teste que nao conseguiu fazer ele falhar

Um descaso leva a outro, assim como um ato autruista leva a outro

Ao fazer testes desde quando o codigo era um feto faz com que vc consiga fazer teste para cada faze do codigo, tornando-o robusto em todas suas etapas

Teste Limpo:

Legibilidade

Legibilidade

Legibilidade

**F.I.R.S.T**

Fast: Testes devem ser rapidos, se um teste rodar devagar, vc tera preguica de rodar com frequencia

Indenpendent: Os testes nao devem depender uns dos outros

Repeatable: Deve-se poder repetir esses testes em qualquer ambiente

Self-Validating: Os testes devem ter uma saida booleana (TRUE/FALSE)

Timely: Testes precisam ser escritos em tempo habil, nao faz sentido escrever um teste para uma versao antiga e nao mais necessaria do codigo