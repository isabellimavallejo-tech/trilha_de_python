1. Qual era o objetivo do projeto ML?
Usar um dataset para testar a acurácia de um modelo, analisar se houve overffiting e visualizar graficamente a diferença entre o treino e teste.
Qual dataset foi escolhido?
load_wine
2. Quais cuidados foram necessários na preparação?
Foi necessário listar os dados de treino e teste, tentar evitar overfitting e escolha do modelo mais adequado para esse contexto.
3. Por que o modelo foi escolhido?
Escolhi por ser menos complexo
4. Por que essas métricas foram utilizadas?
Foram usadas para comparar o treino com o teste, de modo a indicar quanto o modelo se assemelhou com o esperado.
5. O resultado foi satisfatório? Justifique com números.
sim, acurácia varia de 94% a 100%
6. Existem sinais de overfitting ou underfitting?
Sim. O overfitting acontece a partir de max_depth = 4. O modelo ainda está aprendendo com o treino mesmo que a acurácia esteja 100%
7. O que poderia ser melhorado?
Poderia testar o desempenho de outros modelos para comparar a acurácia e para analisar se terá menos overffiting.
