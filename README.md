# metodo4_lbp_textura-
A identificação de áreas navegáveis em estradas rurais não pavimentadas é importante
para sistemas robóticos móveis e aplicações de assistência à navegação, pois a aparência
do terreno varia com a vegetação, a iluminação e as condições da superfície. Este trabalho
avalia uma abordagem de visão computacional baseada em descritores Local Binary
Patterns (LBP) e classificação por Random Forest para gerar máscaras binárias a partir
de imagens RGB do conjunto Off-Road Freespace Detection (ORFD). Foram comparadas
duas configurações: uma que utiliza características locais de textura e intensidade e outra
que acrescenta as coordenadas espaciais normalizadas dos pixels. A seleção experimental
registrada contém 1.416 pares de imagens e máscaras, dos quais 1.132 foram destinados ao
treinamento e 284 ao teste. A implementação é descrita como baseada em Python, com uso
de bibliotecas para processamento de imagens, extração de características e aprendizado
de máquina; entretanto, as versões das bibliotecas e as especificações do hardware não
puderam ser confirmadas nos arquivos disponibilizados para esta revisão. Nos resultados
registrados, a inclusão de informação espacial elevou o IoU médio de 0,4431 para 0,7709 e o
F1-score de 0,5959 para 0,8639; a precisão passou de 0,5741 para 0,8439 e o recall de 0,6666
para 0,9067. Os resultados indicam melhora na divisão experimental avaliada, embora
persistam falhas em cenas específicas e permaneça necessária a validação da generalização
e do tempo de processamento sob um protocolo uniforme.
Palavras-chave: Processamento Digital de Imagens; Áreas Navegáveis; Segmentação de
Imagens; Estradas Rurai
