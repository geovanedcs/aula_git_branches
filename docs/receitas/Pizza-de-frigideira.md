# 🍕 Receita de Pizza de Frigideira Express

Uma solução de alta performance para matar a fome nas noites de *deploy* sem precisar esperar o *delivery*.

---

## ⏱️ Informações Gerais

| Item | Detalhe |
| :--- | :--- |
| **Tempo de Preparo** | 5 minutos |
| **Tempo de Frigideira**| 10 minutos |
| **Rendimento** | 1 pizza individual |
| **Dificuldade** | Muito Fácil |

---

## 🛒 Ingredientes

### Massa
- [ ] `1 xícara` de farinha de trigo
- [ ] `1 colher de sopa` de manteiga (ou margarina)
- [ ] `1 pitada` de sal
- [ ] `1/3 xícara` de água morna

### Recheio
- [ ] `2 colheres de sopa` de molho de tomate
- [ ] `100g` de queijo muçarela ralado
- [ ] `4 rodelas` de linguiça calabresa ou presunto
- [ ] `1 pitada` de orégano a gosto

---

## 🥣 Modo de Preparo

1. **Preparar a Massa**
   - Em uma tigela, misture a **farinha de trigo**, o **sal** e a **manteiga**.
   - Adicione a **água morna** aos poucos e misture com as mãos até formar uma massa lisa que não grude.

2. **Abrir e Dourar**
   - Abra a massa com um rolo (ou garrafa limpa) até ficar fina e no tamanho da sua frigideira.
   - Unte levemente a frigideira com azeite, coloque a massa e doure em fogo baixo por cerca de 3 minutos.

3. **Rechear e Finalizar**
   - Vire a massa. Desligue o fogo temporariamente para dar tempo de rechear.
   - Espalhe o **molho de tomate**, cubra com a **muçarela**, a **calabresa** e o **orégano**.
   - Tampe a frigideira, ligue o fogo bem baixo e deixe por cerca de 5 minutos até o queijo derreter completamente.

---

## 💡 Dicas do Dev

> **Otimização:** Quer uma massa estilo pan-pizza mais altinha? Adicione `1/2 colher de chá` de fermento em pó químico junto com a farinha.

```csharp
// Executando task assíncrona da janta
public async Task JantarRapidoAsync()
{
    var pizza = new Pizza { Preparo = "Frigideira", Tempo = 15 };
    await pizza.AssarAsync();

    Console.WriteLine("Refeição pronta sem interromper a build!");
}