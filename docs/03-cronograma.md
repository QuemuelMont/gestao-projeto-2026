# Cronograma — SIGER

## 1. Cronograma Detalhado

O projeto possui duração estimada de 8 semanas, com atividades sequenciais e paralelas.

| Código | Atividade | Duração | Dependências | Início / Fim |
|---|---|---:|---|---|
| A1 | Planejamento: definição do escopo, requisitos e termo de abertura | 1 semana | - | Semana 1 |
| A2 | Seleção de componentes: pesquisa e escolha do ESP32, sensores e atuadores | 1 semana | A1 | Semana 2 |
| A3 | Montagem do hardware: circuito eletrônico e calibração de sensores em bancada | 1 semana | A2 | Semana 3 |
| A4 | Firmware ESP32: programação de leitura dos sensores e envio Wi-Fi/IoT | 1 semana | A3 | Semana 4 |
| A5 | Banco de Dados & API: modelagem do banco e serviço de recebimento de dados | 1 semana | A1 | Semanas 3–4 |
| A6 | Dashboard: interface gráfica para exibição dos dados e custos | 1 semana | A5 | Semana 5 |
| A7 | Coleta da Base de Dados de IA: geração/coleta do histórico de consumo inicial | 2 semanas | A4 | Semanas 4–5 |
| A8 | Desenvolvimento da IA: treinamento, anomalias e recomendações | 1 semana | A7 | Semana 6 |
| A9 | Integração do Sistema: conexão Hardware + Dashboard + IA | 1 semana | A4, A6, A8 | Semana 7 |
| A10 | Testes e Validação: testes em ambiente controlado e ajustes de IA | 1 semana | A9 | Semanas 7–8 |
| A11 | Encerramento: relatório técnico e preparação da apresentação | 1 semana | A10 | Semana 8 |

## 2. Caminho Crítico — CPM

O caminho crítico representa a sequência de atividades encadeadas sem folga temporal que determina a duração total mínima do projeto.

### Caminho Hardware e IA

```text
A1 → A2 → A3 → A4 → A7 → A8 → A9 → A10 → A11
