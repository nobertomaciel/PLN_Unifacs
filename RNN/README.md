____________________________________________________________________________________________________________________________
# COMPETIÇÃO: rede neural recorrente RNN, sistema de predição textual (autocompletação)

- 1º lugar: 7 pontos na AV2
- 2º lugar 5 pontos na AV2
- 3º lugar 3 pontos na AV2
- Demais equipes (que entregarem os arquivos treinados): 1 ponto na AV2

## OBJETIVO:
- Desenvolver sistema para autocompletação textual que seja capaz de prever até as próximas três palavras em uma frase.
## PODE:
- Alterar número de épocas;
- Alterar o número de camadas da rede;
- Alterar a topologia (se aplicável);
- Aplicar dropout  (se aplicável);
- Aplicar data augmentation (se aplicável);
- Trocar funções de ativação;
- Usar qualquer dataset (apenas em português brasileiro);
- Implementar leitura automática de dataset.
  
## NÃO PODE:
- Usar editor diferente do Google Colab;
- Usar algoritmo diferente da RNN base proposta pelo professor (link abaixo);
- Usar dataset em outra língua que não seja o português brasileiro.
## PRAZO PARA DEFINIÇÃO DAS EQUIPES:
- Até o dia 30/05/2025 às 19h
## PRAZO FINAL PARA ENTREGA DOS ARQUIVOS DO MODELO TREINADO:
- Prazo para envio: 02/06/2025 20:00h
- Arquivos que devem ser enviados: nome_do_grupo_tokenizer_RNN.pkl e nome_do_grupo_modelo_RNN.keras;
## REGRAS GERAIS:
- Os alunos que não participarem das equipes ATIVAMENTE não terão pontuação, os líderes das equipes ficam responsáveis por informar a não participação de qualquer membro;
- o descumprimento de quaisquer prazos gerará a desclassificação da equipe e perda da pontuação;
- TODAS as equipes devem usar apenas o Google Colab para executar o código;
- O líder da equipe deverá enviar os arquivos (devidamente nomeados com o nome da equipe) da rede treinada (nome_do_grupo_tokenizer_RNN.pkl e nome_do_grupo_modelo_RNN.keras) para o e-mail do professor;
- A acurácia será medida pelo código de avaliação do professor, que avaliará a rede treinada com frases que serão divulgadas no momento da avaliação competição.

## AVALIAÇÃO:
- O critério para julgamento será o maior índice de acerto dentro do conjunto de teste (oculto, divulgado apenas no dia da avaliação da RNN);
- Ocorerá no dia 02/06/2025 ao vivo, na aula prática, juntamente com os alunos, o rede de cada equipe será testada e a acurácia final validada.

## CÓDIGO BASE:
- https://github.com/nobertomaciel/AI-UNIFACS/blob/main/RNN/RNN_competition.ipynb
