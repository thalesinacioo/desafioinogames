# Desafio Técnico - QA Lead | INO Games

**Candidato:** Thales Fernandes  
**Cargo:** QA Lead  
**Empresa:** INO Games  

---

## Sobre o Desafio

Cenário baseado na **Nebula Forge Studios**, um estúdio de games em crescimento com entregas semanais internas e releases trimestrais. O desafio propõe um contexto real de qualidade em deterioração:

- 28 bugs críticos encontrados após freeze nos últimos 2 meses
- 9 bugs críticos escaparam para produção no último release
- 40% dos bugs detectados tardiamente
- Time com 2 QAs juniores, sem regressão estruturada

O meu objetivo é propor um plano de melhoria de qualidade sem comprometer a velocidade de entrega.

---

## Artefatos

### 📊 Apresentação (PowerPoint)
`Desafio_QA_Lead_Thales_Fernandes.pptx`

Apresentação executiva com 10 slides cobrindo todas as questões do desafio:

| Slide | Conteúdo |
|-------|----------|
| 1 | Capa |
| 2 | Contexto do cenário e dados |
| 3 | Diagnóstico e 3 prioridades das próximas 2 semanas |
| 4 | Estrutura de Smoke Test, Regressão e Exploratório + Shift-Left |
| 5 | Alocação do QA no ciclo de produção + Delegação |
| 6 | QA Guild (capacitação 8 semanas) + Feature Flags |
| 7 | Decisão de release — bug crítico no freeze |
| 8 | Gráfico de Gantt — 10 sprints × 15 dias |
| 9 | Dia 1 e diferencial competitivo |
| 10 | Encerramento |

---

### 📄 Documento Completo (Word)
`Desafio_QA_Lead_INO_Games.docx`

Documento detalhado com todas as 7 respostas do desafio, textos explicativos, tabelas e um gráfico de Gantt incorporado.

---

## Respostas em Resumo

**1. Diagnóstico e prioridades**  
Três problemas centrais: ausência de regressão estruturada, detecção tardia (shift-right) e tempo de correção alto. Ações prioritárias: Smoke Test mínimo, mapeamento de fluxos críticos e Definition of Ready (DoR).

**2. Estrutura de testes**  
Smoke Test a cada build semanal → Regressão baseada em fluxos críticos → Exploratório com time-box para features novas. Automação, performance e localização fora do escopo imediato.

**3. Antecipar bugs**  
QA entra no refinamento antes do desenvolvimento. Critérios de aceite escritos antes do dev começar. Bug triage semanal para evitar acúmulo até o freeze.

**4. Alocação no ciclo**  
QA presente em todas as fases: do planejamento ao pós-release, com intensidade variando de pontual (desenvolvimento) a crítica (freeze/release).

**5. Delegação**  
Juniores executam smoke tests, regressões e documentação de bugs. QA Lead define processos, conduz exploratórios em áreas críticas, faz mentoria e gerencia a comunicação de risco.

**6. Capacitação — QA Guild**  
Programa de 8 semanas com sessões quinzenais: técnicas de teste, escrita de bug reports, pair testing e apresentação final dos juniores. Objetivo: criar cultura de ownership, não só habilidade técnica.

**7. Decisão de release**  
Bug crítico afetando 20% dos jogadores → recomendação de adiamento de 48h. Se negócio decidir lançar: risco documentado formalmente, plano de hotfix pronto e monitoramento imediato pós-release.

**Diferencial proposto — Feature Flags**  
Implementação de feature flags para rollout gradual (10% → 50% → 100%) e reversão instantânea em caso de bug crítico pós-release, sem necessidade de novo build.