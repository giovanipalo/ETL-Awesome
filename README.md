# Projeto ETL (Extract, Transform, Load)

Este repositório faz parte do curso "Python Project for Data Engineering" da Certificação Profissional IBM Data Engineering. O projeto envolve operações de Extração, Transformação e Carga (ETL) de dados de diferentes fontes e formatos.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:

- `.gitattributes`: Arquivo de configuração do Git.
- `etl_code.py`: Código Python que implementa as operações de ETL.
- `log_file.txt`: Arquivo de registro para rastreamento de atividades.
- `README.md`: Este arquivo de documentação.
- `source.zip`: Arquivo compactado contendo dados de origem.
- `source1.csv`, `source2.csv`, `source3.csv`: Dados de origem em formato CSV.
- `source1.json`, `source2.json`, `source3.json`: Dados de origem em formato JSON.
- `source1.xml`, `source2.xml`, `source3.xml`: Dados de origem em formato XML.
- `transformed_data.csv`: Dados transformados e preparados para carregamento.

## Objetivos

O objetivo deste projeto é demonstrar as seguintes etapas do processo ETL:

1. **Extração**: Os dados de origem estão disponíveis em diferentes formatos, como CSV, JSON e XML, e estão contidos nos arquivos listados acima.

2. **Transformação**: O código Python em `etl_code.py` aplica transformações nos dados de origem para formatá-los de acordo com as necessidades do projeto.

3. **Carga**: Os dados transformados são salvos no arquivo `transformed_data.csv`, pronto para serem carregados em um banco de dados ou utilizado para análises posteriores.

## Instruções

Para executar o projeto e entender as etapas de ETL, siga estas instruções:

1. Consulte o código Python em `etl_code.py` para entender as transformações aplicadas nos dados de origem.

2. Utilize os dados de origem nos arquivos `source1.csv`, `source2.csv`, `source3.csv`, `source1.json`, `source2.json`, `source3.json`, `source1.xml`, `source2.xml`, `source3.xml` como entrada para o código ETL.

3. Após a execução, o resultado das transformações será encontrado no arquivo `transformed_data.csv`.
