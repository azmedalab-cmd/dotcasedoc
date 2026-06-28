---
title: "E-Mail-Vorlagen"
description: "Automatische Bestätigungs- und Benachrichtigungs-E-Mails – und wie Sie die Texte anpassen."
---

# E-Mail-Vorlagen

Bei jedem eingegangenen Widerruf versendet Dotcase **automatisch** E-Mails:

- eine **Bestätigung an die Kundschaft** (Eingangsbestätigung des Widerrufs),
- eine **Benachrichtigung an Sie** (den Händler).

::: callout info "Eingangsbestätigung nach § 356a BGB" icon:info
Die Kunden-E-Mail enthält automatisch eine **Eingangsbestätigung mit Datum und Uhrzeit** des Widerrufs. Diese Zeile wird immer angefügt – auch wenn Sie einen eigenen Text verwenden.
:::

## Texte anpassen (Pro)

Im **E-Mail-Vorlagen**-Editor der App passen Sie die Texte an:

::: steps
1. **E-Mail-Vorlagen öffnen**
   In der App: **E-Mail-Vorlagen**.

2. **Vorlage und Sprache wählen**
   Bearbeiten Sie Betreff und Text der Kunden-Bestätigung, der Händler-Benachrichtigung sowie der **Genehmigungs-** und **Ablehnungs-E-Mails**. Die Texte sind je Sprache pflegbar.

3. **Platzhalter verwenden**
   Nutzen Sie Platzhalter, die beim Versand automatisch ersetzt werden, u. a. `{{name}}`, `{{orderNumber}}`, `{{shopName}}`, `{{email}}`, `{{products}}`, `{{additionalInfo}}`, `{{submittedAt}}`.

4. **Speichern**
   Leere Felder verwenden automatisch den eingebauten Standardtext.
:::

::: callout tip "Free vs Pro" icon:crown
**Free:** Kunden-Bestätigung und Händler-Benachrichtigung werden automatisch versendet.
**Pro:** editierbare Vorlagen sowie **Genehmigungs-/Ablehnungs-E-Mails** an die Kundschaft.
Mehr dazu unter [Pro & Abrechnung](./pro-abrechnung.md).
:::

::: callout warning "Doppelte E-Mails vermeiden" icon:alert-triangle
Shopify versendet bei Rückerstattungen ggf. eigene E-Mails. Wenn Sie keine doppelte Benachrichtigung wünschen, können Sie die Kunden-Genehmigungs-E-Mail in den Einstellungen abschalten.
:::
