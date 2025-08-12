# 📊 Analise_de_Risco_Relativo_Banco_Caja_Laboratoria

## 📌 Sobre
Este projeto foi desenvolvido como parte do **Projeto 03 – Laboratória** com foco em **Análise de Risco Relativo** para o **Banco Caja**.  
O objetivo foi identificar padrões de comportamento financeiro e características demográficas que influenciam a probabilidade de inadimplência, classificando clientes entre **bons** e **maus pagadores**.

A análise foi feita utilizando **Google BigQuery** para consultas SQL e **Looker Studio** para a construção do dashboard interativo.  
O fluxo de trabalho envolveu:

- **Exploração e tratamento dos dados**: limpeza, tratamento de valores nulos, detecção e sinalização de outliers.
- **Criação de variáveis dummies** para atributos categóricos e numéricos relevantes.
- **Cálculo do risco relativo** considerando variáveis comportamentais (ex.: histórico de atrasos, quantidade de empréstimos) e socioeconômicas (ex.: idade, renda).
- **Pontuação de risco (score)** ponderada para segmentação de clientes.
- **Validação da classificação** usando matriz de confusão e a variável `default_flag`.
- **Visualização interativa** dos resultados no Looker Studio.

O resultado foi um modelo interpretativo que permite ao banco identificar clientes com maior propensão à inadimplência, auxiliando na tomada de decisão e mitigação de riscos.

---

## 🔗 Links do Projeto

- **📄 Ficha Técnica**: [Ficha Técnica – Projeto 03 Laboratória](https://coda.io/d/_d10_3IAh9IX/Ficha-Tecnica-Projeto-03-Laboratoria_suQ8taf9)  
- **📊 Dashboard Interativo**: [Looker Studio](https://lookerstudio.google.com/reporting/d7dc7dbd-0453-4992-932c-ce84aa2a2479)  
- **🎥 Apresentação em Vídeo**: [Loom](https://www.loom.com/share/77f8feac3c7d4a50a5f586d7c5341e5b?sid=82fa3b6b-ef93-4a93-ab4f-9da27fd7d9a7)

---

## 🛠 Tecnologias Utilizadas
- **Google BigQuery** – consulta e análise de grandes volumes de dados.
- **SQL** – limpeza, transformação e criação de métricas.
- **Looker Studio** – visualização e construção de dashboard interativo.
- **Google Sheets / Excel** – análises exploratórias complementares.

---

## 📈 Principais Resultados
- **Taxa geral de inadimplência**: 1,9%.  
- **Taxa de maus pagadores** (incluindo atrasos > 90 dias): 7,8%.  
- Identificação das variáveis de maior impacto no risco de inadimplência.  
- Desenvolvimento de um score de risco interpretável, permitindo fácil comunicação dos resultados para stakeholders.

---

💡 *Este projeto reforçou a importância de combinar análise estatística com visualização clara dos dados, garantindo que as conclusões possam ser rapidamente compreendidas e aplicadas pelo negócio.*

