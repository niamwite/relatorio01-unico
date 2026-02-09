# 🔬 Análise Estatística Avançada - Banco Unico_Database
**Data:** 06/02/2026 22:14
**Analista:** Sistema de Análise Estatística
**Foco:** Vendas, Marketing, RH

---
## 🚨 DESCOBERTAS EXPLOSIVAS (LEITURA OBRIGATÓRIA)
### 1. MAIOR CONTRATO: R$ 147,000,000.00
```
Contrato: -  Luiz Teles - Cota real 
Valor: R$ 147,000,000.00
Vendedor: Camila Valadares -  LOTUS
Data: 2025-12-12T08:27:59.590-03:00
```

**Este contrato é:**
- 111.5x maior que a média (R$ 1,318,834.18)
- 11.6% do valor total

### 2. TOP VENDEDORES
```
1. Camila Valadares -  LOTUS
   ├─ Contratos: 16
   ├─ Total: R$ 170,966,455.50
   └─ Ticket: R$ 10,685,403.47
2. Lucimara- HAKA
   ├─ Contratos: 73
   ├─ Total: R$ 156,535,553.00
   └─ Ticket: R$ 2,144,322.64
3. Leonora  | HAKA
   ├─ Contratos: 34
   ├─ Total: R$ 60,669,074.00
   └─ Ticket: R$ 1,784,384.53
4. Larissa - Haka
   ├─ Contratos: 2
   ├─ Total: R$ 57,000,000.00
   └─ Ticket: R$ 28,500,000.00
5. MICAELY REGINA VALE ITALIANO  - HAKA
   ├─ Contratos: 25
   ├─ Total: R$ 56,024,080.00
   └─ Ticket: R$ 2,240,963.20
6. Ane Borges -  Haka
   ├─ Contratos: 26
   ├─ Total: R$ 51,879,739.05
   └─ Ticket: R$ 1,995,374.58
7. FERNANDA SOUZA MIGLIARI -  HAKA
   ├─ Contratos: 37
   ├─ Total: R$ 38,182,141.40
   └─ Ticket: R$ 1,031,949.77
8. KAREN  SANTANA - GARRA
   ├─ Contratos: 24
   ├─ Total: R$ 32,919,931.04
   └─ Ticket: R$ 1,371,663.79
9. JULIANA SILVA - LOTUS
   ├─ Contratos: 19
   ├─ Total: R$ 31,928,125.60
   └─ Ticket: R$ 1,680,427.66
10. Daiane  Diniz - Haka
   ├─ Contratos: 29
   ├─ Total: R$ 29,996,754.00
   └─ Ticket: R$ 1,034,370.83
```

### 3. PERFORMANCE POR EQUIPE
```
EQUIPE             Qtd          Valor Total       Ticket Médio
-----------------------------------------------------------------
Haka               124 R$  202,906,513.80 R$   1,636,342.85
 LOTUS              16 R$  170,966,455.50 R$  10,685,403.47
 HAKA               69 R$   95,006,880.45 R$   1,376,911.31
GARRA               86 R$   83,873,168.57 R$     975,269.40
AVANTE              74 R$   69,355,501.39 R$     937,236.51
LOTUS               48 R$   64,551,216.60 R$   1,344,817.01
BRAVUS             108 R$   49,516,639.06 R$     458,487.40
 BRAVUS             49 R$   25,691,620.52 R$     524,318.79
 AVANTE             18 R$   18,531,426.00 R$   1,029,523.67
GARRA .             12 R$   13,428,372.60 R$   1,119,031.05
GARRA 🦅              5 R$    9,409,992.12 R$   1,881,998.42
MERCURE             16 R$    8,128,500.00 R$     508,031.25
BARRA DA TIJUCA      5 R$    3,637,650.00 R$     727,530.00
HAKA Domingues       6 R$    3,485,000.00 R$     580,833.33
AVANTE .             5 R$    2,710,000.00 R$     542,000.00
Equipe Haka          3 R$      880,000.00 R$     293,333.33
SHARK                8 R$      789,500.00 R$      98,687.50
(DESATIVADO)         1 R$      150,000.00 R$     150,000.00
ATHENAS              1 R$      105,000.00 R$     105,000.00
Rio                  1 R$      100,000.00 R$     100,000.00
```


