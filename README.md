Anonimização de Dados
Este projeto tem como objetivo a anonimização de dados sensíveis em planilhas do Excel, utilizando Python e as bibliotecas Pandas e Faker. O projeto permite a modificação de dados pessoais, como nomes, e-mails e valores financeiros, preservando a integridade dos dados para análise sem comprometer a privacidade dos indivíduos.

Dependências
Certifique-se de ter as seguintes bibliotecas instaladas. Você pode instalar as dependências usando pip:
pip install pandas faker openpyxl

Como Usar
1. Executar os Scripts: Cada script está projetado para anonimizar uma planilha específica. Execute o script correspondente ao arquivo que você deseja modificar.
2.Verificar os Resultados: Os arquivos de saída serão salvos na mesma pasta, com o sufixo -Arquivo_de_saida e um arquivo de controle no formato CSV e XLSX, contendo o mapeamento entre os dados originais e os anonimizados.

Funcionalidades
Anonimização de Nomes e E-mails: Substitui os nomes e e-mails originais por dados gerados aleatoriamente usando a biblioteca Faker.
Modificação de Valores Financeiros: Ajusta valores financeiros para manter a ordem de grandeza, aplicando variações aleatórias de até 10%.
Geração de Códigos Aleatórios: Para colunas que requerem identificadores únicos.
Controle de Dados: Cria arquivos de controle que registram os dados originais e suas versões anonimizadas para rastreamento.
