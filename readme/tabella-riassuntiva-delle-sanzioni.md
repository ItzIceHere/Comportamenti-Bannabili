---
icon: gavel
---

# Tabella Riassuntiva delle Sanzioni

Questa pagina funge da sommario e riferimento rapido per tutte le infrazioni e le relative sanzioni standard applicate durante gli screenshare su Titanet. Per una spiegazione dettagliata di ciascuna infrazione e dei metodi di rilevamento, si prega di consultare le pagine specifiche di questa guida.

Le sanzioni elencate di seguito sono soggette a revisione da parte del SS Management e possono essere aggravate in caso di recidiva o di molteplici infrazioni commesse durante lo stesso controllo.

***

#### Tabella delle Infrazioni

| Infrazione                                        | Motivazione Ufficiale Consigliata | Durata Consigliata |
| ------------------------------------------------- | --------------------------------- | ------------------ |
| **Ammissione**                                    | `Ammissione`                      | `7d`               |
| Cheat trovato durante il controllo                | `Cheating SS`                     | `15d`              |
| **Disabilitazione di Servizi Critici**            | `Processi Disabilitati`           | `10d`              |
| **Cancellazione di Artefatti Forensi**            | `Pulizia di Artefatti`            | `12d`              |
| **Manipolazione di Timestamp (Timestomping)**     | `Alterazione di Prove`            | `20d`              |
| **Manipolazione di Attributi (es. Read-Only)**    | `Alterazione di Prove`            | `20d`              |
| **Utilizzo di Partizioni/Drive per Occultamento** | `Occultamento di Prove`           | `20d`              |
| **Rifiuto Esplicito del Controllo**               | `Rifiuto`                         | `15d`              |
| **Interruzione della Connessione Remota**         | `Rifiuto + Stalling`              | `20d`              |
| **Riavvio o Spegnimento non Autorizzato**         | `Rifiuto + Stalling`              | `20d`              |
| **Ostruzionismo Attivo/Passivo**                  | `Rifiuto + Stalling`              | `20d`              |
| **Utilizzo di Ambienti Virtualizzati (VM)**       | `Virtual Machine`                 | `ban permanente`   |
| **Esecuzioni "Fileless"**                         | `Bypass Attempt`                  | `ban permanente`   |
| **Utilizzo del Task Scheduler (per bypass)**      | `Bypass Attempt`                  | `ban permanente`   |
| **Utilizzo di ADS e WMIC (per bypass)**           | `Bypass Attempt`                  | `ban permanente`   |
| **Process Hollowing**                             | `Bypass Attempt`                  | `ban permanente`   |

***

#### Principio di Recidiva

La **recidiva** si verifica quando un utente commette nuovamente un'infrazione dopo essere già stato sanzionato in passato per una violazione simile o correlata. Questo comportamento dimostra una mancata volontà di rispettare le regole e richiede un approccio sanzionatorio progressivo.

* **Aumento della Sanzione:** In caso di recidiva, la durata della sanzione standard, come definita in questa guida, **verrà aumentata** a discrezione del SS Management. L'entità dell'aumento dipenderà dalla gravità, dalla frequenza delle violazioni e dalla cronologia delle sanzioni precedenti del player.
*   **Formattazione della Motivazione del Ban:** Qualora un utente venga sanzionato per recidiva, la motivazione ufficiale nel report di ban deve seguire un formato specifico per garantirne la tracciabilità. Si utilizzerà la motivazione standard seguita dalla dicitura `(Recidiva N)`, dove `N` rappresenta il numero progressivo della recidiva per quella specifica categoria di infrazione.

    **Esempio:**

    * Un player viene bannato per la prima volta per cheating. La motivazione sarà: `Cheating (SS)`.
    * Se lo stesso player viene nuovamente sorpreso a usare cheat in futuro, la motivazione del secondo ban sarà: `Cheating (SS) (Recidiva 1)`.
    * Un eventuale terzo ban per lo stesso motivo riporterà: `Cheating (SS) (Recidiva 2)`, e così via.

{% hint style="info" %}
**Nota per lo Staff:** È responsabilità dello staffer, prima di emettere un ban, verificare la cronologia delle sanzioni del player per determinare se si tratta di un caso di recidiva. In caso di dubbio, consultare sempre un **SS Mentor** o un **SS Manager**.
{% endhint %}

{% hint style="info" %}
Questa tabella rappresenta lo standard. Il SS Management si riserva il diritto di valutare ogni caso singolarmente e di adeguare la sanzione in base al contesto specifico e alla gravità complessiva delle azioni del player.
{% endhint %}
