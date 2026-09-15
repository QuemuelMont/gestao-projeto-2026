# Escopo e EAP — SIGER

## 1. Declaração do Escopo

### Nome do Projeto

Sistema Inteligente de Gestão Energética Residencial (SIGER)

### Objetivo Geral

Desenvolver um protótipo funcional de um sistema capaz de monitorar o consumo de energia elétrica de uma residência, apresentar os dados ao usuário em uma interface/dashboard e utilizar Inteligência Artificial (IA) para identificar padrões de consumo, detectar possíveis desperdícios/anomalias e gerar recomendações de economia de energia.

## 2. Dentro do Escopo

### Hardware e Sensores

- Desenvolvimento de protótipo em bancada/ambiente residencial controlado utilizando microcontrolador ESP32;
- Integração e medição de grandezas elétricas (corrente, tensão e potência) através de sensores dedicados;
- Utilização opcional de sensores ambientais (temperatura, presença) e relés/módulos de acionamento.

### Comunicação e Dados

- Envio de dados coletados via rede Wi-Fi / IoT;
- Criação e modelagem de banco de dados para armazenamento do histórico de consumo.

### Interface do Usuário

- Desenvolvimento de dashboard/interface para visualização das informações;
- Estimativa de consumo e custos.

### Inteligência Artificial

- Desenvolvimento e aplicação de algoritmos de IA;
- Análise de padrões;
- Detecção de anomalias/desperdícios;
- Geração de recomendações para redução de consumo.

### Testes e Validação

- Testes individuais;
- Calibração de sensores;
- Testes de integração de hardware, software e IA;
- Elaboração da documentação técnica;
- Apresentação final do projeto.

## 3. Fora do Escopo

- Controle ou automação completa da instalação elétrica de toda a residência;
- Alteração da infraestrutura da instalação elétrica existente;
- Desenvolvimento de aplicativo móvel ou produto comercializável;
- Instalação e deployment em múltiplas residências;
- Implementação de sistemas de cobrança ou integração direta com sistemas da concessionária de energia.

## 4. Principais Entregáveis

1. Documento de Requisitos e Planejamento;
2. Projeto do Circuito e Arquitetura de Hardware;
3. Protótipo Montado (ESP32 + Sensores);
4. Firmware do ESP32 (Coleta, Processamento e Transmissão);
5. Banco de Dados para Histórico de Consumo;
6. Dashboard/Interface de Monitoramento;
7. Módulo de Inteligência Artificial Treinado e Validado;
8. Sistema Completo Integrado;
9. Relatório de Testes e Validação;
10. Documentação Técnica e Apresentação Final.

## 5. Estrutura Analítica do Projeto — EAP / WBS

```text
1. SIGER - Sistema Inteligente de Gestão Energética Residencial
│
├── 1.1 Gerenciamento do Projeto
│   ├── 1.1.1 Termo de Abertura (Project Charter)
│   ├── 1.1.2 Requisitos do Projeto e Escopo
│   ├── 1.1.3 Cronograma e Divisão de Tarefas
│   └── 1.1.4 Relatório de Riscos e Mitigações
│
├── 1.2 Hardware e Sensoriamento
│   ├── 1.2.1 Pesquisa e Seleção de Componentes (ESP32, Sensores)
│   ├── 1.2.2 Esquema Elétrico e Projeto do Circuito
│   ├── 1.2.3 Montagem do Hardware em Bancada
│   └── 1.2.4 Calibração dos Sensores (Tensão, Corrente, Potência)
│
├── 1.3 Firmware do ESP32 e Conectividade
│   ├── 1.3.1 Programação da Aquisição de Dados Elétricos
│   ├── 1.3.2 Leitura dos Sensores Ambientais e de Presença
│   ├── 1.3.3 Implementação de Comunicação Wi-Fi / IoT
│   └── 1.3.4 Rotina de Armazenamento Temporário/Local (Modo Offline)
│
├── 1.4 Banco de Dados e Software (Dashboard)
│   ├── 1.4.1 Modelagem e Criação do Banco de Dados
│   ├── 1.4.2 API/Serviço de Recebimento de Dados do ESP32
│   ├── 1.4.3 Desenvolvimento do Dashboard de Monitoramento
│   └── 1.4.4 Implementação da Exibição de Estimativa de Consumo/Custos
│
├── 1.5 Módulo de Inteligência Artificial
│   ├── 1.5.1 Coleta e Preparação da Base de Dados de Treinamento
│   ├── 1.5.2 Desenvolvimento dos Algoritmos de Análise de Padrões
│   ├── 1.5.3 Algoritmo de Detecção de Anomalias e Desperdícios
│   └── 1.5.4 Motor de Recomendações de Economia Energética
│
├── 1.6 Integração e Testes
│   ├── 1.6.1 Integração Hardware + Nuvem/BD + Dashboard
│   ├── 1.6.2 Integração do Módulo de IA com o Dashboard
│   ├── 1.6.3 Testes Globais em Ambiente Controlado
│   └── 1.6.4 Validação das Previsões e Recomendações da IA
│
└── 1.7 Encerramento do Projeto
    ├── 1.7.1 Documentação Técnica Final
    └── 1.7.2 Preparação e Realização da Apresentação Final
