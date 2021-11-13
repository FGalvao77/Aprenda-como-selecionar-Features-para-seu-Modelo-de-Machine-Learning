# Aprenda como selecionar `Features` para seu Modelo de Machine Learning

![image](https://user-images.githubusercontent.com/63373520/141599584-39d11de6-dcab-4c6f-96aa-c754dc3a2370.png)
- Fonte: https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/

A `Feature Selection` ou seleção de variáveis, é uma etapa essencial no processo de criação de um modelo de machine learning. Antes de tudo iremos entender o por que redução de dimensionalidade é tão importante, e posteriormente iremos aplicar algumas técnicas de _feature selection_.

**Por que a redução de dimensionalidade é importante?**

No aprendizado de máquina, para capturar indicadores úteis e obter um resultado mais preciso, instintivamente adicionamos o máximo de features possível logo no início do processo. Porém, a partir de um certo momento, o desempenho do modelo começa a diminuir com o aumento do número de features. Este fenômeno é frequentemente referido como `“The Curse of Dimensionality”` (**A Maldição da Dimensionalidade**).

_A maldição da dimensionalidade ocorre porque a densidade do conjunto de dados diminui exponencialmente com o aumento da dimensionalidade._

Quando continuamos adicionando features sem aumentar o número de amostras do dataset de treinamento, a dimensionalidade do espaço de features aumenta e se torna cada vez mais esparsa. Devido a essa dispersão, torna-se muito mais fácil encontrar uma solução “perfeita” para o modelo de aprendizado de máquina, o que muito provavelmente leva ao problema do overfitting.



