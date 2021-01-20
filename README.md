# Trabalho de Conclusão de Curso de Pós-Graduação BI-Master da PUC-Rio - Projeto Nadir
## Resumo
## Descrição
Muito antes do Homem desenvolver sistemas como o GPS, os Grandes Navegadores tiveram que usar os meios que estavam em seu alcance para se localizar com precisão no mar. Sendo o mais célebre desdes, usar o conhecimento dos astros em seu favor, que também viria a ser conhecido como Navegação Atronômica. Através do conhecimento do céu e de cálculos matemáticos o Homem conseguiu se localizar com precisão aceitável em alto mar. Para uso de tal ferramenta, era necessário o conhecimento do céu, a localização de determinadas estrelas, a medição de certos parâmetros com precisão e a capacidade matemática de transformar esses parâmetros em coordenadas geográficas.
Tendo como inspiração essa técnica milenar, o presente Trabalho de Conclusão de Curso tem como objetivo apresentar uma Proof of Concept (PoC), ou Prova de Conceito, utilizando Redes Neurais Convolucionais, somado a técnicas de Transfer Learning utilizando a Rede Neural VGG16, com o objetivo fim de realizar as primeiras etapas necessárias a navegação astronômica: a identificação de constelações no céu.
O presente trabalho foi desenvolvido inteiramente usando a linguagem de programação Python com o auxílio de bibliotecas específicas de Deep Learning como o Tensorflow e Keras, uma vez que estas ferramentas tem ganhado muito destaque na área de Inteligência Artificial. Usou-se como estrutura inicial as camadas convolucionais da Rede Neural VGG16 que já conhecida por bons resultados em reconhecimento de imagens. Como otimizador para o treinamento, foi escolhido o Stochastic Gradient Descent (SGD).

## Parâmetros
Tamanho incial do Dataset:
Quantidade de constelações trabalhadas: 4
Rede Usada para Transfer Learning: VGG16
Otimizador: Stochastic Gradient Descent (SGD)
Taxa de Aprendizado Inicial: 1e-3
Função de Erro: "categorical_crossentropy"
Métrica: Accuracy
Épocas: (Inicialmente) 1000; (Early Stopping) 713
Early Stopping Patience: 40
Reduce LR On Plateau Patience: 20; Factor: 0.5
- Tamanho incial do Dataset:
- Quantidade de constelações trabalhadas: 4
- Rede Usada para Transfer Learning: VGG16
- Otimizador: Stochastic Gradient Descent (SGD)
- Taxa de Aprendizado Inicial: 1e-3
- Função de Erro: "categorical_crossentropy"
- Métrica: Accuracy
- Épocas: (Inicialmente) 1000; (Early Stopping) 713
- Early Stopping Patience: 40
- Reduce LR On Plateau Patience: 20; Factor: 0.5

## Treinamento


## Resultados

Accuracy
Train set: 0.94
Validation set: 0.90
Test set: 0.84
- Train set: 0.94
- Validation set: 0.90
- Test set: 0.84
