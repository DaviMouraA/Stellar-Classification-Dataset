# PrimeiroProjetoAnaliseDeDados
Bem-vindo ao repositório do projeto PrimeiroProjetoAnaliseDeDados. Este repositório contém a análise de um dataset com informações detalhadas sobre estrelas.

#Descrição do Projeto
Neste projeto, utilizei o Google Colab, Python e as bibliotecas Pandas, Matplotlib e Seaborn para realizar a análise de um dataset de estrelas. A tabela de dados contém as seguintes colunas:

obj_ID = Identificador do Objeto, o valor único que identifica o objeto no catálogo de imagens usado pelo CAS.
alpha = Ângulo de Ascensão Reta (na época J2000).
delta = Ângulo de Declinação (na época J2000).
u = Filtro ultravioleta no sistema fotométrico.
g = Filtro verde no sistema fotométrico.
r = Filtro vermelho no sistema fotométrico.
i = Filtro de infravermelho próximo no sistema fotométrico.
z = Filtro de infravermelho no sistema fotométrico.
run_ID = Número da Execução usado para identificar a varredura específica.
rerun_ID = Número da Reexecução para especificar como a imagem foi processada.
cam_col = Coluna da Câmera para identificar a linha de varredura dentro da execução.
field_ID = Número do Campo para identificar cada campo.
spec_obj_ID = ID Único usado para objetos espectroscópicos ópticos (isso significa que duas observações diferentes com o mesmo spec_obj_ID devem compartilhar a mesma classe de saída).
class = Classe do objeto (galáxia, estrela ou quasar).
redshift = Valor do desvio para o vermelho baseado no aumento do comprimento de onda.
plate = ID da placa, identifica cada placa no SDSS.
MJD = Data Juliana Modificada, usada para indicar quando um determinado conjunto de dados do SDSS foi obtido.
fiber_ID = ID da fibra que identifica a fibra que apontou a luz no plano focal em cada observação.

Ferramentas Utilizadas
Google Colab: Para execução do código e análise interativa.
Python: Linguagem de programação utilizada.
Pandas: Biblioteca utilizada para manipulação e análise de dados.
Matplotlib: Biblioteca utilizada para criação de gráficos.
Seaborn: Biblioteca utilizada para visualização de dados baseada no Matplotlib.

Exemplos de Análise de Dados do Projeto
Abaixo estão alguns exemplos de análises e visualizações de dados que você encontrará no projeto:

Informações gerais sobre o DataFrame.
Seleção de trechos específicos do DataFrame (colunas, linhas, splices).
Filtros para criação de novos DataFrames com critérios específicos.
Agrupamento de dados por valores e cálculo de médias.
Verificação de dados nulos e duplicados.
Visualização de contagens de classes e distribuição de valores com gráficos de dispersão e histogramas.
Medidas descritivas das variáveis.
