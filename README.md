# Pocket Deck for Windows

A personal control surface for streaming and desktop apps. Use your phone on the same network to control your Windows PC.

[Download the latest release](https://github.com/alhnxx/Pocket-Deck-Releases/releases/latest)

## Install

Download the release ZIP, extract it, and run `obs-pocket/Pocket Deck.exe`. The host PC needs Node.js and Microsoft Edge WebView2 Runtime. Connect your own accounts and pair your phone from Settings.

## Updates

From version 3.14.0, Pocket Deck checks GitHub at startup and every six hours. You can also check manually in Settings. Published updates show a notification and download button. Installation is manual.

Close Pocket Deck, extract the new ZIP, replace runtime files in your existing `obs-pocket` folder, **keep your existing `data` folder**, and reopen the app. Your local accounts and keys remain there. Do not copy someone else's data folder.

Local edits reach other devices only after a new release is published. Versions older than 3.14.0 need to install 3.14.0 once to receive notifications.

## التثبيت والتحديث

نزّل أحدث ZIP، فك الضغط وشغّل **Pocket Deck.exe** داخل مجلد `obs-pocket`. يحتاج الكمبيوتر Node.js وWebView2. اربط حساباتك أنت، ثم اقترن بالجوال من الإعدادات.

ابتداءً من **3.14.0** يظهر إشعار داخل البرنامج عند نشر إصدار جديد، ومعه زر تنزيل. بعد التنزيل أغلق البرنامج، واستبدل ملفات التشغيل في مجلده نفسه، **واحتفظ بمجلد `data`** ثم شغّله مجددًا. التثبيت يدوي، وحساباتك وأزرارك تبقى على جهازك.

## Privacy and acknowledgements

Release ZIPs exclude all personal data files, account tokens, paired devices, uploaded images and local sounds. Third-party acknowledgements are included in the ZIP's `licenses` directory.

Pocket Deck is independent of Elgato. Elgato plugins and profiles are not directly compatible.
