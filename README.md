# Pocket Deck for Windows

A personal control surface for streaming and desktop apps. Use your phone on the same network to control your Windows PC.

[Download the latest release](https://github.com/alhnxx/Pocket-Deck-Releases/releases/latest)

## Install once

Download the latest release ZIP, extract it, and run `obs-pocket/Pocket Deck.exe`. The host PC needs **Node.js 22+** and Microsoft Edge WebView2 Runtime. Connect your own accounts and pair your phone from Settings.

## One-click updates — 3.15.0 and later

New published releases appear inside the desktop app. Click **Update and restart** to save pending deck changes, download and verify the official package, close the app, replace runtime files, and reopen it automatically. Checks run at startup and every six hours, with a manual check in Settings.

Your entire `data` folder stays in place. Runtime backups are kept under `data/updates`; failed file replacements are rolled back. The browser version shows release information; one-click installation runs in the Windows app.

If you currently use 3.14.0 or older, install **3.15.0 once**: close the app, replace runtime files in the same folder, **keep your existing data folder**, and reopen it. All later updates can use the in-app button.

Local edits reach other devices only after a new release is published here.

## التحديث بضغطة واحدة

ثبّت **3.15.0** مرة واحدة. بعدها، عند نشر إصدار جديد يظهر إشعار وزر **«تحديث وإعادة التشغيل»** داخل التطبيق: يحفظ تعديلات اللوحة، وينزّل الحزمة ويتحقق منها، ثم يغلق ويستبدل الملفات ويعيد تشغيل نفسه.

حساباتك وأزرارك وأصواتك تبقى داخل مجلد `data`. يحتفظ البرنامج بنسخة احتياطية للملفات السابقة، ويرجعها إذا فشل استبدال ملفات التشغيل. عند الترقية من إصدار أقدم احتفظ بمجلد `data` الموجود عندك.

## Privacy and acknowledgements

Release ZIPs exclude personal data files, account tokens, paired devices, uploaded images and local sounds. Third-party acknowledgements are in the ZIP’s `licenses` directory.

Pocket Deck is independent of Elgato. Elgato plugins and profiles are not directly compatible.
