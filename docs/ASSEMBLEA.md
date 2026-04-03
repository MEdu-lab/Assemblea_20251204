---
mustache: dati.yaml
---

# {{titolo}}

## 1. Dati della riunione

L'anno **{{data-anno}}**, il giorno **{{data-giorno}}** del mese di **{{data-mese}}**, alle ore **{{ora_inizio}}**, presso **{{luogo}}**, si è riunita in **{{convocazione}}** l'**{{tipo_riunione}}** dell'associazione **{{associazione}}**.

La riunione è stata regolarmente convocata nei modi e nei termini previsti dallo statuto vigente.

## 2. Partecipanti e verifica del quorum

**Risultano presenti:**

{{presenti}}

**Risultano assenti:**

{{assenti}}

**Verifica del quorum:**

| | |
|---|---|
| Soci totali aventi diritto di voto | **{{n_soci_totale}}** |
| Presenti in assemblea | **{{n_presenti}}** |
| Deleghe ricevute | **{{n_deleghe}}** |
| Totale aventi diritto al voto presenti o rappresentati | **{{n_aventi_diritto_voto}}** |
| Quorum richiesto | **{{quorum_richiesto}}** |

Il quorum è raggiunto. L'assemblea è **validamente costituita**.

## 3. Costituzione dell'assemblea

Il socio **{{presidente_assemblea}}** propone di assumere la presidenza dei lavori assembleari. Non essendovi opposizioni, assume la presidenza dell'assemblea.

Il Presidente invita il socio **{{segretario_assemblea}}** a svolgere le funzioni di segretario verbalizzante, il quale accetta.

## 4. Ordine del giorno

Il Presidente dichiara aperta la seduta e pone in discussione il seguente ordine del giorno:

{{ordine_del_giorno}}

## 5. Svolgimento della riunione

### 5.1 Accettazione candidatura nuovi soci

Il Presidente informa l'assemblea che in data **{{data_efficacia}}** i membri del Consiglio Direttivo in carica accettano la candidatura ad entrare a far parte dell'associazione sottoposta da:

{{nuovi_soci}}

L'assemblea **prende atto all'unanimità** della cessazione del Consiglio Direttivo e ringrazia i membri uscenti per l'attività svolta nel periodo del mandato.

## 6. Chiusura

Non essendovi altri argomenti da trattare, il Presidente dichiara chiusa la seduta alle ore **{{ora_fine}}**.

Letto, approvato e sottoscritto.

{{luogo}}, lì {{data}}

_________________________          _________________________

Il Presidente dell'Assemblea        Il Segretario Verbalizzante

```{=latex}
\clearpage
```

## Allegato A — Dati anagrafici nuovi soci

### {{socio1_cognome}} {{socio1_nome}}

| Campo | Dato |
|---|---|
| Cognome e nome | **{{socio1_cognome}} {{socio1_nome}}** |
| Data di nascita | {{socio1_data_nascita}} |
| Luogo di nascita | {{socio1_luogo_nascita}} |
| Residenza | {{socio1_residenza}} |
| CAP | {{socio1_cap}} |
| Comune | {{socio1_comune}} |
| Provincia | {{socio1_provincia}} |
| Codice fiscale | {{socio1_codice_fiscale}} |
| Email | {{socio1_email}} |
| Telefono | {{socio1_telefono}} |
| Data di iscrizione | {{socio1_data_iscrizione}} |
| Quota versata (€) | {{socio1_quota}} |

\vspace{1cm}

### {{socio2_cognome}} {{socio2_nome}}

| Campo | Dato |
|---|---|
| Cognome e nome | **{{socio2_cognome}} {{socio2_nome}}** |
| Data di nascita | {{socio2_data_nascita}} |
| Luogo di nascita | {{socio2_luogo_nascita}} |
| Residenza | {{socio2_residenza}} |
| CAP | {{socio2_cap}} |
| Comune | {{socio2_comune}} |
| Provincia | {{socio2_provincia}} |
| Codice fiscale | {{socio2_codice_fiscale}} |
| Email | {{socio2_email}} |
| Telefono | {{socio2_telefono}} |
| Data di iscrizione | {{socio2_data_iscrizione}} |
| Quota versata (€) | {{socio2_quota}} |
