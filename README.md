🔧 Supervisório Industrial com Python e Tkinter

Este projeto consiste em um supervisório industrial desenvolvido em Python utilizando a biblioteca Tkinter. Ele simula o controle de três motores elétricos, permitindo ligar e desligar cada um deles individualmente, além de exibir uma animação indicando a rotação dos motores.

🚀 Funcionalidades

Interface gráfica intuitiva

Controle de três motores com botões Liga/Desliga

Animação representando a rotação dos motores

Indicação visual do estado de cada motor (LED virtual)

Fundo personalizado para melhor visualização

📸 Capturas de Tela

(Adicione imagens/gifs aqui mostrando o funcionamento do sistema!)

🛠 Tecnologias Utilizadas

Python 3

Tkinter (interface gráfica)

PIL (Pillow) (para manipulação de imagens, se necessário)

📂 Estrutura do Projeto

📂 supervisorio_motores
├── 📄 main.py         # Arquivo principal do supervisório
├── 📂 assets         # Pasta para imagens e icones (se houver)
├── 📜 README.md      # Documentação do projeto

🏗️ Como Executar o Projeto

1️⃣ Clonar o Repositório

git clone https://github.com/seuusuario/supervisorio_motores.git
cd supervisorio_motores

2️⃣ Criar e Ativar o Ambiente Virtual (Opcional)

python -m venv venv
# Ativar ambiente virtual
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate

3️⃣ Instalar Dependências (Se Necessário)

O Tkinter já vem embutido no Python, mas se utilizar bibliotecas extras, instale-as com:

pip install pillow

4️⃣ Executar o Sistema

python main.py

📌 Melhorias Futuras

🔹 Adicionar monitoramento de temperatura

🔹 Implementar histórico de eventos

🔹 Criar uma versão com comunicação MQTT para IoT
