# Svenska avtryck, datafil

Den här filen är innehållet i appen [Svenska avtryck](https://apps.apple.com/se/app/id6821462307):
120 svenskar som satt avtryck i världen, med åren före genombrottet.

Appen bär en egen kopia av filen och fungerar helt utan nät. En gång per dygn
tittar den hit efter en nyare version. Filen byts bara om den klarar appens
egen validering, om schemaversionen stöds och om ingen dag som redan har visats
flyttas. Klarar den inte det behåller appen filen den har.

Syftet är att en rättad uppgift ska kunna nå användarna samma dag, utan ett nytt
bygge och utan granskning i butikerna.

Adressen appen läser:

```
https://kakodaglera.github.io/svenska-avtryck-data/svenska-avtryck.json
```

Filen skrivs av `npm run publicera-data` i appens eget repo. Ändra den inte för
hand här, då hamnar den ur fas med appen.

Appen är skapad av [Vivian Bertil Fastighetsrådgivning](https://www.vivianbertil.com).
