# Titulo 01
Este é um parágrafo feito em markdown.
## Título 02
### Título 03
#### Título 04
##### Título 05
##### Título 06

# Ênfase 
Negrito: **palavra01**, __palavra02__  
Itálico:  *palavra01*, _palavra02_  
Negrito + Itálico:  ***palavra01***, **_palavra02_**, __*palavra03*__

Riscado: ~~palavra01~~  
Citação: 
> Essa é uma citação

# Linhas Horizontais
### 01:
***
___ 
### 02:
* * * 
_ _ _ 
### 03:
****************
________________

# Listas Não-Ordenadas
* Item
+ Item
- Item 
    * Subitem
        * Subitem
            * Subitem

# Listas Ordenadas
1. Item
2. Item        
***
1. Item 
1. Item

# Links
### 01:
[Google](https://google.com)

### 02:
[YouTube](https://youtube.com "Clique para acessar o YouTube")

### 03:
[var]: https://instagram.com
[Instagram][var]

# Imagens
## Sem Link
![Icone WhatsApp](https://image.freepik.com/free-icon/whatsapp-logo_318-49685.jpg) 
***

![Outra Imagem][imagem]

[imagem]:https://upload.wikimedia.org/wikipedia/commons/7/7e/Cute-Ball-Favorites-icon.png

## Com Link
[![Ache agora](https://d30y9cdsu7xlg0.cloudfront.net/png/14236-200.png)](https://maps.google.com)
***
[var_01]: https://d30y9cdsu7xlg0.cloudfront.net/png/14236-200.png
[var_02]: https://maps.google.com

[![Olha o Mapa!][var_01]][var_02]

# Tabelas
| Nome | Idade | País |
|:-----|:-----:|-----:|
| Raphael | 20 | Brasil |

# Código 
## Linha Simples
`var == var_02`
## Bloco
```
int num;
num = 15;
printf("%d", num);
```
***
    int num;
    num = 15;
    printf("%d", num);

## Sintaze Highlighting 
```C
int num;
num = 15;
printf("%d", num);
```