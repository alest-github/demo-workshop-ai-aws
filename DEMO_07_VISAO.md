# 👁️ Demo 07: Visão Computacional
**Duração:** 15 minutos  
**Objetivo:** Extrair dados de imagens com IA

---

## 👥 Hands-On

### 🔧 **Configuração**

```
📱 SETUP MULTIMODAL:

1️⃣ Text Playground → Claude 3.5 Sonnet
2️⃣ Clicar no ícone de imagem (📎)
3️⃣ Upload da imagem (máx 5MB)
4️⃣ Aguardar processamento
5️⃣ Adicionar prompt contextual
6️⃣ Executar análise
```

### 🧪 **Exercícios Práticos**

**Documentos para testar:**
- Notas fiscais, recibos, cartões de visita
- Formulários preenchidos, contratos
- Diagramas técnicos, screenshots

**Prompts por tipo:**

```
🎯 NOTA FISCAL:
"Extraia dados desta nota fiscal em JSON estruturado. Inclua emissor, destinatário, itens, valores e data."

🎯 CARTÃO DE VISITA:
"Extraia informações de contato: nome, empresa, cargo, telefone, email, endereço."

🎯 FORMULÁRIO:
"Leia este formulário e extraia dados pessoais, campos preenchidos e assinaturas em JSON."

🎯 DIAGRAMA:
"Descreva este diagrama: componentes, conexões, fluxo de processo e anotações importantes."
```

**Verificar se as respostas:**
- ✅ Extraem dados corretamente
- ✅ Estruturam em formato útil
- ✅ Indicam incertezas quando necessário

---

## 🛠️ Troubleshooting

### ❌ **Imagem não processada**
- Verificar formato (JPG, PNG, PDF)
- Reduzir tamanho (máx 5MB)
- Melhorar qualidade da imagem

### ❌ **OCR impreciso**
- Melhorar qualidade da imagem
- Ser mais específico no prompt
- Usar imagem com melhor resolução

### ❌ **Dados inventados**
- Instruir para usar null quando incerto
- Pedir para indicar nível de confiança
- Validar dados críticos manualmente
