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
gantt
    title Roadmap Servizi Rapidi Casa - 7 settimane
    dateFormat  DD-MM-YYYY
    axisFormat  %d %b

    section 1. Setup & Infrastruttura
    Acquisto/upgrade VPS Aruba (fatto)                         :a1, 17-09-2026, 1d
    configurazione server (fatto)                              :a2, 22-09-2026, 1d
    Installazione WordPress + SSL + DNS (fatto)                :a3, 2026-09-24, 2d
    Configurazione SMTP esterno (SendGrid/Brevo)               :a4, 2026-09-26, 1d
    Installazione plugin base (sicurezza, backup, cache)       :a5, 2026-09-27, 2d

    section 2. Design & Branding
    Installazione tema Kadence + configurazione base (fatto)          :a6, 22-09-2026, 1d
    Personalizzazione grafica (colori, font, logo)             :a7, 2026-10-01, 3d
    Personalizzazione immagini                                 :a8, 
    Setup header, footer, menu di navigazione                  :a8, 2026-10-04, 2d

    section 3. Struttura & Pagine Istituzionali
    Creazione pagine - Home, Chi Siamo, Come Funziona           :a9, 2026-10-06, 3d
    Creazione pagine legali (Privacy, Cookie, Termini)         :a10, 2026-10-09, 2d
    Setup categorie servizi (idraulico, elettricista, ecc.)    :a11, 2026-10-11, 2d

    section 4. Core Marketplace
    Configurazione HivePress (profili fornitori, annunci)      :a12, 2026-10-13, 3d
    Sistema di ricerca e geolocalizzazione                     :a13, 2026-10-16, 2d
    Flusso registrazione fornitori + verifica documenti        :a14, 2026-10-18, 2d

    section 5. Booking & Pagamenti
    Setup WooCommerce + Stripe + PayPal                        :a15, 2026-10-20, 3d
    Configurazione WooCommerce Subscriptions (piani)           :a16, 2026-10-23, 3d
    Setup piani BASE / SILVER / GOLD / PLATINUM                :a17, 2026-10-26, 2d
    Test flussi di pagamento (ambiente sandbox)                :a18, 2026-10-28, 2d

    section 6. Rifinitura & SEO
    Ottimizzazione SEO con RankMath (meta, sitemap, schema)    :a19, 2026-10-30, 3d
    Ottimizzazione velocità (WP Rocket, immagini WebP)         :a20, 2026-11-02, 2d
    Test responsive (mobile, tablet, desktop)                  :a21, 2026-11-04, 2d

    section 7. Testing & Lancio
    Testing completo flussi (cliente + fornitore + admin)      :a22, 2026-11-06, 3d
    Revisione con il cliente e raccolta feedback               :a23, 2026-11-09, 3d
    Correzioni finali e ottimizzazioni                         :a24, 2026-11-12, 2d
    Backup pre-lancio + Go Live                                :milestone, a25, 2026-11-14, 0d
