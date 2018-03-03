# Urls Disponíveis

## Wikiolapbase

| Url | Método | Ação | Sucesso | Erro |
|-----|--------|------|---------|------|
| /base/api/getmetadata/(datasetID)/ | GET | Requisita os metadados da tabela de id `datasetID` | Retorna um JSON contendo os metadados da tabela | Retorna um erro de status 500 do servidor |
| /base/api/getrandommetadata/(limit)/ | GET | Requisita os metadados de `limit` tabelas aleatórioas | Retorna um JSON contendo um array de metadados de tabelas | Retorna um erro de status 500 do servidor |
| /base/api/searchmetadata/(keywords) | GET | Requisita os metadados de tabelas que possuam `keywords` no título ou descrição | Retorna um JSON contendo um array de metadados | Retorna um erro de status 500 do servidor |
| /base/api/getdata/(tableId)/ | GET | Requisita os dados da tabela com id igual a `table_id` | Retorna um JSON contendo os dados requisitados | Retorna um erro de status 500 do servidor |
| /base/api/getdata/(tableId)/orderBy=(orderBy)/ | GET | Requisita os dados da table com id igual a `table_id` ordenados pelo campo `orderBy` | Retorna um JSON contendo os dados da tabela | Retorna um erro de status 500 do servidor |
| /base/api/getdata/(tableId)/(limit)/ | GET | Requisita os dados da tabela de id `table_id` limitando o número de linhas a `limit` | Retorna um JSON contendo os dados da tabela limitados | Retorna um erro de status 500 de servidor |
| /base/api/getdata/(tableId)/(selectColumns)/ | GET | Requisita o conteúdo das colunas `selectColumns` da tabela de id `tableId` | Retorna um JSON contendo os dados das colunas | Retorna um erro de status 500 do servidor |
| /base/api/getdata/(tableId)/(selectColumns)/(limit)/ | GET | Requisita o conteúdo das colunas `selectColumns` da tabela de id `tableId` limitadas a `limit` linhas | Retorna um JSON contendo o conteúdo das colunas limitado | Retorna um erro de status 500 do servidor |
| /base/api/getdata/(tableId)/(groupBy) /(aggFunc)/(aggColumns)/ | GET | Requisita os dados da tabela de id `tableId` agrupados pela coluna `groupBy` e agregados pela função `aggFunc` nas colunas `aggColumns`| Retorna um JSON contendo os dados requisitados | Retorna um erro de stats 500 do servidor |
| /base/api/getdata/(tableId)/(groupBy)/(aggFunc) /(aggColumns)/orderBy=(orderBy)/ | GET | Requisita os dados da tabela de id `tableId` agrupados pela coluna `groupBy` e agregados pela função `aggFunc` nas colunas `aggColumns` ordenadors pela coluna `orderBy`| Retorna um JSON contendo os dados requisitados | Retorna um erro de stats 500 do servidor |
| /base/api/getdata/(tableId)/(groupBy)/(aggFunc) /(aggColumns)/(limit) | GET | Requisita os dados da tabela de id `tableId` agrupados pela coluna `groupBy` e agregados pela função `aggFunc` nas colunas `aggColumns` limitados às `limit` primeiras colunas | Retorna um JSON contendo os dados requisitados | Retorna um erro de stats 500 do servidor |
| /base/api/getdata/(tableId)/(groupBy)/(aggFunc) /(aggColumns)/groupBy=(groupBy)/(limit)/ | GET | Requisita os dados da tabela de id `tableId` agrupados pela coluna `groupBy` e agregados pela função `aggFunc` nas colunas `aggColumns` ordenados ela coluna `orderBy` e limitados às `limit` primeiras linhas| Retorna um JSON contendo os dados requisitados | Retorna um erro de stats 500 do servidor |
| /base/api/joindata/(tableIdRoot)/(tableIdJoin) /(columnsRoot)/(columnsJoin)/ | GET | Requisita o  join entre as tabelas de id `tableIdRoot` e `tableIdJoin`, incluindo as colunas `columnsRoot` e `columnsJoin` | Retorna um JSON contendo o join requisitado | Retorna um erro de status 500 do servidor |
| /base/api/joindata/(tableIdRoot)/(tableIdJoin) /(columnsRoot)/(columnsJoin)/(limit)/ | GET | Requisita o  join entre as tabelas de id `tableIdRoot` e `tableIdJoin`, incluindo as colunas `columnsRoot` e `columnsJoin` limitando às `limit` primeiras linhas| Retorna um JSON contendo o join requisitado | Retorna um erro de status 500 do servidor |
| /base/api/joindata/(tableIdRoot)/(tableIdJoin) /(columnsRoot)/(columnsJoin)/(groupBy)/(aggFunc) /(aggColumns) | GET | Requisita o  join entre as tabelas de id `tableIdRoot` e `tableIdJoin`, incluindo as colunas `columnsRoot` e `columnsJoin`, agrupando pela coluna `groupBy` aplicando a função de agregação `aggFunc` nas colunas `aggColumns` | Retorna um JSON contendo o join requisitado | Retorna um erro de status 500 do servidor |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
