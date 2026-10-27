# Eleições 2026

Resultado oficial das eleições gerais de 2026 para presidente e governador, nos dois turnos, por estado e por
município, e o que mudou entre o 1º e o 2º turno (comparecimento e votos ganhos por cada finalista).

Página: https://fabrizioloes.github.io/urnas-2026/

Fonte: TSE, arquivos de divulgação de resultados (resultados.tse.jus.br), eleições 6257 e 6258 (presidente) e 6259 e
6260 (governador), baixados em 26/10/2026 com todas as seções totalizadas. A soma dos municípios confere com o total
oficial de cada estado e do país. Malha municipal do IBGE (2022).

- `index.html`: a página (d3 e topojson pelo cdnjs)
- `dados/eleicao.json`: votos por município, montados a partir dos arquivos do TSE
- `dados/malha.json`: contornos dos municípios e estados em TopoJSON
