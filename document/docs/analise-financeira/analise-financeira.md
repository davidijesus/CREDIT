---
sidebar_label: "Análise Financeira (inclui B2B2C)"
sidebar_position: 1
---

# Análise Financeira

## Entendimento do tópico

&emsp;O CRED.IT adota um modelo **freemium** com assinatura mensal de R$ 30,00 para PMEs e distribuição **B2B2C** via associações comerciais e cooperativas parceiras. Esta seção detalha **fontes de receita**, **premissas**, **indicadores** (ROI, LTV, CAC), **unidade econômica por canal** e **cenários de escala**. Todos os valores são hipóteses calibráveis.

---

## Modelo de Negócios

- **Plano gratuito**: recursos limitados, foco em aquisição e ativação.  
- **Assinatura individual (B2C)**: R$ 30,00/mês por empreendedor.  
- **Distribuição B2B2C**: associações e cooperativas atuam como canais de entrada e ativação local; dois arranjos possíveis:
  1) **Wholesale** (associação contrata para os membros): preço de atacado de R$ 18,00/mês por membro ativo (faturado para a associação).  
  2) **Indicação** (membro paga individualmente): R$ 30,00/mês, com **comissão de referência** à associação por 12 meses (ex.: 20% sobre a mensalidade).  
- **Licença institucional** para associações: **R$ 5.000/ano** por entidade (painéis coletivos, analytics, treinamento, materiais de engajamento).

:::info
Parcerias com cooperativas (ex.: Cresol) podem incluir **co-marketing** e **integrações**. Qualquer remuneração adicional (ex.: fee por encaminhamento qualificado) deve respeitar compliance e não envolver participação em juros.
:::

---

## Fontes de Receita

| Linha | Descrição | Base de cálculo | Observações |
|------|-----------|-----------------|-------------|
| Assinatura B2C | Pagamento direto do empreendedor | R$ 30,00 × usuários pagantes | ARPU maior; CAC de marketing digital |
| Wholesale B2B2C | Faturamento por membro ativo via associação | R$ 18,00 × membros ativos | ARPU menor; CAC reduzido |
| Licença institucional | Acesso a dashboards e ferramentas B2B | R$ 5.000/ano × associações | Alta margem, recorrente |
| (Opcional) Co-marketing/fee | Acordos com cooperativas | Valor fixo por lead qualificado | Sujeito a compliance |

---

## Premissas (base)

- **Ticket mensal**: R$ 30,00 (B2C) e R$ 18,00 (wholesale).  
- **Margem operacional**: 65% (infra, mensageria, suporte e dados incluídos nos 35% variáveis).  
- **Churn mensal**: 2,8% (vida média ≈ **36 meses**).  
- **CAC por canal**: R$ **120** (B2C digital) e R$ **50** (B2B2C via associação).  
- **Licença associação**: R$ **5.000/ano** (margem estimada 90%).  
- Conversão do gratuito para pago: **8–12%** em 90 dias (ajustável por cohort).  
- Mix de aquisição inicial (Ano 1): **62,5% B2C** e **37,5% B2B2C** (pode evoluir conforme parcerias).

---

## Indicadores e Fórmulas

- **LTV** = ARPU_mensal × Vida_média (meses) × Margem  
- **CAC** = Investimento total em aquisição ÷ novos clientes  
- **ROI de aquisição** = (LTV − CAC) ÷ CAC  
- **Payback** (meses) = CAC ÷ (ARPU_mensal × Margem)  
- **ARR** = 12 × receita mensal recorrente + licenças anuais

---

## Unidade Econômica por Canal

### B2C (assinatura direta)
- ARPU_mensal: **R$ 30,00**  
- LTV = 30 × 36 × 0,65 = **R$ 702,00**  
- CAC médio: **R$ 120,00**  
- ROI = (702 − 120) ÷ 120 ≈ **4,85**  
- Payback ≈ 120 ÷ (30 × 0,65) ≈ **6,2 meses**

### B2B2C (wholesale via associação)
- ARPU_mensal: **R$ 18,00**  
- LTV = 18 × 36 × 0,65 = **R$ 421,20**  
- CAC médio: **R$ 50,00**  
- ROI = (421,2 − 50) ÷ 50 ≈ **7,42**  
- Payback ≈ 50 ÷ (18 × 0,65) ≈ **4,3 meses**

### Blended (mix Ano 1: 62,5% B2C / 37,5% B2B2C)
- ARPU_blend = 0,625×30 + 0,375×18 = **R$ 25,50**  
- LTV_blend = 25,5 × 36 × 0,65 ≈ **R$ 596,70**  
- CAC_blend = 0,625×120 + 0,375×50 = **R$ 93,75**  
- LTV:CAC ≈ **6,36**; Payback ≈ **5,7 meses**

---

## Cenários de Escala

### Ano 1 (base)
- **Associações ativas**: 50  
- **Membros/associação**: 300  
- **Conversão wholesale**: 25% → **3.750** pagantes via B2B2C  
- **B2C direto**: **6.250** pagantes  
- **Total pagantes**: **10.000**

**Receita anual recorrente (ARR)**  
- Assinaturas B2C: 6.250 × 30 × 12 = **R$ 2.250.000**  
- Assinaturas wholesale: 3.750 × 18 × 12 = **R$ 810.000**  
- Licenças: 50 × 5.000 = **R$ 250.000**  
- **ARR total**: **R$ 3.310.000**

