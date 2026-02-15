# Consumismo de Bicicleta
Este repositório contém uma análise abrangente de um conjunto de dados demográficos e comportamentais composto por 11.000 registros de consumidores. O estudo examina padrões de renda, comportamento de compra e características sociodemográficas da população amostrada.

## Índice

- [Descrição do Dataset](#descrição-do-dataset)
- [Estrutura dos Dados](#estrutura-dos-dados)
- [Principais Descobertas](#principais-descobertas)
- [Análise Detalhada](#análise-detalhada)
- [Metodologia](#metodologia)
- [Conclusões](#conclusões)

### Visão Geral

O dataset analisado compreende informações detalhadas de 11.000 indivíduos, coletadas com o objetivo de compreender perfis socioeconômicos e padrões de consumo. Os dados foram estruturados para permitir análises multidimensionais considerando variáveis demográficas, econômicas e comportamentais.


### Período e Escopo

- **Tamanho da Amostra**: 11.000 registros
- **Tipo de Dados**: Transversais (cross-sectional)
- **Cobertura Geográfica**: Duas regiões principais (Europa e Pacífico)

## Estrutura dos Dados

### Variáveis Disponíveis

O dataset contém as seguintes variáveis:

| Variável | Tipo | Descrição | Valores Possíveis |
|----------|------|-----------|-------------------|
| **ID** | Numérico | Identificador único do registro | 12496 - 34400+ |
| **Marital Status** | Categórica | Estado civil | Married, Single |
| **Gender** | Categórica | Gênero | Male, Female |
| **Income** | Numérica | Renda anual em dólares | $10,000 - $170,000 |
| **Children** | Numérica | Número de filhos | 0 - 5 |
| **Education** | Categórica | Nível educacional | High School, Partial High School, Partial College, Bachelors, Graduate Degree |
| **Occupation** | Categórica | Tipo de ocupação | Manual, Skilled Manual, Clerical, Professional, Management |
| **Home Owner** | Booleana | Proprietário de imóvel | Yes, No |
| **Cars** | Numérica | Quantidade de automóveis | 0 - 4 |
| **Commute Distance** | Categórica | Distância de deslocamento | 0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, 10+ Miles |
| **Region** | Categórica | Região geográfica | Europe, Pacific |
| **Age** | Numérica | Idade do indivíduo | 33 - 63 anos |
| **Age Range** | Categórica | Faixa etária classificada | Adult, Senior |
| **Purchased Bike** | Booleana | Compra de bicicleta | Yes, No |


## Principais Explorações

### 1. Análise de Renda por Gênero

#### Distribuição Geral
- **Renda Média Total**: $56.360
- **Renda Média - Mulheres**: $54.875
- **Renda Média - Homens**: $58.063

#### Diferencial de Gênero
- Diferença absoluta: **$3.188** (5,8% superior para homens)
- O gap salarial observado reflete disparidades comuns em mercados de trabalho globais

### 2. Comportamento de Compra de Bicicletas

#### Por Gênero

**Mulheres:**
- Não compraram: $53.440 (média de renda)
- Compraram: $55.774 (média de renda)
- **Diferença**: +$2.334 (+4,4%)

**Homens:**
- Não compraram: $56.208 (média de renda)
- Compraram: $60.124 (média de renda)
- **Diferença**: +$3.916 (+7,0%)

#### Insights Comportamentais
- Consumidores com maior renda apresentam maior propensão à compra de bicicletas
- O efeito renda é mais pronunciado entre homens (+7,0%) do que entre mulheres (+4,4%)
- Sugere que a decisão de compra de bicicletas está positivamente correlacionada com poder aquisitivo

### 3. Perfil Demográfico

#### Distribuição Etária
- **Faixa predominante**: Adultos (Adult)
- **Idade mínima observada**: 33 anos
- **Idade máxima observada**: 63 anos
- Presença de categoria "Senior" para idades mais avançadas

#### Estado Civil
- Representação equilibrada entre casados (Married) e solteiros (Single)
- Variação no número de filhos (0-5 dependentes)

#### Educação
Níveis educacionais identificados:
- Graduate Degree (Pós-graduação)
- Bachelors (Bacharelado)
- Partial College (Superior incompleto)
- High School (Ensino médio)
- Partial High School (Ensino médio incompleto)

#### Ocupação
Categorias profissionais distribuídas em:
- Management (Gestão)
- Professional (Profissional qualificado)
- Skilled Manual (Manual especializado)
- Clerical (Administrativo)
- Manual (Trabalho manual)

### 4. Características Socioeconômicas

#### Propriedade de Imóvel
- Distribuição entre proprietários e não-proprietários
- Possível correlação com renda e estabilidade financeira

#### Posse de Automóveis
- Variação de 0 a 4 veículos por domicílio
- Indicador de status socioeconômico

#### Distância de Deslocamento
Categorias observadas:
- Curta distância: 0-1 Miles
- Distância média: 1-2 Miles, 2-5 Miles
- Longa distância: 5-10 Miles, 10+ Miles

#### Distribuição Geográfica
- **Europa**: Presença significativa na amostra
- **Pacífico**: Segunda região principal
---

## Análise Detalhada

### Padrões de Renda

#### Estatísticas Descritivas
- **Renda Mínima**: $10.000
- **Renda Máxima**: $170.000
- **Amplitude**: $160.000
- **Renda Modal**: Concentração entre $20.000 - $80.000

#### Distribuição por Perfil
Observa-se heterogeneidade significativa nos níveis de renda, com:
- Concentração de casos entre $30.000 - $60.000
- Presença de outliers em ambas as extremidades
- Variação relacionada a fatores como educação, ocupação e região

### Segmentação de Mercado

#### Perfis de Compradores de Bicicletas

**Perfil Alto Potencial:**
- Renda superior à média
- Predominância masculina
- Possível correlação com estilo de vida ativo

**Perfil Padrão:**
- Renda próxima à média geral
- Distribuição mais equilibrada entre gêneros

#### Fatores Influenciadores
Variáveis que potencialmente impactam a decisão de compra:
1. **Renda**: Efeito positivo e significativo
2. **Gênero**: Diferenças no comportamento de compra
3. **Distância de deslocamento**: Pode indicar necessidade de mobilidade alternativa
4. **Região**: Possíveis diferenças culturais e infraestruturais

---
## Metodologia

### Coleta de Dados
- Amostra de 11.000 observações
- Coleta transversal (cross-sectional)
- Variáveis múltiplas capturando aspectos demográficos, econômicos e comportamentais

### Técnicas de Análise
- **Análise Descritiva**: Cálculo de médias, medianas e distribuições
- **Análise Comparativa**: Comparação entre grupos (gênero, compradores vs não-compradores)
- **Segmentação**: Identificação de perfis distintos na população

### Limitações
- Dados transversais não permitem inferências causais definitivas
- Ausência de informações temporais para análise longitudinal
- Possível viés de seleção não avaliado nesta análise preliminar
---

## Conclusões

### Principais Achados

1. **Gap Salarial**: Existe uma diferença de renda de aproximadamente 5,8% entre homens e mulheres, com homens apresentando renda média superior.

2. **Renda e Comportamento de Compra**: Consumidores que adquiriram bicicletas apresentam renda média superior aos que não adquiriram, sugerindo que o produto analisado pode estar posicionado em um segmento de mercado de renda média-alta.

3. **Diferenças de Gênero no Comportamento**: O efeito da renda sobre a propensão de compra é mais acentuado entre homens (+7,0%) do que entre mulheres (+4,4%), indicando possíveis diferenças nas motivações ou barreiras à compra.

4. **Diversidade Socioeconômica**: O dataset captura uma população heterogênea com ampla variação em renda, educação, ocupação e características familiares.
---

### Suposições Práticas

**Para Marketing e Vendas:**
- Segmentar campanhas considerando níveis de renda
- Desenvolver estratégias diferenciadas por gênero
- Considerar fatores geográficos e de mobilidade

**Para Desenvolvimento de Produtos:**
- Avaliar posicionamento de preço atual
- Explorar oportunidades em segmentos de renda média
- Considerar adaptações regionais

**Para Pesquisas Futuras:**
- Investigar causas do gap salarial observado
- Aprofundar análise de fatores motivacionais para compra
- Realizar estudos longitudinais para compreender mudanças temporais
