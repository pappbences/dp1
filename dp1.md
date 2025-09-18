# 🖥️ **Új feladatsor – Markdown + VS Code + Git + PowerShell**

---

## 🔹 1. blokk – Logolás indítása és mappa előkészítése

1. Nyisd meg a **Visual Studio Code**-ot.
2. Indítsd el a konzolon a logolást, hogy minden parancsod bekerüljön a `log01.txt` fájlba:

```powershell
Start-Transcript -Path .\log01.txt -Append
```

3. Navigálj a `webprogramozas/` mappába:

```powershell
cd z://webprogramozas
ls
```

4. Forkold le és utána Klónozd le a megadott GitHub repót konzolon!:

> [!caution]
> ```powershell
> git clone a SAJÁT REPOD LINKJE
> ```

5. Ha kész vagy, állítsd le a logolást:

```powershell
Stop-Transcript
```

---

> [!CAUTION]
> A feladat során **TILOS mesterséges intelligencia vagy bármilyen más segédeszköz használata - rajta kapás esetén 3db egyes!**.
> Amennyiben a mappa topológiája hibás, most még kijavíthatod.
> Ha így kerül beadásra, a teljes dolgozat **elégtelen** minősítést kap.

---

## 🔹 2. blokk – Új repo megnyitása és második logolás

1. Visual Studio Code-ban nyisd meg a most létrehozott **dp1** repozitóriumot.
2. Indítsd el újra a logolást, most a `log02.txt` fájlba:

```powershell
Start-Transcript -Path .\log02.txt -Append
```

---





## 🔹 3. blokk – Markdown feladatok elkészítése

A `dp1` mappába készítsd el a következő fájlokat:
Segítség: [Markdown Guide](https://www.markdownguide.org/)

### ✏️ Feladatok

1. **`cv.md`**

   # H1 címsor: „Önéletrajz”
   

2. **`projekt.md`**

   # H1 címsor: „Projektek”
   > nem vagyok buzi
   ```Javasricpt
   console.log("szija")
   
   * Egy link egy általad használt weboldalra
   ```
3. **`konyvek.md`**

   * H1 címsor: „Kedvenc könyveim”
   * Táblázat: *Cím – Szerző – Év* (legalább 3 könyv)
   * Egy dőlt betűs mondat a könyvekről

4. **`celok.md`**

   * H1 címsor: „Jövőbeli céljaim”
   * Számozott lista (pl. tanulás, munka, utazás)
   * Táblázat a célokhoz: *Év – Cél – Megvalósítás módja*
   * Egy kép beszúrása internetes linkről

---

## 🔹 4. blokk – Feltöltés GitHub-ra

1. A `dp1` mappában add hozzá a fájlokat:

```powershell
git add .
```

2. Készítsd el a committet:

```powershell
git commit -m "20250917-dp1"
```

3. Küldd fel a központi tárolóba:

```powershell
git push
```

4. Ellenőrizd, hogy a **dp1** repóban megjelentek-e a `log01.txt`, `log02.txt` és az összes `.md` fájl.

5. Ha sikerült, állítsd le a logolást:

```powershell
Stop-Transcript
```

> [!IMPORTANT]
> Add meg ki még egyszer a feltőltést, hogy log2.txt is bekerüljön!
> Ellenőrizd le, hogy minden file és log1 és log2 file is feltöltésre került!



