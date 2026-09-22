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
%%{init: {'theme':'dark'}}%%
gantt
    title Roadmap Servizi Rapidi Casa - 7 settimane
    dateFormat  DD-MM-YYYY
    axisFormat  %d %b

    section 1. Setup & Infrastruttura
    Acquisto/upgrade VPS Aruba                         :done, a1, 17-09-2026, 1d
    configurazione server                             :done, a2, 22-09-2026, 1d
    Installazione WordPress + SSL + DNS               :done, a3, 24-09-2026, 2d
    Configurazione SMTP esterno (SendGrid/Brevo)               :a4, 26-09-2026, 1d
    Installazione plugin base (sicurezza, backup, cache)       :a5, 27-09-2026, 2d

    section 2. Design & Branding
    Installazione tema Kadence + configurazione base         :done, a6, 22-09-2026, 1d
    Personalizzazione grafica (colori, font, logo)             :a7, 01-10-2026, 3d
    Personalizzazione immagini                                 :a8, 02-10-2026, 1d
    Setup header, footer, menu di navigazione                  :a9, 04-10-2026, 2d

    section 3. Struttura & Pagine Istituzionali
    Creazione pagine - Home, Chi Siamo, Come Funziona           :a10, 06-10-2026, 3d
    Creazione pagine legali (Privacy, Cookie, Termini)         :a11, 09-10-2026, 2d
    Setup categorie servizi (idraulico, elettricista, ecc.)    :a12, 11-10-2026, 2d

    section 4. Core Marketplace
    Configurazione HivePress (profili fornitori, annunci)      :a13, 13-10-2026, 3d
    Sistema di ricerca e geolocalizzazione                     :a14, 16-10-2026, 2d
    Flusso registrazione fornitori + verifica documenti        :a15, 18-10-2026, 2d

    section 5. Booking & Pagamenti
    Setup WooCommerce + Stripe + PayPal                        :crit, a16, 20-10-2026, 3d
    Configurazione WooCommerce Subscriptions (piani)           :crit, a17, 23-10-2026, 3d
    Setup piani BASE / SILVER / GOLD / PLATINUM                :crit, a18, 26-10-2026, 2d
    Test flussi di pagamento (ambiente sandbox)                :crit, a19, 28-10-2026, 2d

    section 6. Rifinitura & SEO
    Ottimizzazione SEO con RankMath (meta, sitemap, schema)    :a20, 30-10-2026, 3d
    Ottimizzazione velocità (WP Rocket, immagini WebP)         :a21, 02-11-2026, 2d
    Test responsive (mobile, tablet, desktop)                  :a22, 04-11-2026, 2d

    section 7. Testing & Lancio
    Testing completo flussi (cliente + fornitore + admin)      :a23, 06-11-2026, 3d
    Revisione con il cliente e raccolta feedback               :a24, 09-11-2026, 3d
    Correzioni finali e ottimizzazioni                         :a25, 12-11-2026, 2d
    Backup pre-lancio + Go Live                                :milestone, a26, 14-11-2026, 0d
```
