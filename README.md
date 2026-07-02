# Datasets-Sinteticos
Datasets com redações geradas por LLMs (Gemini 2.5 Flash e Gemini 2.5 Flash Lite).
Nos datasets existem redações de diferentes qualidades, ou seja, redações excelentes, redações boas, redações medianas e ruins. Isso ocorre pois foram criados 4 prompts diferentes que exigiam essas qualidades distintas. Além disso, isso se deve para garantir a diversidade dos dados afim de se tornarem escaláveis.
Em cada arquivo JSON presente nos datasets, encontram-se o tema, o comando temático, os textos motivadores e a redação original, que foram usados como parâmetro para gerar as redações sintéticas e o mapeamento das frases.
O mapeamento de frases relaciona o comando temático e os textos motivadores á redação gerada.
As redações originais foram retiradas do dataset da Professora Evelin Amorim.
Ademais, as redações sintéticas passaram por um processo de revisão e validação realizado por Joaquim Estefan Vivas, estudante do Instituto Federal do Espírito Santo.
Cada dataset concentra cerca de 1800 redações sintéticas.
Nas pastas desse repositório encontram-se também as métricas calculadas de diversidade (baseado no TTR), complexidade e subjetividade.
