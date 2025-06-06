# anxiety-depression-dataset-pt
Este repositório contém um dataset com frases relacionadas a sintomas de ansiedade e depressão. 
As frases foram coletadas da rede social Bluesky, em português, com o objetivo de testar o desempenho do VADER em identificar sinais emocionais em textos em português.

# Como Usar
1. Clone este repositório para o seu ambiente local:
git clone https://github.com/raynasc/anxiety-depression-dataset-pt.git

# Conjunto de dados
Explicação de cada coluna da planilha:
1. Texto: Contém o texto analisado.
2. rotulo_humano: Rótulo atribuído manualmente com base no consenso entre duas avaliadoras: a autora e uma psicóloga.
3. rotulo_vader: Classificação automática gerada pelo VADER, podendo ser negativo, neutro ou positivo.
4. interpretacao_rotulo_vader: Interpretação clínica do rotulo_vader, com base na seguinte regra:
→ negativo → sintoma
→ positivo ou neutro → sem sintoma. Essa conversão serve para aproximar a análise de sentimento do VADER a um contexto clínico de triagem de sintomas.
5.vader_metricas: Pontuações brutas de sentimento geradas pelo VADER, incluindo neg, neu, pos e compound.



# anxiety-depression-dataset-pt
This repository contains a dataset with phrases related to symptoms of anxiety and depression.
The sentences were collected from the social network Bluesky, in Brazilian Portuguese, with the goal of testing the performance of VADER in identifying emotional cues in Portuguese-language texts.

# How to Use
Clone this repository to your local environment:
git clone https://github.com/raynasc/anxiety-depression-dataset-pt.git


# Dataset Description

1. **texto**: Contains the analyzed phrase or sentence.
2. **rotulo_humano**: Label manually assigned by consensus between two annotators: the author and a psychologist.
3. **rotulo_vader**: Automatic sentiment label generated by VADER (negative, neutral, or positive).
4. **interpretacao_rotulo_vader**: Clinical interpretation of rotulo_vader, based on the following rule:
   → negative → symptom
   → positive or neutral → no symptom
   This translation aims to approximate VADER's sentiment analysis to a mental health screening context.
5. **vader_metricas**: Raw sentiment scores returned by VADER, including neg, neu, pos, and compound.
