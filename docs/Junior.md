## 📌 Regras gerais

* Cada atividade deve conter **link da Pull Request aprovada**.
* A PR precisa ter:

  * descrição clara do problema
  * explicação da solução aplicada
  * instruções de como testar
  * tipo de mudança
* O código deve estar **em produção ou homologação**.
* Revisão obrigatória de **desenvolvedor pleno ou sênior**.

---

# 1. Fundamentos de Git e Fluxo de Trabalho

## 1.1 Criar PR seguindo o padrão do time

**Comprovação:**
Link de PR contendo:

* descrição do problema
* solução aplicada
* como testar
* tipo de mudança

---

## 1.2 Resolver conflitos de merge sem ajuda

**Comprovação:**
PR com histórico demonstrando resolução de conflito.

---

## 1.3 Realizar code review simples em outro PR

**Comprovação:**
Link de comentário técnico em PR de outro desenvolvedor.

---

# 2. Correção de Bugs Reais

## 2.1 Corrigir bug simples em produção

**Exemplos:**

* erro de validação
* erro de `null`
* mensagem incorreta

**Comprovação:**
PR do bug + evidência de teste manual.

---

## 2.2 Investigar erro de log e corrigir causa raiz

**Comprovação:**
PR + trecho do log analisado e explicação da causa.

---

# 3. Desenvolvimento Backend Básico (Laravel)

## 3.1 Criar endpoint CRUD simples

**Requisitos:**

* Request validation
* Controller
* Service ou Repository (se o time usar)
* Migration
* Teste básico

**Comprovação:**
PR do CRUD completo.

---

## 3.2 Escrever teste unitário ou feature

**Comprovação:**
PR contendo teste automatizado passando.

---

## 3.3 Utilizar Eloquent corretamente

**Exemplos:**

* evitar N+1
* usar relationships
* criar scopes simples

**Comprovação:**
PR demonstrando uso adequado.

---

# 4. Qualidade de Código

## 4.1 Seguir padrão PSR e convenções do projeto

**Comprovação:**
PR aprovado sem correções de estilo.

---

## 4.2 Refatorar código legado simples

**Exemplos:**

* remover duplicação
* melhorar nomes de variáveis
* extrair métodos

**Comprovação:**
PR de refatoração sem alteração de regra de negócio.

---

# 5. Banco de Dados

## 5.1 Criar migration segura

**Boas práticas:**

* índices corretos
* rollback funcionando

**Comprovação:**
PR da migration aplicada.

---

## 5.2 Escrever query eficiente

**Exemplos:**

* substituir loop por query
* uso correto de índices

**Comprovação:**
PR demonstrando melhoria de performance ou legibilidade.

---

# 6. Debug e Observabilidade

## 6.1 Reproduzir bug localmente

**Comprovação:**
Descrição clara no PR explicando como reproduzir.

---

## 6.2 Utilizar logs para investigação

**Comprovação:**
PR mencionando análise de logs e conclusão.

---

# 7. Comunicação Técnica

## 7.1 Escrever documentação simples

**Exemplos:**

* README de feature
* comentário explicando regra complexa

**Comprovação:**
PR com documentação adicionada.

---

## 7.2 Explicar solução em review ou daily

**Comprovação:**
Descrição clara do raciocínio técnico na PR.

---

# 8. Uso de Outra Linguagem de Programação

## 8.1 Implementar pequena funcionalidade fora da linguagem principal

**Objetivo:**
Demonstrar capacidade de adaptação e entendimento de conceitos além da stack principal.

**Exemplos:**

* criar API simples em Go, Node.js ou Python
* script de automação
* worker de fila
* CLI utilitária

**Comprovação:**
Repositório ou PR funcional contendo:

* instruções de execução
* explicação do objetivo
* código executável

---

## 8.2 Explicar diferenças entre a linguagem principal e a nova linguagem

**Comprovação:**
Documento curto ou descrição na PR abordando:

* tipagem
* modelo de concorrência
* gerenciamento de dependências
* pontos fortes e fracos

---

# 9. Autonomia Inicial

## 9.1 Entregar tarefa do início ao fim sem ajuda direta

**Critérios:**

* entendimento correto do problema
* implementação funcional
* testes
* PR aprovado

**Comprovação:**
PR completo da tarefa.

---