# Resposta aos comentários do orientador — revisão de 08/11/2026

Documento de origem: PDF comentado de 25 páginas recebido do orientador. PSE é a modalidade principal; o REX permanece como alternativa, sem presumir duas submissões.

| Comentário | Alteração realizada | Local no PSE revisado |
| --- | --- | --- |
| C1: demonstrar originalidade com comparação sistemática | Comparação documental por critérios comuns; discussão com FlowMind, AppWorld e τ-bench; inclusão de experimento pareado de contexto e explicitação da contribuição aplicada | Seções 2.2 e 5.4; Quadro 1; Tabela 2 |
| C2: ampliar solicitações e discutir generalização | Corpus complementar de 60 cenários em 3 domínios, 360 chamadas; análise por classe e estabilidade por cenário; limites de amostragem sintética explicitados | Seções 3.3, 5.2 e 5.4 |
| C3: ampliar catálogo de 1 cliente e 1 serviço | 24 clientes e 6 serviços por catálogo, nomes semelhantes, durações de 30 a 240 minutos; 3 domínios | Seção 3.3 e suplemento |
| C4: identificar provedor, modelo, versão e parâmetros | OpenAI Responses API; gpt-6-luna solicitado e registrado; ausência de snapshot datado fixado; esquema estrito, limite de saída, reasoning, store, parâmetros não enviados e timeout | Seção 3.3; código e registros do suplemento |
| C5: separar implementação e integrações futuras | Figura 2 explicita integrações externas fora dos ensaios; Quadro 3 distingue núcleo, experimento separado e evolução; mantida a visão de ponta a ponta e futura descoberta por consumidores | Seções 4.1 e 4.2; Figura 2; Quadro 3 |
| C6: reduzir extensão e conferir limite | Redução de 41 para 23 referências e de 5 para 3 figuras; corte de repetições da jornada e dos resultados; prévia PSE com 17 páginas e REX com 8 | Manuscritos revisados |

## O que os novos resultados demonstram

O catálogo completo teve 174/180 respostas conformes; o contexto selecionado, 179/180. Foram 159.588 e 86.187 tokens de entrada, respectivamente, redução de 46,0%. As medianas da chamada ao modelo foram de 1.496,4 e 1.507,6 ms. Não houve redução da latência observada. Os resultados completos, inclusive as 7 divergências de classe, estão no suplemento.

Os corpora são sintéticos e elaborados pelos pesquisadores. A ampliação aumenta a variedade do ensaio, sem provar generalização para a população ou benefício econômico ao usuário. A contribuição apresentada é técnica e empírica, sem reivindicação de algoritmo inédito ou exclusividade de funcionalidades.

## Conferências e escopo

- As 360 chamadas foram concluídas sem repetição automática, com os resultados esperados congelados antes da coleta.
- Nenhuma gravação de negócio ou integração externa foi executada na comparação.
- As 37 fontes congeladas da avaliação do aplicativo de 06/11 continuam com os mesmos hashes. Não houve nova alteração de interface ou transferência de métricas para um aplicativo modificado.
- As evidências integradas de 06/11 e a comparação de inferência de 08/11 têm escopos diferentes e não foram somadas em uma taxa geral.
- Os PDFs são prévias de leitura geradas em Chromium. A conferência no Word informada pelo autor se refere à versão anterior; a nova disposição pode variar no Word.
- A avaliação do orientador sobre suficiência da contribuição continua sendo acadêmica; esta resposta registra alterações e evidências, não aceite do evento.

Diretrizes consultadas: https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/about/submissions e modalidades: https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/schedConf/trackPolicies .
