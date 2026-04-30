# 🛡️ Cisco Ethical Hacker - Jornada de Estudos e Laboratórios

![Cisco](https://img.shields.io/badge/Cisco-Course-049fd9?style=for-the-badge&logo=cisco&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Ethical%20Hacking-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Andamento-success?style=for-the-badge)

Bem-vindo ao meu repositório de estudos do curso **Ethical Hacker da Cisco**. 
Este espaço foi criado para documentar meu progresso, anotações teóricas e, principalmente, os **Write-ups dos laboratórios práticos** realizados durante as 10 sessões do curso. O foco principal aqui é a aplicação prática de técnicas de segurança ofensiva (Red Team) e a compreensão de como defender infraestruturas contra essas ameaças (Blue Team/SOC).

## 🎯 Objetivo do Repositório
* Consolidar o conhecimento adquirido em cada módulo do curso.
* Criar um acervo rápido de consultas de comandos (Cheat Sheets) para ferramentas de terminal Linux.
* Documentar a metodologia de Penetration Testing, desde a fase de Reconhecimento até a Exploração.

---

## 📚 Estrutura do Curso (As 10 Sessões)

Navegue pelas pastas abaixo para ver as anotações e laboratórios detalhados de cada sessão:

- [x] **[Sessão 1: Introdução ao Ethical Hacking](./Sessao_01)**
  - Conceitos de Red Team, Blue Team, e a ética profissional (Regras de Engajamento).
- [ ] **[Sessão 2: Reconhecimento Passivo (Footprinting)](./Sessao_02)**
  - OSINT, Google Dorking (GHDB), Transparência de Certificados (crt.sh), WHOIS e consultas DNS (`dig`, `dnsrecon`).
- [ ] **[Sessão 3: Reconhecimento Ativo (Scanning e Enumeração)](./Sessao_03)**
  - Varreduras com Nmap (TCP Connect, SYN Scans), Host Sweep e identificação de superfície de ataque.
- [ ] **[Sessão 4: Engenharia Social](./Sessao_04)**
  - Técnicas de Elicitação, Pretexting, Phishing e Pharming. Análise de vazamentos (Data Dumps) com ferramentas como `h8mail`.
- [ ] **[Sessão 5: Análise de Vulnerabilidades](./Sessao_05)**
  - Mapeamento de falhas criptográficas (Certificados SSL/TLS fracas), CVEs e varreduras automatizadas.
- [ ] **[Sessão 6: Exploração de Sistemas (System Hacking)](./Sessao_06)**
  - Quebra de senhas, escalonamento de privilégios e manutenção de acesso.
- [ ] **[Sessão 7: Ameaças de Malware e Sniffing](./Sessao_07)**
  - Análise de tráfego de rede (Wireshark/tcpdump), MitM e comportamento de artefatos maliciosos.
- [ ] **[Sessão 8: Ataques a Aplicações Web e Bancos de Dados](./Sessao_08)**
  - OWASP Top 10, SQL Injection, XSS e Session Hijacking.
- [ ] **[Sessão 9: Segurança e Ataques em Redes Sem Fio](./Sessao_09)**
  - Auditoria de protocolos Wireless e quebra de chaves WPA/WPA2.
- [ ] **[Sessão 10: Evasão, Pós-Exploração e Relatórios](./Sessao_10)**
  - Apagando rastros (Covering Tracks) e estruturação do relatório final de Pentest para os stakeholders.

*(Nota: Os links acima apontam para as pastas internas deste repositório onde os Write-ups estão armazenados).*

---

## 🛠️ Ferramentas e Tecnologias Utilizadas no Lab

Durante os estudos, utilizo um ambiente controlado (Kali Linux / Parrot OS) e as seguintes ferramentas:

* **Reconhecimento & OSINT:** `dnsrecon`, `whois`, `dig`, `h8mail`, Shodan, Google Dorks.
* **Scanning & Enumeração:** `nmap` (incluindo NSE scripts), `fping`, `openssl`.
* **Análise de Rede:** Wireshark, tcpdump.
* **Sistemas Operacionais:** Linux (Foco em administração e linha de comando) e Windows Server.

---

## 📝 Exemplo de Write-up (Padrão Utilizado)

Dentro de cada pasta de laboratório, você encontrará a documentação estruturada da seguinte forma:
1. **Cenário:** O objetivo do lab (Ex: Mapear subdomínios de um alvo).
2. **Execução:** Os comandos exatos utilizados no terminal.
3. **Análise de Resultados (SOC View):** O que o atacante descobriu e como a equipe de defesa (Blue Team) detectaria esse ataque nos logs (SIEM/Firewall).

---

## 👨‍💻 Autor

**Bruno Ronan Alves de Moraes**  
*Cybersecurity / SOC Analyst*

Estudante de Cibersegurança focado em operações defensivas, infraestrutura de redes e sistemas Linux. Acredito que dominar as técnicas de ataque é o primeiro passo para construir defesas eficientes.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/SEU_LINKEDIN_AQUI)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github)](https://github.com/SEU_GITHUB_AQUI)

---
*Aviso: Todas as ferramentas e técnicas documentadas neste repositório foram utilizadas em ambientes de laboratório isolados (como Hack The Box, TryHackMe e laboratórios virtuais da Cisco). Este repositório tem fins estritamente educacionais.*
