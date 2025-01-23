# Simulador de Consumo de Energia

Este é um projeto desenvolvido em Salesforce com Lightning Web Components (LWC) para simular o consumo mensal de energia elétrica e estimar o custo com base nas tarifas de energia.

## 🎯 Objetivo

O simulador permite que os usuários insiram informações sobre aparelhos elétricos, como potência (Watts) e tempo médio de uso diário, e retorna:
- O consumo mensal estimado (em kWh).
- O custo estimado com base na tarifa de energia selecionada.

Este projeto demonstra o uso de **LWC**, **Fórmulas em Salesforce** e automação para cálculos e salvamento de dados.

---

## 📋 Funcionalidades

1. **Entrada de Dados**:
   - Nome do aparelho.
   - Potência (Watts).
   - Tempo médio de uso diário (horas por dia).
   - Tarifa de energia elétrica (R$/kWh).

2. **Cálculos Automáticos**:
   - Consumo mensal em kWh.
   - Custo estimado em R$ com base no consumo e tarifa.

3. **Salvamento no Salesforce**:
   - Permite salvar simulações para consulta futura.

4. **Interface Amigável**:
   - Desenvolvido com Lightning Web Components para uma experiência de usuário moderna e responsiva.

---

## 🛠️ Tecnologias Utilizadas

- **Salesforce Lightning Web Components (LWC)**: Interface e cálculos no front-end.
- **Salesforce Apex**: Back-end para salvamento de simulações.
- **Fórmulas em Salesforce**: Cálculos automáticos de consumo e custo.
- **Lightning App Builder**: Configuração e integração do componente.

---

## ⚙️ Configuração

### Pré-requisitos
1. Acesso a uma org Salesforce com permissões para criar e modificar objetos e componentes.
2. Salesforce CLI para deploy do código.

### Deploy do Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/simulador-de-energia.git
# Simulador de Consumo de Energia

Este é um projeto desenvolvido em Salesforce com Lightning Web Components (LWC) para simular o consumo mensal de energia elétrica e estimar o custo com base nas tarifas de energia.

## 🎯 Objetivo

O simulador permite que os usuários insiram informações sobre aparelhos elétricos, como potência (Watts) e tempo médio de uso diário, e retorna:
- O consumo mensal estimado (em kWh).
- O custo estimado com base na tarifa de energia selecionada.

Este projeto demonstra o uso de **LWC**, **Fórmulas em Salesforce** e automação para cálculos e salvamento de dados.

---

## 📋 Funcionalidades

1. **Entrada de Dados**:
   - Nome do aparelho.
   - Potência (Watts).
   - Tempo médio de uso diário (horas por dia).
   - Tarifa de energia elétrica (R$/kWh).

2. **Cálculos Automáticos**:
   - Consumo mensal em kWh.
   - Custo estimado em R$ com base no consumo e tarifa.

3. **Salvamento no Salesforce**:
   - Permite salvar simulações para consulta futura.

4. **Interface Amigável**:
   - Desenvolvido com Lightning Web Components para uma experiência de usuário moderna e responsiva.

---

## 🛠️ Tecnologias Utilizadas

- **Salesforce Lightning Web Components (LWC)**: Interface e cálculos no front-end.
- **Fórmulas em Salesforce**: Cálculos automáticos de consumo e custo.
- **Lightning App Builder**: Configuração e integração do componente.

