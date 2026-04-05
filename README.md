# 🔐 Simulação de Malware com Python (Ransomware + Keylogger)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de **compreender, na prática, o funcionamento de malwares**, especificamente:

- Ransomware (sequestro de dados)
- Keylogger (captura de teclas)

⚠️ **Importante:**  
Todos os testes foram realizados em ambiente controlado e com fins exclusivamente educacionais.

---

## 🎯 Objetivo

- Entender como malwares funcionam na prática
- Identificar riscos e vulnerabilidades
- Simular ataques de forma segura
- Estudar estratégias de defesa e prevenção
- Desenvolver habilidades em cibersegurança com Python

---

## 🧠 Conceito de Malware

Malware é qualquer software desenvolvido com intenção maliciosa, como:

- Roubo de dados
- Espionagem
- Interrupção de sistemas
- Extorsão (como no caso de ransomware)

---

# 🔐 Ransomware Simulado

## 📖 O que é?

Ransomware é um tipo de malware que **criptografa arquivos da vítima e exige pagamento (resgate)** para restaurar o acesso.

---

## ⚙️ O que foi implementado

- Criação de arquivos de teste
- Script de criptografia dos arquivos
- Script de descriptografia
- Geração de chave de segurança
- Simulação de mensagem de resgate

---

## 🧪 Funcionamento

1. Os arquivos dentro da pasta `/test_files` são lidos  
2. O conteúdo é transformado (simulação de criptografia)  
3. Os arquivos são sobrescritos  
4. Apenas a chave correta permite recuperar os dados  

---

## 📸 Demonstração

Adicione imagens na pasta `/images` mostrando:

- Antes da execução  
- Depois da criptografia  
- Após a recuperação  

---

## ⚠️ Riscos reais

- Perda total de dados  
- Interrupção de empresas  
- Prejuízo financeiro  
- Vazamento de informações  

---

# ⌨️ Keylogger Simulado

## 📖 O que é?

Keylogger é um tipo de malware que captura tudo o que o usuário digita, como:

- Senhas  
- Dados bancários  
- Informações pessoais  

---

## ⚙️ O que foi implementado

- Captura de teclas digitadas  
- Armazenamento em arquivo `.txt`  
- Execução local controlada  
- Simulação de envio de dados  

---

## 🧪 Funcionamento

1. O script monitora entradas do teclado  
2. Cada tecla é registrada  
3. Os dados são armazenados em `logs.txt`  
4. Pode-se simular envio dessas informações  

---

## ⚠️ Riscos reais

- Roubo de contas  
- Vazamento de dados sensíveis  
- Fraudes financeiras  

---

# 🛡️ Defesa e Prevenção

## 🔐 Boas práticas de segurança

- Utilizar antivírus atualizado  
- Manter sistema operacional atualizado  
- Evitar downloads de fontes desconhecidas  
- Não clicar em links suspeitos  
- Utilizar autenticação em dois fatores (2FA)  

---

## 🧠 Engenharia social

Grande parte dos ataques ocorre por erro humano:

- Phishing (e-mails falsos)  
- Links maliciosos  
- Arquivos infectados  

---

## 🧪 Técnicas de proteção

- Sandboxing (ambiente isolado)  
- Monitoramento de processos  
- Análise de comportamento  
- Firewalls  

---

# 📂 Estrutura do Projeto
malware-simulation-python/
├── ransomware/
│ ├── encrypt.py
│ ├── decrypt.py
│ ├── key.key
│ ├── test_files/
│
├── keylogger/
│ ├── keylogger.py
│ ├── logs.txt
│
├── images/
├── README.md
├── requirements.txt


---

# 🚀 Tecnologias Utilizadas

- Python  
- Manipulação de arquivos  
- Conceitos de criptografia  
- Captura de eventos de teclado  

---

# 📈 Aprendizados

Durante este projeto, foi possível:

- Entender como malwares operam internamente  
- Compreender riscos reais de segurança digital  
- Aprender práticas de defesa e prevenção  
- Desenvolver pensamento crítico em cibersegurança  

---

# ⚠️ Aviso Legal

Este projeto foi desenvolvido apenas para fins educacionais.  
Não deve ser utilizado para atividades maliciosas ou ilegais.

---

# 👨‍💻 Autor

Herbet dos Santos Silva

---

# 📌 Conclusão

Compreender como ataques funcionam é essencial para construir sistemas mais seguros.  
A cibersegurança não é apenas técnica, mas também comportamental.
