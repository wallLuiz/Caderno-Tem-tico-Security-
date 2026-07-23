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

📚 (https://notebooklm.google.com/notebook/134f4c62-8e9e-477c-bb6c-d67f3a5c2582)

> Acesso disponível apenas para visualização.

# 📖 Curadoria de Fontes

As seguintes fontes foram carregadas no NotebookLM para análise e geração de conteúdo:

### Fonte 1 - Guia Oficial CompTIA Security+

* PDF oficial da certificação Security+ (SY0-701)
https://assets.ctfassets.net/82ripq7fjls2/6TYWUym0Nudqa8nGEnegjG/0f9b974d3b1837fe85ab8e6553f4d623/CompTIA-Security-Plus-SY0-701-Exam-Objectives.pdf

### Fonte 2 - Anotações da Comunidade

* Link do GitHub 1: [[INSERIR LINK](https://github.com/daniellaurin/security-plus-701-study-guide)]

### Fonte 3 - Anotações da Comunidade

* Link do GitHub 2: [[INSERIR LINK](https://github.com/heraclescap/comptia-secplus-sy0-701-notes)]

---

# 🤖 Engenharia de Prompts

## Prompt 1

### Objetivo
Compreender a Tríade CIA utilizando exemplos corporativos.

### Prompt Utilizado

```text
Explique o conceito de CIA Triad utilizando exemplos do mundo corporativo.
```

### Resultado Obtido

O NotebookLM explicou os três pilares da Segurança da Informação:

- **Confidencialidade:** proteção contra acesso não autorizado.
- **Integridade:** garantia de que os dados não sejam alterados indevidamente.
- **Disponibilidade:** garantia de acesso aos sistemas quando necessário.

Também apresentou exemplos corporativos utilizando:

- MFA
- Criptografia
- Assinaturas Digitais
- Backups
- Balanceamento de carga

### Aprendizado

Prompts contextualizados geram respostas mais próximas da realidade profissional.

---

## Prompt 2

### Objetivo
Criar um resumo rápido para revisão.

### Prompt Utilizado

```text
Resuma o domínio Threats, Vulnerabilities and Mitigations em até 10 tópicos.
```

### Resultado Obtido

O NotebookLM resumiu os principais conceitos:

- Atores de ameaça
- Vetores de ataque
- Engenharia social
- Malware
- Vulnerabilidades Web
- Ataques de rede
- Indicadores de Comprometimento (IoCs)
- Hardening
- Segmentação de rede
- Gestão de vulnerabilidades

### Aprendizado

Solicitar um limite de tópicos ajuda a criar materiais de revisão mais eficientes.

---

## Prompt 3

### Objetivo
Simular questões da certificação Security+.

### Prompt Utilizado

```text
Crie 10 questões no estilo CompTIA Security+ com gabarito comentado.
```

### Resultado Obtido

O NotebookLM gerou questões abordando:

- Controles de Segurança
- Cloud Security
- Forense Digital
- EAP-TLS
- Engenharia Social
- Continuidade de Negócios
- Criptografia
- Descarte seguro de mídia
- SIEM e SOAR

### Validação das Questões

Após análise manual, algumas questões apresentaram possíveis ambiguidades:

| Questão | Observação |
|----------|------------|
| Questão 3 | Ordem de volatilidade pode gerar interpretações diferentes. |
| Questão 4 | Responsabilidade compartilhada em SaaS poderia ser mais específica. |
| Questão 9 | Secure Erase também poderia ser considerado dependendo do cenário. |
| Questão 10 | O cenário mistura características de SIEM e SOAR. |

### Aprendizado

A IA produziu questões relevantes, porém a validação humana continua essencial para garantir aderência ao exame oficial.

---

# ⚠️ Cicatrizes e Troubleshooting

## Problema

Respostas excessivamente longas.

### Solução

Solicitar:

```text
Resuma em até 10 tópicos.
```

---

## Problema

Respostas muito técnicas.

### Solução

Solicitar:

```text
Explique como se eu estivesse estudando para a prova CompTIA Security+.
```

---

## Problema

Diferenças entre as fontes utilizadas.

### Solução

Solicitar:

```text
Compare as informações apresentadas pelas fontes e destaque divergências.
```

### Aprendizado Geral

O NotebookLM demonstrou excelente capacidade para consolidar informações provenientes de múltiplas fontes. Entretanto, a revisão manual continua sendo necessária para validar conceitos, identificar ambiguidades e garantir aderência ao conteúdo cobrado pela certificação CompTIA Security+.


# 🎓 Conclusão

O NotebookLM mostrou-se uma ferramenta eficiente para consolidar conteúdos da certificação CompTIA Security+, permitindo centralizar materiais, gerar resumos, criar simulados e acelerar revisões. A utilização de técnicas de engenharia de prompts contribuiu para obter respostas mais precisas e alinhadas aos objetivos de estudo da certificação.

# 🎥 Materiais Complementares

Videoaulas para auxiliar nos estudos para a certificação CompTIA Security+ (SY0-701):

### Professor Messer - CompTIA Security+ SY0-701 Training Course

Canal amplamente reconhecido pela comunidade de Segurança da Informação, oferecendo uma série completa e gratuita cobrindo todos os domínios da certificação Security+.

🔗 https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-training-course/

### Canal do Professor Messer no YouTube

🔗 https://www.youtube.com/@professormesser
