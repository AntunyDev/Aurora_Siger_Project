# 🚀 Aurora Siger

Sistema de telemetria para verificação de pré-decolagem de espaçonaves.

---

## 🛰️ Descrição do Projeto

O **Aurora Siger** é um sistema de simulação de telemetria que realiza a análise completa das condições operacionais de uma espaçonave antes da decolagem.

O sistema avalia dados críticos em tempo real e determina, com base em critérios de segurança, se o lançamento pode ser autorizado ou deve ser abortado.

---

## ⚙️ Funcionalidades

- 📡 Leitura de dados de telemetria
- 🔋 Análise energética com cálculo de autonomia
- 🌡️ Monitoramento térmico (interno e externo)
- ⛽ Verificação de pressão dos tanques
- 🧠 Análise assistida por Inteligência Artificial
- 🚦 Sistema de decisão automática de lançamento

---

## 📊 Parâmetros Monitorados

| Sistema | Critério |
|--------|--------|
| 🌡️ Temperatura Interna | 15°C a 35°C |
| 🌡️ Temperatura Externa | -50°C a 60°C |
| 🔋 Energia | ≥ 80% |
| ⛽ Pressão dos Tanques | 120 a 150 bar |
| 🏗️ Integridade Estrutural | Ativo (1) |
| 🧩 Módulos Críticos | Ativo (OK) |

---

## 🧪 Verificação de Segurança

```text
[✔] Temperatura interna dentro do limite
[✔] Temperatura externa dentro do limite
[✔] Estrutura íntegra
[✔] Pressão dos tanques adequada
[✔] Módulos críticos operacionais
 ```
---

## ▶️ Como Executar

O projeto foi desenvolvido utilizando o **Google Colab** em formato de notebook interativo.

Para executar o código:

1. Abra o notebook no Google Colab  
2. No menu superior, clique em **"Executar tudo"**  
3. Insira os dados solicitados pelo sistema conforme indicado  

O sistema irá processar alguns inputs e depois automaticamente as informações, após isso vai exibir o **relatório de pré-decolagem** com a decisão final.

---
