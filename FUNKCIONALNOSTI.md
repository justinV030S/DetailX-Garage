# Seznam funkcionalnosti -- DetailX-Garage

## Uvod

Dokument zajema pregled ključnih funkcionalnosti spletne aplikacije **DetailX-Garage**, ustvarjene za potrebe avto detailing studia in njegovih strank. Rešitev digitalizira celotno uporabniško pot: strankam omogoča enostavno izbiro storitev, hiter informativni izračun cene glede na vrsto vozila ter spletno rezervacijo termina.

Vsaka funkcionalnost je označena z unikatno oznako (`F01`–`F12`), kratkim imenom, jedrnatim opisom ter prioritetno oceno implementacije:
- **Visoka (Nujna):** ključna funkcionalnost, brez katere osnovna različica aplikacije ne deluje.
- **Srednja:** pomembna funkcionalnost, ki bistveno izboljša uporabniško izkušnjo in upravljanje studia.
- **Nizka:** dodatna funkcionalnost za nadgradnjo v kasnejših fazah razvoja.

## Preglednica funkcionalnosti

| ID | Kratko ime | Opis | Prioritetna ocena |
| :--- | :--- | :--- | :--- |
| **F01** | Pregled storitev in paketov | Uporabnik lahko pregleduje kategorije detailing storitev (zunanje pranje, globinsko čiščenje, poliranje, keramična zaščita) z opisom vključenih del in osnovno ceno. Pri vsakem paketu vidi tudi okvirni čas trajanja izvedbe. | Visoka (Nujna) |
| **F02** | Izbira tipa vozila in kalkulator cene | Uporabnik izbere velikost oziroma tip svojega vozila (npr. limuzina, karavan, SUV, kombi) ter poljubne dodatke. Sistem samodejno preračuna informativno končno ceno in predvideno trajanje storitve. | Visoka (Nujna) |
| **F03** | Spletna rezervacija termina | Uporabnik v interaktivnem koledarju izbere prost datum in uro ter odda rezervacijo izbranega paketa. Sistem prepreči podvojene rezervacije v istem časovnem oknu. | Visoka (Nujna) |
| **F04** | Registracija in prijava uporabnika | Uporabnik si lahko ustvari osebni račun z e-poštnim naslovom in geslom ter se varno prijavi v aplikacijo. Prijavljenim uporabnikom se kontaktni podatki ob rezervaciji izpolnijo samodejno. | Visoka (Nujna) |
| **F05** | Upravljanje lastnih rezervacij | Prijavljen uporabnik lahko na enem mestu pregleduje vse prihajajoče rezervacije. Po potrebi lahko rezervacijo do določenega roka pred terminom prestavi na drug prost datum ali jo prekliče. | Visoka (Nujna) |
| **F06** | Samodejna potrditev in opomniki | Po uspešni oddaji rezervacije uporabnik prejme samodejno potrditveno e-poštno sporočilo s povzetkom naročila. En dan pred terminom sistem pošlje opomnik o prihajajočem obisku studia. | Srednja |
| **F07** | Sledenje statusu obdelave vozila | Uporabnik lahko v svojem profilu v realnem času spremlja trenutno fazo obdelave vozila (npr. *Potrjeno*, *V obdelavi*, *Pripravljeno za prevzem*). Ob spremembi statusa na *Pripravljeno* prejme obvestilo. | Srednja |
| **F08** | Profil vozil (Moja garaža) | Prijavljen uporabnik lahko v svoj profil shrani eno ali več vozil (znamka, model, tip vozila, registrska oznaka) ter pregleduje zgodovino opravljenih storitev in zaščitnih premazov na posameznem vozilu. | Srednja |
| **F09** | Galerija opravljenih del (Prej/Potem) | Obiskovalec si lahko ogleda galerijo zaključenih projektov s fotografijami stanja vozila pred in po posegu. Galerijo je mogoče filtrirati glede na vrsto storitve (poliranje, notranjost, keramika). | Srednja |
| **F10** | Administratorski koledar in upravljanje terminov | Skrbnik studia ima dostop do nadzorne plošče, kjer pregleduje vse rezervacije, potrjuje ali ureja termine ter posodablja statuse vozil v delavnici. Skrbnik lahko blokira proste dneve ali izredne odsotnosti. | Visoka (Nujna) |
| **F11** | Urejanje cenika in paketov | Skrbnik lahko prek nadzorne plošče dodaja nove storitve, spreminja opise, cene glede na tip vozila ter sezonske akcije brez spreminjanja izvorne kode strani. | Srednja |
| **F12** | Ocene in mnenja strank | Stranka lahko po zaključenem terminu odda oceno od 1 do 5 zvezdic in kratek komentar o opravljeni storitvi. Potrjena mnenja se prikažejo na javni strani za večje zaupanje novih strank. | Nizka |