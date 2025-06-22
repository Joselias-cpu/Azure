# Objetivo aplicar técnicas de organização e pesquisa de documentos por meio da ingestão de dados e indexação utilizando ferramentas de inteligência artificial.

> Utilizando Azure AI Search index (UI), Pesquisa Cognitiva do Azurre, para minerar e extrair conhecimento de grandes volumes de informação.
>
## Processos: 

> Coleta dos dados de avaliações
Reunir todas as avaliações dos clientes da Fourth Coffee numa pasta de arquivos.

> Preparação e limpeza dos dados
Remover duplicados, corrijir erros de ortografia, filtrar informações irrelevantes e estruturar os dados em campos como: `cliente`, `data`, `nota`, `comentário`, `local da loja`, etc.

> Criação de um recurso de Armazenamento no Azure
Hospedar os dados limpos no armazenamento  Azure Blob Storage

> Criação de um serviço Azure AI Search: No portal do Azure:
- Criar um novo recurso Azure AI Search
- Escolher o escalonamento apropriado com base no volume de dados e complexidade das buscas

> Definir o Indexador
Definir os campos que devem ser pesquisáveis, filtráveis, ordenáveis, etc. 

> Habilitar os recursos de IA. Acoplar um Skillset com habilidades cognitivas como:
- Análise de sentimentos
- Extrair frases-chave
- Tradução automática
- Extrair nomes de locais

> Fazer Testes de busca 
Utilizar o portal do Azure ou sua própria aplicação para testar buscas. 
