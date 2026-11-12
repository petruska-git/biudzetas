# Biudžetas

Paprasta mėnesio išlaidų apskaita telefone (Android ir iPhone). Programėlė įdiegiama iš naršyklės,
veikia be interneto, duomenys saugomi tik telefone.

**Adresas:** https://petruska-git.github.io/biudzetas/

## Įdiegimas

**iPhone (Safari):** atidarykite adresą → apačioje **Bendrinti** (□↑) → **Į pradžios ekraną** → **Pridėti**.

**Android (Chrome):** atidarykite adresą → **Įdiegti** (arba meniu ⋮ → **Įdiegti programą** / **Pridėti prie pagrindinio ekrano**).

## Funkcijos

- Išlaidų pridėjimas: + mygtukas, suma eurais, grupė, data, pastaba
- Grupės: kurti, redaguoti, ištrinti, rikiuoti, mėnesio limitas grupei
- Mėnesio biudžetas; kiekvieno mėnesio 1 d. skaičiavimas prasideda iš naujo
- Istorija pagal mėnesius ir metus
- Grafikai: pagal grupes, per dienas, 12 mėnesių
- Atsarginė kopija (JSON) ir atkūrimas, eksportas į CSV (Excel)

## Svarbu

Duomenys laikomi tik tame telefone. Reguliariai darykite atsarginę kopiją
(Nustatymai → Atsarginė kopija → Išsaugoti) ir laikykite ją Google Drive, iCloud ar el. pašte.

## Techniškai

Vienas statinis puslapis (`index.html`) + `manifest.webmanifest` + `sw.js` (veikimas be interneto).
Jokių priklausomybių ar kompiliavimo. Talpinama per GitHub Pages iš `main` šakos.
