# Kalkulatori Avancum C#

## Pershkrim
Ky asht nji **kalkulator i avancum** i shkruem në C#, që punon në konzolë.  
Lejon përdoruesin me kry veprime të zakonshme matematikore si mbledhje, zbritje, shumëzim, pjestim, fuqi, rrenjë katrore dhe përqindje.  
Ka edhe funksione të memories, që e bajn si nji kalkulator real.

---

## Funksionet që ofron

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

1. Programi nis dhe tregon listën me veprime që munesh me perdor.  
2. Ti shkrun **numrin e parë**.  
   - Mundesh me shkru edhe `MR` nese don me marr vleren e ruajtun ne memorie.  
3. Shkruan **veprimin** (p.sh. `+`, `RNJE`, `%`, etj).  
4. Neese veprimi ka nevoje per dy numra, shkruan edhe **numrin e dytë**.  
5. Kalkulatori e llogarit rezultatin dhe ta tregon.  
6. Mundesh me vazhdu me veprime të tjera, ose me shkru `dil` për me dal.

---

##  Funksioni i memories

Kalkulatori ka memorie që ruan një numër, për me e përdor ma vonë.  
- `M+` – shton numrin aktual në memorie.  
- `M-` – zbrit numrin aktual prej memories.  
- `MC` – fshin krejt memorien.  
- `MR` – lexon çka ke ruajt në memorie.  

### Shembull:
```plaintext
Shkruj numrin e pare: 10
Shkruj veprimin: M+
U shtu ne memorie. Tash memoria asht: 10

Shkruj numrin e pare: MR
Lexu prej memories: 10
