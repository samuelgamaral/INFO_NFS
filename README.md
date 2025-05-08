# INFO_NFS

Esse script feito em python tem como finalidade extrair algumas informações como 'arquivo', 'numero_nf', 'prestador_cnpj', 'tomador_cnpj', 'valor_servico', 'valor_iss' e 'data_emissao'.

São feitas as seguintes verificações para detectar alguma inconsistência:
1. Verifica se o valor da Nota Fiscal é menor ou igual a zero.
2. Verifica se a Nota Fiscal tem data de emissão posterior a atual.
3. Verifica se está faltando o CNPJ do tomador.
   
A variável 'pasta_xml' armazena o caminho que contém os arquivos XML das Notas Fiscais.

Ao executar, o script gera um arquivo EXCEL onde cada linha contém as informações para cada Nota Fiscal e os resultados das inconsistências.
