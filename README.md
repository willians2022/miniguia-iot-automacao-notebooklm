# 🚀 Miniguia de Estudos — IoT na Automação Industrial com NotebookLM

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Tema](https://img.shields.io/badge/tema-IoT%20%7C%20Automação%20Industrial-blue)
![Ferramenta](https://img.shields.io/badge/IA-NotebookLM-orange)

## 📌 Sobre o projeto

Este projeto foi desenvolvido para o desafio **“Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM”**, da DIO.

O objetivo é utilizar a Inteligência Artificial como uma ferramenta de **aprendizagem ativa**, combinando curadoria de fontes, engenharia de prompts, análise crítica e organização do conhecimento.

### Tema escolhido

**IoT na Automação Industrial: sensores, ESP32, MQTT e monitoramento inteligente**

O tema foi escolhido por sua relação com tecnologias de eletrônica, automação, sistemas embarcados e Indústria 4.0.

---

## 🎯 Objetivos

- Compreender os fundamentos da Internet das Coisas (IoT).
- Entender o papel do ESP32 em sistemas conectados.
- Estudar o protocolo MQTT e o modelo publish/subscribe.
- Relacionar sensores, microcontroladores, comunicação e aplicações industriais.
- Identificar aspectos básicos de segurança em dispositivos IoT.
- Utilizar o NotebookLM para transformar fontes técnicas em material de estudo.
- Criar prompts reutilizáveis para revisão e aprofundamento.

---

## 📚 1. Curadoria de fontes

Foram selecionadas fontes abertas e preferencialmente institucionais:

| # | Fonte | Utilização |
|---|---|---|
| 1 | Espressif — ESP32 Product Overview | Arquitetura, conectividade e aplicações do ESP32 |
| 2 | OASIS — MQTT Version 5.0 | Conceitos e funcionamento do protocolo MQTT |
| 3 | NIST — Internet of Things (IoT) | Fundamentos, confiança e riscos de IoT |
| 4 | NIST — IoT Device Cybersecurity Capability Core Baseline | Segurança de dispositivos IoT |
| 5 | NIST — IoT Cybersecurity Capabilities Catalog | Capacidades técnicas de segurança |

### Links das fontes

- Espressif ESP32: https://docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32/product-overview.html
- OASIS MQTT 5.0: https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html
- NIST IoT: https://www.nist.gov/internet-things-iot
- NISTIR 8259A: https://www.nist.gov/publications/iot-device-cybersecurity-capability-core-baseline
- NIST IoT Cybersecurity Catalog: https://pages.nist.gov/IoT-Device-Cybersecurity-Requirement-Catalogs/

> **Como usar no NotebookLM:** faça o upload das páginas/PDFs disponíveis ou adicione as URLs quando a opção de fonte por link estiver disponível.

---

## 🤖 2. Como o NotebookLM foi utilizado

O notebook foi estruturado para responder perguntas baseadas nas fontes selecionadas.

Fluxo de estudo:

```text
Fontes técnicas
      ↓
NotebookLM
      ↓
Perguntas estratégicas
      ↓
Comparação e refinamento
      ↓
Resumo + glossário
      ↓
Miniguia reutilizável
```

A ideia não foi simplesmente pedir “faça um resumo”, mas utilizar perguntas progressivas para verificar conceitos, comparar tecnologias, identificar limitações e transformar informação em conhecimento aplicável.

---

## 🧠 3. Engenharia de Prompts

### Prompt 1 — Fundamentos

**Pergunta inicial:**

> Explique o conceito de Internet das Coisas (IoT) utilizando exclusivamente as fontes fornecidas. Apresente definição, características, exemplos e aplicações industriais. Cite a fonte utilizada em cada afirmação importante.

**Objetivo:** construir uma visão geral confiável.

### Prompt 2 — ESP32

> Explique o papel do ESP32 em um sistema IoT. Identifique recursos de conectividade, periféricos e aplicações relacionadas à automação industrial presentes nas fontes.

**Objetivo:** relacionar microcontrolador e IoT.

### Prompt 3 — MQTT

> Explique o protocolo MQTT para um estudante de eletrônica. Mostre os conceitos de cliente, servidor/broker, publisher, subscriber, tópico e QoS. Utilize somente as informações presentes na fonte MQTT.

**Objetivo:** compreender a comunicação publish/subscribe.

### Prompt 4 — Comparação

> Compare uma arquitetura IoT baseada em ESP32 + MQTT com uma solução baseada em comunicação HTTP. Considere modelo de comunicação, eficiência, uso em dispositivos com recursos limitados e aplicações de monitoramento.

**Objetivo:** desenvolver pensamento comparativo.

### Prompt 5 — Segurança

> Com base nas fontes do NIST, liste os principais recursos de segurança que devem ser considerados em um dispositivo IoT. Explique por que identificação, configuração, proteção de dados, controle de acesso e atualização de software são importantes.

**Objetivo:** introduzir segurança desde a etapa de projeto.

### Prompt 6 — Aplicação prática

> Proponha uma arquitetura de monitoramento industrial usando ESP32, sensores, MQTT e uma aplicação de supervisão. Descreva o fluxo dos dados desde o sensor até o sistema de visualização e destaque os pontos de segurança.

**Objetivo:** transformar teoria em arquitetura de projeto.

---

## 🔬 4. Testes, variações e “cicatrizes”

### Teste A — Prompt genérico

> Explique IoT.

**Problema:** resposta ampla demais para o objetivo do estudo.

**Melhoria:** especificar público, escopo, fontes e formato.

### Teste B — Prompt contextualizado

> Explique IoT para um estudante de eletrônica interessado em automação industrial, usando apenas as fontes fornecidas.

**Resultado esperado:** resposta mais direcionada e útil.

### Teste C — Prompt com critérios

> Explique MQTT, definindo publisher, subscriber, broker, tópico e QoS. Organize em tabela e cite a fonte utilizada.

**Resultado esperado:** melhor organização e possibilidade de conferência.

### Teste D — Prompt crítico

> Identifique possíveis limitações, ambiguidades ou pontos que não podem ser concluídos diretamente pelas fontes. Não invente informações ausentes.

**Aprendizado:** uma boa utilização da IA exige controle de escopo e verificação das evidências.

---

## 🛠️ 5. Troubleshooting / dificuldades encontradas

### Problema 1 — Respostas muito genéricas

**Causa:** prompt sem contexto.

**Solução:** informar objetivo, público-alvo, fontes e formato da resposta.

### Problema 2 — Mistura de conceitos

**Causa:** perguntar vários assuntos simultaneamente.

**Solução:** dividir a investigação em etapas: IoT → ESP32 → MQTT → segurança → aplicação.

### Problema 3 — Risco de informações não sustentadas

**Causa:** solicitar conhecimentos que não estão nas fontes.

**Solução:** utilizar instruções como:

> “Use somente as fontes fornecidas e indique quando uma informação não estiver disponível.”

### Problema 4 — Resposta difícil de estudar

**Causa:** texto corrido.

**Solução:** pedir tabelas, tópicos, exemplos, perguntas de revisão e glossário.

---

# 📖 6. Miniguia de Estudo

## 6.1 O que é IoT?

Internet das Coisas é um conceito relacionado à conexão de dispositivos físicos capazes de coletar, processar, transmitir ou receber dados por meio de redes.

Em uma aplicação de automação, isso permite conectar sensores e equipamentos a sistemas de monitoramento e análise.

## 6.2 Papel do ESP32

O ESP32 é uma família de sistemas em chip da Espressif que integra conectividade Wi-Fi e Bluetooth, processamento e diversos periféricos. A documentação da Espressif lista aplicações como automação industrial e dispositivos IoT.

Em um projeto, o ESP32 pode atuar como:

- controlador;
- coletor de dados;
- interface com sensores;
- dispositivo conectado à rede;
- cliente MQTT;
- elemento de controle de atuadores.

## 6.3 MQTT

MQTT é um protocolo de mensagens baseado no modelo **publish/subscribe**.

Elementos principais:

- **Publisher:** publica uma mensagem.
- **Subscriber:** recebe mensagens de um tópico assinado.
- **Broker:** intermedeia a comunicação.
- **Topic:** endereço lógico usado para organizar mensagens.
- **Payload:** conteúdo da mensagem.
- **QoS:** nível de garantia de entrega.

Uma arquitetura simplificada:

```text
[SENSOR]
    |
    v
[ESP32]
    |
    | MQTT
    v
[BROKER]
    |
    +-----------> [DASHBOARD]
    |
    +-----------> [BANCO DE DADOS]
```

## 6.4 IoT aplicado à automação

Um exemplo de aplicação:

```text
Sensor de temperatura
        ↓
      ESP32
        ↓
      Wi-Fi
        ↓
      MQTT
        ↓
     Broker
        ↓
Sistema de supervisão
        ↓
Gráfico / Alarme / Histórico
```

O mesmo conceito pode ser expandido para:

- temperatura;
- umidade;
- vibração;
- corrente;
- tensão;
- pressão;
- nível;
- presença;
- estado de máquinas.

## 6.5 Segurança

A conectividade aumenta as possibilidades de monitoramento, mas também cria riscos.

Entre as capacidades de segurança destacadas pelo NIST estão:

- identificação do dispositivo;
- configuração segura;
- proteção de dados;
- controle de acesso às interfaces;
- atualização de software;
- consciência do estado de segurança;
- segurança do dispositivo.

Portanto, segurança deve ser considerada desde a arquitetura do sistema e não apenas depois da instalação.

---

# 📘 7. Glossário

| Termo | Significado |
|---|---|
| IoT | Internet das Coisas |
| ESP32 | Família de SoCs/microcontroladores com conectividade e periféricos |
| MQTT | Protocolo de mensagens publish/subscribe |
| Broker | Servidor que intermedeia mensagens MQTT |
| Publisher | Cliente que publica mensagens |
| Subscriber | Cliente que recebe mensagens |
| Topic | Tópico usado para organizar mensagens MQTT |
| QoS | Quality of Service |
| Sensor | Dispositivo que mede uma grandeza física |
| Atuador | Dispositivo que executa uma ação |
| Telemetria | Coleta e transmissão de dados à distância |
| Gateway | Elemento de comunicação entre redes/sistemas |
| Dashboard | Interface visual para acompanhamento dos dados |
| Indústria 4.0 | Conceito associado à digitalização e integração de processos industriais |
| Cibersegurança | Práticas para proteção de sistemas, dados e dispositivos |

---

# ♻️ 8. Prompts reutilizáveis

### Resumo

> Resuma o conteúdo abaixo em tópicos, mantendo somente as informações essenciais e indicando as fontes.

### Explicação para iniciante

> Explique este conceito como se eu fosse estudante de eletrônica, utilizando uma linguagem simples e um exemplo prático.

### Explicação técnica

> Explique o conceito em nível técnico, incluindo funcionamento, componentes, vantagens, limitações e aplicações.

### Comparação

> Compare A e B em uma tabela considerando funcionamento, vantagens, limitações, custo, complexidade e aplicações.

### Revisão

> Crie 10 perguntas de revisão sobre o conteúdo, começando por questões básicas e terminando com questões de aplicação.

### Quiz

> Crie um quiz de 10 questões de múltipla escolha. Não mostre as respostas inicialmente. Depois apresente o gabarito e explique cada resposta.

### Verificação de evidências

> Responda utilizando somente as fontes fornecidas. Para cada afirmação importante, indique qual fonte sustenta a resposta. Se a informação não estiver nas fontes, diga explicitamente.

### Aplicação prática

> Transforme o conhecimento estudado em uma proposta de projeto de automação. Apresente objetivo, componentes, arquitetura, fluxo de dados e possíveis riscos.

---

# 🧩 9. Perguntas para revisão

1. O que caracteriza um sistema IoT?
2. Qual é o papel do ESP32 em uma aplicação conectada?
3. O que diferencia publisher e subscriber?
4. Qual é a função do broker MQTT?
5. O que é um tópico MQTT?
6. O que representa QoS?
7. Por que MQTT pode ser interessante em dispositivos com recursos limitados?
8. Quais riscos aparecem quando dispositivos são conectados à rede?
9. Quais recursos básicos de segurança devem ser considerados em um dispositivo IoT?
10. Como sensores, ESP32, MQTT e dashboard podem formar um sistema de monitoramento?

---

# 🏭 10. Projeto prático proposto

## Monitoramento Inteligente de Temperatura

### Componentes

- ESP32
- Sensor de temperatura/umidade
- Rede Wi-Fi
- Broker MQTT
- Dashboard
- Banco de dados opcional

### Funcionamento

1. O sensor realiza a medição.
2. O ESP32 lê o valor.
3. O ESP32 conecta-se à rede.
4. O dispositivo publica os dados via MQTT.
5. O broker recebe a mensagem.
6. O dashboard recebe os dados.
7. O usuário acompanha temperatura e alarmes.
8. Os dados podem ser armazenados para análise histórica.

### Possível evolução

- acionamento de ventilação;
- alarmes;
- histórico;
- análise de tendência;
- manutenção preditiva;
- integração com CLP/SCADA;
- autenticação e comunicação segura.

---

# 🧠 11. Conclusão

O uso do NotebookLM neste projeto demonstra como uma IA pode ser utilizada não apenas para gerar respostas, mas como uma ferramenta de aprendizagem estruturada.

A combinação de fontes confiáveis, perguntas progressivas, comparação de conceitos e verificação das respostas permite transformar informação técnica em conhecimento organizado.

O principal aprendizado foi perceber que a qualidade da resposta depende também da qualidade da pergunta. Prompts mais específicos, contextualizados e baseados em fontes produzem resultados mais úteis para estudo.

O projeto também reforça a importância de considerar segurança, arquitetura e aplicação prática ao estudar IoT.

---

## 👨‍💻 Autor

**Willys Tecnologia IoT**

Projeto desenvolvido para portfólio e para o desafio da DIO.

---

## 📄 Licença

Este material é um projeto educacional. As fontes externas pertencem aos respectivos autores e organizações.
