# gyakorlas
1. Módosítottam a gépemen egy fájlt, hogyan tudom felpusholni a változtatásaimat githubra?
-git add .
-git commit -m "commit message"
-git push

2. Clone-oztam egy repositorymat githubról. Ahhoz, hogy pusholjak szükségem lesz valamilyen azonosítási módra. Mivel a jelszó felhasználónév nem működik, ezért más azonosítási módot kell keresnem. Úgy döntök tokennel fogom magamat azonosítani. Milyen tokenre van szükségem?
-personal access token

3. Módosítottam a gépemen egy fájlt, de amikor commitolni próbálom azt írja ki, hogy "no changes added to commit". Mit felejtettem el?
-Nem választottuk ki,  hogy mit akarunk committelni. (Git add .)

4. Módosítottam egy fájlt hozzáadtam egy commithoz, de amikor push parancsra azt írja ki, hogy "Everything up-to-date". Mit felejtettem el?
-Nem adtuk meg a git commmit -m "" parancsot

5. Szeretnék lokálisan egy új branchet létrehozni az aktuális branchről. Milyen paranccsal tudom ezt megtenni?
-Git checkout -b [New-Branch_Name]

6. Megtetszett egy publikus repository githubon, szeretném átmásolni a saját accountomra, hogy jövőbeni módosításaimat fel tudjam pusholni. Mit kell tennem?
-Le kell forkolni

7. Szeretnék visszalépni egy 2-vel ezelőtti commitomra. Milyen lépésekre és információkra van szükségem?
-Git log -> Ezzel kilistázzuk az előző commitjeinket
-Git Checkout [Commit url](Az a hosszú sárga számsor és betűsor) ->Ezzel visszalépünk a korábbi commitre

8. Módosítottam egy fájlt, de rossz branchen vagyok. Hogyan tudom egy új branchre commitolni a változtatásaimat?
-Git checkout -b [branch_name] -> Ezzel átállunk a kívánt új branchre
-Git add .
-Git commit -m "commit message"


9. Az alábbi két css szabályom van:
table tbody tr td {
    background-color: red;
}

table tbody tr {
    background-color: blue;
}

Milyen színű lesz a táblázat sorainak háttérszine?
-Piros


10. Az alábbi két css szabályom van:
table tr {
    background-color: red;
}

table tbody tr {
    background-color: blue;
}

Milyen színű lesz a táblázat sorainak háttérszine?
-Kék


11. Az alábbi két css szabályom van:
table tr td {
    background-color: red;
}

table tbody tr {
    background-color: blue;
}

Milyen színű lesz a táblázat sorainak háttérszine?
-piros


12. Az alábbi két css szabályom van:
table tbody tr:nth-child(2n){
    background-color: blueviolet;
}

tbody tr {
    background-color: red;
}

Milyen színű lesz a táblázat páros sorainak háttérszine?
-Blueviolet

13. Az alábbi két css szabályom van:
tbody tr:nth-child(2n){
    background-color: blueviolet;
}

table tbody tr td{
    background-color: red;
}

Milyen színű lesz a táblázat páros sorainak háttérszine?
-piros

14. Milyen css pseudo classal tudom megadni, hogy megváltozzon a css szabály ha egy elem fölé viszem az egeret?
- :hover

15. Hogyan tudom beállítani, hogy a táblázat celláinak szegélyei ne duplázódjanak meg?
-border-collapse: collapse

16. Milyen tagek közé írjuk a táblázat fejlécét?
-thead

17. Milyen tagek közé írjuk a táblázat fejlécének celláit?
-th

18. Milyen tagek közé írjuk a táblázat sorait?
-tr

19. Milyen tagek közé írjuk a táblázat celláit?
-td

20. Lehet-e egy táblázatnak több soros fejléce?
-igen

21. Milyen tagek közé írjuk a táblázat törzsét?
-tbody

22. Lehetséges-e a következő:
let a = 5;
a=7
-igen

23. Lehetséges-e a következő:
let a = 5;
a="7"
-Igen

24. Lehetséges-e a következő:
const b = 5;
b="7"
-Nem

25. Lehetséges-e a következő:
const b = 5;
b=7
-Nem

26. Lehetséges-e a következő:
let pers = {fname: "Laci", lname: "Kovács" }
pers = {fname: "Ferenc", lname: "Balogh" }
-Igen

27. Lehetséges-e a következő:
const pers = {fname: "Laci", lname: "Kovács" }
pers = {fname: "Ferenc", lname: "Balogh" }
-Nem

28. Lehetséges-e a következő:
const pers = {fname: "Laci", lname: "Kovács" };
pers.fname="Ferenc";
pers.lname="Balogh";
-Igen

29. Lehetséges-e a következő:
let pers = {fname: "Laci", lname: "Kovács" };
pers.fname="Ferenc";
pers.lname="Balogh";
-Igen

30. Lehetséges-e a következő:
let pers = {fname: "Laci", lname: "Kovács" };
pers.married = true;
-Igen

31. Lehetséges-e a következő:
const pers = {fname: "Laci", lname: "Kovács" };
pers.married = true;
-Igen

32. Lehetséges-e a következő:
const personList = [];
personList = [{fname: "Laci", lname: "Kovács" }]
-Nem

33. Lehetséges-e a következő:
const personList = [];
personList.push({fname: "Laci", lname: "Kovács" })
-igen

34. Lehetséges-e a következő:
let personList = [];
personList = [{fname: "Laci", lname: "Kovács" }]
-igen

35. Létreszeretnék hozni egy táblázatot, és hozzáadni a bodyhoz javascriptben. Mi lehetne a kód?
-const table = document.createElement('table');
-document.body.appendChild(table);

36. Létrehoztam már egy táblázatot js-ben és eltároltam egy table változóban. Hogyan tudok hozzáadni egy sort és a sorhoz két cellát (a tbody tag nem kötelező eleme a table-nek)?
-const tr = document.createElement('tr');
-table.appendChild(tr);

-const td_1 = document.createElement("td");
-tr.appendChild(td_1);

-const td_2 = document.createElement("td");
-tr.appendChild(td_2);

37. Létrehoztam már egy táblázatot js-ben és eltároltam egy table változóban. Hogyan tudok hozzáadni két sort és mindkét sorhoz egy-egy cellát (a tbody tag nem kötelező eleme a table-nek)?
-const tr_1 = document.createElement('tr');
-table.appendChild(tr_1);

-const td_1 = document.createElement("td");
-tr_1.appendChild(td_1);

-const tr_2 = document.createElement('tr');
-table.appendChild(tr_2);

-const td_2 = document.createElement("td");
-tr_2.appendChild(td_2);


38. Mi a különbség az == és a === között?
-A === megnézi a változó/érték típusát is, a == pedig nem

39. Milyen property változtatásával tudjuk egy tábla 2 celláját összevonni?
-colspan

40. Milyen property változtatásával tudjuk egy tábla 2 sorát összevonni?
-rowspan

41. Milyen property változtatásával tudjuk egy javascriptben létrehozott html elementnek megadni, hogy a html tag-ek között mi szerepeljen?
-innerHTML