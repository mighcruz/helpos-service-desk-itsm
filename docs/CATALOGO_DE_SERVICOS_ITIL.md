# 📚 Catálogo de Serviços de TI – HelpOS

> Documento oficial que descreve os serviços de Tecnologia da Informação disponíveis aos usuários da HelpOS, alinhado às boas práticas de ITIL 4 e ISO/IEC 20000.

**Versão:** 1.0  
**Última Atualização:** 2024  
**Responsável pela Gestão do Catálogo:** Coordenação de Service Desk

---

## ℹ️ Sobre este Catálogo

Este catálogo tem como objetivo fornecer transparência, padronização e previsibilidade no atendimento às demandas de TI. Ele define claramente o que é oferecido, quem pode solicitar, quais informações são necessárias e quais são os Acordos de Nível de Serviço (SLA) comprometidos.

**Legenda de Janelas:**
- **Janela de Atendimento:** Horário em que a equipe de Service Desk está ativa para receber e iniciar o tratamento de novas solicitações (ex: 8h às 18h, dias úteis).
- **Janela de Serviço:** Período total em que o serviço/sistema deve estar disponível para uso (ex: 24x7).
- **SLA (em horas):** Tempo máximo comprometido para a **primeira resposta** ou resolução, contado a partir do início da Janela de Atendimento.

---

## 🖥️ 1. Hardware

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Instalação de Computador** | Instalação e configuração de novo equipamento para o usuário. | Novo Func. / Func. | Sim (Gestor de TI) | Modelo, SO, software necessário, localização. | 8 | 8h-18h (8x5) | 24x7 | Inclui transferência de dados e config. de periféricos. |
| **Manutenção de Computador** | Diagnóstico e reparo de problemas (lentidão, travamentos, etc.). | Funcionário | Não | Descrição do problema, modelo, nº de série. | 4 | 8h-18h (8x5) | 24x7 | Pode incluir formatação e reinstalação do SO. |
| **Troca de Peça** | Substituição de componentes defeituosos (HD, memória, etc.). | Funcionário | Sim (Gestor de TI) | Descrição da peça, modelo, nº de série. | 8 | 8h-18h (8x5) | 24x7 | Sujeito à disponibilidade de estoque de peças. |
| **Instalação de Periféricos** | Instalação e config. de impressoras, scanners, etc. | Funcionário | Não | Modelo, tipo de conexão, SO. | 2 | 8h-18h (8x5) | 24x7 | Inclui teste de funcionamento. |

---

## 💿 2. Software

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Instalação de Software Padrão** | Instalação de softwares corporativos (Office, Antivírus, etc.). | Novo Func. / Func. | Não | Nome do software, SO. | 2 | 8h-18h (8x5) | 24x7 | Requer licenças de software válidas. |
| **Instalação de Software Específico** | Instalação de softwares específicos para a função (CAD, editores, etc.). | Funcionário | Sim (Gestor do Depto.) | Nome, justificativa, licença (se aplicável). | 4 | 8h-18h (8x5) | 24x7 | Requer análise prévia de compatibilidade e licenciamento. |
| **Problemas com Software** | Diagnóstico e solução de erros, lentidão ou falhas em softwares. | Funcionário | Não | Nome do software, descrição do erro, print da tela. | 4 | 8h-18h (8x5) | 24x7 | Pode incluir reinstalação ou correção de configurações. |

---

## 🌐 3. Rede e Conectividade

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Problemas de Conexão (Internet)** | Diagnóstico e solução de falhas de conexão (Wi-Fi, cabo). | Funcionário | Não | Tipo de conexão, localização, descrição. | 2 | 8h-18h (8x5) | 24x7 | Inclui verificação de roteadores e modems. |
| **Acesso a Pastas Compartilhadas** | Liberação ou correção de acesso a diretórios de rede. | Funcionário | Sim (Gestor da Pasta) | Nome da pasta, usuário, nível de acesso desejado. | 4 | 8h-18h (8x5) | 24x7 | Requer configuração de permissões (ACLs) no servidor. |
| **Criação de Acesso VPN** | Configuração de acesso remoto seguro para trabalho externo. | Funcionário | Sim (Gestor de TI) | Justificativa, tempo de acesso necessário. | 8 | 8h-18h (8x5) | 24x7 | Requer configuração no servidor VPN e entrega de token/credenciais. |

---

