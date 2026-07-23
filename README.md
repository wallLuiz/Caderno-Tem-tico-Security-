# 📚 Caderno Temático - Preparação para a Certificação CompTIA Security+

## 🎯 Contexto e Objetivos

Este projeto foi desenvolvido utilizando o NotebookLM como ferramenta de apoio para os estudos da certificação CompTIA Security+.

A proposta consiste em utilizar Inteligência Artificial para organizar, resumir e relacionar conteúdos provenientes de materiais oficiais e anotações da comunidade, criando um ambiente de estudo mais eficiente e direcionado para a preparação do exame.

### Objetivos de Estudo

* Consolidar os principais conceitos de Segurança da Informação.
* Compreender os domínios abordados pela certificação Security+.
* Utilizar o NotebookLM para gerar resumos, explicações e revisões rápidas.
* Desenvolver técnicas de engenharia de prompts para otimizar o aprendizado.
* Criar um material de consulta para futuras certificações e atividades profissionais.

---

## 🔗 NotebookLM

Como complemento deste projeto, disponibilizo o caderno temático desenvolvido no NotebookLM:

📚 [Acessar Caderno no NotebookLM](https://notebooklm.google.com/notebook/134f4c62-8e9e-477c-bb6c-d67f3a5c2582)

> Acesso disponível apenas para visualização.

---

## 📖 Curadoria de Fontes

As seguintes fontes foram carregadas no NotebookLM para análise e geração de conteúdo:

### Fonte 1 - Guia Oficial CompTIA Security+
PDF oficial da certificação Security+ (SY0-701).
🔗 [CompTIA Security+ SY0-701 Exam Objectives (PDF)](https://assets.ctfassets.net/82ripq7fjls2/6TYWUym0Nudqa8nGEnegjG/0f9b974d3b1837fe85ab8e6553f4d623/CompTIA-Security-Plus-SY0-701-Exam-Objectives.pdf)

### Fonte 2 - Anotações da Comunidade
🔗 [Security+ 701 Study Guide (GitHub - daniellaurin)](https://github.com/daniellaurin/security-plus-701-study-guide)

### Fonte 3 - Anotações da Comunidade
🔗 [CompTIA SecPlus SY0-701 Notes (GitHub - heraclescap)](https://github.com/heraclescap/comptia-secplus-sy0-701-notes)

---

## 🤖 Engenharia de Prompts e Cicatrizes

### Prompt 1

**Objetivo:** Compreender a Tríade CIA utilizando exemplos corporativos.

**Prompt Utilizado:**
```text
Explique o conceito de CIA Triad utilizando exemplos do mundo corporativo.
```

**Resultado Obtido:**

O NotebookLM explicou os três pilares da Segurança da Informação:

- **Confidencialidade:** proteção contra acesso não autorizado.
- **Integridade:** garantia de que os dados não sejam alterados indevidamente.
- **Disponibilidade:** garantia de acesso aos sistemas quando necessário.

Também apresentou exemplos corporativos utilizando: MFA, Criptografia, Assinaturas Digitais, Backups e Balanceamento de carga.

**Aprendizado:** Prompts contextualizados geram respostas mais próximas da realidade profissional.

---

### Prompt 2

**Objetivo:** Criar um resumo rápido para revisão.

**Prompt Utilizado:**
```text
Resuma o domínio Threats, Vulnerabilities and Mitigations em até 10 tópicos.
```

**Resultado Obtido:**

O NotebookLM resumiu os principais conceitos: Atores de ameaça, Vetores de ataque, Engenharia social, Malware, Vulnerabilidades Web, Ataques de rede, Indicadores de Comprometimento (IoCs), Hardening, Segmentação de rede e Gestão de vulnerabilidades.

**Aprendizado:** Solicitar um limite de tópicos ajuda a criar materiais de revisão mais eficientes.

---

### Prompt 3

**Objetivo:** Simular questões da certificação Security+.

**Prompt Utilizado:**
```text
Crie 10 questões no estilo CompTIA Security+ com gabarito comentado.
```

**Resultado Obtido:**

O NotebookLM gerou questões abordando: Controles de Segurança, Cloud Security, Forense Digital, EAP-TLS, Engenharia Social, Continuidade de Negócios, Criptografia, Descarte seguro de mídia, SIEM e SOAR.

**Validação das Questões:**

Após análise manual, algumas questões apresentaram possíveis ambiguidades:

| Questão | Observação |
|----------|------------|
| Questão 3 | Ordem de volatilidade pode gerar interpretações diferentes. |
| Questão 4 | Responsabilidade compartilhada em SaaS poderia ser mais específica. |
| Questão 9 | Secure Erase também poderia ser considerado dependendo do cenário. |
| Questão 10 | O cenário mistura características de SIEM e SOAR. |

**Aprendizado:** A IA produziu questões relevantes, porém a validação humana continua essencial para garantir aderência ao exame oficial.

---

### ⚠️ Cicatrizes e Troubleshooting

**Problema:** Respostas excessivamente longas.
**Solução:** Solicitar:
```text
Resuma em até 10 tópicos.
```

**Problema:** Respostas muito técnicas.
**Solução:** Solicitar:
```text
Explique como se eu estivesse estudando para a prova CompTIA Security+.
```

**Problema:** Diferenças entre as fontes utilizadas.
**Solução:** Solicitar:
```text
Compare as informações apresentadas pelas fontes e destaque divergências.
```

**Aprendizado Geral:** O NotebookLM demonstrou excelente capacidade para consolidar informações provenientes de múltiplas fontes. Entretanto, a revisão manual continua sendo necessária para validar conceitos, identificar ambiguidades e garantir aderência ao conteúdo cobrado pela certificação CompTIA Security+.

---

## 📘 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

**Domínio: General Security Concepts**
- Tríade CIA: Confidencialidade, Integridade e Disponibilidade como base de qualquer controle de segurança.
- Controles de segurança classificados por categoria (técnico, gerencial, operacional, físico) e por tipo (preventivo, detectivo, corretivo, dissuasório, compensatório, diretivo).
- Conceitos de AAA (Authentication, Authorization, Accounting) e Zero Trust.

**Domínio: Threats, Vulnerabilities and Mitigations**
- Atores de ameaça (nation-state, hacktivista, insider, script kiddie) e suas motivações.
- Vetores de ataque comuns: phishing, engenharia social, dispositivos removíveis, cadeia de suprimentos.
- Tipos de malware (ransomware, spyware, worms, rootkits) e indicadores de comprometimento (IoCs).
- Estratégias de mitigação: hardening, segmentação de rede, gestão de patches e vulnerabilidades.

**Domínio: Security Architecture**
- Arquiteturas de rede seguras (segmentação, zero trust, SASE).
- Segurança em nuvem: modelo de responsabilidade compartilhada entre provedor e cliente.
- Resiliência e recuperação: backups, alta disponibilidade, planos de continuidade de negócios (BCP) e recuperação de desastres (DRP).

**Domínio: Security Operations**
- Hardening de sistemas, gestão segura de configuração e descarte de mídia.
- Monitoramento com SIEM (coleta e correlação de logs) e automação com SOAR (resposta orquestrada a incidentes).
- Resposta a incidentes: identificação, contenção, erradicação, recuperação e lições aprendidas.
- Forense digital: ordem de volatilidade na coleta de evidências.

**Domínio: Security Program Management and Oversight**
- Governança, políticas e conformidade regulatória.
- Gestão de risco: identificação, análise, tratamento e monitoramento contínuo.
- Treinamento e conscientização de usuários como controle de mitigação de engenharia social.

### 2. Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **CIA Triad** | Modelo que resume os objetivos da segurança da informação: Confidencialidade, Integridade e Disponibilidade. |
| **MFA (Multi-Factor Authentication)** | Autenticação que exige dois ou mais fatores independentes (algo que você sabe, tem ou é). |
| **IoC (Indicator of Compromise)** | Evidência técnica de que um sistema pode ter sido comprometido (ex: hash de arquivo malicioso, IP suspeito). |
| **Hardening** | Conjunto de práticas para reduzir a superfície de ataque de um sistema (desativar serviços desnecessários, aplicar patches, etc.). |
| **SIEM (Security Information and Event Management)** | Ferramenta que coleta, correlaciona e analisa logs de segurança de múltiplas fontes. |
| **SOAR (Security Orchestration, Automation and Response)** | Plataforma que automatiza e orquestra respostas a incidentes de segurança. |
| **Zero Trust** | Modelo de segurança que não confia implicitamente em nenhum usuário ou dispositivo, exigindo verificação contínua. |
| **Responsabilidade Compartilhada (Shared Responsibility)** | Modelo em nuvem onde a segurança é dividida entre o provedor (infraestrutura) e o cliente (dados, configurações, acessos). |
| **Ordem de Volatilidade** | Sequência de coleta de evidências forenses, da mais volátil (memória RAM) à menos volátil (backups em disco). |
| **BCP / DRP** | Planos de Continuidade de Negócios e de Recuperação de Desastres, respectivamente, para manter ou restaurar operações após um incidente. |
| **Engenharia Social** | Técnicas de manipulação psicológica para induzir pessoas a revelar informações ou executar ações inseguras (ex: phishing, pretexting). |

### 3. Prompts Reutilizáveis para Revisão Futura

```text
1. Explique [conceito] utilizando exemplos do mundo corporativo.

2. Resuma o domínio [nome do domínio] em até 10 tópicos.

3. Crie 10 questões no estilo CompTIA Security+ sobre [domínio/tema] com gabarito comentado.

4. Compare as informações apresentadas pelas fontes e destaque divergências sobre [tema].

5. Explique [conceito técnico] como se eu estivesse estudando para a prova CompTIA Security+.

6. Monte um glossário com os 10 termos mais importantes do domínio [nome do domínio].

7. Quais são as pegadinhas mais comuns da certificação Security+ sobre [tema]?

8. Crie um quadro comparativo entre [conceito A] e [conceito B].
```

---

## 🎓 Conclusão

O NotebookLM mostrou-se uma ferramenta eficiente para consolidar conteúdos da certificação CompTIA Security+, permitindo centralizar materiais, gerar resumos, criar simulados e acelerar revisões. A utilização de técnicas de engenharia de prompts contribuiu para obter respostas mais precisas e alinhadas aos objetivos de estudo da certificação.

---

## 🎥 Materiais Complementares

Videoaulas para auxiliar nos estudos para a certificação CompTIA Security+ (SY0-701):

### Professor Messer - CompTIA Security+ SY0-701 Training Course
Canal amplamente reconhecido pela comunidade de Segurança da Informação, oferecendo uma série completa e gratuita cobrindo todos os domínios da certificação Security+.
🔗 [Curso completo SY0-701](https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-training-course/)

### Canal do Professor Messer no YouTube
🔗 [YouTube - Professor Messer](https://www.youtube.com/@professormesser)
