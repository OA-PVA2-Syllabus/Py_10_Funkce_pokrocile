# SMS brána pokračování
... pokračujeme předchozím příkladem

Zkus svoji první funkci vytunit tak, že si bude umět poradit s mezerami
v telefonním čísle. Mezer se zbavíš tak, že použiješ funkci `replace()` a tečkovou notaci.
První parametr je znak, který chceš nahradit, a druhý parametr nový znak. Níže je příklad
použití.

```python
tel_cislo = "+420 734 123 456"
tel_cislo = tel_cislo.replace(" ", "")
```

## Aktualizace

Nemusíte kontrolovat, zda uživatel zadal skutečně číslo, či zda jsou tam i jiné znaky. To jsme
v kurzu zatím neřešili.

Pokud chcete zkontrolovat předvolbu, stačí využít podmínku `"+420 in cislo`, alternativně můžete využít
indexy. Můžete využít indexy, Python umožňuje kromě jednoho znaku z řetězce získat i více znaků, a to
pomocí řezu a podmínku
`cislo[0:4] == "+420"`.