## 📈 ESTATÍSTICAS DESCRITIVAS

### Medidas de Tendência Central
```
Total de Contratos: 958
Valor Total: R$ 1,263,443,142.91

Média:    R$ 1,318,834.18
Mediana:  R$ 543,000.00
Desvio Padrão: R$ 5,394,000.70

Mínimo:   R$ 1,020.00
Máximo:   R$ 147,000,000.00
Amplitude: R$ 146,998,980.00

Q1 (25%): R$ 300,000.00
Q3 (75%): R$ 1,035,673.02
IQR:      R$ 735,673.02
CV (Coef. Variação): 4.09
```

### Distribuição por Faixas de Valor
```
< R$100k           22 (  2.3%) → R$ 1,542,520.00 (  0.1%)
R$100k-500k       388 ( 40.5%) → R$ 110,970,993.66 (  8.8%)
R$500k-1M         267 ( 27.9%) → R$ 175,281,868.24 ( 13.9%)
R$1M-5M           239 ( 24.9%) → R$ 425,799,478.65 ( 33.7%)
R$5M-10M           30 (  3.1%) → R$ 201,288,655.70 ( 15.9%)
> R$10M            12 (  1.3%) → R$ 348,559,626.66 ( 27.6%)
               ↑                ↑
            Qtd contratos     Valor Total
```

## 🔍 DETECÇÃO DE OUTLIERS

### Método IQR (Interquartile Range)
**Outliers detectados:** 93 contratos
**Limite superior:** R$ 2,139,182.55

### Top 20 Contratos (Possíveis Outliers)
```
1. -  Luiz Teles - Cota real                R$  147,000,000.00 (Z=27.0σ)
   └─ Camila Valadares -  LOTUS
2. rodrigo/PARCEIRO                         R$   55,000,000.00 (Z=10.0σ)
   └─ Larissa - Haka
3. Turano Construtora (2º venda)            R$   23,276,524.86 (Z=4.1σ)
   └─ Lucimara- HAKA
4. Atacadan distribuidora                   R$   21,352,680.00 (Z=3.7σ)
   └─ Lucimara- HAKA
5. Posto São João                           R$   20,096,640.00 (Z=3.5σ)
   └─ MICAELY REGINA VALE ITALIANO  - HAKA
6. Wanderley                                R$   14,500,000.00 (Z=2.4σ)
   └─ Camila Valadares -  LOTUS
7. Behave ABA - MARCIA - MILENA             R$   12,144,273.84 (Z=2.0σ)
   └─ MYLEIA - GARRA
8. ERICK BRITO | MICA                       R$   11,618,370.00 (Z=1.9σ)
   └─ Leonora  | HAKA
9. Ind Com Maq. Ramos Universo              R$   11,469,591.96 (Z=1.9σ)
   └─ MAIRA AVANTE
10. Michel Fontes | MICA                     R$   10,990,350.00 (Z=1.8σ)
   └─ Leonora  | HAKA
11. Drogaria ULTRAMAIS - Danilo              R$   10,748,866.00 (Z=1.7σ)
   └─ KAREN  SANTANA - GARRA
12. Moldsoft Tecnologia E Inovação LTDA - Rafael e Tiago - Mica R$   10,362,330.00 (Z=1.7σ)
   └─ Ane Borges -  Haka
13. IMIL - Indústria Mecânica Itajaí ltda    R$    9,420,000.00 (Z=1.5σ)
   └─ Lucimara- HAKA
14. Roper plast - LAERTI                     R$    8,900,000.00 (Z=1.4σ)
   └─ Carolina  Bravus
15. F3 PRODUÇÕES E EVENTOS LTDA              R$    8,628,020.00 (Z=1.4σ)
   └─ Greice- LOTUS
16. ZR CONSTRUÇÃO                            R$    8,478,270.00 (Z=1.3σ)
   └─ GISLEANNE KARLA GONCALO VIEIRA - AVANTE
17. Frutas da fazenda                        R$    8,400,000.00 (Z=1.3σ)
   └─ Greice- LOTUS
18. Luiz Maximiliano / R$ 5.000.000,00       R$    8,150,000.00 (Z=1.3σ)
   └─ JULIANA SILVA - LOTUS
19. Prime Cargo Logistica                    R$    8,123,125.60 (Z=1.3σ)
   └─ JULIANA SILVA - LOTUS
20. Junior / 7.800.000,00                    R$    7,800,000.00 (Z=1.2σ)
   └─ MICAELY REGINA VALE ITALIANO  - HAKA
```

