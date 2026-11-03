Legacy Modernization Framework
Framework para analisar modernização de sistemas legados sob a ótica de Produto e Business Analysis.
1. Entendimento do legado
Mapear:
módulos;
usuários;
processos;
integrações;
regras;
dados;
dependências;
limitações;
incidentes;
custos operacionais.
2. Inventário de funcionalidades
ID	Funcionalidade	Sistema atual	Usuário	Criticidade
3. Mapeamento AS-IS
Documentar:
fluxo atual;
regras existentes;
exceções;
sistemas;
entradas;
saídas;
responsáveis.
4. Gap Analysis
Tema	AS-IS	Problema	TO-BE
5. Regras de negócio
Documentar regras explícitas e regras que hoje existem apenas no código ou no conhecimento operacional.
6. Requisitos
Separar em:
funcionais;
não funcionais;
integração;
segurança;
auditoria;
dados;
performance.
7. Backlog
Estruturar:
```text
Iniciativa
  ↓
Épico
  ↓
Feature
  ↓
História
  ↓
Critérios de aceite
```
8. Priorização
Avaliar:
impacto no cliente;
risco operacional;
compliance;
dependência técnica;
esforço;
valor de negócio.
9. Estratégia de migração
Possíveis abordagens:
Strangler Pattern
migração incremental
coexistência
feature flags
APIs de compatibilidade
10. Métricas
redução de incidentes;
redução de retrabalho;
lead time;
tempo de processamento;
conversão;
SLA;
disponibilidade;
satisfação do usuário.  
