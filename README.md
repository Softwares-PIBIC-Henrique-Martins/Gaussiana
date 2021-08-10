# Gaussiana
O programa Gaussiana plota um histograma com base em dados de uma tabela do Excel e realiza um ajuste segundo a equação de uma gaussiana, fornecendo os parâmetros de ajuste. 

Vale salientar que o ajuste não foi feito diretamente ao histograma. O ajuste foi feito aos pontos que se encontram no topo de cada barra do histograma. Para a obtenção desses pontos, foi usada a própria função plt.hist(), já que essa função retorna o array dos bins usados para plotar o histograma e o array da distribuição das fequências dos dados.
