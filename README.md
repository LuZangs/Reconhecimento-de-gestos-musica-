🎵 Controle de Música por Gestos (Python + OpenCV)

Este projeto permite controlar a música do computador usando gestos da mão, capturados pela webcam, aplicando conceitos de Visão Computacional e Interação Humano–Computador.

🚀 Funcionalidades

Detecta a mão em tempo real usando a webcam

Identifica o movimento horizontal do dedo indicador

▶️ Gesto para a direita → próxima música

⏮️ Gesto para a esquerda → música anterior

Sistema de cooldown para evitar múltiplos comandos seguidos

🧠 Conceitos aplicados

Detecção e rastreamento de mãos

Análise de movimento entre frames

Uso de limiar (threshold) para evitar falsos positivos

Controle de tempo para estabilizar ações

🛠️ Tecnologias utilizadas

Python

OpenCV

MediaPipe Hands

PyAutoGUI

📦 Instalação

Instale as dependências com:

pip install opencv-python mediapipe pyautogui

▶️ Como executar:

python main.py

📷 Como funciona

O sistema acompanha a posição X do dedo indicador.
Quando o deslocamento ultrapassa um valor mínimo (limiar), o gesto é interpretado como um comando para trocar a música.

📚 Objetivo do projeto

Este projeto foi desenvolvido com foco em aprendizado, buscando compreender a lógica por trás da Visão Computacional, e não apenas obter um resultado funcional.
