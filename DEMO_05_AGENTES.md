# 🤖 Demo 05: Agentes Bedrock
**Duração:** 25 minutos  
**Objetivo:** Criar agente que executa ações

---

## 👥 Hands-On

### 🔧 **Criando Agente**

```
📱 CONFIGURAÇÃO BÁSICA:

1️⃣ Menu lateral → "Agents"
2️⃣ Botão "Create Agent"
3️⃣ Nome: "Assistente-[SEUNOME]"
4️⃣ Descrição: "Agente do workshop"

5️⃣ FOUNDATION MODEL:
   - Selecionar: Claude 3.5 Sonnet

6️⃣ INSTRUCTIONS:
   "Você é um assistente útil que pode responder perguntas e executar ações quando solicitado. Seja sempre educado e preciso."

7️⃣ Clicar "Create Agent"
```

### ⚙️ **Adicionando Ações**

```
📱 ACTION GROUP:

1️⃣ Na página do agente → "Action groups"
2️⃣ Botão "Add action group"
3️⃣ Nome: "UtilityActions"
4️⃣ Tipo: "Define with function details"

5️⃣ FUNCTION DETAILS:
   Nome: "get_current_time"
   Descrição: "Retorna data e hora atual"
   Parâmetros: nenhum

6️⃣ Conectar com Lambda function (se disponível)
7️⃣ Salvar configuração
```

---

### 🧪 **Testando o Agente**

```
📱 INTERFACE DE TESTE:

1️⃣ Página do agente → "Test"
2️⃣ Aguardar preparação (1-2min)
3️⃣ Iniciar conversa
```

**Prompts para testar:**

```
🧪 TESTE 1: "Olá! Que horas são?"
🧪 TESTE 2: "Preciso saber se ainda dá tempo de almoçar"
🧪 TESTE 3: "Me ajude a planejar minha tarde"
```

**Observar:**
- Como o agente "pensa" (trace logs)
- Quando decide usar ferramentas
- Como lida com falhas
- Memória da conversa

---

## 🛠️ Troubleshooting

### ❌ **Agente não executa função**
- Verificar permissões Lambda
- Confirmar configuração action group
- Testar função Lambda separadamente
- Verificar logs do agente

### ❌ **Resposta muito lenta**
- Otimizar código Lambda
- Reduzir complexidade das instruções
- Usar modelo mais rápido (Nova Lite)
- Implementar timeout adequado

### ❌ **Agente "alucina" ações**
- Ser mais específico nas instruções
- Limitar escopo de ações
- Adicionar validações
- Usar guardrails
