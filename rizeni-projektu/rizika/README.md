# Rizika projektu DF Fabric

Tento adresáø obsahuje dokumentaci rizik projektu a zpùsoby jejich øešení.

## Identifikovaná rizika

### Technická rizika

#### Funkènost generativní AI -- možné halucinování
- **Závažnost:** Vysoká
- **Pravdìpodobnost:** Støední
- **Dopad:** Generování nesprávných nebo zavádìjících podnìtù
- **Opatøení:**
  - Implementace kontrolních mechanismù
  - Omezení generativních výstupù na základì dostupných dat
  - Monitoring a validace výstupù

#### Kvalita dat ve zdrojových systémech
- **Závažnost:** Vysoká
- **Pravdìpodobnost:** Vysoká
- **Dopad:** Nekvalitní vstupy vedoucí k nekvalitním výstupùm
- **Opatøení:**
  - Dùkladná analýza kvality dat pøed implementací
  - Data cleansing a preprocessing
  - Monitorování kvality dat v prùbìhu projektu

#### Dopady na výkonnost zdrojového systému
- **Závažnost:** Støední
- **Pravdìpodobnost:** Støední
- **Dopad:** Zpomalení provozního systému
- **Opatøení:**
  - Optimalizace pøístupu k datùm
  - Replikace dat do separátního analytického prostøedí
  - Monitoring výkonnosti bìhem naèítání dat

### Projektová rizika

*Další projektová rizika budou prùbìžnì doplòována.*

## Proces øízení rizik

1. Identifikace rizik
2. Hodnocení rizik
3. Plánování reakcí na rizika
4. Implementace opatøení
5. Monitoring a kontrola
6. Aktualizace registru rizik
