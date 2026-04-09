# PulseWire
PulseWire è una news app Android progettata per offrire un’esperienza di lettura veloce, moderna e personalizzabile. L’app raccoglie notizie da più fonti, organizza i contenuti per categoria e permette di salvare gli articoli preferiti per la consultazione offline. 

Pensata per offrire un'esperienza pulita e fluida, PulseWire combina una UI essenziale con un'architettura Android moderna e facilmente estendibile.

## Funzionalità

- Homepage con notizie in evidenza
- Sezioni per categoria
- Ricerca articoli per parola chiave
- Salvataggio articoli nei preferiti
- Supporto offline per i contenuti salvati
- Filtri per fonte, categoria e paese
- Modalità chiara e scura
- Condivisione articoli
- Notifiche push per notizie importanti
- Aggiornamento dei contenuti con pull-to-refresh
- Interfaccia moderna, veloce e responsive

---

## Fonti dati

PulseWire può integrare più sorgenti di contenuti, tra cui:

- **NewsAPI** per headline, categorie e ricerca
- **GNews** come fonte secondaria o fallback
- **The Guardian Open Platform** per contenuti editoriali
- **RSS feed** per copertura aggiuntiva e ridondanza

Le fonti vengono normalizzate in un modello interno unico per garantire consistenza nell'interfaccia.

---

## Stack tecnico

- **Kotlin**
- **Jetpack Compose**
- **MVVM / Clean Architecture**
- **Retrofit**
- **Room**
- **DataStore**
- **Hilt**
- **Paging 3**
- **Coil**
- **Firebase Cloud Messaging**
