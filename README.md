# Fascicolo Sanitario Elettronico – Ecosistema Dati Sanitari (EDS) – prototipi

[![License](https://img.shields.io/github/license/italia/design-ui-kit.svg)](https://github.com/italia/design-ui-kit/blob/main/LICENSE)
[![Join the #design channel](https://img.shields.io/badge/Slack%20channel-%23design-blue.svg)](https://developersitalia.slack.com/messages/C7VPAUVB3/)
[![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)

## Nota bene: puoi scaricare i prototipi solo dalla pagina delle [release ufficiali](https://github.com/italia/design-fse-eds-ui-kit/releases). 

## Descrizione

Questo repository contiene i file dei **prototipi** dell’Ecosistema Dati Sanitari (EDS) del Fascicolo Sanitario Elettronico, con relativo **UI Kit del Fascicolo Sanitario Elettronico versione EDS** realizzato per la progettazione delle schermate. Per lo UI Kit del Fascicolo Sanitario Elettronico di riferimento FSE si rimanda al repository ufficiale [italia/design-fse-ui-kit](https://github.com/italia/design-fse-ui-kit/).

Sono allegate alla [release corrente del repository](https://github.com/italia/design-fse-eds-ui-kit/releases) le seguenti risorse:

| Risorsa | Nome del file
|---|-|
| **UI Kit del Fascicolo Sanitario Elettronico - EDS** | `FSE-EDS-Libreria-componenti` |
| **Ecosistema Dati Sanitari (EDS)** | `FSE-EDS-Ecosistema-dati-sanitari` |
| **Gestione dei consensi - EDS** | `FSE-EDS-Gestione-dei-consensi` |
| **Gestione del taccuino personale - EDS** | `FSE-EDS-Gestione-del-taccuino-personale` |
| **Professionisti sanitari - EDS** | `FSE-EDS-Professionisti-sanitari` |
| **Prototipo di base - EDS** | `FSE-EDS-Prototipo-di-base` |
| **Servizi di patient empowerment - EDS** | `FSE-EDS-Servizi-di-Patient-Empowerment` |
| **Servizi di variazione della posizione del cittadino rispetto al SSN - EDS** | `FSE-EDS-Servizi-di-variazione-della-posizione-del-cittadino-rispetto-al-SSN` |
| **Servizi per i miei percorsi di cura - EDS** | `FSE-EDS-Servizi-per-i-miei-percorsi-di-cura` |
| **Servizio di visualizzazione campagne di screening e prevenzione - EDS** | `FSE-EDS-Campagne-di-screening-e-prevenzione` |
| **Servizio la mia storia clinica - EDS** | `FSE-EDS-Servizio-la-mia-storia-clinica` |
| **Servizio per la visualizzazione delle deleghe - EDS** | `FSE-EDS-Servizio-per-la-visualizzazione-delle-deleghe` |


Questi file, disponibili sia per Figma e Sketch, forniscono un quadro chiaro di come dovrebberoo apparire le funzionalità dell'Ecosistema Dati Sanitari del sito web del Fascicolo Sanitario Elettronico.

Attenzione: alcune funzionalità presenti nei file Figma (.fig) potrebbero non essere presenti e/o non corrette nei file .sketch convertiti utilizzando la versione più recente di [fig2sketch](https://github.com/sketch-hq/fig2sketch). È consigliato pertanto controllare sempre il risultato della conversione e dichiarare lo stato delle risorse e questa eventualità agli utenti.

## Come iniziare

Scarica l'ultima versione disponibile nella pagina [Releases](https://github.com/italia/design-fse-ui-kit/releases). Ogni rilascio include i file sia per Figma che per Sketch.

Scarica inoltre la **[versione 3.6.3 di UI Kit Italia](https://github.com/italia/design-ui-kit/releases/tag/v3.6.3)**.  

Una volta scaricati, potrai aprire i file con i rispettivi programmi di progettazione e iniziare a esplorare le risorse.

### Collegamento delle librerie (UI Kit) ai prototipi in Figma

I prototipi utilizzano componenti collegati a **UI Kit del Fascicolo Sanitario Elettronico EDS** (`FSE-EDS-Libreria-componenti`) e alla **versione 3.6.3** di UI Kit Italia (`UI-Kit-Italia`), che include icone, tipografia, colori e ombre applicati.

**Per collegare le librerie in Figma:**
1. Assicurati di disporre di un **account Figma Pro** o superiore, necessario per pubblicare e collegare le librerie.
2. Scarica le librerie `UI-Kit-Italia` e `FSE-EDS-Libreria-componenti` e i file dei prototipi come descritto nel paragrafo Come iniziare. 
3. Carica tutti i file nel tuo spazio di lavoro su Figma.
4. Pubblica le librerie `UI-Kit-Italia` e `FSE-EDS-Libreria-componenti` nel tuo spazio di lavoro su Figma seguendo la guida ufficiale: 
  - [Pubblica una libreria in Figma](https://help.figma.com/hc/en-us/articles/360025508373-Publish-a-library)
5. In `FSE-EDS-Libreria-componenti`, effettua lo "swap" dei componenti e stili mancanti ("Missing libraries") con quelli di `UI-Kit-Italia` seguendo la guida ufficiale: 
  - [Swap di una libreria su Figma](https://help.figma.com/hc/en-us/articles/4404856784663-Swap-style-and-component-libraries)
6. Pubblica gli aggiornamenti della libreria `FSE-EDS-Libreria-componenti`.
7. Dentro al file di ciascun prototipo, seguendo la stessa procedura, effettua lo swap dei componenti e stili mancanti con quelli di `FSE-EDS-Libreria-componenti` e `UI-Kit-Italia`.
8. Aggiungi i file `FSE-EDS-Libreria-componenti` e `UI Kit Italia` come librerie seguendo la guida ufficiale:
  - [Aggiungere una libreria in Figma](https://help.figma.com/hc/en-us/articles/1500008731201-Enable-or-disable-a-library-in-a-design-file)

**Nota per gli account Figma gratuiti:**
- Con un account Figma gratuito, non è possibile collegare le librerie direttamente. Tuttavia, puoi accedere agli elementi aprendo i file `FSE-EDS-Libreria-componenti` e `UI-Kit-Italia` e copiando manualmente i componenti nel tuo progetto.
