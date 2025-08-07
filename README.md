# 📄 Análise de Alerta de Phishing Seguindo um Playbook
*(Scroll down for English version)*

Este projeto demonstra o fluxo de trabalho de um Analista de Segurança Nível 1 (SOC) ao responder a um alerta de phishing. O objetivo é aplicar um **playbook** predefinido para garantir uma resposta estruturada, consistente e eficaz, culminando na documentação e escalonamento adequado do incidente.

*Esta atividade foi realizada como parte do [Certificado Profissional de Cibersegurança do Google](https://www.coursera.org/professional-certificates/google-cybersecurity) (Curso 6, Módulo 3).*

---

## 🎯 Cenário (Scenario)
Como Analista de SOC Nível 1, um alerta foi gerado indicando que um funcionário baixou e executou um anexo de e-mail malicioso. Uma análise prévia já confirmou que o hash SHA256 do arquivo é malicioso. Minha tarefa é seguir o "Playbook de Resposta a Phishing" da organização para avaliar, documentar e determinar os próximos passos.

## 🛠️ Ferramentas e Processos
* **Playbook de Resposta a Phishing**: Documento com o fluxograma e os procedimentos passo a passo para este tipo de incidente.
* **Ticket de Alerta**: O documento central para registrar o status e as observações da investigação.
* **Diário do Tratador de Incidentes**: Usado para anotações detalhadas durante a análise.

## 🕵️‍♂️ Execução do Playbook
<img width="602" height="816" alt="image" src="https://github.com/user-attachments/assets/1d5963e9-e373-4f84-85a1-18f28c498171" />


### Passo 1: Avaliação do Alerta (Os 5 Ws)
A primeira etapa, conforme o playbook, foi avaliar o alerta para entender a natureza do incidente. As seguintes informações foram estabelecidas com base no cenário:

* **Who (Quem)?** Um funcionário da empresa.
* **What (O quê)?** Execução de um anexo de e-mail malicioso (planilha com senha) que criou novos arquivos executáveis no host.
* **When (Quando)?** Quarta-feira, 20 de julho de 2022, 09:30:14
* **Where (Onde)?** No computador do funcionário.
* **Why (Por quê)?** O funcionário foi vítima de um ataque de phishing.

### Passo 2: Ponto de Decisão (Escalonamento)
O playbook continha um ponto de decisão crítico (Passo 3.1): "O anexo/link é malicioso?". Com base na informação do cenário de que o hash do arquivo já havia sido verificado como malicioso, a resposta foi **afirmativa**.

Seguindo o fluxograma do playbook (Passo 3.2), a ação obrigatória para um incidente com malware confirmado é o **escalonamento**.

### Passo 3: Atualização e Conclusão do Ticket
A ação final como analista Nível 1 foi documentar as descobertas e escalonar o ticket para a próxima fila de análise (Nível 2), que ficará responsável pela contenção e erradicação. O ticket foi atualizado com o status **"Escalated"** e com comentários detalhando a análise e a justificativa.

📷 **Captura de Tela - Ticket de Alerta Finalizado:**
<br>
<img width="819" height="498" alt="image" src="https://github.com/user-attachments/assets/15f8d67b-65ae-466a-9798-a1ef34fbd67d" />


## ✅ Conclusão
Este exercício demonstra a importância fundamental de seguir um playbook na resposta a incidentes. A aplicação de um processo definido garantiu que:

* A análise do alerta fosse completa e estruturada.
* A decisão de escalonamento fosse baseada em critérios predefinidos, eliminando a incerteza.
* A documentação final fosse clara, concisa e fornecesse todas as informações necessárias para a próxima equipe dar continuidade à resposta.

Esta abordagem garante uma resposta a incidentes mais rápida, consistente e eficaz, minimizando o impacto para a organização.

---
---

# 📄 Phishing Alert Analysis Using a Playbook (English Version)

This project demonstrates a Security Analyst Level 1 (SOC) workflow when responding to a phishing alert. The objective is to apply a predefined **playbook** to ensure a structured, consistent, and effective response, culminating in the proper documentation and escalation of the incident.

*This activity was completed as part of the [Google Cybersecurity Professional Certificate on Coursera](https://www.coursera.org/professional-certificates/google-cybersecurity) (Course 6, Module 3).*

---

## 🎯 Scenario
As a Level 1 SOC Analyst, an alert was generated indicating that an employee downloaded and executed a malicious email attachment. A prior analysis had already confirmed the file's SHA256 hash as malicious. My task was to follow the organization's "Phishing Response Playbook" to assess, document, and determine the next steps.

## 🛠️ Tools and Processes
* **Phishing Response Playbook**: A document containing the flowchart and step-by-step procedures for this type of incident.
* **Alert Ticket**: The central document for recording the investigation's status and observations.
* **Incident Handler's Journal**: Used for detailed note-taking during the analysis.

## 🕵️‍♂️ Playbook Execution
<img width="602" height="816" alt="image" src="https://github.com/user-attachments/assets/703c7c22-7916-49b0-b00c-11fe52d54adc" />


### Step 1: Alert Evaluation (The 5 Ws)
The first step, according to the playbook, was to evaluate the alert to understand the nature of the incident. The following information was established from the scenario:

* **Who?** A company employee.
* **What?** Execution of a malicious email attachment (password-protected spreadsheet) which created new unauthorized executables on the host.
* **When?** Wednesday, July 20, 2022 09:30:14 AM
* **Where?** On the employee's computer.
* **Why?** The employee fell victim to a phishing attack.

### Step 2: Decision Point (Escalation)
The playbook contained a critical decision point (Step 3.1): "Is the attachment/link malicious?". Based on the scenario information that the file hash was already verified as malicious, the answer was **yes**.

Following the playbook's flowchart (Step 3.2), the mandatory action for an incident with confirmed malware is **escalation**.

### Step 3: Ticket Update and Conclusion
The final action as a Level 1 analyst was to document the findings and escalate the ticket to the next analysis queue (Tier 2), which will be responsible for containment and eradication. The ticket was updated with the status **"Escalated"** and comments detailing the analysis and justification.

📷 **Screenshot - Finalized Alert Ticket:**
<br>
<img width="819" height="498" alt="image" src="https://github.com/user-attachments/assets/fa611624-8299-4cec-9234-14f5b52a1c9e" />


## ✅ Conclusion
This exercise demonstrates the fundamental importance of following a playbook in incident response. Applying a defined process ensured that:

* The alert analysis was complete and structured.
* The escalation decision was based on predefined criteria, eliminating guesswork.
* The final documentation was clear, concise, and provided all necessary information for the next team to continue the response.

This approach guarantees a faster, more consistent, and effective incident response, minimizing the impact on the organization.
