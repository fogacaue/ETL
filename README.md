<h1> Seu Uso</h1>
 O código utiliza a biblioteca pandas para manipular e analisar dados em formato tabular. Primeiro, ele carrega os dados de vendas de duas filiais diferentes: "filial 1" de um arquivo CSV e "filial 2" de um arquivo Excel, armazenando esses dados nos DataFrames vendas_filial1 e vendas_filial2, respectivamente.
Em seguida, realiza cálculos para determinar o valor total de vendas para cada transação em ambas as filiais. Para isso, multiplica a quantidade vendida pelo preço unitário, adicionando essa informação como uma nova coluna chamada "Valor total" nos respectivos DataFrames.



<h2>Resultado1></h2>

Dados da filial 1:
   ID do Produto                   Nome do Produto  Quantidade Vendida  \
0            101                Laptop Dell XPS 13                  20   
1            102     Smartphone Samsung Galaxy S20                  30   
2            103          Monitor LG UltraWide 34"                  15   
3            104  Teclado Mecânico Corsair K95 RGB                  25   
4            105        Mouse Logitech MX Master 3                  10   

   Preco Unitario  Valor total  
0          1500.0      30000.0  
1          1000.0      30000.0  
2           600.0       9000.0  
3           200.0       5000.0  
4            80.0        800.0  

Dados da Filial 2:
   ID do Produto                    Nome do Produto  Quantidade Vendida  \
0            201         Impressora HP LaserJet Pro                  12   
1            202                    SSD Samsung 1TB                  18   
2            203              Tablet Apple iPad Pro                   8   
3            204  Smartwatch Samsung Galaxy Watch 4                  14   
4            205            Headset HyperX Cloud II                  20   

   Preço Unitário  Valor total  
0           250.0       3000.0  
1           180.0       3240.0  
2           900.0       7200.0  
3           300.0       4200.0  
4           120.0       2400.0  
Dados transformados da Filial 1:
   ID do Produto                   Nome do Produto  Quantidade Vendida  \
0            101                Laptop Dell XPS 13                  20   
1            102     Smartphone Samsung Galaxy S20                  30   
2            103          Monitor LG UltraWide 34"                  15   
3            104  Teclado Mecânico Corsair K95 RGB                  25   
4            105        Mouse Logitech MX Master 3                  10   

   Preco Unitario  Valor total  
0          1500.0      30000.0  
1          1000.0      30000.0  
2           600.0       9000.0  
3           200.0       5000.0  
4            80.0        800.0  

Dados Transformados ds Filial 2:
   ID do Produto                    Nome do Produto  Quantidade Vendida  \
0            201         Impressora HP LaserJet Pro                  12   
1            202                    SSD Samsung 1TB                  18   
2            203              Tablet Apple iPad Pro                   8   
3            204  Smartwatch Samsung Galaxy Watch 4                  14   
4            205            Headset HyperX Cloud II                  20   

   Preço Unitário  Valor total  
0           250.0       3000.0  
1           180.0       3240.0  
2           900.0       7200.0  
3           300.0       4200.0  
4           120.0       2400.0  
Dados transformados da Filial 1: (do arquivo CSV)
   ID do Produto                   Nome do Produto  Quantidade Vendida  \
0            101                Laptop Dell XPS 13                  20   
1            102     Smartphone Samsung Galaxy S20                  30   
2            103          Monitor LG UltraWide 34"                  15   
3            104  Teclado Mecânico Corsair K95 RGB                  25   
4            105        Mouse Logitech MX Master 3                  10   

   Preco Unitario  Valor total  
0          1500.0      30000.0  
1          1000.0      30000.0  
2           600.0       9000.0  
3           200.0       5000.0  
4            80.0        800.0  

Dados Transformados ds Filial 2: (do arquivo CSV)
   ID do Produto                    Nome do Produto  Quantidade Vendida  \
0            201         Impressora HP LaserJet Pro                  12   
1            202                    SSD Samsung 1TB                  18   
2            203              Tablet Apple iPad Pro                   8   
3            204  Smartwatch Samsung Galaxy Watch 4                  14   
4            205            Headset HyperX Cloud II                  20   

   Preço Unitário  Valor total  
0           250.0       3000.0  
1           180.0       3240.0  
2           900.0       7200.0  
3           300.0       4200.0  
4           120.0       2400.0  





<h2>Resultado2></h2>


Dados Transformados da Filial 1 (do banco de dados SQL):
   ID do Produto                   Nome do Produto  Quantidade Vendida  \
0            101                Laptop Dell XPS 13                  20   
1            102     Smartphone Samsung Galaxy S20                  30   
2            103          Monitor LG UltraWide 34"                  15   
3            104  Teclado Mecânico Corsair K95 RGB                  25   
4            105        Mouse Logitech MX Master 3                  10   

   Preco Unitario  Valor total  
0          1500.0      30000.0  
1          1000.0      30000.0  
2           600.0       9000.0  
3           200.0       5000.0  
4            80.0        800.0  

Dados Transformados da Filial 2 (do banco de dados SQL):
   ID do Produto                    Nome do Produto  Quantidade Vendida  \
0            201         Impressora HP LaserJet Pro                  12   
1            202                    SSD Samsung 1TB                  18   
2            203              Tablet Apple iPad Pro                   8   
3            204  Smartwatch Samsung Galaxy Watch 4                  14   
4            205            Headset HyperX Cloud II                  20   

   Preço Unitário  Valor total  
0           250.0       3000.0  
1           180.0       3240.0  
2           900.0       7200.0  
3           300.0       4200.0  
4           120.0       2400.0 



<h2>Resultado3></h2>

Dados Transformados da Filial 1:
(101, 'Laptop Dell XPS 13', 20, 1500.0, 30000.0)
(102, 'Smartphone Samsung Galaxy S20', 30, 1000.0, 30000.0)
(103, 'Monitor LG UltraWide 34"', 15, 600.0, 9000.0)
(104, 'Teclado Mecânico Corsair K95 RGB', 25, 200.0, 5000.0)
(105, 'Mouse Logitech MX Master 3', 10, 80.0, 800.0)
Dados Transformados da Filial 2:
(201, 'Impressora HP LaserJet Pro', 12, 250.0, 3000.0)
(202, 'SSD Samsung 1TB', 18, 180.0, 3240.0)
(203, 'Tablet Apple iPad Pro', 8, 900.0, 7200.0)
(204, 'Smartwatch Samsung Galaxy Watch 4', 14, 300.0, 4200.0)
(205, 'Headset HyperX Cloud II', 20, 120.0, 2400.0)
