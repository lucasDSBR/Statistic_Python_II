# Statistic_Python_II

## Intervalos de Confiança:
    - Como estamos utilizando amostra... Devemos esperar variação.
    - A Primeira amostra pode variar com relação a segunda...
    - A segunda com relação a terceira e etc...
    - Mas devemos poder "medir" o quanto pode ser esta variação.
    - Intervalode de Congiança: O parâmetro mais ou menos a margem de erro estimada;
    - Parâmetro: valor a ser estimado;
    - Margem de erro: variabilidade, para mais ou para menos;
    - Nível de Confiança: de 80 a 99%;
    - Tamanho da Amostra (n)
    
    ### TOPOS DE INTERVALOS DE CONFIANÇA ###
    
    - Intervalo de Confiança para a média;
    - Intervalo de Confiança para a proporção;
## Intervalos de Confiança para a média:
    -> Troca entre Margem de Erro, Intervalo de Confiança e Amostra:
        - Aumentando a margem de erro, é natural que as chances da minha amostra estarem dentro do intervalo,
          por isso eu tenho um intervalo de confiança maior.
        - Da mesma forma, aumentando n, reduz a chance do efeito acaso, por isso minha margem de erro reduz.

## Teste de Hipótese:
    - Confirmar ou negar uma premissa usando uma amostra;
    - Esta premissa usa parâmetro, por exemplo: 56% dos brasileiros não gostam de estatística.
    - Encontrar diferença não é tudo. É preciso saber se esta diferença é estatisticamente significante.
    
    ### ETAPAS PARA FAZER UM TESTE DE HIPÓTESE:
    1 - Definir o tamanho da sua amostra;
    2 - Coletar dados;
    3 - Calcular a média e o desvio padrão;
    4 - Definir as duas hipóteses: H0 e Ha
    5 - Definir o seu 'α' – alpha
    6 - Padronizar seus dados gerando a estatística de teste;
    7 - Encontrar o valor-p na Tabela Z
    8 - Comparar com seu 'α' – alpha
    9 - Emitir seu veredito.
## T de Student:
    - Utilizada quando a amostra é pequena(menor que 30);
    - E não se conhece o desvio padrão da população;
    - Custo: Maior variabilidade(por exemplo, em um teste de hipótese)
    - Tendência maior de encontrar valores nas caudas(caudas maiores)
    - Se n >= 30, se assemelha a uma distribuição normal.