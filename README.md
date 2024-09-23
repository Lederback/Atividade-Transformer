# Transformer

O Transformer é um modelo de rede neural direcionado para o processamento de linguagem natural, como por exemplo tradução de textos como realizado nessa atividade. Ele se diferencia de outras arquiteturas com RNNs, ao usar um mecanismo de atenção que processa todas as palavras de uma vez, capturando de forma eficiente as dependências entre elas, sem seguir uma ordem sequencial.

## Pontos Positivos

Os Transformers são altamente eficientes devido a sua capacidade de processar todos os tokens de entrada de uma vez, o que acelera significativamente o treinamento em comparação com RNNs. Além disso, sua flexibilidade permite que sejam adaptados para diversos tipos de dados, como texto, áudios e imagens, ampliando sua aplicação para além do processamento de linguagem natural.

## Pontos Negativos

Os Transformers exigem alto custo computacional devido às múltiplas camadas de atenção e ao paralelismo, tornando seu uso inviável para alguns dispositivos. Além disso, são propensos a overfitting em datasets pequenos, a menos que técnicas de regularização sejam aplicadas na base de dados.