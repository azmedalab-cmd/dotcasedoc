---
title: "Fehlerbehebung"
description: "Häufige Probleme und ihre Lösung: Button erscheint nicht, E-Mail kommt nicht an, u. a."
---

# Fehlerbehebung

::: collapsible "Der Button / das Formular erscheint nicht im Shop"
Prüfen Sie der Reihe nach:

- Ist das App-Embed **„EU Withdrawal Button"** im Theme-Editor **eingeschaltet** und das Theme gespeichert? Siehe [App-Embed-Button](./formular-einbinden/app-embed-button.md).
- Haben Sie die **Widerrufsseite** angelegt (Formular-Einstellungen → „Widerrufsseite anlegen")? Siehe [Inline-Formular](./formular-einbinden/inline-formular.md).
- Bei eingefügtem Button-Code: Wurde er in die **HTML-Ansicht** (`<>`) eingefügt, nicht in den Texteditor?
- Sehr altes Theme ohne App-Blocks? Siehe [Legacy-Themes](./formular-einbinden/legacy-themes.md).
:::

::: collapsible "Die Bestätigungs-E-Mail kommt nicht an"
- Ist unter **Formular-Einstellungen** eine gültige **Benachrichtigungs-E-Mail** hinterlegt? Ohne Eintrag wird die Shopify-Shop-Kontaktadresse verwendet.
- Prüfen Sie den **Spam-/Werbung-Ordner**.
- Senden Sie einen **Test-Widerruf** ab und prüfen Sie erneut.
:::

::: collapsible "Das Formular ist leer oder lädt nicht"
- Das App-Embed muss aktiv sein (es lädt das Formular).
- Rufen Sie die richtige **Widerrufsseite** auf.
- Laden Sie die Seite neu (Browser-Cache).
:::

::: collapsible "Installation / Schritt 0 lässt sich nicht abschließen"
- Sie müssen **beide** Kästchen ankreuzen – **AVV und AGB**. Der Button „Akzeptieren und fortfahren" ist erst dann aktiv.
- Die Bestätigung wird auch serverseitig geprüft; ohne beide Häkchen wird die Annahme abgelehnt.
- Siehe [Installation & Gate](./installation.md).
:::

::: collapsible "Der Widerruf-Button auf der Bestellstatus-Seite fehlt"
- Die **Order-Status-Funktion** ist eine **Pro**-Funktion und muss in den Einstellungen für Bestellstatus/Checkout aktiviert sein.
- Prüfen Sie Ihren Tarif unter [Pro & Abrechnung](./pro-abrechnung.md).
:::

::: collapsible "Installation schlägt fehl / Endlosschleife bei der Installation"
Tritt dies nur bei einem bestimmten Shop auf, kann ein älterer/halber Datensatz oder eine geänderte Shop-Domain die Ursache sein. Bitte wenden Sie sich an den Support (siehe unten) – schildern Sie, **welcher Shop** betroffen ist.
:::

::: callout info "Weiterhin ein Problem?" icon:life-buoy
Schreiben Sie an **support.euwithdrawal@dotcaseglobal.com** und nennen Sie Ihre Shop-Domain (z. B. `ihr-shop.myshopify.com`), damit wir schneller helfen können.
:::