**Margem bruta**  
- Assinaturas: 65% × (2.250.000 + 810.000) = **R$ 1.989.000**  
- Licenças: 90% × 250.000 = **R$ 225.000**  
- **Margem bruta total**: **R$ 2.214.000**

**CAC do ano (novos 10k)**  
- B2C: 6.250 × 120 = **R$ 750.000**  
- B2B2C: 3.750 × 50 = **R$ 187.500**  
- **CAC total**: **R$ 937.500**  
- **Contribuição pós-CAC** (antes de OPEX fixo): ≈ **R$ 1.276.500**

### Ano 3 (marco 100k pagantes)
- **Associações**: 200; conversão wholesale 30%; membros/associação 400  
- **B2B2C pagantes**: 200 × 400 × 30% = **24.000**  
- **B2C pagantes**: **76.000**  
- **ARR**  
  - Assinaturas: (76.000 × 30 × 12) + (24.000 × 18 × 12) = **R$ 33.544.000**  
  - Licenças: 200 × 5.000 = **R$ 1.000.000**  
  - **ARR total**: **R$ 34.544.000**  
- **Margem bruta** (aprox.): 65% sobre assinaturas + 90% sobre licenças ≈ **R$ 22.053.600**

### Ano 5 (marco 500k pagantes)
- **Associações**: 600; conversão wholesale 35%; membros/associação 500  
- **B2B2C pagantes**: 600 × 500 × 35% ≈ **105.000**  
- **B2C pagantes**: **395.000**  
- **ARR**  
  - Assinaturas: (395.000 × 30 × 12) + (105.000 × 18 × 12) = **R$ 167.880.000**  
  - Licenças: 600 × 5.000 = **R$ 3.000.000**  
  - **ARR total**: **R$ 170.880.000**  
- **Margem bruta** (aprox.): 65% sobre assinaturas + 90% sobre licenças ≈ **R$ 109.872.000**

---

## Funil B2B2C (da associação ao assinante)

1. **Parceria** com associação (contrato e onboarding do time).  
2. **Engajamento**: campanha local, materiais, treinamentos, eventos.  
3. **Ativação**: membros conectam WhatsApp e registram fluxo diário (free).  
4. **Conversão**: upgrade para pago por necessidade de relatórios e crédito integrado.  
5. **Retenção**: valor contínuo via recomendações, metas e acesso cooperativo.

**Efeitos no CAC**:  
- Materiais e eventos compartilhados **reduzem CAC** por escala local.  
- Confiança da associação **aumenta conversão** e **diminui churn** de early cohorts.

---

## Sensibilidade (churn × LTV)

| Churn mensal | Vida média (meses) | LTV B2C (R$) | LTV B2B2C (R$) |
|--------------|--------------------|--------------|----------------|
| 1,8%         | ~55                | 30×55×0,65 = **1.072,5** | 18×55×0,65 = **643,5** |
| 2,8% (base)  | 36                 | **702,0**    | **421,2**      |
| 4,5%         | ~22                | 30×22×0,65 = **429,0**   | 18×22×0,65 = **257,4** |

Observação: mesmo com churn elevado, a relação LTV:CAC permanece saudável, sobretudo no canal B2B2C.

---

## Custos, Margens e OPEX

- **Variáveis** (35% sobre receita de assinaturas): mensageria/WhatsApp, infraestrutura cloud, dados e suporte de 1º nível.  
- **Fixos**: produto/engenharia, design, compliance/LGPD, parcerias, operação de comunidade e atendimento escalonado.  
- **Licenças B2B**: margem estimada de 90% (baixa pressão de custos variáveis).

---

## Riscos e Mitigações

- **Regulatório**: conformidade com LGPD e diretrizes do Banco Central; não receber participação em juros; contratos de parceria claros.  
- **Dependência de canal**: diversificar entre B2C e B2B2C; playbooks de ativação por associação.  
- **Churn**: foco em valor recorrente (recomendações, crédito cooperativo, metas e alertas).  
- **Aquisição**: CAC sob controle via conteúdo educacional, kits de engajamento e programas de referência.

---

## Métricas a Monitorar

- **ARPU** por canal; **LTV**; **CAC**; **LTV:CAC**; **Payback**.  
- **Churn** e **retention** por cohort e por associação.  
- **Ativação** (D7/D30 com registro diário via WhatsApp).  
- **Conversão** free→pago por campanha/associação.  
- **Blended CAC** e contribuição pós-CAC.

---

## Notas de Implementação Financeira

- **Reconhecimento de receita** mensal e provisionamento de **licenças anuais** pro-rata.  
- Controle por **centro de custo** para separar marketing digital de programas B2B2C.  
- BI financeiro com **dashboards** de cohort, canal, associação, cidade e vertical.

---

## Referências Bibliográficas

- SEBRAE. Boletim Anual de PMEs 2023. Brasília, 2023.  
- Banco Central do Brasil. Relatório de Economia Bancária. Brasília, 2021.  
- CRESOL. Relatório Institucional 2024. Disponível em: https://www.cresol.com.br  
- McKinsey & Company. Digital SME Banking Reports, 2022.  
- Harvard Business Review. The Economics of Subscription Models, 2021.

---
