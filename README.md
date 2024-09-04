# Capabilidade de Processo - Análise de SensorReading
Este repositório contém como realizar um teste de capabilidade em dados de sensores (SensorReading). O objetivo deste projeto é ilustrar a aplicação do teste de capabilidade, um componente importante na fase "Analyze" do ciclo DMAIC (Definir, Medir, Analisar, Melhorar, Controlar).</br>
</br>
## Teste de Capabilidade no DMAIC </br>
O teste de capabilidade é uma etapa fundamental na fase "Analyze" do DMAIC. Durante a fase "Analyze", busca-se entender as causas raízes de problemas no processo e determinar a capacidade do processo de atender aos requisitos estabelecidos. Os índices Cp e Cpk são ferramentas essenciais para fornecer uma visão clara sobre a performance do processo em relação aos limites de especificação.</br>
</br>
## Quando Usar o Teste de Capabilidade
O teste de capabilidade é usado para avaliar a capacidade de um processo em produzir resultados dentro de limites de especificação definidos. Ele é aplicado quando é necessário verificar se um processo pode atender consistentemente às especificações exigidas sem a necessidade de ajustes frequentes.</br>
</br>
## Aplicação
Utilizamos dados simulados de leitura de sensores. A análise envolve:</br>
</br>
### 1. Definição dos Limites de Especificação</br>
</br>
LSL (Lower Specification Limit): 22.5</br>
USL (Upper Specification Limit): 75.4</br>

![image](https://github.com/user-attachments/assets/e77031a0-ad52-43e2-bd23-f491fb15e30f)

</br>

### 2. Cálculos de Capabilidade
</br>
Cálculo dos índices Cp e Cpk para determinar a capacidade do processo.</br>

![image](https://github.com/user-attachments/assets/6990c628-c5f2-46c3-8b30-7d98fdbd1109)


### 3. Visualização dos Resultados

Um histograma com os limites de especificação e a média das leituras do sensor.</br>
![image](https://github.com/user-attachments/assets/c72098eb-8531-4c47-b77a-a6160d335b77)



## Conclusão
Neste exemplo, os valores de Cp e Cpk indicaram que o processo não é capaz. Quando o teste de capabilidade revela que o processo não é capaz, é necessário investigar as causas e realizar melhorias no processo. Isso pode envolver ajustes nos parâmetros de processo, manutenção de equipamentos ou até mesmo uma revisão dos limites de especificação.

Se o processo não for capaz, recomenda-se implementar um plano de ação para corrigir as deficiências identificadas e monitorar continuamente o processo para garantir que as melhorias sejam sustentáveis.

## Contato
Para mais informações ou colaborações, entre em contato:
- **Nome**: Fellipe Bandeira
- **Email**: flzeta7@gmail.com
- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/fellipe-bandeira)

---

Obrigado por visitar meu projeto de análise de capabilidade!
