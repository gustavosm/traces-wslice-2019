# traces-wslice-2019
Dados utilizados no experimento realizado para o artigo submetido para o Workshop de Teoria, Tecnologias e Aplicações de Slicing para Infraestruturas Softwarizadas (WSlice) - 2019

Os dados disponíveis neste repositório estão sob a licença CC-BY-4.0. Os termos podem ser vistos no arquivo LICENSE.txt no diretório raiz ou no site: https://creativecommons.org/licenses/by/4.0/

Se deseja usar os dados de alguma forma, por favor faça a referência como:
Gustavo Marques e Aryadne Guardieiro e Ian Resende e Raquel Lafetá e Rafael Pasquini. "Arcabouço de um Sistema Inteligente de Monitoramento para Cloud Slices" em: Workshop de Teoria, Tecnologias e Aplicações de Slicing para Infraestruturas Softwarizadas (WSlice), 01 de abril de 2019.

Os autores podem ser contactados em: guto_silveira_@ufu.br; aryadne.guardieiro@ufu.br; ianresende@ufu.br; raquel.lafeta@ufu.br; rafael.pasquini@ufu.br

# Descrição dos dados
Os dados coletados da infraestrutura (X_Completo) e os dados do cliente (Y) estão representados nos arquivos X_file.csv e Y_file.csv, respectivamente.
O arquivo X_file.csv contém uma coluna denominada timestamp, cujo valor é o timestamp da coleta dos dados informados na linha, e outras 374 colunas, uma para cada métrica coletada da infraestrutura, cujos valores são os coletados pelo Prometheus.
O arquivo Y_file.csv contém uma coluna denominada timestamp, cujo valor é o timestamp da coleta dos dados informados na linha, e outras 22 colunas (W_totalops; W_op/s; W_pk/s; W_row/s; W_mean; W_med; W_95; W_99; W_999; W_max; W_stderr; R_totalops; R_op/s; R_pk/s; R_row/s; R_mean; R_med; R_95; R_99; R_999; R_max; R_stderr), das quais as iniciadas com "W_" indicam as medidas da operação de escrita e as iniciadas com "R_" indicam as medidas da operação de leitura.
