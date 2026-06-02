# Desafio de Projeto: O Dia a Dia de um QA na Prática

Este repositório contém a documentação técnica e os artefatos de testes funcionais manuais desenvolvidos para o desafio de projeto "O Dia a Dia de um QA: A Prática de Testes Manuais Funcionais". Todo o planejamento e mapeamento foram aplicados sobre o contexto da plataforma de e-commerce fictícia **SwagLabs Shopping**.

O objetivo deste trabalho é consolidar o entendimento prático do fluxo de qualidade de software em ambientes que utilizam metodologias ágeis (Scrum), abrangendo desde a engenharia de requisitos até a escrita de cenários de teste estruturados.

---

## 📂 Estrutura dos Artefatos Entregues

A documentação oficial foi compilada em um único arquivo PDF unificado, disponível na raiz deste repositório:

* 📄 **`Desafio_QA_SwagLabs_Roque-v2.pdf`**: Documento formal em escala de cinza e tipografia Times New Roman, contendo todo o escopo de qualidade exigido pelo desafio.

### Conteúdo Detalhado do Documento:

1. **Plano de Fluxo de Trabalho (Workflow):**
   * Mapeamento dos estados de transição das tarefas no quadro ágil (*To Do*, *In Progress*, *Ready for QA*, *In Test*, *Done* e *Blocked*).
   * Definição clara do **Ciclo de Vida do Bug**, descrevendo a esteira de triagem desde a abertura do defeito (*New*) até a validação e encerramento (*Closed*).

2. **Histórias de Usuário (User Stories):**
   * **US-01 (Autenticação no SwagLabs):** Focada na segurança do login de clientes cadastrados e prevenção contra enumeração de usuários.
   * **US-02 (Gestão do Carrinho de Compras):** Focada na manipulação de itens na vitrine e regras de validação de estoque.
   * Ambas as histórias foram escritas utilizando o formato padrão de narrativa (*Como*, *Desejo*, *Para que*) e validadas sob os critérios do princípio **INVEST**.

3. **Mapeamento Visual (Mind-Map):**
   * Topologia de testes em formato de árvore aplicada sobre a **US-01**, ramificando a cobertura de testes entre *Happy Path* (Fluxo de Sucesso), *Sad Path* (Fluxo de Exceção), testes de fronteira/input e Requisitos Não Funcionais (Segurança e Usabilidade).

4. **Casos de Teste Step-by-Step:**
   * Dois roteiros estruturados passo a passo aplicados à **US-02** (Adição e Remoção de produtos), isolando pré-condições, ações consecutivas, dados de entrada e resultados esperados de forma objetiva.

5. **Casos de Teste em BDD (Behavior-Driven Development):**
   * Dois cenários de testes funcionais descritos em linguagem **Gherkin** (utilizando as cláusulas *Dado*, *Quando*, *E*, *Então*) para validar comportamentos de sucesso e regras de *lockout* (usuário bloqueado) na tela de autenticação.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **Metodologia Ágil:** Scrum
* **Nível de Teste:** Sistema e Aceite (UAT)
* **Tipo de Teste:** Funcional Caixa-Preta (Manual)
* **Padrões de Escrita:** INVEST, 3Cs (Cartão, Conversa, Confirmação) e BDD (Gherkin)

---

## 🚀 Como Visualizar os Documentos

Para ler a documentação completa com a formatação padronizada:
1. Navegue até o arquivo [Desafio_QA_SwagLabs_Roque.pdf](./Desafio_QA_SwagLabs_Roque.pdf) no topo da página.
2. Clique no botão **Download** para baixar e visualizar em seu leitor de PDF local.
