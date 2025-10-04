# Kalkulatori Avancum C#

## Pershkrim
Ky asht nji **kalkulator i avancum** i shkrum ne C#, qe punon në konzole.  
Lejon njerin me kry veprime normale matematikore si mbledhje, zbritje, shumezim, pjestim, fuqi, rrenje katrore dhe perqindje.  
Ka edhe funksione të memories, që e bajn si nji kalkulator real.

---

## Funksionet qe ofron

| Komanda | Pershkrimi |
|----------|-------------|
| `+` | Mbledhje |
| `-` | Zbritje |
| `*` | Shumzim |
| `/` | Pjestim |
| `^` | Fuqi (numri1 ngrit ne numri2) |
| `RNJE` | Rrenje katrore e numrit |
| `%` | Perqindje (a % e b) |
| `MC` | Fshi memorien |
| `MR` | Lexo memorien |
| `M+` | Shto ne memorie |
| `M-` | Zbrit prej memories |
| `dil` | Dil prej kalkulatorit |

---

## Qysh funksionon

1. Programi nis dhe tregon listën me veprime qe munesh me perdor.  
2. Ti shkrun **numrin e parë**.  
   - Mundesh me shkru edhe `MR` nese don me marr vleren e ruajtun ne memorie.  
3. Shkruan **veprimin** (p.sh. `+`, `RNJE`, `%`, etj).  
4. Neese veprimi ka nevoje per dy numra, shkruan edhe **numrin e dytë**.  
5. Kalkulatori e llogarit rezultatin dhe ta tregon.  
6. Mundesh me vazhdu me veprime të tjera, ose me shkru `dil` për me dal.

---

##  Funksioni i memories

Kalkulatori ka memorie qe ruan ni numer, per me e perdor ma vone  
- `M+` – shton numrin aktual ne memorie.  
- `M-` – zbrit numrin aktual prej memories.  
- `MC` – fshin krejt memorien.  
- `MR` – lexon çka ke ruajt në memorie.  

Shkruj numrin e pare: 10
Shkruj veprimin: M+
U shtu ne memorie. Tash memoria asht: 10

Shkruj numrin e pare: MR
Lexu prej memories: 10
