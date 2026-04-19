# Gestor Térmico Bioclimático IoT - IFCE

Projeto de Eficiência Energética utilizando ESP32 para gestão ativa de carga térmica (Free Cooling).

## 📋 Sobre o Projeto
Este sistema monitora a temperatura interna e externa de um ambiente para decidir, de forma autônoma, entre o uso de climatização artificial (Ar-condicionado) ou ventilação natural. 

**Objetivo:** Reduzir o consumo elétrico em até 30% através da automação inteligente.

## 🚀 Funcionalidades
- **Web Server Nativo:** Dashboard acessível via IP na rede local (Edge Computing).
- **Lógica de Free Cooling:** Acionamento de exaustores baseado em diferencial de temperatura ($\Delta T$).
- **Segurança Higrométrica:** Bloqueio de entrada de ar caso a umidade externa seja > 70%.
- **Interface Física:** Feedback visual via LCD 16x2 e LED RGB.

## 🛠️ Hardware Utilizado
- ESP32 DevKit V1
- 2x Sensores DHT22
- Display LCD 16x2 com I2C
- Módulo Relé + Contatora de Potência
- LED RGB

## 💻 Como usar
1. Clone este repositório.
2. Abra o código na Arduino IDE.
3. Altere as credenciais de Wi-Fi no código.
4. Faça o upload para o ESP32.
5. Acesse o IP exibido no LCD através do seu navegador.

---
*Desenvolvido para a disciplina de Sustentabilidade e Eficiência Energética - IFCE CAMPUS AVANÇADO DO PECÉM.*
