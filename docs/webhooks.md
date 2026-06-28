---
title: "Webhooks"
description: "Die von Shopify vorgeschriebenen Webhooks – automatisch unterstützt, nichts einzurichten."
---

# Webhooks

Dotcase unterstützt die von Shopify **vorgeschriebenen Webhooks** automatisch. **Sie müssen hierfür nichts einrichten.** Diese Seite erklärt nur, was im Hintergrund passiert.

::: card "Anfrage auf Kundendaten" icon:file-search
Fordert eine betroffene Person über Shopify Auskunft an, stellt Dotcase die zugehörigen Daten bereit, damit Sie der Auskunftspflicht nachkommen können.
:::

::: card "Löschung von Kundendaten (Redact)" icon:user-x
Sendet Shopify eine Löschanforderung für eine kundenbezogene Person, werden die passenden Widerrufsanträge **vollständig anonymisiert**, sodass die Person nicht mehr identifizierbar ist.
:::

::: card "Löschung des Shops (Shop-Redact)" icon:store
Wird Ihr Shop gelöscht bzw. die App deinstalliert, werden **alle** Daten Ihres Shops entfernt.
:::

::: card "App deinstalliert" icon:plug
Bei der Deinstallation werden ein laufendes Abonnement beendet und die im Auftrag verarbeiteten Daten gelöscht (innerhalb von 30 Tagen).
:::

::: callout tip "Nichts zu konfigurieren" icon:check
Diese Abläufe sind Teil der App und laufen automatisch. Es gibt dafür keine Einstellung im Admin.
:::

::: callout info "Mehr zum Datenschutz" icon:lock
Wie lange Daten gespeichert werden und wer als Sub-Auftragsverarbeiter beteiligt ist, lesen Sie unter [Datenschutz & AVV](./datenschutz-avv.md).
:::
