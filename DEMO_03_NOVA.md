# 🆕 Demo 03: Amazon Nova + Comparação de Modelos
**Duração:** 20 minutos  
**Objetivo:** Comparar diferentes modelos de IA

---

## 👥 Hands-On

### 🧪 **Teste Comparativo**

```
📱 CONFIGURAÇÃO:

1️⃣ Abrir 3 abas do Text Playground
2️⃣ Configurar modelos:
   - Aba 1: Claude 3.5 Sonnet
   - Aba 2: Amazon Nova Pro
   - Aba 3: Amazon Nova Lite

3️⃣ Usar MESMO prompt em todas as abas
4️⃣ Cronometrar tempo de resposta
5️⃣ Comparar qualidade das respostas
```

**Prompts por Setor:**

```
🏦 FINANCEIRO:
"Analise os riscos de investir em criptomoedas para um fundo de pensão. Liste 5 riscos principais e 3 estratégias de mitigação."

🏥 SAÚDE:
"Crie um protocolo de triagem para emergência hospitalar que reduza tempo de espera em 40%. Inclua critérios objetivos."

🏭 INDÚSTRIA:
"Desenvolva um plano de manutenção preditiva para reduzir paradas não programadas em 50%. Inclua tecnologias e cronograma."

🛒 VAREJO:
"Estratégia de personalização de ofertas que aumente conversão em 25%. Inclua segmentação de clientes e canais."
```

### 📊 **Tabela de Comparação**

```
📋 PREENCHER DURANTE O TESTE:

| Critério | Claude 3 Sonnet | Nova Pro | Nova Lite |
|----------|-----------------|----------|-----------||
| ⏱️ Velocidade (segundos) | ___ | ___ | ___ |
| 🎯 Qualidade (1-5) | ___ | ___ | ___ |
| 📝 Estrutura da resposta | ___ | ___ | ___ |
| 🎪 Adequação ao seu setor | ___ | ___ | ___ |
```

### 💡 **Quando Usar Cada Modelo**

```
🚀 CLAUDE 3.5 SONNET:
✅ Análises complexas e profundas
✅ Conteúdo criativo e elaborado
✅ Quando qualidade > velocidade

🔥 AMAZON NOVA PRO:
✅ Multimodalidade (texto + imagem)
✅ Tarefas complexas com boa velocidade
✅ Integração nativa com AWS

⚡ AMAZON NOVA LITE:
✅ Respostas rápidas e diretas
✅ Alto volume de requisições
✅ Custo-benefício excelente
```

---

## 🛠️ Troubleshooting

### ❌ **Nova não disponível**
- Verificar região (us-east-1 ou us-west-2)
- Verificar model access
- Usar Titan Text como alternativa

### ❌ **Respostas muito similares**
- Usar prompts mais específicos
- Testar tarefas diferentes (criativa vs analítica)
- Ajustar temperatura se disponível

### ❌ **Custo não aparece**
- É estimativa baseada em tokens
- Consultar pricing page da AWS
- Focar na comparação relativa