## 📊 FUNIL DE CONVERSÃO

```
Meta Leads (Leads):            30,743
    ↓
DealsInProgress:               14,201 (46.2%)
    ↓
DealsLost:                     28,400 (92.4%)
DealsWin:                         990 (3.2%)
```

**Taxa de Sucesso:**
- Lead → Deal Ganho: 3.22%
- Deal Ganho / Perdido: 3.37%
- DealsInProgress → Ganho: 6.97%

## 🕐 ANÁLISE TEMPORAL

### Últimos 30 Dias com Maior Volume
```
2026-01-21 →   2 contratos = R$ 1,104,681.88
2026-01-20 →   1 contratos = R$   506,012.00
2026-01-19 →   2 contratos = R$ 1,433,699.00
2026-01-16 →   1 contratos = R$   430,000.00
2026-01-15 →   1 contratos = R$   376,812.00
2026-01-14 →   1 contratos = R$   210,000.00
2026-01-13 →   1 contratos = R$   640,000.00
2026-01-06 →   1 contratos = R$   337,340.94
2026-01-05 →   2 contratos = R$ 6,274,617.57
2025-12-18 →   3 contratos = R$ 2,500,000.00
2025-12-16 →   2 contratos = R$ 3,373,409.40
2025-12-15 →   6 contratos = R$ 9,511,006.40
2025-12-12 →   3 contratos = R$ 149,386,705.00
2025-12-11 →   3 contratos = R$ 4,267,363.64
2025-12-10 →   2 contratos = R$ 2,062,022.00
2025-12-05 →   3 contratos = R$ 4,293,409.94
2025-12-04 →   1 contratos = R$ 1,500,000.00
2025-12-03 →   3 contratos = R$ 3,024,045.64
2025-12-01 →   2 contratos = R$ 3,873,409.40
2025-11-28 →   2 contratos = R$ 1,400,000.00
2025-11-27 →   1 contratos = R$ 1,580,000.00
2025-11-25 →   5 contratos = R$ 8,698,587.52
2025-11-24 →   2 contratos = R$ 1,332,498.00
2025-11-18 →   4 contratos = R$ 2,896,832.82
2025-11-17 →   1 contratos = R$   809,619.00
2025-11-14 →   1 contratos = R$   379,508.56
2025-11-11 →   1 contratos = R$ 12,144,273.84
2025-11-10 →   2 contratos = R$   716,848.56
2025-11-07 →   1 contratos = R$   337,341.00
2025-11-06 →   1 contratos = R$   720,000.00
```

## 📱 LEADS POR UTM SOURCE

### Top 20 Campanhas
```
(direto)                       (sem campanha)                            23664
{{site_source_name}}           {{campaign.name}}                          7079
```

## 👥 ANÁLISE DE RH

