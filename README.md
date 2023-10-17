# Verziókezelés

- helyi repo inicializálása
    > git init
- megadjuk a felhasználó nevünket és emailunket
    > git config user.name Flerzy
    > git config user.email email
- ellenőrizzük
    > git config user.name
    > git config user.email
- ellenőrzés (van-e különbség a repo és munkakönyvtár közt)
    > git status
- előkészítjük a helyi repóba való eltárolásra a fájlokat commitol-ásra (a verzó beindexelése megtörténik)
    > git add .
- ellnőrzés:
    > git status
- commitolás:eltároljuk az aktuális állapotot mint egy verzó
    > git commit -m "first commit"
- ellenőrzés:
    > git status
- az összes verzió megjelenítése:
    > git log
- távoli repo létrehozása: GitHub
- helyi repo és távoli repo összekapcsolása
    > git remote add origin [https://**token@** github.com/Flerzy/reponame.git]
- **első** push parancs alkalmával megkell adni hogy melyik ágba(branch) kerüljön
    >git push -u origin main
- fogja kérni a tokent, kímásoljuk
    > JobbKatt+enter
- a következő módósításkor:
    > git push