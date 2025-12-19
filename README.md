# Z_REPORT_GET_SMALL_MENOR
relatório de vendas para pegar maior  menor
Especificação do desafio

Problema : Relatório de Ordens de venda 

 

Tela de seleção  

VBAK-VBELN 

VBAK-ERDAT 

VBAK-VBTYP 

VBAK-AUART 

VBAP- MATNR 

 

Detalhes da seleção 

Selecionar os dados da tabela VBAK com o filtro da tela de seleção. Com os dados da VBAK, selecionar os dados da tabela VBAP onde VBAK-VBELN = VBAP-VBELN + filtros da tela de seleção 

Com os dados da seleção acima, selecionar a VBEP onde VBEP-VBELN = VBAP-VBELN e VBEP-POSNR = VBAP-POSNR 

Com os dados selecionados, selecionar a MAKT onde MAKT-MATNR = VBAP-MATNR e MAKT-SPRAS = idioma de login  

 

Detalhes da lógica 

Não é permitido o uso do comando SORT! 

Primeiro Item: Dentro do mesmo VBAP-VBELN, marcar com o valor “X” qual for o menor valor de VBAP-POSNR. Se o VBAP-POSNR se repetir, marcar somente a primeira linha 

Último Item: Dentro do mesmo VBAP-VBELN, marcar com o valor “X” qual for o maior valor de VBAP-POSNR. Se o VBAP-POSNR se repetir, marcar somente a última linha 

Menor Qtd: Dentro do mesmo VBAP-POSNR, marcar com o valor “X” qual for o menor valor de VBEP-WMENG 

Maior Qtd: Dentro do mesmo VBAP-POSNR, marcar com o valor “X” qual for o maior valor de VBEP-WMENG 

Exemplo 

A screenshot of a computer

Description automatically generated
 

 

Detalhes da saída 

Exibir um relatório ALV com os seguintes campos 

VBAK-VBELN 

VBAP-POSNR 

VBEP-ETENR 

VBAK-ERDAT 

VBAP-MATNR 

VBAP-MATWA 

VBAP-PMATN 

VBAP-CHARG 

VBAP-MATKL 

VBEP-WMENG 

VBEP-BMENG 

VBEP-VRKME 

VBEP-LMENG 

VBEP-MEINS 

Primeiro Item 

Último Item 

Menor Qtd 

Maior Qtd 
