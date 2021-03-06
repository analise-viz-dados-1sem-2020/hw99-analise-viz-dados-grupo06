Trabalho final
================
Grupo 6: Eduardo Resende, Gabriel Isrrael, Leandro Saraiva e Matheus
Castro
03/08/2020

## Introdução

A base de dados escolhida para o trabalho, disponível nesse
[link](http://www.transparencia.dadosabertos.mg.gov.br/dataset/compras-contratos-do-estado-de-minas-gerais),
apresenta os dados de compras e aquisições de materiais, bens e serviços
pelo Estado de Minas Gerais.

Para a análise da base de dados escolhidas, o grupo buscou responder,
com a ajuda da visualização de dados, as seguintes perguntas:

1)  Quais foram os funções que receberam maiores verbas?
2)  Quais os programas que receberam maiores verbas?
3)  Como foi distribuído o gasto no programa que recebeu maior verba ?
4)  O valor total e média mensal de gastos dos 3 poderes em 2019 e 2020.
5)  O valor total e média mensal de gastos das 3 ou 5 unidades
    executores que tem os maiores gastos.
6)  Analisando as compras realizadas em 2019 e 2020, quais foram os bens
    e serviços que apresentaram os maiores gastos?
7)  Qual a evolução dos gastos em compras na área de saúde considerando
    os anos de 2019 e 2020?
8)  Comparação das despesas correntes e despesas de capital
9)  Evolução comparativa dos gastos das unidades orçamentárias

## Respostas para as perguntas sobre o banco de dados dos gastos do estado de Minas Gerais

1)  Quais foram os funções que receberam maiores verbas?

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

## Análise dos dados da questão 1

Com a questão um fica claro um padrão que será observado em todo o
trabalho: O maior gasto do Estado de Minas Gerais é com a garantia da
saúde dos mineiros. Tal característica se dá em virtude,
principalmente, dos gastos com medicamentos, como será mostrado a
seguir.

As outras áreas com maiores gastos são:

Segurança pública, como se esperado, tendo em vista o plano de governo
do Governador Romeu Zema. Jurídica, um gasto engessado e pré-determinado
para a manutenção da justiça do estado Tranporte, essa uma função é um
gasto que chama a atenção, em sociedade com tantas mecanismos de
comunicação é impensável um gasto de 300 milhões com transporte.
Entretanto, analisando os dados é possível afirmar que se trata de todo
tipo de transporte, por exemplo, ambulâncias. Dessa forma, essa é uma
função cabível de uma análise mais aprofundada e que, provavelmente,
permitirá ao estado redução de gastos. Administração, aqui entra os
gastos para manter a máquina pública como um todo funcionando. Também é
um função que permite melhores análises e possíveis reduções de gastos.

2)  Quais os programas que receberam maiores verbas?

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

## Análise dos dados da questão 2

Aqui estão os programas do Governo de Minas, em todas as esferas, que
mais receberam verbas entre os anos de 2019 e até março de 2020.

Prestação Jurisdicional: basicamente é a necessidade, resguardada por
lei, do Estado de oferecer o direito ao cidadão de ter sua defesa em um
processo jurídico. Ou seja, aqui são alocados recursos para todas as
atividades relacionadas a defesa pública. Apoio a administração pública:
também relacionada com o funcionamento da máquina pública. Gestão do
SUS: relacionado com a manutenção da saúde pública no estado. Estradas
de Minas: programa que tem a função de garantir a manutenção das
rodovias mineiras. É interessante analisar que, a despeito do senso
comum pensa, são investidos milhões na manutenção das estradas do
estado. Assistência hospitalar especializada: também relacionada com a
manutenção da saúde pública no estado.

3)  Como foi distribuído o gasto no programa que recebeu maior verba ?

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

## Análise dos dados da questão 3

Dentre os programas que mais recebem recursos, foi desconsiderado os
dois primeiro, em virtude de um ser relacionado com a defensoria pública
e o outro ser muito amplo. Dessa forma, foi feita análise com base no
programa de gestão do SUS.

Analisando o gráfico em questão fica evidente os grandes valores gastos
com medicamentos, ocupando mais de 95% dos gastos do programa,por parte
do estado de minas gerais. Nesse sentido, fica evidente a necessidade de
se propor soluções para o barateamento dos medicamentos, como a quebra
de patentes e a escolha de medicamentos genéricos.

4)  O valor total e média mensal de gastos dos 3 poderes em 2019 e 2020.

## Análise dos dados

4)  O gráfico abaixo apresenta a evolução mensal dos gastos da
    totalidade dos órgãos dos poderes Executivo, Legislativo e
    Judiciário.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->

