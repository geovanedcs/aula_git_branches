# 🥐 Receita de Croissant de Salgado de Nutella e Morango (Com Massa Folhada)

Uma sobremesa gourmet de *deploy* rápido para fechar a *sprint* com chave de ouro.

---

## ⏱️ Informações Gerais

| Item | Detalhe |
| :--- | :--- |
| **Tempo de Preparo** | 10 minutos |
| **Tempo de Forno** | 18 minutos |
| **Rendimento** | 6 mini croissants |
| **Dificuldade** | Fácil |

---

## 🛒 Ingredientes

- [ ] `1 rolo` de massa folhada pronta (refrigerada ou descongelada)
- [ ] `6 colheres de sopa` de Nutella (ou creme de avelã)
- [ ] `6` morangos frescos picados
- [ ] `1` gema de ovo (para pincelar)
- [ ] `1 colher de sopa` de açúcar de confeiteiro (para decorar)

---

## 🥣 Modo de Preparo

1. **Cortar a Massa**
   - Abra a **massa folhada** sobre uma bancada limpa mantendo o papel manteiga.
   - Corte a massa em triângulos compridos (como fatias de pizza finas).

2. **Rechear e Enrolar**
   - Coloque `1 colher de sopa` de **Nutella** na base mais larga de cada triângulo.
   - Adicione alguns pedaços de **morango** sobre o creme.
   - Enrole a massa a partir da base larga em direção à ponta fina, formando o formato de meia-lua.

3. **Assar**
   - Pincela a **gema de ovo** batida sobre a superfície de cada croissant.
   - Leve ao forno pré-aquecido a **200°C** por **15 a 18 minutos**, até ficarem bem dourados e estufados.
   - Polvilhe **açúcar de confeiteiro** por cima assim que sair do forno.

---

## 💡 Dicas do Dev

> **Otimização de Performance:** Certifique-se de que o forno está bem quente (200°C) antes de colocar a massa. O choque térmico é essencial para a massa folhar e criar aquelas camadas crocantes.

```csharp
// Executando sobremesa pós-deploy
public async Task TratarBugGraveAsync()
{
    var croissant = new Sobremesa { Tipo = "Massa Folhada", Recheio = "Nutella + Morango" };
    await croissant.AssarAsync();

    Console.WriteLine("Nível de dopamina reestabelecido com sucesso!");
}