### Pessoas com Mais Contratações
```
Pessoa ID: 107
  ├─ Contratações: 2
  ├─ Primeira: 2022-03-30
  ├─ Área ID: 1
Pessoa ID: 155
  ├─ Contratações: 2
  ├─ Primeira: 2022-09-12
  ├─ Área ID: 1
  └─ Equipe ID: 6
Pessoa ID: 216
  ├─ Contratações: 2
  ├─ Primeira: 2023-06-02
  ├─ Área ID: 1
  └─ Equipe ID: 4
Pessoa ID: 346
  ├─ Contratações: 2
  ├─ Primeira: 2025-07-17
  ├─ Área ID: 1
  └─ Equipe ID: 27
Pessoa ID: 122
  ├─ Contratações: 2
  ├─ Primeira: 2022-05-10
  ├─ Área ID: 1
Pessoa ID: 74
  ├─ Contratações: 2
  ├─ Primeira: 2021-11-11
  ├─ Área ID: 1
  └─ Equipe ID: 19
Pessoa ID: 41
  ├─ Contratações: 2
  ├─ Primeira: 2021-06-26
  ├─ Área ID: 1
Pessoa ID: 26
  ├─ Contratações: 2
  ├─ Primeira: 2021-03-01
  ├─ Área ID: 1
  └─ Equipe ID: 11
Pessoa ID: 140
  ├─ Contratações: 2
  ├─ Primeira: 2022-07-18
  ├─ Área ID: 1
  └─ Equipe ID: 9
Pessoa ID: 243
  ├─ Contratações: 2
  ├─ Primeira: 2025-02-04
  ├─ Área ID: 5
  └─ Equipe ID: 26
Pessoa ID: 69
  ├─ Contratações: 2
  ├─ Primeira: 2021-11-03
  ├─ Área ID: 1
  └─ Equipe ID: 5
Pessoa ID: 151
  ├─ Contratações: 2
  ├─ Primeira: 2022-08-23
  ├─ Área ID: 2
  └─ Equipe ID: 33
Pessoa ID: 357
  ├─ Contratações: 2
  ├─ Primeira: 2025-10-07
  ├─ Área ID: 1
  └─ Equipe ID: 27
Pessoa ID: 131
  ├─ Contratações: 2
  ├─ Primeira: 2022-07-04
  ├─ Área ID: 5
  └─ Equipe ID: 14
Pessoa ID: 112
  ├─ Contratações: 2
  ├─ Primeira: 2024-11-01
  ├─ Área ID: 1
  └─ Equipe ID: 25
Pessoa ID: 132
  ├─ Contratações: 2
  ├─ Primeira: 2022-07-04
  ├─ Área ID: 5
  └─ Equipe ID: 14
Pessoa ID: 154
  ├─ Contratações: 2
  ├─ Primeira: 2022-08-29
  ├─ Área ID: 5
  └─ Equipe ID: 26
Pessoa ID: 181
  ├─ Contratações: 2
  ├─ Primeira: 2023-02-06
  ├─ Área ID: 1
  └─ Equipe ID: 7
Pessoa ID: 188
  ├─ Contratações: 2
  ├─ Primeira: 2023-04-03
  ├─ Área ID: 2
  └─ Equipe ID: 34
Pessoa ID: 66
  ├─ Contratações: 2
  ├─ Primeira: 2021-11-01
  ├─ Área ID: 1
  └─ Equipe ID: 4
```


## 🎯 INSIGHTS ACIONÁVEIS

🚨 **Taxa de conversão muito baixa (3.2%)**   - Apenas 3-4% dos leads viram vendas   - Revisar qualidade dos leads   - Melhorar qualificação inicial
⚠️ **93 outliers detectados**   - Contratos com valores muito acima da média   - Investigar se são erros ou vendas legítimas   - Verificar documentação dos contratos maiores
🏆 **Melhor equipe: Haka**   - R$ 202,906,513.80 em vendas   - Ticket médio: R$ 1,636,342.85
📊 **Pior equipe: Rio**   - R$ 100,000.00 em vendas   - Ticket médio: R$ 100,000.00
📈 **Alta variabilidade nos contratos (CV=4.09)**   - Distribuição muito enviesada   - Poucos contratos gigantes puxam a média   - Usar mediana como métrica central

## 📋 RECOMENDAÇÕES

### URGENTES (Esta semana)
1. **Investigar contratos outliers**
   - Verificar autenticidade dos maiores contratos
   - Confirmar documentação
   - Se erro: corrigir imediatamente

2. **Melhorar taxa de conversão**
   - Taxa atual: 3.2%
   - Meta: Dobrar taxa para {taxa_conversao*2:.1f}%
   - Implementar qualificação de leads

### CURTO PRAZO (Próximo mês)
3. **Análise de DealsLost**
   - Entender motivos de perda
   - Implementar campo obrigatório de motivo
   - Criar ações corretivas

4. **Treinamento de equipes**
   - Estudar práticas da equipe Haka
   - Replicar para outras equipes
   - Elevar performance geral


---

## 🎉 CONCLUSÕES

**Total analisado:**
- 30,743 leads
- 990 vendas fechadas
- R$ 1,263,443,142.91 em valor total
- 110 vendedores
- 20 equipes

**🔒 RELATÓRIO CONFIDENCIAL - USO INTERNO ONLY**
**DADOS SENSÍVEIS: NÃO COMPARTILHAR EXTERNAMENTE**
