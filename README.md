# dio_project
# Projeto de Transfer Learning em Python

Este projeto utiliza Transfer Learning com a rede VGG16 para classificar imagens de leões e tigres. Aproveitando os pesos pré-treinados da VGG16 no ImageNet, o modelo foi ajustado para classificar duas classes (leão e tigre) a partir de imagens extraídas de um arquivo .zip. As imagens foram pré-processadas para o formato adequado, com resolução de 224x224 pixels e normalizadas. A última camada da VGG16 foi substituída por uma camada densa para classificação binária, enquanto as camadas anteriores foram congeladas. O modelo foi treinado e testado com dados balanceados, monitorando métricas como perda e acurácia. O projeto demonstra a eficácia do Transfer Learning em cenários com dados limitados.

## Transfer Learning Project in Python

This project uses Transfer Learning with the VGG16 network to classify images of lions and tigers. By leveraging the pre-trained weights of VGG16 on ImageNet, the model was adjusted to classify two classes (lion and tiger) from images extracted from a .zip file. The images were preprocessed to the appropriate format, with a resolution of 224x224 pixels and normalized. The last layer of VGG16 was replaced with a dense layer for binary classification, while the previous layers were frozen. The model was trained and tested with balanced data, monitoring metrics like loss and accuracy. The project demonstrates the effectiveness of Transfer Learning in scenarios with limited data.
