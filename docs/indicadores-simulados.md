# Indicadores de desempenho — cenário 100% simulado

> **Atenção:** todos os valores desta página são inventados para demonstração profissional e não têm origem em sistemas produtivos.

| KPI | Definição / fórmula | Baseline hipotético | Meta hipotética | Fonte necessária em um piloto real |
| --- | --- | --- | --- | --- |
| Resolução em autosserviço | Conversas encerradas com sucesso sem atendimento humano / conversas elegíveis × 100 | 20% | 55% | Eventos do chatbot + CRM |
| Tempo até primeira resposta | Média ou percentil do tempo entre mensagem inicial e primeira resposta útil | 8 min | 20 s | Logs com timestamps |
| CSAT | Respostas satisfeitas / total de respostas válidas × 100 | 72% | 85% | Pesquisa ao término |
| Abandono da jornada | Jornadas iniciadas sem conclusão e sem transbordo / jornadas iniciadas × 100 | 28% | 15% | Funil de eventos |
| Volume para equipe humana | Contatos mensais × (1 - taxa de autosserviço) | 8.000 | 4.500 | CRM + chatbot |

## Simulação econômica

- Volume considerado: 10.000 contatos/mês.
- Baseline: 20% resolvidos automaticamente → 8.000 enviados a humano.
- Meta: 55% resolvidos automaticamente → 4.500 enviados a humano.
- Diferença: **3.500 atendimentos por mês**.
- Custo unitário **hipotético**: R$ 8,00 por atendimento.
- Benefício bruto ilustrativo: **R$ 28.000/mês**.
- Projeção anual aritmética (sem sazonalidade): **R$ 336.000**, **não** uma economia efetivamente realizada.

## Limitações e governança

A taxa de autosserviço só deve contar demandas efetivamente resolvidas; não basta o usuário não ter pedido atendente. CSAT pode ter viés de não resposta. A comparação antes/depois exige considerar mudanças de mix, volume e período. Não divulgar ROI sem custo total da solução e validação do financeiro.

## Critérios de sucesso do piloto (propostos)

- Taxa de resolução automática ≥ 55% entre jornadas elegíveis.
- CSAT ≥ 85% nas respostas válidas.
- Abandono ≤ 15%.
- Nenhum vazamento conhecido de dados protegidos e auditoria de acessos implementada.
- Quedas de serviços gerenciadas com transbordo e aviso compreensível.
