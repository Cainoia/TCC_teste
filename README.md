# Gêmeo Digital Didático - TCC

## Utilizar WSL para fins didáticos

## Descrição
Este projeto implementa um Gêmeo Digital modular para fins didáticos, demonstrando os conceitos de:
- Camada Física (webcam)
- Camada de Percepção (YOLOv8)
- Camada de Integração (MQTT)
- Gêmeo Digital (Flask Dashboard)
- Camada de Analítica (Gráficos e KPIs)

## Requisitos
- Python 3.9 ou superior
- Mosquitto (broker MQTT)
- Webcam

## Instalação

1. Clone o repositório:

git clone [seu-repositorio]
cd gemeo_digital_tcc

## Criar e ativar o ambiente virtual:

python -m venv venv

venv\Scripts\activate     # Windows

## Instalar as dependências 

pip install -r requirements.txt

## Instalar e iniciar o MQTT (Mosquito)

