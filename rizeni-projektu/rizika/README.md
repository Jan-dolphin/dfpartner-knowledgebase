# Rizika projektu DF Fabric

Tento adres�� obsahuje dokumentaci rizik projektu a zp�soby jejich �e�en�.

## Identifikovan� rizika

### Technick� rizika

#### Funk�nost generativn� AI -- mo�n� halucinov�n�
- **Z�va�nost:** Vysok�
- **Pravd�podobnost:** St�edn�
- **Dopad:** Generov�n� nespr�vn�ch nebo zav�d�j�c�ch podn�t�
- **Opat�en�:**
  - Implementace kontroln�ch mechanism�
  - Omezen� generativn�ch v�stup� na z�klad� dostupn�ch dat
  - Monitoring a validace v�stup�

#### Kvalita dat ve zdrojov�ch syst�mech
- **Z�va�nost:** Vysok�
- **Pravd�podobnost:** Vysok�
- **Dopad:** Nekvalitn� vstupy vedouc� k nekvalitn�m v�stup�m
- **Opat�en�:**
  - D�kladn� anal�za kvality dat p�ed implementac�
  - Data cleansing a preprocessing
  - Monitorov�n� kvality dat v pr�b�hu projektu

#### Dopady na v�konnost zdrojov�ho syst�mu
- **Z�va�nost:** St�edn�
- **Pravd�podobnost:** St�edn�
- **Dopad:** Zpomalen� provozn�ho syst�mu
- **Opat�en�:**
  - Optimalizace p��stupu k dat�m
  - Replikace dat do separ�tn�ho analytick�ho prost�ed�
  - Monitoring v�konnosti b�hem na��t�n� dat

### Projektov� rizika

*Dal�� projektov� rizika budou pr�b�n� dopl�ov�na.*

## Proces ��zen� rizik

1. Identifikace rizik
2. Hodnocen� rizik
3. Pl�nov�n� reakc� na rizika
4. Implementace opat�en�
5. Monitoring a kontrola
6. Aktualizace registru rizik
