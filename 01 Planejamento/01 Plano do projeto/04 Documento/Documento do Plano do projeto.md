# Plano do Projeto de Software: Plataforma Bancária Digital - AppBank

## 1. Visão Geral do Projeto

**Nome do Projeto**: Plataforma Bancária Digital  

**Objetivo**: Criar uma plataforma bancária digital segura e intuitiva que permita aos usuários gerenciar suas contas, realizar transações, e acompanhar suas finanças de forma eficiente e acessível, com alta segurança.

## 2. Escopo do Projeto

### Funcionalidades Principais

Segue uma versão ajustada e melhorada dos requisitos do software, consolidando e organizando as funcionalidades principais para maior clareza e alinhamento com as necessidades do projeto:

---

### **Funcionalidades Principais**

#### **1. Cadastro de Usuário e Autenticação Segura**
- **Cadastro de usuários:** Criação de contas de usuários com validação de identidade.  
- **Login seguro:** Implementação de autenticação multifator (MFA) para garantir maior segurança.  
- **Recuperação de senha:** Processo automatizado e seguro para recuperação de credenciais.  
- **Gestão de permissões:** Administradores podem gerenciar níveis de acesso e permissões por perfil de usuário.  

#### **2. Gerenciamento de Contas**
- **Registro de contas bancárias:** Usuários podem cadastrar e gerenciar várias contas (corrente, poupança, etc.).  
- **Consulta de saldo e extrato:** Exibição em tempo real de saldos e extratos detalhados.  
- **Configuração de perfis:** Personalização das contas com preferências específicas, como alertas e notificações.  
- **Encerramento de contas:** Administradores podem fechar contas e zerar saldos, especialmente em casos departamentais.  

#### **3. Transações Bancárias**
- **Realização de transações:** Funcionalidades para depósitos, transferências e saques com confirmação em tempo real.  
- **Pagamentos:** Opções para pagamento de contas e serviços diretamente pelo sistema.  
- **Aprovação de transações:** Gerentes financeiros têm a responsabilidade de validar ou recusar transações realizadas por outros usuários.  

#### **4. Histórico de Transações**
- **Consulta detalhada:** Usuários podem acessar o histórico completo de transações, com informações sobre data, valor e descrição.  
- **Exportação de dados:** Disponibilização de relatórios financeiros em formatos como PDF ou CSV.  

#### **5. Controle e Acompanhamento Financeiro**
- **Relatórios financeiros:** Geração automática de gráficos e relatórios com análises de despesas e receitas.  
- **Configuração de metas:** Usuários podem definir orçamentos e metas financeiras.  
- **Monitoramento de desempenho:** Sistema que envia alertas sobre desvios das metas ou comportamento financeiro suspeito.  

#### **6. Consultas e Relatórios Avançados**
- **Relatórios consolidados:** Gerentes podem acessar relatórios financeiros por usuário, conta ou departamento.  
- **Visualização em tempo real:** Atualização instantânea de saldos e movimentações.  

#### **7. Suporte e Segurança**
- **Atendimento ao usuário:** Chatbot automatizado e suporte humano para resolução de problemas.  
- **Monitoramento de atividades:** Detecção de atividades suspeitas com envio de alertas.  
- **Conformidade com LGPD:** Proteção de dados dos usuários e adesão à legislação vigente.  

---

### **Funcionalidades Futuras**
- **Integração com serviços de terceiros:** Compatibilidade com carteiras digitais, investimentos e sistemas de pagamento externos.  
- **Personalização da interface:** Recursos para customização da interface do usuário.  
- **Planejamento financeiro avançado:** Ferramentas para simulações e estratégias financeiras detalhadas.  
- **Automação de pagamentos recorrentes:** Configuração de débitos automáticos para serviços e contas.  


## 3. Objetivos do Projeto

-   Desenvolver uma plataforma que combine usabilidade e segurança robusta.
-   Fornecer uma interface amigável, responsiva e intuitiva para todos os dispositivos.
-   Garantir proteção dos dados de acordo com a legislação e melhores práticas de segurança.
-   Promover a inclusão financeira, oferecendo acessibilidade para diversos públicos.

## 4. Cronograma do Projeto

| Fase do Projeto              | Descrição                                 | Duração Estimada |
| ---------------------------- | ----------------------------------------- | ---------------- |
| Planejamento                 | Definição de requisitos e metas           | 2 semanas        |
| Design da Interface e UX     | Design da interface e fluxos de usuário   | 3 semanas        |
| Desenvolvimento              | Desenvolvimento das funcionalidades       | 4 meses          |
| Testes e Qualidade           | Testes de unidade, integração e segurança | 6 semanas        |
| Implementação e Lançamento   | Deploy da plataforma                      | 2 semanas        |
| Manutenção e Suporte Inicial | Correções de bugs e feedback de usuários  | 1 mês            |

Total estimado: 6 meses e 2 semanas

## 5. Recursos e Orçamento

### Equipe

-   **Gerente de Projeto** - Responsável pela gestão e planejamento do projeto.
-   **Desenvolvedores Backend** - Para criação da lógica de negócios e segurança.
-   **Desenvolvedores Frontend** - Para desenvolvimento da interface e experiência do usuário.
-   **Designer UX/UI** - Para a criação de uma interface intuitiva e acessível.
-   **Analista de Segurança** - Para assegurar a conformidade e proteção de dados.
-   **Analista de Testes** - Responsável por garantir a qualidade e funcionalidade.

### Tecnologias

-   **Backend**: Node.js, Express, banco de dados SQL/NoSQL.
-   **Frontend**: React ou Angular, com design responsivo.
-   **Segurança**: MFA, criptografia de dados em trânsito e em repouso.
-   **Testes**: Jest, Selenium, ferramentas de testes de carga e penetração.

### Orçamento (Estimado)

| Item                           | Custo Estimado |
| ------------------------------ | -------------- |
| Desenvolvimento                | $60,000        |
| Design de Interface            | $15,000        |
| Testes e Garantia de Qualidade | $10,000        |
| Segurança e Conformidade       | $8,000         |
| Infraestrutura e Deploy        | $7,000         |
| Total                          | $100,000       |

## 6. Riscos do Projeto

| Risco                                | Probabilidade | Impacto | Mitigação                                                        |
| ------------------------------------ | ------------- | ------- | ---------------------------------------------------------------- |
| Problemas de segurança               | Alta          | Alto    | Uso de práticas e ferramentas de segurança atualizadas           |
| Mudanças nos requisitos              | Média         | Médio   | Revisões regulares com stakeholders                              |
| Atrasos na entrega                   | Média         | Alto    | Gerenciamento ágil e uso de buffers de tempo                     |
| Problemas de conformidade com a LGPD | Baixa         | Alto    | Consultoria jurídica e implementação de políticas de privacidade |

## 7. Aprovação e Controle de Qualidade

**Critérios de Aceitação**:

-   Interface fácil de usar e intuitiva.
-   Autenticação segura e sem vulnerabilidades conhecidas.
-   Funcionalidades de transação e consulta de saldo 100% operacionais.
-   Conformidade com LGPD e demais regulamentações financeiras.

**Responsável pela Aprovação Final**: Comitê de Governança do Projeto (Gerente de Projeto, CTO, e representantes de segurança e compliance).


## Conhecimentos:

http://www.dsc.ufcg.edu.br/~jacques/cursos/apoo/html/intro/intro2.htm
