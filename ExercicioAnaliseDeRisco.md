CENÁRIO 1 - Interrupção Temporária do Serviço devido a Manutenção Programada

Probabilidade: B
Impacto: 2
Matriz do Risco: 2B - Baixo

Teste utilizado:

Teste de integração
Teste funcional
Teste de regressão

Estratégia de mitigação:
Planejar a manutenção em horários de menor acesso e realizar testes antes da liberação para evitar indisponibilidade prolongada.

Tipos de risco:

Operacional: manutenção pode deixar o sistema indisponível.
Negócio: usuários podem ficar sem acesso ao serviço temporariamente.
Humano: erro da equipe durante deploy ou manutenção.

-----------------------------------------------------------------------------------------------------------------------------------

CENÁRIO 2 - Vulnerabilidade de Segurança em Dependência de Terceiros

Probabilidade: C
Impacto: 5
Matriz do Risco: 5C - Muito Alto

Teste utilizado:

Pentest
Teste de segurança
Teste de API

Estratégia de mitigação:
Atualizar bibliotecas frequentemente, aplicar correções de segurança e realizar testes contínuos para identificar vulnerabilidades.

Tipos de risco:

Técnico: falha em biblioteca externa.
Negócio: vazamento de dados pode causar prejuízo financeiro.
Operacional: necessidade de correções urgentes no sistema.
Humano: falhas de configuração ou atualização inadequada.

-----------------------------------------------------------------------------------------------------------------------------------

CENÁRIO 3 - Erro de Interface do Usuário

Probabilidade: C
Impacto: 3
Matriz do Risco: 3C - Médio

Teste utilizado:

Teste funcional
Teste de usabilidade
Teste de regressão

Estratégia de mitigação:
Realizar testes de usabilidade e validar alterações da interface antes da publicação do sistema.

Tipos de risco:

Humano: usuários podem interpretar funções de forma errada.
Técnico: problemas na interface e componentes.
Negócio: aumento de reclamações e dificuldade de uso.

---------------------------------------------------------------------------------------------------------------------------
CENÁRIO 4 - Falha no Processo de Backup

Probabilidade: D
Impacto: 5
Matriz do Risco: 5D - Muito Alto

Teste utilizado:

Teste de integração
Teste de desempenho
Teste operacional

Estratégia de mitigação:
Criar rotinas automáticas de backup, monitoramento e testes periódicos de restauração dos dados.

Tipos de risco:

Operacional: falha no backup compromete recuperação do sistema.
Negócio: perda de dados pode causar prejuízos.
Técnico: erro no armazenamento ou processamento do backup.
Humano: configuração incorreta do backup.

-------------------------------------------------------------------------------------------------------------------------------------
CENÁRIO 5 - Ataque de Phishing aos Usuários

Probabilidade: C
Impacto: 4
Matriz do Risco: 4C - Alto

Teste utilizado:

Pentest
Teste de segurança
Teste funcional

Estratégia de mitigação:
Implementar autenticação MFA, validações de segurança e campanhas de conscientização para os usuários.

Tipos de risco:

Humano: usuários podem cair em golpes.
Negócio: prejuízo financeiro e perda de confiança.
Técnico: exploração de falhas de autenticação.
Operacional: necessidade de resposta rápida a incidentes.