Ao analisar o gráfico e o banco de dados, foi possível perceber,
primeiramente, que há uma vacância de dados das compras realizadas pela
Assembléia Legislativa de Minas Gerais (ALMG) em 2019. Como esses dados
estão ausentes, e sendo a ALMG o único órgão que possui gastos no poder
Legislativo, as informações sobre este poder se mostram inconclusivas
durante o ano de 2019.

Por outro lado, é possível perceber, como já podia se esperar, que os
gastos do poder Executivo excedem muito aos gastos dos outros dois
poderes. Isso ocorre pelo fato do Poder Executivo ser reponsável pelos
gastos com políticas públicas em todas áreas, como segurança, saúde,
educação, trasnporte, infraestrutura e etc.

Na tabela abaixo podemos verificar o valor total (em milhões de reais)
gasto pelos três poderes no período analisado, de janeiro de 2019 até
março de 2020, bem como a média mensal dos seus gastos (lembrando que os
dados de 2019 dos gastos do poder Legislativo estão ausentes).

| Poder       | Gasto\_total | Media\_mensal |
| :---------- | -----------: | ------------: |
| Executivo   |   2464.14198 |    164.276132 |
| Judiciario  |    336.04589 |     22.403059 |
| Legislativo |     38.84253 |      2.589502 |

5)  A tabela abaixo apresenta as cinco unidades executoras que
    apresentaram os maiores gastos totais durante o período analisado,
    exibindo os valores dos seus gastos totais e a média mensal, ambos
    em reais.

| unidade\_executora            | gasto\_total\_unidade | media\_mensal |
| :---------------------------- | --------------------: | ------------: |
| TJMG                          |             335519667 |      22367978 |
| NAJS                          |             183794847 |      12252990 |
| Diretoria de Manutenção - DER |             183690482 |      12246032 |
| SUBPAS - SAF                  |             137289403 |       9152627 |
| FUNED                         |             132338212 |       8822547 |

Apesar do poder Executivo apresentar gastos muito superiores ao do poder
Judiciário, a tabela acima traz um órgão do Judiciário como o que mais
gasta em compras públicas. Isso occorre pois, ao contrário do Executivo,
que possui inúmeros órgãos executando suas políticas públicas, o
Judiciário aqui é composto exclusivamente pelo Tribunal de Justiça de
Minas Gerais (TJMG). Dessa forma, o TJMG, como único compontente do
poder Judiciário, apresenta gastos superiores a qualquer órgão do
Executivo (lembrando da ausência dos dados da ALMG nessa análise).

Em seguida, podemos verificar que os órgãos executores que ocupam da 2ª
à 4ª posição pertencem ao poder Executivo, representando os 4 órgãos
que mais gastam em compras desse poder. O primeiro deles (2º lugar
geral) é o Nucleo de Atendimento À Judicialização da Saúde, enquanto o
terceiro (4º lugar geral) é a Subsecretaria de Políticas e Ações de
Saúde referente às compras de medicamentos para a população. Esse é um
fator importante que destaca como a judicialização da saúde representa
um fator muito oneroso para a administração pública do Estado de Minas
Gerais, como foi estudado mais a fundo na disciplina de Direito
Administrativo. Esse fator se refere às inúmeras ações judiciárias
sofridas pelo Estado para o fornecimento de medicamentos para os
cidadãos, que não são contemplados pelo SUS. [saiba
mais](http://www.mpdft.mp.br/saude/images/judicializacao/Judicializacao_acesso_medicamentos_MG.pdf).

Já o 3º lugar geral pertence á diretoria de manutenção do Departamento
de Estradas e Rodagem de Minas Gerais, o que é algo esperado pelos
gastos elevados em manutenção da infraestrutura viária do Estado. Por
último, a Fundação Ezequiel Dias, que visa participar do fortalecimento
do Sistema Único de Saúde, protegendo e promovendo a saúde, completando
3 das 4 unidades com maiores gastos do Executivo pertencendo, de alguma
forma, ao setor de saúde.

6)  Analisando as compras realizadas em 2019 e 2020, quais foram os bens
    e serviços que apresentaram os maiores gastos?

Ao analisar o gráfico abaixo percebe-se que os maiores gastos em compras
de bens em serviços em 2019 foram em **Medicamentos**, **Execução de
obras por contrato de bens não patrimoniáveis** e **Execução de obras
por contrato de bens patrimoniáveis**. Estes dois últimos itens estão
relacionados com as despesas com o pagamento de empreiteiras contratadas
para execução de obras. Já os gastos com compras de medicamentos tiveram
um valor de 348,94 milhões para os cofres públicos em 2019. Vale
ressaltar também que os gastos em **Material médico e hospitalar** e
**Serviços de produção e logística de medicamentos** tiveram custos
expressivos no ano de 2019.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-8-1.png)<!-- -->

