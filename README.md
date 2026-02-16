## Guia de Markdown HTML e outros, simples para início


## 📚️ Sumário
- [Estrutura de Títulos](#estrutura-de-títulos)
- [Lista ordenada](#lista-ordenada)
- [Destaques de Texto](#destaques-de-texto)
- [imagens](#imagens)   

---

### Estrutura de Títulos

> Use <span style="color:#00FFFF">"#"</span> Na frente de cada título

&nbsp;

# Título 1 > `"# TÍTULO"`
## Título 2 > `"## TÍTULO"`
### Título 3 > > `"### TÍTULO"`
#### título 4 > `"##### TÍTULO"`
##### Título 5 > `"##### TÍTULO"` 
###### título 6 > `"###### TÍTULO"`

---

### Lista ordenada
🔀 Quando a *Ordem* da lista não importa

> Use <span style="color:Red">"-"</span> 
no *Início* de cada item

- Exemplo
- Exemplo
- Exemplo 
  
 #### Quando a *Ordem* dos itens importa

1. exemplo 
2. Exemplo
3. Exemplo 

+ também podemos fazer uma lista com `+`, `-`, ou `*`
+ sub lista com 2 espaços:
  - bem assim.
  - marque um caráter e force ele começar uma lista nova:
    * podemos criar com um asteristco
    + com o símbolo de mais
    - e com um menos
        - :D
  
+ bem fácil 🕺

###### Como realmente se faz/fica:

```md 
+ fazer lista com `+`, `-`, or `*`
+ Sub Listas aqui:
  - também com outros carácteres:
    * podemos criar com um asteristco
    + com o símbolo de mais
    - e com um menos
+ hell yeah
```

### 📊 Tabela simples

| Nome | Idade | Cidade |
| --- | --- | --- |
| Ana | 22  | SP  |
| Leo | 19  | RJ  |
| Leoncio | 30 | MT |

###### Como se faz/fica:

```md
| Nome | Idade | Cidade |
| --- | --- | --- |
| Ana | 22  | SP  |
| Leo | 19  | RJ  |
```

---

### Destaques de Texto 

 &nbsp;

*Texto em itálico* > usamos "*" no início e fim do texto

**Texto em negrito** > deta vez "**" no início e fim

 ***Combinação de Negrito e Itálico*** > Com "***"

`Texto inline` > usamos a crase "`" no início e fim 

###### <small>agora a parte empolgante hehe

#### 🎨 Textos destacados 

| Código | resultado |
| --- | --- |
| `<span style= "color: red">Texto</span>`| <span style="color: red"> Texto em vermelho</span> |
| `<span style="color: #00FF7F">Texto</span>` | <span style="color: #00FF7F">Texto em verde</span> |
| `<span style="background-color: #b8731f; color: #fff">Texto</span>` | <span style="background-color: #b8731f; color: #fff">Texto marcado</span> |

// correções de seu love S2 :)
### Opção 1: Usando LaTeX (Cores reais no texto)

Esta e uma forma de colorir palavras específicas dentro de uma frase ou tabela no GitHub

| Estilo | Código para copiar | Resultado (Como aparece no GitHub) |
| --- | --- | --- |
| **Vermelho** | `$\color{red}{\text{Texto em vermelho}}$` | $\color{red}{\text{Texto em vermelho}}$ |
| **Verde** | `$\color{#00FF7F}{\text{Texto em verde}}$` | $\color{#00FF7F}{\text{Texto em verde}}$ |
| **Laranja** | `$\color{orange}{\text{Texto laranja}}$` | $\color{orange}{\text{Texto laranja}}$ |
| **Azul** | `$\color{blue}{\text{Texto azul}}$` | $\color{blue}{\text{Texto azul}}$ |

---

### Opção 2: Usando blocos de Código `diff`

Se você quer destacar uma linha inteira como se fosse um erro (vermelho) ou um sucesso (verde), use o marcador `diff`. É muito comum em documentações.

```markdown
```diff
- Texto em vermelho (use o sinal de menos)
+ Texto em verde (use o sinal de mais)
! Texto em laranja (use o sinal de exclamação)

```
| `$\color{red}{Texto}$`| $\color{red}{texto}$ |
| `$\color{green}{Texto}$>` | $\color{green}{texto}$ |
| `$\color{blue}{Texto}$` | $\color{Blue}{texto}$ |

---
### Imagens!


```md
![texto altermativo][id da imagem]

também como..

![texto alternativo][imagem]
```

![img](https://ichef.bbci.co.uk/images/ic/512xn/p09j7x4c.jpg.webp)


