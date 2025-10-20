# ✅ Checklist de Preparação Pré-Workshop
**Workshop:** IA Generativa AWS - 2h30  
**Formato:** Hands-On via Console AWS

---

## 📅 Preparação

### 🗓️ **1 Semana Antes**
- [ ] **Conta AWS configurada** com billing alerts
- [ ] **Região definida** (us-east-1 ou us-west-2)
- [ ] **Todos os modelos habilitados** (ver seção Modelos)
- [ ] **Demos testadas** em ambiente limpo
- [ ] **Credenciais temporárias** criadas
- [ ] **Material de apoio** preparado

### 🗓️ **1 Dia Antes**
- [ ] **Ambiente final** testado
- [ ] **Internet e projeção** validados
- [ ] **Canal de suporte** ativo

### 🗓️ **30min Antes**
- [ ] **Consoles AWS** abertos e testados
- [ ] **Credenciais** distribuídas
- [ ] **Material** organizado

---

## 🔧 Configuração Técnica AWS

### 🎯 **Modelos Obrigatórios**

**Acesso aos modelos via Console → Bedrock → Model access:**

```
✅ MODELOS ESSENCIAIS:
- Anthropic Claude 3.5 Sonnet
- Amazon Nova Pro  
- Amazon Nova Lite
- Amazon Titan Embeddings G1 - Text
- Amazon Titan Text G1 - Express

⚠️ TEMPO DE APROVAÇÃO:
- Modelos Anthropic: Instantâneo
- Modelos Amazon Nova: Até 24h
- Modelos Titan: Instantâneo
```

### 📋 **Recursos de Backup**

**Ter prontos para emergência:**

```
🛡️ GUARDRAIL BACKUP:
Nome: "Workshop-Backup-Guardrail"
Content Filters: todos HIGH
Denied Topics: informações confidenciais, senhas

📚 KNOWLEDGE BASE BACKUP:
Nome: "Workshop-Demo-KB"
Documentos: PDFs de exemplo preparados

🤖 AGENTE BACKUP:
Nome: "Workshop-Demo-Agent"
Função: get_current_time
```

---

## 👥 Material de Apoio

### 📄 **Guia Rápido para Participantes**

```
🔗 LINKS ESSENCIAIS:
- Console Bedrock: https://console.aws.amazon.com/bedrock/
- Text Playground: Menu → Text Playground
- Guardrails: Menu → Guardrails  
- Knowledge Bases: Menu → Knowledge bases
- Agents: Menu → Agents

🆘 TROUBLESHOOTING RÁPIDO:
- Erro de permissão → Verificar região (us-east-1)
- Modelo indisponível → Verificar model access
- Resposta lenta → Aguardar 10-15 segundos
```

### 💾 **Material Digital Necessário**

- [ ] **Documentos PDF** para testes de RAG
- [ ] **Imagens de exemplo** para visão computacional  
- [ ] **Templates de prompts** prontos
- [ ] **Credenciais temporárias** distribuídas

---

## 💰 Orçamento Estimado

```
📊 CUSTOS AWS (20 participantes, 2.5h):
- Modelos: ~$100
- Serviços: ~$40
- TOTAL: ~$140
- MARGEM SEGURANÇA: $60
- ORÇAMENTO RECOMENDADO: $200
```

---

## ✅ Checklist Final (30min antes)

### 🔧 **Validação Técnica**
- [ ] **Internet** funcionando
- [ ] **Projeção** clara e visível
- [ ] **Consoles AWS** abertos e testados
- [ ] **Credenciais** distribuídas
- [ ] **Material** organizado

### 👥 **Preparação Final**
- [ ] **Facilitador** preparado
- [ ] **Material** distribuído
- [ ] **Planos B** revisados
