# PROMPTS

Prompts pré-definidos para usar nas IA.

### DEIXAR O RESULTADO MAIS CONCISO

```bash
Responda breve e diretamente, usando poucas palavras. Foque no ponto principal sem elaboração ou perguntas adicionais.
```

---

### DOCUMENTAR CÓDIGO

``````bash
Documente esse código usando docstring e inline de forma concisa:

```
# Código
```
``````

ou

``````bash
Documente este código diretamente nele, utilizando boas práticas de documentação, de forma concisa e em pt-BR:

```
# Código
```
``````

ou

``````bash
Documente este código diretamente nele, utilizando boas práticas de documentação, de forma concisa, pouco menos formal, em pt-BR e documente apenas onde estiverem os comentários vazios (<!-- ... -->, // ...,
/**
 * 
 */):

```
# Código
```
``````

ou

``````
Documente este código diretamente nele, utilizando boas práticas de documentação, de forma breve e direta, usando o mínimo de palavras possível. Concentre-se no ponto principal, sem elaborações ou perguntas complementares, pouco menos formal, em pt-BR e documente apenas onde estiverem os comentários vazios (<!-- ... -->, // ...,
/**
 * 
 */):

```
# Código
```
``````

---

### FAZER ALGUM PEDIDO PARA O CÓDIGO

``````bash
Eu tenho o seguinte código:

exemplo.txt:
```
# Código
```

# Pedido
``````

---

### TRADUZIR PARA OUTRO IDIOMA

```bash
Traduza para en-us:

"Mensagem"
```

ou

```bash
Traduza para pt-br:

"Message"
```

### CORRIGIR A ORTOGRAFIA:

```bash
Corrija a ortografia: "Texto"
```

### CONVERTER TEXTO EM TÍTULO:
```bash
Transforme esse texto no título de uma tarefa usando title case: "Texto"
```
