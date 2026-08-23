# Help OS — Criação e Desenvolvimento de Plataforma para Service Desk 

> Desenvolvimento de sistema de gestão de serviços de TI aplicando conceitos de ITIL, COBIT e engenharia de software, com foco em automação de incidentes e workflows de SLA.

**Status:** Concluído  
**Natureza:** Acadêmico / Laboratorial (Simulação Corporativa)

---

## 🔒 Nota de Confidencialidade

*Tratando-se de um projeto desenvolvido em ambiente acadêmico e de simulação corporativa, dados de usuários, configurações de sistema e detalhes de implementação foram tratados de forma genérica, preservando a integridade de eventuais ambientes reais e informações sensíveis.*

---

## Visão Geral

O HelpOS é uma plataforma de Service Desk desenvolvida para demonstrar a aplicação prática de frameworks de governança de TI (ITIL, COBIT e ISO 20000) em um sistema funcional de gestão de serviços. O projeto abrange todo o ciclo de vida de incidentes, desde a abertura pelo usuário até a resolução e fechamento pelo atendente, com workflows automatizados, categorização de chamados e métricas de SLA.

## Contexto e Problema

Organizações que operam sem um sistema estruturado de Service Desk enfrentam desafios como falta de padronização no atendimento, dificuldade de rastreamento de incidentes, ausência de métricas de desempenho e baixa visibilidade sobre a qualidade dos serviços de TI. Para evoluir a maturidade em gestão de serviços, é necessário implementar uma plataforma que centralize demandas, automatize processos e forneça indicadores para melhoria contínua.

## Objetivos

- Criar plataforma centralizada para gestão de incidentes e requisições de serviços de TI.
- Automatizar suporte e workflows de TI com base em boas práticas de ITIL e COBIT.
- Implementar categorização, priorização e rastreamento de chamados.
- Garantir conformidade com frameworks ITIL, COBIT e ISO 20000.
- Fornecer dashboards e relatórios para monitoramento de SLA e desempenho da equipe.

## Escopo

**Inclusões:** Desenvolvimento SDLC completo, automação de incidentes, gestão de portfólio de serviços, workflows de aprovação, categorização de chamados, sistema de priorização, anexos de arquivos, relatórios e dashboards.  
**Exclusões:** Integração física com hardware externo de terceiros, desenvolvimento de aplicativos móveis nativos.  
**Limites:** Cenário de simulação corporativa desenvolvido em ambiente acadêmico, sem impacto em operações de produção.

## Papel e Responsabilidades

Atuação no desenvolvimento da plataforma HelpOS, incluindo modelagem de dados, implementação de workflows de atendimento, configuração de regras de SLA, desenvolvimento de dashboards gerenciais e documentação técnica do sistema.

## Metodologia e Abordagem

O projeto foi conduzido em fases estruturadas de engenharia de software:
1. **Planejamento e Arquitetura:** Definição de requisitos funcionais e não-funcionais, modelagem de dados (DER, Diagrama de Classes) e arquitetura da plataforma.
2. **Desenvolvimento de Workflows e SLA:** Implementação de fluxos de atendimento, regras de priorização (impacto x urgência), categorização de chamados e definição de SLAs.
3. **Implementação do Sistema:** Desenvolvimento da interface de login, dashboard administrativo, formulários de abertura de chamados, listagem de tickets e sistema de resolução.
4. **Testes de Performance e Segurança:** Validação de funcionalidades, testes de usabilidade e verificação de conformidade com requisitos de segurança.
5. **Entrega e Documentação:** Disponibilização de ambiente funcional, documentação técnica e vídeo de apresentação (pitch).

## Frameworks e Boas Práticas

- **ITIL 4:** Aplicado para estruturação do gerenciamento de incidentes, requisições de serviço, priorização de chamados e definição de SLAs.
- **COBIT 2019:** Utilizado para alinhamento entre TI e negócio, governança de serviços e definição de métricas de desempenho.
- **ISO 20000:** Referência para padronização de processos de gestão de serviços de TI e melhoria contínua.

## Tecnologias e Ferramentas

