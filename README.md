# Demonstração de Ataques de Phishing com Kali Linux e Setoolkit

Este projeto demonstra como configurar um ataque de phishing usando Kali Linux e Setoolkit para fins educacionais. Ele destaca a importância da segurança digital ao simular técnicas de engenharia social. O objetivo é conscientizar sobre vulnerabilidades e incentivar o uso de boas práticas para proteger informações pessoais e corporativas contra ataques cibernéticos.


---

## 📋 Descrição

Este repositório contém um exemplo prático de configuração de um ataque de phishing usando o **Kali Linux** e a ferramenta **Setoolkit**. O objetivo é demonstrar como ataques de engenharia social podem ocorrer e destacar a importância de medidas preventivas para proteger dados pessoais e corporativos.

---

## 🔧 Ferramentas Utilizadas

- **Kali Linux:** Sistema operacional focado em testes de segurança.
- **Setoolkit (Social-Engineering Toolkit):** Ferramenta para ataques de engenharia social.

---

## 🛠️ Configuração do Phishing no Kali Linux

1. **Acesso como root:**
   ```bash
   sudo su
## Iniciando o Setoolkit:

bash
Copiar código
setoolkit
Selecionando o tipo de ataque:

Escolha a opção: Social-Engineering Attacks.
Definindo o vetor de ataque:

Opção: Web Site Attack Vectors.
Método de ataque:

Escolha: Credential Harvester Attack Method.
Clonando a página:

Use a opção: Site Cloner.
URL alvo: http://www.facebook.com.
Obtendo o IP da máquina:

Comando:
bash
Copiar código
ifconfig


POSSIBLE USERNAME FIELD FOUND: email=***@gmail.com
POSSIBLE PASSWORD FIELD FOUND: pass=passwd123
