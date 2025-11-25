# Simulação de Ataques de Brute Force

Este repositório contém uma simulação prática de ataques de força bruta realizada em um ambiente controlado de laboratório. O objetivo foi compreender na prática como funcionam ataques de autenticação contra serviços e formulários vulneráveis, utilizando ferramentas amplamente utilizadas em testes de segurança.

---

## 📌 Ataques Simulados

### 🔹 1. Brute Force em Serviço FTP
Foi realizada uma simulação de ataque de força bruta contra um serviço **FTP** utilizando listas de usuários e senhas fracas.  
O objetivo era demonstrar como serviços com credenciais fracas podem ser facilmente comprometidos.

### 🔹 2. Brute Force em Formulário Web (DVWA)
Também foi feito um ataque contra o módulo **“Brute Force”** do DVWA (Damn Vulnerable Web Application).  
O ataque foi automatizado utilizando ferramentas projetadas para testar autenticação em aplicações web.

---

## 🛠️ Ferramentas Utilizadas

- **Hydra** – Ataques de brute force em serviços como FTP.  
- **Medusa** – Ferramenta rápida para ataques a serviços de rede.  
- **Wordlists e Passwordlists** – Listas de senhas e usuários para realizar os testes.  
- **DVWA** – Aplicação web propositalmente vulnerável usada para fins de estudo.

---

## 📂 Estrutura do Repositório

│ README.md
│ wordlist.txt
│ usuários.txt
│ outras_wordlists...
│
└── image/

A pasta **/image** contém prints das simulações e resultados dos ataques realizados.

---

## ▶️ Como foi realizado

1. Configuração do ambiente de laboratório com:
   - Máquina atacante (Kali Linux)
   - Máquina vítima com FTP vulnerável (Metasploitable2)
   - DVWA configurado em modo Low Security

2. Utilização das ferramentas Hydra e Medusa apontando para serviços e formulários vulneráveis.

3. Execução dos ataques de brute force usando diferentes wordlists para validar credenciais fracas.

---

## 📝 Objetivo Educacional

Este projeto tem finalidade **totalmente educacional** e foi realizado exclusivamente em **ambiente controlado** para aprendizado em segurança ofensiva.  
Não deve ser utilizado contra sistemas reais sem autorização.

---

## 📷 Capturas de Tela

As capturas dos testes realizados estão disponíveis na pasta **/image** deste repositório.
