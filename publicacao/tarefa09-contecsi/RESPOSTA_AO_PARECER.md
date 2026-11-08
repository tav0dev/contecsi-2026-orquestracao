# Resposta aos comentários do orientador — revisão de 08/11/2026

Documento de origem: PDF comentado de 25 páginas recebido do orientador. PSE é a modalidade principal; o REX permanece como alternativa, sem presumir duas submissões.

| Comentário | Alteração realizada | Local no PSE revisado |
| --- | --- | --- |
| C1: demonstrar originalidade com comparação sistemática | Comparação documental por critérios comuns e discussão com FlowMind, AppWorld e τ-bench; contribuição aplicada sustentada por comparação pareada de contexto | Seções 2.2 e 5.4; Quadro 1; Tabela 2 |
| C2: ampliar solicitações e discutir generalização | Corpus de 60 cenários em 3 domínios, 360 chamadas; análise por classe e estabilidade por cenário; alcance sintético explicitado | Seções 3.3, 5.2 e 5.4 |
| C3: ampliar catálogo de 1 cliente e 1 serviço | 24 clientes e 6 serviços por catálogo, nomes semelhantes e durações de 30 a 240 minutos | Seção 3.3 e suplemento |
| C4: identificar provedor, modelo, versão e parâmetros | OpenAI Responses API; gpt-6-luna solicitado e registrado; esquema estrito, limite de saída, reasoning, store, parâmetros não enviados e timeout; ausência de snapshot datado fixado | Seção 3.3; fontes e registros do suplemento |
| C5: separar implementação e integrações futuras | Seleção incorporada ao servidor; Figura 2 e Quadro 3 distinguem núcleo implementado de conectores externos e jornada futura | Seções 4.1 e 4.2; Figura 2; Quadro 3 |
| C6: reduzir extensão e conferir limite | 21 referências e 3 figuras no PSE; tabelas concentram resultados; prévias com 16 páginas no PSE e 8 no REX | Manuscritos revisados |

## Resultados desta rodada

As 360 chamadas pelo HTTP do servidor integrado foram concluídas sem repetição automática: 176/180 respostas conformes com catálogo completo e 178/180 com seleção. Foram 159.588 e 86.187 tokens de entrada, redução de 46,0%. As medianas HTTP foram 1.508,0 e 1.494,5 ms. Todos os registros, inclusive os 6 desvios de esclarecimento em vez de recusa, estão no suplemento. Nenhum desvio continha proposta executável.

Passaram 59 testes Python, 20 contratos Dart do núcleo, 14 do fluxo, 20 testes Flutter e 3 disputas SQL. A verificação remota passou em 16 checagens com 2 identidades sintéticas e 1 inferência real, sem confirmar operações ou alterar registros do negócio. Ela não integra a taxa de concordância das 360 chamadas. A discussão do REX relaciona diretamente resultados, FlowMind, AppWorld e Goal Question Metric.

## Rastreabilidade e escopo

- PSE, REX e suplemento utilizam somente a rodada integrada de 08/11/2026. Os resultados anteriores permanecem arquivados, sem entrar nas contagens atuais.
- O seletor integra o fluxo principal. A comparação tem inferência real e transportes controlados de catálogo e revisão, sem gravações de negócio.
- O servidor atual e as fontes da rodada têm hashes próprios. As 37 fontes históricas de 06/11 foram preservadas em uma cópia identificada, sem atribuir suas métricas à versão modificada.
- O suplemento reúne cenários, oráculo, respostas, análise, fontes e registros sem credenciais. Os comandos permitem reproduzir a análise e os testes Python sem chamadas pagas; SQL e Flutter têm dependências documentadas.
- Os PDFs são prévias de leitura geradas em Chromium. A conferência visual da versão atual no Microsoft Word permanece indicada, pois a paginação pode variar.
- A contribuição é técnica e empírica no recorte sintético; os benefícios de tempo, resultados financeiros e tranquilidade deverão ser avaliados com o público.

Diretrizes utilizadas: https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/about/submissions e modalidades: https://contecsi.tecsi.org/index.php/contecsi/21CONTECSI/schedConf/trackPolicies . Nenhuma submissão foi realizada.

## Revisão de clareza

Resumos e texto integral foram revistos para explicar primeiro o problema e o funcionamento da plataforma, definir os termos técnicos no método e distinguir a oferta do negócio da proposta de ação da IA. O diagrama recebeu rótulos mais diretos. Os resultados, os critérios de avaliação e as referências foram preservados. As 6 diferenças de classificação permanecem apresentadas e explicadas.