Já o gráfico abaixo permite entender o comportamento dos gastos em
compras de bens e serviços no primeiro trimestre de 2020. O maiores
gastos estão no grupo de **Execução de obras por contrato de bens não
patrimoniáveis**, seguido pela **Locação de serviços de apoio
administrativo** e **Medicamentos**.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-9-1.png)<!-- -->

7)  Qual a evolução dos gastos em compras na área de saúde considerando
    os anos de 2019 e 2020?

No gráfico seguinte é possível mensurar os gastos que o Estado teve com
compras de bens em serviços na área de saúde em 2019. É percebido um
comportamento praticamente linear durante o período. De acordo com a
base de dados estudada, o valor total de recursos que o Estado gastou
nessa categoria em 2019 ficou em torno de 895 milhões de reais.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-10-1.png)<!-- -->

Analisando o primeiro trimestre de 2020 percebe-se que o Estado gastou
em torno de R$211 milhões em compras de bens e serviços na área de
saúde. No mesmo período de 2019 o Estado tinha gastado R$133 milhões.
Apesar da base de dados não trazer os dados do segundo trimestre de 2020
já é possível perceber um possível aumento nos gastos da área de saúde
provenientes da pandemia.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-11-1.png)<!-- -->

8)  O gráfico abaixo compara os valores empenhados referentes a despesas
    correntes e despesas de capitais.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-13-1.png)<!-- -->

A pergunta 8 é respondida pela análise da figura do chamado gráfico de
pizza. Buscou-se por meio dessa visualização comparar as despesas
correntes e as despesas de capital, confrontando-as por meio da
visualização em faixas no gráfico. Nota-se que as despesas correntes são
bem superiores as despesas de capital, o que era de se esperar tendo em
vista a natureza e utilização de cada uma. Não houve dificuldades no
tratamento dos dados nem surpresas na visualização, sendo o resultado
final muito parecido com o esperado inicialmente.

9)  O gráfico de linha abaixo apresenta a comparação das despesas
    empenhadas por 12 das unidades orçamentárias no período analisado de
    2019 a 2020 que mais empenharam.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-14-1.png)<!-- -->
Inicialmente, pensou-se em comparar as despesas das unidades
orçamentárias por meio do gráfico de área, no qual seria possível
observar a evolução das despesas a depender do tamanho da área colorida
daquela unidade. Contudo, diversos problemas surgiram com essa
visualização. A primeira delas é a enorme quantidade de unidades, o que
tornou a visualização muito confusa. Em segundo lugar, o fato das
despesas não serem continuas, ou seja, as unidades orçamentárias não
empenham despesas todos os dias. Por fim, os valores são muito distintos
uns dos outros, tendo valores de pouco reais e outros valores na
proporção de milhões de reais. Tudo isso distorceu o gráfico e o
tornou inviável.

Nesse sentido, para resolver o problema, filtrou-se as unidades
orçamentárias pelas 12 que mais empenharam ao longo do período
2019/2020 analisado. Ademais, utilizou-se a visualização por pontos e o
faceting (facet\_wrap) para separar as unidades e poder comparar a
evolução de suas despesas ao longo do tempo. As unidades foram
ordenadas das que mais empenharam no período para as que menos
empenharam.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-15-1.png)<!-- -->
Nota-se pelo primeiro gráfico de faceting que o Fundo Estadual de Saúde
é o que mais empenhou no período. Contudo, é importante ressaltar que a
grande maioria dos empenhos são menores que R$1.000.000,00 para todas as
unidades, mas esse fundo em especial possui uma maior quantidade de
empenhos acima desse valor, o que corrobora para ser o que mais empenhou
no período.

Dessa forma, para melhor visualizar os gastos, foi-se limitando o valor
máximo do empenho no eixo das ordenadas do gráfico. Dessa forma, fez-se
limitações de até R$1.000.000,00, até R$125.000,00 e até R$40.000,00.
Por meio dessa limitação, foi possível avaliar melhor a quantidade de
empenhos de cada unidade, verificar qual possui uma maior densidade de
empenhos ao longo do período, se esses empenhos se deram bem
distribuídos ao longo do período ou concentrado em uma determinada
faixa.

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-16-1.png)<!-- -->

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-17-1.png)<!-- -->

![](trabalho-final-grupo6_files/figure-gfm/unnamed-chunk-18-1.png)<!-- -->
