# 🥊 Projeto ICD - Análise Preditiva de Resultados do UFC

## 👥 Equipe
- **João Vitor Chaves de Souza**
- **João Rafael da Silva Sousa**
- **Diego de Sousa Maciel**
- **Nathan David Figueiredo Barros**

## 🎯 Objetivo do Projeto

Desenvolver um sistema de **análise preditiva de lutas do UFC** através da identificação e classificação de arquétipos de lutadores, permitindo prever probabilidades de vitória em confrontos diretos baseado em características técnicas e estatísticas históricas.

## 📊 Metodologia

### Coleta de Dados
- Compilação de dados abrangentes sobre lutadores do UFC
- Análise de estatísticas de performance, estilos de luta e histórico
- Tratamento e normalização dos dados para análise comparativa

### Técnicas Aplicadas
- **Machine Learning** para classificação de arquétipos
- **Análise estatística** para identificação de padrões
- **Clustering** para segmentação de perfis de lutadores
- **Análise preditiva** para estimativa de probabilidades

---

## 🔍 Descobertas: Os 5 Arquétipos do UFC

Nossa análise revelou **1.669 lutadores** distribuídos em **5 arquétipos distintos**, cada um com características técnicas e estratégicas únicas:

### 1. 🛡️ **Lutadores Básicos**
**279 lutadores (16.7%)**

**Perfil**: Atletas em desenvolvimento ou com habilidades equilibradas sem especialização clara.

**Características Técnicas**:
- Baixa absorção de golpes significativos
- Volume reduzido de quedas executadas
- Poucos knockdowns registrados
- Taxa baixa de finalizações

**Estratégia Típica**: Abordagem conservadora focada em fundamentos, evitando riscos desnecessários.

---

### 2. 🛡️ **Especialistas Defensivos**
**603 lutadores (36.1%)**

**Perfil**: Lutadores técnicos com excelência em defesa e controle de distância.

**Características Técnicas**:
- ⭐ **Melhor defesa contra golpes**: 63% de eficiência
- ⭐ **Excelente defesa contra quedas**: 69% de eficiência
- Absorção mínima de danos
- Estilo técnico e calculado

**Estratégia Típica**: Controle de ritmo e distância, priorizando defesa sólida e oportunidades técnicas.

---

### 3. 🤼 **Grapplers Finalizadores**
**275 lutadores (16.5%)**

**Perfil**: Especialistas em luta no chão com foco em submissões e controle posicional.

**Características Técnicas**:
- ⭐ **Maior volume de quedas**: 2.93 por luta
- ⭐ **Maior taxa de finalizações**: 1.41 por luta
- Boa precisão no striking
- Baixa absorção de golpes em pé

**Estratégia Típica**: Transição para luta no chão e busca ativa por finalizações.

---

### 4. 👊 **Strikers Agressivos**
**351 lutadores (21.0%)**

**Perfil**: Especialistas em trocação com alto volume ofensivo e estilo dinâmico.

**Características Técnicas**:
- ⭐ **Maior volume ofensivo**: 4.97 golpes conectados por minuto
- Alta absorção de golpes (estilo "guerra")
- Boa defesa contra quedas (66%)
- Ritmo acelerado e pressão constante

**Estratégia Típica**: Trocação em pé, pressão ofensiva contínua e volume alto de golpes.

---

### 5. 💥 **Nocauteadores Elite**
**161 lutadores (9.7%)**

**Perfil**: Atletas com poder de nocaute excepcional e capacidade de finalização em pé.

**Características Técnicas**:
- ⭐ **Maior poder de nocaute**: 1.24 knockdowns por luta
- Alto volume ofensivo: 4.53 golpes conectados por minuto
- Boa defesa contra quedas (65%)
- Precisão e poder devastadores

**Estratégia Típica**: Busca ativa pelo nocaute com golpes de alto impacto.

---

## 📈 Insights e Descobertas

### 🎯 Principais Achados

1. **Evolução Técnica do Esporte**: A predominância de "Especialistas Defensivos" (36.1%) indica a crescente sofisticação técnica no UFC

2. **Diversidade Estratégica**: A distribuição equilibrada entre arquétipos demonstra múltiplas abordagens viáveis para o sucesso

3. **Especialização vs Versatilidade**: Cada arquétipo desenvolveu pontos fortes específicos como vantagem competitiva

4. **Eficiência vs Volume**: Diferentes filosofias de combate coexistem no mais alto nível

### 🔮 Aplicações Práticas

#### Para Atletas
- **Autoconhecimento**: Identificação do próprio arquétipo e potencial
- **Desenvolvimento**: Estratégias específicas baseadas no perfil individual
- **Matchmaking**: Compreensão de compatibilidades e desafios estilísticos

#### Para Equipes Técnicas
- **Personalização de Treinos**: Programas específicos por arquétipo
- **Análise de Oponentes**: Identificação de pontos fracos e fortes
- **Estratégia de Luta**: Planos táticos baseados em dados

#### Para Analistas e Mídia
- **Previsões**: Modelos preditivos para resultados de lutas
- **Narrativas**: Histórias baseadas em arquétipos e estilos
- **Educação**: Explicação técnica para audiências diversas

#### Para Organizações
- **Matchmaking Inteligente**: Lutas mais balanceadas e interessantes
- **Desenvolvimento de Talentos**: Identificação precoce de potencial
- **Marketing**: Promoção baseada em arquétipos e narrativas


## 📁 Estrutura do Projeto

```
projeto-icd/
├──lutadores.csv              # Datasets utilizados                                       
├──data.ipynb                 # Análises exploratórias
└── README.md         
```

## 🔄 Próximos Passos

- Expansão para outras organizações de MMA
- Incorporação de dados biomecânicos
- Desenvolvimento de aplicação web interativa
- Refinamento dos modelos preditivos



**Projeto desenvolvido como parte da disciplina de Introdução à Ciência de Dados**
