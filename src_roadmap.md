# Roadmap Sito Web — Servizi Rapidi Casa

## 📋 Prefazione

Questo documento è la **roadmap ufficiale di progetto** per la realizzazione del sito web *Servizi Rapidi Casa*. Serve a:

1. **Condividere chiaramente** le fasi di lavoro, le tempistiche e le responsabilità.
2. **Evitare malintesi** su "quando sarà pronto" e "cosa serve da voi".
3. **Tracciare lo stato di avanzamento** in modo trasparente, senza bisogno di continue chiamate o messaggi.

>  **Come leggere questo documento:** ogni sezione ha una data di inizio e fine. Se i materiali (testi, logo, foto) arrivano in ritardo, le date successive slittano di conseguenza. La timeline è valida **solo se entrambe le parti rispettano le scadenze concordate**.

---

## 🗓️ Timeline di Progetto

```mermaid
%%{init: {
  'theme': 'dark',
  'themeVariables': {
    'fontSize': '20px',
    'sectionFontSize': '20px'
  },
  'gantt': {
    'barHeight': 34,
    'barGap': 8,
    'topPadding': 60,
    'leftPadding': 220,
    'gridLineStartPadding': 20,
    'fontSize': 22,
    'sectionFontSize': 22,
    'numberSectionStyles': 4
  }
}}%%
gantt
    title Roadmap Servizi Rapidi Casa - 6 settimane
    dateFormat  DD-MM-YYYY
    axisFormat  %d %b

    section 1. Setup & Infrastruttura
    Acquisto/upgrade VPS Aruba                                 :done, a1, 17-09-2026, 1d
    configurazione server                                      :done, a2, 21-09-2026, 1d
    Installazione WordPress + SSL + DNS                        :done, a3, 21-09-2026, 1d
    Configurazione SMTP esterno (SendGrid/Brevo)               :a4, 23-09-2026, 1d
    Installazione plugin base (sicurezza, backup, cache)       :done, a5, 24-09-2026, 1d

    section 2. Struttura & Pagine 
    Confronto per struttura sito                               :done, crit, a10, 23-09-2026, 1d
    Creazione pagine - Home, Chi Siamo, Come Funziona          :a11, 24-09-2026, 4d
    Creazione pagine legali (Privacy, Cookie, Termini)         :a12, 23-09-2026, 10d
    Setup categorie servizi (idraulico, elettricista, ecc.)    :a13, 28-09-2026, 2d
    Creazione pagine mancanti                                  :a14, 01-10-2026, 1d

    section 3. Design & Branding
    Installazione tema Kadence + configurazione base           :done, a6, 22-09-2026, 1d
    Personalizzazione grafica (colori, font, logo)             :a7, 01-10-2026, 5d
    Personalizzazione immagini                                 :a8, 02-10-2026, 4d
    Setup header, footer, menu di navigazione                  :a9, 04-10-2026, 2d

    section 4. Core Marketplace
    HivePress (profili utenti, fornitori, annunci) :a15, 02-10-2026, 5d
    Sistema di ricerca e geolocalizzazione                     :a16, 07-10-2026, 2d
    Flusso registrazione fornitori + verifica documenti        :a17, 09-10-2026, 5d

    section 5. Punto di confronto
    Confronto per pagamenti e lato legale                      :crit, a18, 08-10-2026, 1d

    section 6. Booking & Pagamenti
    Setup WooCommerce + Stripe + PayPal (probabile split fondi)         :crit, a19, 13-10-2026, 2d
    Configurazione WooCommerce abbonamenti / piani fornitori   :crit, a20, 15-10-2026, 2d
    Setup piani BASE / SILVER / GOLD / PLATINUM                :crit, a21, 17-10-2026, 2d
    Test flussi di pagamento (ambiente sandbox)                :crit, a22, 19-10-2026, 2d

    section 7. Rifinitura & SEO
    Google Analytics account                                   :crit, a23, 21-10-2026, 1d
    Ottimizzazione SEO con RankMath (meta, sitemap, dati strutturati)    :a24, 21-10-2026, 2d
    Ottimizzazione velocità (cache, infrastruttura, immagini/CSS/JS)         :a25, 23-10-2026, 2d
    Attivazione CDN Aruba                             :a26, 23-10-2026, 1d
    Test responsive (mobile, tablet, desktop)                  :a27, 25-10-2026, 1d

    section 8. Testing & Lancio
    Testing completo flussi (cliente + fornitore + admin)      :a28, 25-10-2026, 1d
    Correzioni finali e ottimizzazioni eventuali               :a29, 26-10-2026, 1d
    Backup pre-lancio + Go Live                                :milestone, a30, 27-10-2026, 0d
```
