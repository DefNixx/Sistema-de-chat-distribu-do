# 📱 Servidor e Cliente em Python - Sistemas Distribuídos

Este projeto demonstra a implementação de um servidor e clientes que se comunicam através de sockets em Python.

## 📌 Descrição

O objetivo deste projeto é criar um sistema de comunicação entre múltiplos clientes utilizando um servidor central. O servidor recebe mensagens dos clientes e possibilita a troca de mensagens entre eles.

## 🚀 Tecnologias Utilizadas

Python

Sockets

PyCharm (IDE recomendada para execução)

## 📂 Estrutura do Projeto

/PythonProject
│── Aula_Pratica_Nicolas/
│   ├── Servidor.py  # Código do servidor
│   ├── Cliente.py   # Código do cliente
│   └── README.md    # Documentação do projeto

## ⚙️ Instalação e Execução

1️⃣ Instalar o Python e a IDE PyCharm

Certifique-se de ter o Python instalado na sua máquina.

2️⃣ Clonar o repositório

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

3️⃣ Criar um ambiente virtual (opcional, mas recomendado)

python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows

4️⃣ Executar o Servidor

python Servidor.py

5️⃣ Executar os Clientes

Abra novas instâncias do terminal e execute:

python Cliente.py

⚠️ Certifique-se de que sua IDE permite múltiplas instâncias do mesmo arquivo.

📰 Funcionamento

O servidor aguarda conexões dos clientes.

Cada cliente pode enviar mensagens, e o servidor repassa para os demais.

O chat é mantido enquanto o servidor estiver ativo.

📷 Exemplo de Execução

(Adicione aqui uma captura de tela mostrando o chat em funcionamento)

📝 Licença

Este projeto é de código aberto e pode ser usado para fins educacionais.