## 🔒 4. Acessos e Segurança

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Reset de Senha** | Redefinição de senha de acesso a sistemas e contas corporativas. | Funcionário | Não | Nome de usuário, sistema/conta. | **1** | 8h-18h (8x5) | 24x7 | Prioritário. Requer validação de identidade do solicitante. |
| **Liberação de Acesso a Sistemas** | Concessão de perfil em sistemas internos (ERP, CRM, etc.). | Funcionário | Sim (Gestor do Sistema) | Nome do sistema, justificativa, nível de acesso. | 8 | 8h-18h (8x5) | 24x7 | Segue o Princípio do Menor Privilégio. |
| **Bloqueio de Acesso Imediato** | Bloqueio emergencial de contas (desligamento, suspeita de uso indevido). | Gestor / RH | Sim (Gestor de TI) | Nome de usuário, sistema, motivo do bloqueio. | **1** | 8h-18h (8x5) | 24x7 | **Crítico.** Acionado imediatamente para mitigação de risco. |

---

## 📧 5. E-mail e Comunicação

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Criação de Conta de E-mail** | Provisionamento de nova conta de e-mail corporativo. | Novo Funcionário | Sim (Gestor de TI) | Nome completo, departamento, cargo. | 4 | 8h-18h (8x5) | 24x7 | Inclui configuração no cliente de e-mail (Outlook, etc.). |
| **Problemas com E-mail** | Diagnóstico de falhas de envio, recebimento ou sincronização. | Funcionário | Não | Descrição do problema, conta de e-mail afetada. | 2 | 8h-18h (8x5) | 24x7 | Inclui verificação de regras de caixa de entrada e servidores. |

---

## 📞 6. Telefonia

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Configuração de Ramal** | Instalação e configuração de novo ramal telefônico. | Novo Func. / Func. | Não | Número do ramal, localização física. | 2 | 8h-18h (8x5) | 24x7 | Inclui teste de funcionamento (chamada local e externa). |
| **Problemas com Ramal** | Diagnóstico de falhas (mudo, chiado, sem tom de discar). | Funcionário | Não | Número do ramal, descrição detalhada do problema. | 2 | 8h-18h (8x5) | 24x7 | Inclui verificação de cabeamento e PABX. |

---

## 🏢 7. Sistemas Corporativos

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Suporte a Sistema Específico** | Atendimento a falhas operacionais em sistemas corporativos (ex: ERP). | Funcionário | Não | Nome do sistema, descrição, print do erro. | 8 | 8h-18h (8x5) | 24x7 | Requer conhecimento específico do módulo/sistema. |
| **Solicitação de Melhoria** | Pedido de novas funcionalidades ou ajustes em sistemas existentes. | Funcionário | Sim (Gestor do Sistema) | Descrição da melhoria, justificativa de negócio. | 16 | 8h-18h (8x5) | 24x7 | Entra no fluxo de Gerenciamento de Mudanças/Projetos. |

---

## 🛠️ 8. Outros Serviços

| Serviço | Descrição | Solicitante | Aprovação Necessária? | Informações Requeridas | SLA (h) | Janela de Atendimento | Janela de Serviço | Observações |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- |
| **Treinamento de Software** | Capacitação para utilização de softwares corporativos específicos. | Funcionário | Sim (Gestor do Depto.) | Nome do software, nível de conhecimento, data/hora. | 16 | Sob Demanda | Sob Demanda | Requer agendamento prévio com a equipe de TI. |
| **Solicitação de Equip. Adicional** | Pedido de itens como monitores extras, teclados, mouses, etc. | Funcionário | Sim (Gestor do Depto.) | Descrição do equipamento, justificativa de necessidade. | 8 | 8h-18h (8x5) | 24x7 | Sujeito à análise de disponibilidade de estoque. |

---

## ⚖️ Notas de Governança e Conformidade

1. **Priorização:** Todos os chamados são priorizados com base na matriz **Impacto x Urgência**, conforme definido no processo de Gerenciamento de Incidentes (ITIL).
2. **SLA:** O cronômetro do SLA é pausado quando o chamado aguarda uma ação do solicitante (status "Aguardando Usuário") ou aprovação de terceiros.
3. **Segurança:** Solicitações que envolvem alteração de privilégios de acesso (ex: Liberação de Acesso, Criação de VPN) passam obrigatoriamente por validação do gestor responsável, em conformidade com o Princípio do Menor Privilégio.
4. **Evolução:** Este catálogo é revisado semestralmente pela Gestão de Nível de Serviço para garantir que reflita a realidade operacional e as necessidades do negócio.

---

## 🧭 Navegação do Portfólio

[⬅️ Voltar ao README Principal do Projeto HelpOS](README.md)  
[📂 Voltar ao Hub Central de Projetos](https://github.com/mighcruz/portfolio-ti)
