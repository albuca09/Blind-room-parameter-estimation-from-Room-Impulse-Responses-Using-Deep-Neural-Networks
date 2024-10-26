# Blind-room-parameter-estimation-from-Room-Impulse-Responses-Using-Deep-Neural-Networks

PT-BR:

Estimativa Cega de Parâmetros Acústicos de Salas

Este repositório contém a implementação do projeto de Estimativa Cega de Parâmetros Acústicos de Salas a partir de Respostas ao Impulso usando Redes Neurais Profundas. O objetivo do trabalho é estimar parâmetros acústicos de ambientes, como tempo de reverberação (T60), índice de claridade (C80), entre outros, a partir de respostas ao impulso, utilizando métodos de aprendizado profundo.

Estrutura do Repositório:

O código está dividido nas seguintes partes:

1- Análise e Seleção de Simulação de Respostas ao Impulso Sintéticas
Nessa seção, são exploradas diferentes simulações de respostas ao impulso para avaliar sua adequação ao problema. O processo envolve a seleção de métodos de simulação que melhor replicam condições reais de ambientes acústicos.

2- Geração e Pré-processamento dos Dados
Aqui, são geradas as respostas ao impulso sintéticas com base nos parâmetros definidos e, em seguida, realizadas etapas de pré-processamento, como normalização e filtragem dos dados, preparando-os para entrada na rede neural.

3- Implementação da Rede Neural Profunda
Desenvolvimento do modelo de rede neural profunda, que é treinado para estimar parâmetros acústicos de forma cega, ou seja, sem conhecimento prévio das características físicas da sala.

4- Treinamento e Validação do Modelo
O modelo é treinado usando um conjunto de dados de respostas ao impulso sintéticas. Nesta etapa, são definidos os hiperparâmetros, a função de custo e o processo de avaliação, visando otimizar a capacidade de generalização do modelo.

5- Avaliação de Desempenho em Dados Reais
Teste do modelo em respostas ao impulso reais para verificar sua precisão na estimativa dos parâmetros acústicos em ambientes reais, comparando com métodos tradicionais.

ENG:

Blind Estimation of Room Acoustic Parameters

This repository contains the implementation of the Blind Estimation of Room Acoustic Parameters from Impulse Responses using Deep Neural Networks project. The objective is to estimate acoustic parameters of environments, such as reverberation time (T60), clarity index (C80), among others, from impulse responses using deep learning methods.

Repository Structure

The code is divided into the following parts:

1- Analysis and Selection of Synthetic Impulse Response Simulations
In this section, different impulse response simulations are explored to assess their suitability for the problem. The process involves selecting simulation methods that best replicate real acoustic environment conditions.

2- Data Generation and Preprocessing
Here, synthetic impulse responses are generated based on defined parameters, followed by preprocessing steps such as normalization and data filtering, preparing them for input into the neural network.

3- Deep Neural Network Implementation
Development of the deep neural network model, which is trained to estimate acoustic parameters in a blind manner, i.e., without prior knowledge of the room’s physical characteristics.

4- Model Training and Validation
The model is trained using a dataset of synthetic impulse responses. This step defines hyperparameters, the cost function, and the evaluation process, aiming to optimize the model's generalization capability.

5- Performance Evaluation on Real Data
Testing the model on real impulse responses to verify its accuracy in estimating acoustic parameters in real environments, comparing it to traditional methods.
