# Procesas

- [x] pradine failu struktura
    - index.html
    - .gitignore
    - main.css (bet ne butinai viena)
- [] paviesinti projekta per Github (gausim URL)
- [] README.md
    -skirta aprasyti kas, ka ir kodel daro
    -iterpti nuoroda i daroma dizaina
    -iterpti nuoroda, kur tas musu kodas gali buti pamatytas
- [] atlikti dizaino analize
- [] surasyti HTML
- [] issikirpti nuotraukas ir jas panaudoti
    -panaudoti reliatyvu kelia
- [] aprasome stiliu
    -turinys turi buti centre
    -pagrindinis plotis turi buti fiksuotas
- [] atskiri puslapiai, kurie naviguoja "ratu"
    -sign up
    -sign in
    - forgot password
- [] css turi buti tik vienas failas, kur stiliaus taisykles veikia vienodai per visus puslapius

# Pozicionavimas

1. vaikui duodam `position:absolute;`
2. artimiausiam logiskam teviniam elementui, kuri norim tureti kaip atskaitos taska, suteikiame:
    a) `position: relative`, jeigu tas elementas neturi kitokiu `position` savybiu;
    b) paliekame tokia `position` savybe kokia tas elementas turi, jei nurodytas;
Isvada:
absoliuciai pozicionuojamas elementas bus pastatytas artimiausio ne `position: static` elemanto atzvilgiu.