- **Desenvolvimento:** Mad Builder (plataforma low-code), HTML, CSS, JavaScript.
- **Banco de Dados:** MySQL/PostgreSQL (modelagem relacional).
- **Ferramentas de Modelagem:** Draw.io, BrModelo.
- **Gestão e Versionamento:** GitHub.
- **Infraestrutura Conceitual:** Terraform, Ansible, Kubernetes, Docker, AWS/Azure (arquitetura documentada).

## Solução e Arquitetura

A plataforma HelpOS foi desenvolvida com arquitetura modular e interface web responsiva. O sistema inclui:
- **Módulo de Autenticação:** Login seguro com controle de perfis (Administrador, Atendente, Cliente/Usuário).
- **Módulo de Chamados:** Abertura, categorização, priorização, atribuição e resolução de incidentes.
- **Workflows Automatizados:** Fluxos de aprovação, notificações e escalonamento baseados em regras de SLA.
- **Dashboards Gerenciais:** Visualização de métricas como tickets abertos/fechados, tempo médio de resolução (MTTR), top clientes, top produtos e distribuição por prioridade/categoria.
- **Relatórios e Exportação:** Geração de relatórios em PDF, XLS, XML e CSV para análise de dados.

## Evidências e Entregáveis

- **Sistema Funcional HelpOS:** Plataforma completa com login, dashboard, abertura de chamados, listagem de tickets e resolução de incidentes.
- **Modelagem de Dados Completa:** DER, Diagrama de Classes, modelo lógico e físico de banco de dados.
- **Requisitos Funcionais e Não-Funcionais:** Documentação detalhada de RFs e RNFs alinhados a ITIL.
- **Catálogo de Serviços ITIL:** Estrutura de produtos e categorias de atendimento (Hardware, Software, Rede, E-mail, Telefonia, etc.).
- **Vídeo de Apresentação (Pitch):** Demonstração completa das funcionalidades do sistema.
- **Documentação Técnica:** Arquitetura, fluxos de trabalho, regras de SLA e manual de uso.

*[Espaço reservado para inserção de screenshots do sistema, diagramas de arquitetura e link para o vídeo de apresentação]*

## Resultados e Validação

- Sistema de Service Desk funcional desenvolvido e testado em ambiente de simulação.
- Implementação de workflows de atendimento alinhados a ITIL (abertura → atendimento → resolução → fechamento).
- Categorização e priorização de chamados baseadas em impacto e urgência.
- Dashboards gerenciais com métricas de desempenho (tickets abertos/fechados, MTTR, satisfação).
- Conformidade com requisitos de governança ITIL, COBIT e ISO 20000 documentada.

## Aprendizados e Limitações

- **Aprendizado:** A aplicação prática de ITIL em um sistema funcional demonstrou a importância de workflows bem definidos, categorização adequada e métricas de SLA para a eficiência do Service Desk. A plataforma low-code (Mad Builder) permitiu desenvolvimento ágil, mas exigiu adaptações para atender requisitos específicos de governança.
- **Limitação:** O sistema foi desenvolvido em ambiente de simulação acadêmica, sem integração com ferramentas de monitoramento de infraestrutura (Zabbix, PRTG) ou sistemas corporativos (Active Directory, SAP). A escalabilidade para um ambiente de produção real exigiria adaptações de infraestrutura e segurança.

## Próximos Passos e Evoluções Futuras

- Integração com ferramentas de monitoramento de infraestrutura para abertura automática de chamados baseada em alertas.
- Implementação de chatbot com IA para atendimento inicial e triagem automatizada.
- Desenvolvimento de aplicativo mobile para acesso de usuários e atendentes.
- Integração com Active Directory/LDAP para autenticação corporativa.
- Expansão dos dashboards com análise preditiva e machine learning para antecipação de incidentes.

---

## 📂 Documentação, Evidências e Recursos

- [Link para o Vídeo de Apresentação (Pitch)](#)
- [Link para a Documentação Técnica Completa (PDF)](#)
- [Link para o Repositório de Código/Modelagem (GitHub)](#)
- [Link para o Catálogo de Serviços ITIL](#)

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguelhcruz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mig.kruz@gmail.com)

---

## 🧭 Navegação do Portfólio

[⬅️ Voltar ao Perfil Principal](https://github.com/mighcruz) 

[📂 Voltar ao Hub Central de Projetos](https://github.com/mighcruz/portfolio-ti)
