# 🛡️ Cisco CyberOps Associate - Professional Portfolio
### Network Security Analysis | Incident Response | SOC Operations

Este repositório centraliza a documentação técnica e as evidências práticas dos laboratórios realizados durante a formação **Cisco CyberOps Associate**. O foco deste portfólio é demonstrar competências em análise de tráfego de rede, monitoramento de segurança e resposta a incidentes.

---

## 📈 Status do Programa
- **Módulos Concluídos:** 1 / 28 
- **Previsão de Conclusão:** 20 de julho
- **Objetivo Atual:** Monitoramento de Redes e Protocolos.

---

## 🛠️ Laboratórios em Destaque

### 1. Análise de Quadros Ethernet II com Wireshark (Lab 8.2.8)
Este laboratório consistiu na análise profunda do encapsulamento de dados na Camada 2 e sua relação com a Camada 3 do modelo OSI.

* **Ferramentas Utilizadas:** Wireshark, Mininet (CyberOps Workstation VM).
* **Atividades Realizadas:**
    * Mapeamento de endereços MAC e IP em topologia simulada.
    * Captura e inspeção de pacotes **ICMP** (Ping) e **ARP**.
    * Análise de cabeçalhos Ethernet II (Preâmbulo, Destino, Origem, Tipo e FCS).
* **Resultados Técnicos:**
    * Identificação do processo de transmissão local vs. remota.
    * Comprovação do conceito de entrega *hop-by-hop*: observou-se que o IP de destino permanece constante, enquanto o MAC de destino é alterado para o do Gateway (Default Gateway) ao sair da rede local.

---

## 📂 Estrutura do Repositório

O conteúdo está organizado por domínios de conhecimento para facilitar a auditoria técnica:

* 📁 `networking-analysis/`: Capturas de tráfego, análise de protocolos (TCP/UDP, ICMP, ARP) e relatórios de Wireshark.
* 📁 `endpoint-security/`: Gerenciamento de segurança em Linux e Windows, análise de permissões e hardening.
* 📁 `siem-operations/`: Projetos de centralização de logs (**Elasticsearch & Kibana** - Em progresso).
* 📁 `incident-response/`: Documentação de detecção de intrusão e playbooks.

---

## 🛠️ Stack Tecnológica & Ferramentas
* **Análise de Pacotes:** Wireshark, Tcpdump.
* **Sistemas Operacionais:** Linux (CLI e Administração de Servidores), Windows.
* **Monitoramento:** Elasticsearch, Kibana, Snort (IDS).
* **Simulação:** Mininet, Cisco Packet Tracer.

---

## 🎯 Objetivo Profissional
Como um aspirante a **Analista de Segurança Júnior**, mantenho uma rotina de estudos focada em consistência e documentação técnica precisa. Este repositório serve como prova de conceito para minha capacidade de operar ferramentas de padrão industrial e analisar eventos de segurança com rigor técnico.

---
*Documentação mantida e atualizada regularmente por narutoxdo(ronan bruno)*
