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


> Podemos usar estes comando para colorir ou destacar textos a partir do markdown e HTML

---
### Imagens!


```md
![texto altermativo][id da imagem]

também como..

![texto alternativo][imagem]
```

![img](https://ichef.bbci.co.uk/images/ic/512xn/p09j7x4c.jpg.webp)


## ⚠️ Observação de Compatibilidade

Alguns exemplos com HTML e estilos CSS (cores, fundo, gradientes)
funcionam melhor no preview do VS Code e podem não renderizar
da mesma forma no GitHub.
