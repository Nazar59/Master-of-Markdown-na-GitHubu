#  Fotbalová Příručka Přežití: Od gauče na hřiště

Tento dokument slouží jako ultimátní průvodce pro každého, kdo chce fotbal nejen sledovat, ale i hlouběji chápat. 

##  Úvod do fotbalového šílenství

Fotbal je víc než jen 22 chlapů běhajících za míčem. Je to vášeň, taktika a občas taky105 minut čistého utrpení, když tvůj tým prohrává v 90. minutě.

### Pro koho je tato příručka určena?
- Pro fanoušky, kteří chtějí rozumně diskutovat u pivu.
- Pro hráče, kteří si chtějí zlepšit přehled na hřišti.
- ~Pro každého, kdo si myslí, že ofsajd je jméno nového auta.~ (Přeškrtnuto pro jistotu!)

##  Výbava a povinné úkoly fanouška

Když jde do tuhého, musíš být připraven. *Někdy si říkám, jestli má vůbec smysl kupovat další dres...* ale pak stejně 
**musíš mít ten nejnovější**! 

### Co nesmí chybět v tašce:
1. Kvalitní kopačky nebo pohodlné tenisky.
2. Správný **klubový dres** s číslem tvého oblíbeného hráče.
3. Láhev s pitím a nějaká ta svačina na doplnění energie.

### Můj zápasový To-Do list:
- [x] Koupit lístky na zápas předem
- [x] Zkontrolovat, jestli je dres vypraný
- [ ] Naučit se všechny pokřiky fanoušků
- [ ] Připravit hlasivky na 90 minut fandění

##  Zdroje a vizuální inspirace

Pokud se chceš o fotbale dozvědět víc, doporučuji navštívit [oficiální stránky FIFA](https://www.fifa.com) nebo sledovat statistiky na [portálu Livesport](https://www.livesport.cz).

### Pohled z hřiště
Takhle vypadá ideální fotbalová atmosféra na stadionu:

![Plný stadion fanoušků fandících při zápase](stadium.webp)

##  Analýza zápasu v kódu

Pro sledování statistik si můžeme pomoci jednoduchým skriptem v Pythonu, který spočítá úspěšnost střelby týmu:

```python
def vypocet_uspesnosti(goly, strely):
    if strely == 0:
        return 0.0
    uspesnost = (goly / strely) * 100
    return round(uspesnost, 2)

# Příklad: 3 góly ze 12 střel
print(f"Úspěšnost střelby: {vypocet_uspesnosti(3, 12)} %")
```


## Strukturovaná data
| Vlastnost | Křídelní útočník (Winger) | Defenzivní záložník (CDM) |
| :--- | :--- | :--- |
| **Hlavní úkol** | Oklamat obránce a centrovat | Zničit soupeřův útok |
| **Klíčová vlastnost** | Extrémní rychlost | Perfektní přehled a čtení hry |
| **Riziko** | Zdvojování obránci | Žluté karty za tvrdé zákroky |

