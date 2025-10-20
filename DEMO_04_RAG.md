# 📚 Demo 04: RAG Knowledge Base
**Duração:** 30 minutos  
**Objetivo:** Criar chatbot que responde sobre seus documentos

---

## 👥 Hands-On

### 🏗️ **Criando Knowledge Base**

```
📱 PASSO A PASSO:

1️⃣ Menu lateral → "Knowledge bases"
2️⃣ Botão "Create knowledge base"
3️⃣ Nome: "Workshop-KB-[SEUNOME]"
4️⃣ Descrição: "Base de conhecimento do workshop"

5️⃣ DATA SOURCE:
   - Tipo: S3
   - Bucket: Criar automaticamente
   
6️⃣ EMBEDDINGS MODEL:
   - Selecionar: "Titan Embeddings G1 - Text"

7️⃣ VECTOR DATABASE:
   - Selecionar: "Quick create a new vector store"
   
8️⃣ Clicar "Create knowledge base"
```

### 📁 **Upload de Documentos**

**Documentos aceitos:**
- PDF, TXT, DOC/DOCX (máx 10MB)
- Manuais, políticas, FAQs, contratos

```
📱 UPLOAD:

1️⃣ Aguardar KB ser criada (2-3min)
2️⃣ Clicar na KB criada
3️⃣ Aba "Data source" → "Sync"
4️⃣ Upload dos PDFs
5️⃣ Clicar "Sync data source"
6️⃣ Aguardar processamento (5-8min)
```

**Status de processamento:**
- ✅ Uploading documents
- ✅ Chunking documents  
- ✅ Creating embeddings
- ✅ Ready for queries

---

### 🧪 **Testando o Chatbot**

```
📱 CONFIGURAR CHAT:

1️⃣ Voltar ao Text Playground
2️⃣ Advanced settings → Knowledge bases
3️⃣ Selecionar a KB criada
4️⃣ Aplicar configuração
```

**Perguntas para testar:**

```
🔍 TESTE 1: "Qual é a política de reembolso mencionada no documento?"
🔍 TESTE 2: "Resuma os principais benefícios oferecidos."
🔍 TESTE 3: "Quais as diferenças entre os planos básico e premium?"
🔍 TESTE 4: "Com base nos documentos, quais os 3 maiores riscos?"
🔍 TESTE 5: "Crie um checklist baseado no procedimento descrito."
```

**Verificar se as respostas:**
- ✅ Citam fonte específica
- ✅ São precisas ao documento
- ✅ Não inventam informações
- ✅ Indicam quando não sabem

---

## 🛠️ Troubleshooting

### ❌ **Sincronização falhou**
- Verificar formato do documento
- Reduzir tamanho do arquivo
- Verificar permissões do S3
- Tentar novamente em 5 minutos

### ❌ **Respostas imprecisas**
- Melhorar qualidade dos documentos
- Usar documentos mais específicos
- Refinar prompts de pergunta

### ❌ **Não encontra informação**
- Verificar se documento foi indexado
- Reformular pergunta
- Usar termos exatos do documento
- Verificar se informação realmente existe
