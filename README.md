# Quão efetivas são Redes Neurais baseadas em Grafos na Detecção de Fraude para Dados em Rede?

Repository containing all experiments for my paper in X Brazilian Workshop on Social Network Analysis and Mining (BraSNAM 2021): "Quão efetivas são Redes Neurais baseadas em Grafos na Detecção de Fraude para Dados em Rede?"

## Dataset Repository

- [YelpChi](http://odds.cs.stonybrook.edu/yelpchi-dataset/)
- [Elliptic Data Set](https://www.kaggle.com/ellipticco/elliptic-data-set)
- [AMLSim](https://github.com/ronaldpereira/AMLSim)

## Experiments


- [XGBoost](https://github.com/ronaldpereira/amlsim_xgb)
- [GCN](https://github.com/ronaldpereira/gcn)
- [GAT](https://github.com/gordicaleksa/pytorch-GAT)
- [GraphSAGE](https://github.com/williamleif/GraphSAGE)
- [GraphSAINT](https://github.com/GraphSAINT/GraphSAINT)
- [EvolveGCN](https://github.com/ronaldpereira/EvolveGCN)
- [FastGCN](https://github.com/ronaldpereira/FastGCN)
- [Pick And Choose GNN](https://github.com/ronaldpereira/pick-and-choose-gnn)

## Cite

Please cite our paper if you use this code in your own work:

``` TEX
@INPROCEEDINGS{pereira2021efetivas,
    AUTHOR="Ronald Pereira and Fabricio Murai",
    TITLE="Quão efetivas são Redes Neurais baseadas em Grafos na Detecção de Fraude para Dados em Rede?",
    BOOKTITLE="CSBC 2021 - BraSNAM () ",
    ADDRESS="",
    DAYS="18-22",
    MONTH="jul",
    YEAR="2021",
    ABSTRACT="Redes Neurais baseadas em Grafos (GNNs) são modelos recentes criados para o aprendizado de representações de nós (e de grafos), que alcançaram resultados promissores na detecção de padrões que ocorrem em dados de larga escala que relacionam diferentes entidades. Dentre esses padrões, fraudes financeiras se destacam por sua relevância socioeconômica e por apresentarem desafios particulares, tais como o desbalanceamento extremo entre as classes positivas (fraudes) e negativas (transações legítimas), e o desvio de conceito (i.e., propriedades estatísticas dos dados mudam ao longo do tempo). Como as GNNs são baseadas em propagação de mensagem, a representação de um nó acaba sendo muito impactada pelos seus vizinhos e pelos hubs da rede, amplificando os efeitos do desbalanceamento. Pesquisas recentes tentam adaptar estratégias de sub- e sobreamostragem para GNNs a fim de mitigar esse efeito sem, contudo, considerar o desvio de conceito. Neste trabalho, realizamos uma série de experimentos para avaliar técnicas existentes de detecção de fraudes em rede, considerando os dois desafios anteriores. Para isso, utilizamos conjuntos de dados reais, complementados por dados sintéticos criados a partir de uma nova metodologia introduzida aqui. Baseado nessa análise, propomos uma série de pontos de melhoria a serem investigados em pesquisas futuras.",
    KEYWORDS="Lifecycle: characterization, analysis, mining, learning, sampling, monitoring, ; Human: spam, misinformation, malicious activities, ; Context: marketing, business, management, digital humanities, and software ecosystems. ",
    URL="http://XXXXX/214293.pdf"
}
```
