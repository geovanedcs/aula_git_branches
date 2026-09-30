# 🌮 Receita de Guacamole Express com Chips de Doritos ou Torradas

Uma solução leve e cheia de frescor para recarregar as energias após uma maratona de *debug*.

---

## ⏱️ Informações Gerais

| Item | Detalhe |
| :--- | :--- |
| **Tempo de Preparo** | 10 minutos |
| **Tempo de Cozimento**| 0 minutos (Sem fogo) |
| **Rendimento** | 2 a 3 porções |
| **Dificuldade** | Muito Fácil |

---

## 🛒 Ingredientes

- [ ] `2` abacates maduros (ou 4 avocados)
- [ ] `1` tomate médio sem sementes, picado em cubos pequenos
- [ ] `1/2` cebola roxa picada bem fina
- [ ] `1/2` xícara de coentro fresco picado (ou salsinha)
- [ ] `Suco de 1` limão grande
- [ ] `2 colheres de sopa` de azeite de oliva
- [ ] `1 pitada` de pimenta do reino e sal a gosto
- [ ] `1 pacote` de tortilhas, doritos ou torradas para acompanhar

---

## 🥣 Modo de Preparo

1. **Amassar a Base**
   - Corte os **abacates** ao meio, remova o caroço e retire a polpa com uma colher.
   - Em uma tigela, amasse a polpa com um garfo (mantenha alguns pedaços rústicos para dar textura).

2. **Temperar e Misturar**
   - Regue imediatamente com o **suco de limão** para evitar que o abacate escureça (oxidação).
   - Adicione o **tomate**, a **cebola roxa** e o **coentro picado**.
   - Tempere com o **azeite**, o **sal** e a **pimenta do reino**. Misture delicadamente.

3. **Servir**
   - Transfira para um bowl bonito e sirva acompanhado das tortilhas ou torradas.

---

## 💡 Dicas do Dev

> **Garbage Collection (Anti-Oxidação):** Se sobrar guacamole e você precisar guardar na geladeira, coloque o próprio caroço do abacate dentro do pote e vede bem com plástico filme encostando diretamente na superfície da mistura. Isso evita que fique escuro!

```csharp
// Refresco de fim de expediente
public async Task HappyHourAsync()
{
    var guacamole = new Snack { Tipo = "Mexicano", Refrescante = true };
    await guacamole.ServirComTorradasAsync();

    Console.WriteLine("Branch mergeada e snack servido!");
}