# 📋 Plano de Testes

## 🧪 Objetivo
Este plano de testes tem como objetivo garantir que a aplicação fornecida esteja funcionando conforme os requisitos definidos, validando a funcionalidade, usabilidade, segurança e compatibilidade do sistema.

## 📦 Escopo
Serão realizados testes manuais e automatizados sobre as principais funcionalidades da aplicação. Os testes cobrirão:

- Funcionalidades principais
- Navegação e usabilidade
- Compatibilidade entre navegadores e dispositivos
- Validações de segurança básicas

## 🔍 Tipos de Testes

| Tipo de Teste           | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| Funcionais              | Verificar se a aplicação realiza as funções conforme especificado         |
| Usabilidade             | Avaliar a experiência do usuário e facilidade de navegação                |
| Compatibilidade         | Testar em diferentes navegadores e resoluções                            |
| Segurança (básica)      | Testar campos com dados inválidos, tentativas de injeção, etc.            |
| Testes Automatizados    | Validar duas funcionalidades críticas automaticamente com Cypress/Selenium |

## 🧠 Priorização dos Testes

A priorização será feita com base em risco e criticidade das funcionalidades. Funcionalidades que impactam diretamente o fluxo principal do usuário terão prioridade.

| Prioridade | Funcionalidade                     | Justificativa                                    |
|------------|-------------------------------------|--------------------------------------------------|
| Alta       | Login/Autenticação                  | Acesso ao sistema depende dessa funcionalidade   |
| Alta       | Cadastro/Formulários                | Impacta diretamente no funcionamento do sistema  |
| Média      | Navegação entre páginas             | Relacionado à experiência do usuário             |
| Baixa      | Ajustes visuais e responsividade    | Não afeta diretamente o funcionamento da app     |

## 🛠️ Ferramentas Utilizadas

- **Testes Manuais**: Google Sheets / Excel, Print de tela
- **Testes Automatizados**: [Cypress](https://www.cypress.io/) (JavaScript)
- **Gerenciamento de Evidências**: Google Drive / Repositório GitHub privado
- **Relatórios**: Markdown + PDF

## 📅 Cronograma Estimado

| Etapa                        | Período Estimado     |
|-----------------------------|----------------------|
| Compreensão dos Requisitos  | DD/MM/YYYY           |
| Planejamento dos Testes     | DD/MM/YYYY           |
| Execução Manual             | DD/MM/YYYY           |
| Automação de Testes         | DD/MM/YYYY           |
| Análise e Relatório Final   | DD/MM/YYYY           |

---