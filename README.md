# Repairs & Sales – Repair Shop Management App (Live Demo)

> A lightweight, offline-first web app for **phone / electronics repair shops**: register repairs and sales, track payments, and print **thermal receipts** — in **Arabic (RTL), English and French**.

▶ **Live demo:** https://ayoubnq19-sketch.github.io/repair-sale-demo/

> ⚠️ **Demonstration only.** This repository exists to showcase the project online. It is not offered for download, redistribution or commercial use (see [LICENSE](LICENSE)).

---

## What it does

Small repair shops often juggle paper notebooks, chat messages and loose receipts. This app replaces that with one simple screen that works on a phone or a computer, with no account and no server.

- **New repair** – brand, model, drop-off date, payment status, and one or more repair lines with their own price.
- **New sale** – brand, model, sale date, price, condition (new / used), defects, return period and warranty.
- **Operations list** – all repairs and sales in one place, with search (brand, model, number), paid / unpaid filters, edit, mark as collected, delete, and **undo**.
- **Receipts** – instant receipt preview and printing, sized for **72 mm thermal printers** (also prints on A4).
- **Customizable forms** – add, remove and restore fields (text, number, amount, date) to fit your own workflow.
- **Optional password lock** – protects access on the device.

## Languages and right-to-left support

The whole interface switches between **العربية · English · Français** from **Settings → Language**, including fields, messages and receipts.

Arabic is handled as a first-class language, not just translated text:

- full **RTL layout** (menus, forms, buttons, receipts)
- Arabic-Indic digits (٣٥٠٠) are **converted automatically** to standard digits
- correct Arabic **plural forms** for durations (يوم واحد · يومان · 3 أيام · 11 يومًا)
- amounts, dates and mixed Arabic/Latin text stay in the right order
- Arabic-friendly font and letter-spacing

## Privacy and data

- **No server, no account, no tracking.** Everything is stored **locally in your own browser** (IndexedDB, with a localStorage fallback).
- Every visitor of the demo has their **own private data**; nothing is shared between visitors.
- Clearing the browser data removes the demo data.

## Tech

- A **single HTML file** — vanilla JavaScript, HTML and CSS, no framework, no build step, no dependencies.
- Works **offline** once loaded; responsive for phones, tablets and desktops.
- Internationalization through a built-in dictionary (ar / en / fr) with logical CSS properties for RTL.

## Try it

1. Open the **[live demo](https://ayoubnq19-sketch.github.io/repair-sale-demo/)**.
2. Add a repair or a sale and save — the receipt preview opens automatically.
3. Open **Settings** to switch language (Arabic switches the whole app to RTL).

## Keywords

repair shop software · phone repair management · sales tracker · receipt printing · thermal printer 72mm · Arabic RTL web app · multilingual (Arabic, English, French) · offline-first · IndexedDB · vanilla JavaScript · Algeria

---

## بالعربية

**تطبيق «الإصلاحات والمبيعات»** — تطبيق ويب خفيف يعمل دون إنترنت لمحلات **صيانة الهواتف والأجهزة الإلكترونية**: تسجيل الإصلاحات والمبيعات، متابعة حالة الدفع، وطباعة **وصولات حرارية**، بثلاث لغات (العربية بدعم كامل للاتجاه من اليمين إلى اليسار، الإنجليزية، الفرنسية).

- حقول قابلة للتخصيص (إضافة، حذف، استرجاع)
- بحث وتصفية وتعديل وتراجع عن الحذف
- معاينة وطباعة الوصل
- قفل اختياري بكلمة مرور
- كل البيانات تُحفظ في متصفحك فقط، دون خادم ولا حساب

▶ **العرض الحي:** https://ayoubnq19-sketch.github.io/repair-sale-demo/

> هذا المستودع **للعرض والتجربة فقط**، وليس للتحميل أو الاستعمال أو إعادة التوزيع.

## En français

**Réparations & Ventes** — application web légère et hors ligne pour **ateliers de réparation** (téléphones, électronique) : suivi des réparations et des ventes, paiements, **tickets thermiques**, en **arabe (RTL), anglais et français**. Les données restent dans votre navigateur.

▶ **Démo en ligne :** https://ayoubnq19-sketch.github.io/repair-sale-demo/

> Projet présenté **à titre de démonstration uniquement**.

---

© 2026 YOUR NAME — All rights reserved. Demonstration purposes only.
