# ✍️ Demo 06: Prompt Engineering
**Duração:** 15 minutos  
**Objetivo:** Transformar dados não estruturados em JSON

---

## 👥 Hands-On

### 🧪 **Exercício: Estruturação de Dados**

**Dados bagunçados para praticar:**

```
📧 EMAIL DE VENDAS:
"Oi pessoal! Fechamos mais alguns negócios:
- Cliente Empresa ABC fechou contrato de consultoria por 50 mil
- João da XYZ Ltda quer o pacote premium (R$ 25.000) 
- Maria falou que aprova os 15k do projeto básico
- Empresa DEF está interessada no plano anual de 100 mil reais"
```

**Template de prompt:**

```
🎯 PROMPT ESTRUTURADO:
"Extraia dados de vendas em JSON:

Formato:
{
  "contratos": [
    {
      "cliente": "string",
      "tipo": "string",
      "valor": number,
      "status": "fechado|interessado|aprovado"
    }
  ]
}

[INSERIR DADOS AQUI]

JSON:"
```

### 💡 **Técnicas Importantes**

```
✅ PROMPT BOM:
- Especificar formato exato
- Dar exemplos (few-shot)
- Definir regras claras
- Usar "responda APENAS com JSON"

❌ PROMPT RUIM:
- "Extraia os dados"
- Sem formato específico
- Sem exemplos
- Sem regras
```

---

## 🛠️ Troubleshooting

### ❌ **JSON inválido**
- Usar temperature=0 (determinístico)
- Especificar formato exato
- Pedir para verificar sintaxe

### ❌ **Dados inconsistentes**
- Dar mais exemplos (few-shot)
- Ser mais específico nas regras
- Usar chain of thought

### ❌ **Informações inventadas**
- Instruir para usar null quando não souber
- Adicionar "baseie-se apenas no texto"
- Validar outputs críticos
