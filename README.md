# Algoritmo_Ordenacao_n2

O objetivo deste é a execução de um algoritmo O(n²) e o mapeamento do seu tempo em tabela para que possa ser comprovada sua complexidade.

Para efeito deste optamos por comparar o shellsort utilizando como gap os meios do vetor como, os números de fibonacci e os números de catalan.

A tabela gerada pode ser conferida abaixo.

|N |middle(ns)|fibonacci(ns)|catalan(ns)|
|--|----------|-------------|-----------|
|100|17875|2720|2885|
|200|52024|5733|3214|
|300|78432|6389|3275|
|400|128145|4034|3220|
|500|152884|4456|3733|
|600|192951|7529|4140|
|700|241629|6493|3774|
|800|281436|4899|4027|
|900|348630|5359|4087|
|1000|342632|5411|4068|
|1100|406393|8572|4246|
|1200|413829|7881|4422|
|1300|495707|5730|4376|
|1400|526524|5369|3741|
|1500|546298|5429|4274|
|1600|655502|5786|4523|
|1700|642857|8712|4431|
|1800|726088|5998|3323|
|1900|711511|6176|4477|
|2000|762192|6353|4043|
|2100|836464|12992|3858|
|2200|689693|8469|3594|
|2300|903984|6917|4926|
|2400|976736|47724|6420|
|2500|943116|38109|8960|
|2600|1023071|36383|6603|
|2700|1071305|61512|8671|
|2800|931280|6046|3689|
|2900|934742|4565|3601|
|3000|984306|4385|3639|
|3100|1112830|5220|3624|
|3200|1161331|6036|3723|
|3300|1069890|4195|3555|
|3400|1309974|14823|3959|
|3500|1327205|10717|4285|
|3600|1523505|9878|5180|
|3700|1457707|70711|9066|
|3800|1551078|34639|11372|
|3900|1414754|12197|4739|
|4000|1480396|5754|4268|
|4100|1869444|17941|4034|
|4200|1586073|19620|7719|
|4300|2376812|25221|9307|
|4400|1636244|25057|9502|
|4500|1945761|33053|13535|
|4600|1832582|31902|10828|
|4700|1574011|18996|6714|
|4800|1666125|16960|5764|
|4900|1618775|16347|5705|
|5000|1724084|19550|6574|
|5100|1971757|144578|57562|
|5200|1906559|23715|7632|
|5300|2112540|26159|9124|
|5400|2061633|86820|25261|
|5500|2384762|30662|11186|
|5600|2278607|21428|7636|
|5700|2079491|20468|7337|
|5800|2281219|23246|8322|
|5900|2196287|21949|7425|
|6000|2151505|21312|7462|
|6100|2273844|20975|7391|
|6200|2528807|21796|7797|
|6300|2295833|23022|6601|
|6400|2688613|22878|7668|
|6500|2328888|22260|7541|
|6600|2368590|22264|7583|
|6700|2450577|22521|7534|
|6800|2446631|24421|6912|
|6900|2548491|25129|6610|
|7000|2749262|25984|7108|
|7100|2489491|25451|7034|
|7200|3031574|25520|7188|
|7300|2805779|25973|7223|
|7400|2769845|26592|6983|
|7500|2677295|25148|6712|
|7600|2739723|23309|6122|
|7700|2926318|26365|7138|
|7800|2780908|26969|7234|
|7900|2834335|27049|6758|
|8000|3000898|28165|6754|
|8100|3281747|40629|12256|
|8200|5848667|12256|7358|
|8300|3328464|33261|5426|
|8400|3301762|26154|5271|
|8500|3139351|25799|5312|
|8600|3177501|25995|5308|
|8700|3297348|26010|5426|
|8800|3378832|28084|5444|
|8900|3383326|27104|5517|
|9000|3599914|28007|5601|
|9100|3472423|27933|5461|
|9200|3534253|27811|5396|
|9300|3640210|27176|5355|
|9400|3512484|28530|5529|
|9500|3596457|29596|5544|
|9600|4761885|67647|9932|
|9700|4818152|56080|8893|
|9800|4557819|47921|6692|
|9900|3915916|32677|5960|
|10000|3840804|30107|5688|

Pode-se notar que para a execução, onde o gap eram os meios do vetor o tempo de ficou proximo de n², apenas a multiplicação de uma pequena constante de diferença, contudo em alguns valores específicos o tempo de execução teve uma variação um pouco maior.

Efetuando a ordenação utilizando tanto fibonacci quanto catalan a diferença de performance foi extremamente significativa. No caso dos números de catalan conforme o valor de N fosse crescendo, ele chegou a executar em O(n).

Para melhor visualização dos dados, foi gerado um gráfico, porém os tempos referentes a execução utilizando como gap os meios do vetor foram omitidos pois seu crescimento impede a verificação utilizando fibonacci e catalan.

![Comparativo Catalan e Fibonacci](https://i.imgur.com/2Mkw6k0.png)
