# Qualidade e Teste de Software

## Princípios de Teste

### 1. Testes mostram a presença de defeitos
Os testes ajudam a encontrar erros no sistema, mas não garantem que não existam mais defeitos.

**Exemplo:**  
Um teste encontra erro no cálculo de imposto de um sistema financeiro.

---

### 2. Testes exaustivos são impossíveis
Não é possível testar todas as combinações possíveis de um sistema.

**Exemplo:**  
Um formulário com vários campos teria milhões de combinações possíveis de entrada.

---

### 3. Teste antecipado
Os testes devem começar o mais cedo possível no desenvolvimento.

**Exemplo:**  
Revisar requisitos antes de começar a programar.

---

### 4. Agrupamento de defeitos
Muitos defeitos costumam estar concentrados em poucas partes do sistema.

**Exemplo:**  
Um módulo de pagamento pode ter mais erros que outras partes.

---

### 5. Paradoxo do pesticida
Se os mesmos testes forem executados sempre, eles deixam de encontrar novos erros.

**Exemplo:**  
Criar novos casos de teste após várias execuções.

---

### 6. Testes dependem do contexto
O tipo de teste depende do tipo de sistema.

**Exemplo:**  
Um sistema bancário precisa de mais testes de segurança.

---

### 7. Ausência de erros não significa sucesso
Mesmo sem erros, o sistema pode não atender às necessidades do usuário.

**Exemplo:**  
Sistema funciona perfeitamente, mas não resolve o problema do cliente.

---

# Níveis de Teste

### Teste de Componentes (ou Unitário)
Testa partes pequenas do sistema, como funções ou métodos.

**Exemplo:**  
Testar uma função que calcula o valor total de uma compra.

---

### Teste de Integração
Testa a comunicação entre diferentes componentes do sistema.

**Exemplo:**  
Verificar se o sistema de login se conecta corretamente ao banco de dados.

---

### Teste de Sistema
Testa o sistema completo funcionando.

**Exemplo:**  
Simular todo o processo de compra em um site.

---

### Teste de Aceite
Testa se o sistema atende às necessidades do usuário ou cliente.

**Exemplo:**  
Usuários testando um sistema antes da entrega final.

---

# Tipos de Teste

### Teste Funcional
Verifica se as funções do sistema funcionam corretamente.

**Exemplo:**  
Testar se o botão de login realmente permite acessar o sistema.

---

### Teste Não Funcional
Avalia características como desempenho, segurança e usabilidade.

**Exemplo:**  
Testar quantos usuários o sistema suporta ao mesmo tempo.

---

### Teste Caixa-Branca
Testa o código interno do sistema.

**Exemplo:**  
Testar todos os caminhos de um `if` no código.

---

### Teste Relacionado à Mudança
Executado quando o sistema sofre alterações.

**Exemplo:**  
Testar novamente o login após modificar o código.

---

# Técnicas de Teste

## Caixa-Preta

### Particionamento de Equivalência
Divide os dados em grupos para reduzir a quantidade de testes.

**Exemplo:**  
Campo que aceita números de 1 a 100.

- menor que 1
- entre 1 e 100
- maior que 100

---

### Análise de Valor Limite
Testa os limites de entrada de dados.

**Exemplo:**  
Se o campo aceita de 1 a 100, testar:
- 1
- 2
- 99
- 100

---

### Tabela de Decisão
Usada quando existem várias condições.

**Exemplo:**  
Empréstimo aprovado apenas para pessoas com:
- idade maior que 18
- renda maior que R$1000

---

### Transição de Estado
Testa mudanças de estado no sistema.

**Exemplo:**  
Sistema de temperatura:
- aquecendo
- resfriando
- neutro

---

### Caso de Uso
Baseado nos fluxos que o usuário executa.

**Exemplo:**  
Sistema de login:
- login correto
- senha incorreta
- usuário inexistente

---

## Caixa-Branca

### Cobertura de Instruções
Garante que todas as linhas do código sejam executadas.

**Exemplo:**  
Testar uma função que soma dois números.

---

### Teste de Decisão
Garante que todas as decisões do código sejam testadas.

**Exemplo:**  
Testar um `if` para verdadeiro e falso.

---

## Baseado em Experiência

### Suposição de Erro
Testes baseados na experiência do testador.

**Exemplo:**  
Testar campos vazios em formulários.

---

### Teste Exploratório
Testar o sistema sem roteiro definido.

**Exemplo:**  
Explorar menus e funcionalidades livremente.

---

### Lista de Verificação
Executar testes com base em uma checklist.

**Exemplo:**  
Verificar:
- login
- cadastro
- recuperação de senha
