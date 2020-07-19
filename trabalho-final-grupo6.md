Trabalho final
================
Grupo 6
15/07/2020

A base de dados escolhida para o trabalho, disponível nesse
[link](http://www.transparencia.dadosabertos.mg.gov.br/dataset/compras-contratos-do-estado-de-minas-gerais),
apresenta os dados de compras e aquisições de materiais, bens e serviços
pelo Estado de Minas Gerais.

Perguntas:

1)  Quais foram os órgãos que tiveram maior gasto com essas compras?

2)  Lista dos programas que receberam maior verba e como isso se
    relaciona com o programa de governo atual.

3)  Como foi distribuído o gasto no programa que recebeu maior verba e
    no que recebeu menor verba.

4)  O valor total e média mensal de gastos dos 3 poderes em 2019 e 2020.

5)  O valor total e média mensal de gastos das 3 ou 5 unidades
    executores que tem os maiores gastos.

6)  Analisando as compras realizadas em 2019 e 2020, quais foram os bens
    e serviços que apresentaram os maiores gastos?

7)  Qual a evolução dos gastos em compras na área de saúde considerando
    os anos de 2019 e 2020?

8)  Comparação das despesas correntes e despesas de capital

9)  Evolução comparativa dos gastos das unidades orçamentárias

<!-- end list -->

    ## # A tibble: 10 x 27
    ##    id_empenho ano_exercicio sqa_gmifp sqa_credor sqa_natureza sqa_unidade_orc
    ##         <dbl>         <dbl>     <dbl>      <dbl>        <dbl>           <dbl>
    ##  1   12591660          2020  13659599     858955        41446            2586
    ##  2   12591661          2020  13659599     767278        41433            2586
    ##  3   12591663          2020  13659599     302530        41395            2586
    ##  4   12591665          2020  13659079     193878        41391            2604
    ##  5   12591666          2020  13659079     856737        41333            2604
    ##  6   12591672          2020  13659079     206748        41441            2632
    ##  7   12591673          2020  13659079     541520        41424            2632
    ##  8   12591677          2020  13659079     856737        41333            2661
    ##  9   12591678          2020  13659079       1300        41469            2667
    ## 10   12592779          2020  13659079      55712        41383            2583
    ## # … with 21 more variables: sqa_progtrab <dbl>, sqa_unidade_exec <dbl>,
    ## #   sqa_empenho <dbl>, nr_empenho <dbl>, dt_empenho <date>,
    ## #   unidade_orcamentaria <chr>, unidade_executora <chr>, funcao <chr>,
    ## #   subfuncao <chr>, programa <chr>, acao <chr>, categoria_econ <chr>,
    ## #   grupo_desp <chr>, elemento_desp <chr>, item_desp <chr>,
    ## #   modalidade_aplic <chr>, tipo_empenho <chr>, fonte_recurso <chr>,
    ## #   identificador_orc <chr>, razao_social_credor <chr>, vr_empenho <dbl>
