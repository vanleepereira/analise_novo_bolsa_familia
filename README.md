🇧🇷 Análise de Impacto: Programa Bolsa Família
Este projeto apresenta um diagnóstico espacial e financeiro do Programa Bolsa Família em 2026. O objetivo é mapear a distribuição dos benefícios e entender a capilaridade da principal política de transferência de renda do Brasil.

🛠️ Workflow de Dados
Ingestão & Extração (PostgreSQL): Processamento de dados brutos de pagamentos mensais para consolidar valores totais e ocorrências por estado e região.

Limpeza & Tratamento: Padronização de nomes de UFs e regiões para garantir compatibilidade com bases geográficas.

Análise Geoespacial (Python & GeoPandas): Cruzamento de dados tabulares com Shapefiles do IBGE para visualização de disparidades regionais.

📊 Principais Indicadores Analisados
Distribuição por Região: Comparativo do alcance do programa entre as grandes regiões brasileiras.

Densidade de Ocorrências por UF: Mapeamento do número de famílias beneficiadas por estado.

Investimento Total: Cálculo do montante injetado na economia através dos benefícios.

📁 Estrutura de Arquivos
dados_bolsa_por_regiao.csv: Agregado de beneficiários por macrorregião.

ocorrencias_por_uf.csv: Detalhamento do número de benefícios por Unidade da Federação.

valor_total_beneficios.csv: Consolidado financeiro dos repasses.

analise_spatial.ipynb: Notebook com a lógica de GeoPandas e geração de mapas coropléticos.

🌍 Por que isso importa para Relações Internacionais?
A análise de programas como o Bolsa Família é essencial para entender o Desenvolvimento Econômico e a Segurança Alimentar, pilares da agenda internacional do Brasil (como no G20 e nos BRICS). Este projeto demonstra a capacidade de traduzir políticas públicas em dados visuais para tomada de decisão estratégica.
