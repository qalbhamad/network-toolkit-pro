Network Toolkit PRO  v1.6.3.28
=====================================================
Designed by : ENG FAISEL ALATAWI
Contact     : qalbhamad@gmail.com
© 2026 ENG Faisel Alatawi. All rights reserved.


ENGLISH
-------
WHAT TO DO
  1. Copy Network-Toolkit-PRO.exe anywhere you like (Desktop, USB stick...).
  2. Double-click it. Windows will ask for administrator permission - this is
     required because changing IP settings needs it.

THAT IS ALL. Only the .exe is the program - the icon and logo are inside it. The
PDF and this note are just documentation you can keep or delete.

DIAGNOSTIC TOOLS (on the menu bar)
  Connection Monitor - pings several targets (modem gateway, SIM/WAN address, RTU,
    remote server) once a second and records a timestamped CSV log, so a dropped link
    can be pinned to the guilty layer with objective evidence. ICMP only - it never
    opens a session to your equipment.
  IP Verifier - proves whether the control centre has your equipment's IP entered
    correctly, WITHOUT needing anyone at the control centre to check. With the
    equipment unplugged, the laptop takes its address and LISTENS: a connection
    arriving proves the entry is right, silence proves it is wrong or not added. It
    only listens - it never opens a connection towards equipment, so it cannot take
    an RTU's single session away.
  Device Discovery - sweeps the local network with ARP and lists every device with its
    address, MAC and maker, so you can find an RTU whose address you do not know.
    Reachable from the Connection Monitor and the IP Verifier.

CHECKING FOR UPDATES
  Help > Check for Updates asks a version file whether a newer release exists and, if
  so, offers to open its download page. It never installs anything by itself, and it
  sends nothing out - it only reads a small version file. The address it reads is in
  update-source.txt beside the program; comment that line out to switch the check off.

FULL ILLUSTRATED GUIDE
  Network-Toolkit-PRO-Guide.pdf - a bilingual (English + Arabic) guide with
  screenshots explaining every button and option. Open it with any PDF reader.

REQUIREMENTS
  - Windows 11, Windows 10, or Windows 8.1  (.NET Framework 4.x is already built in)
  - Windows 7 users may need the free "Microsoft .NET Framework 4.8" from microsoft.com
  - Administrator permission when launching

LANGUAGE AND APPEARANCE
  The program opens matching your Windows settings automatically. If Windows is set
  to dark mode, it opens dark. If your Windows language is Arabic, it opens in Arabic.
  You can still switch language and theme inside the program at any time.

FILES THE PROGRAM CREATES (next to the .exe, on first use)
  settings.json         your saved network profiles
  original-config.json  a copy of your adapter's original settings, so Revert still
                        works even after you close and reopen the program

BECAUSE IT IS PORTABLE, keep the .exe in a folder you can write to. Running it from
a read-only location still works, but your profiles will not be saved.

SHARING PROFILES WITH SOMEONE
  Do not send your settings.json - it would overwrite theirs.
  Use  File > Export Profiles...  to make a share file, send that, and the other
  person uses  File > Import Profiles...  and chooses Merge.


العربية
-------
طريقة الاستخدام
  ١. انسخ ملف Network-Toolkit-PRO.exe في أي مكان (سطح المكتب، فلاشة...).
  ٢. اضغط عليه مرتين. سيطلب ويندوز صلاحيات المسؤول، وهذا ضروري لأن تغيير
     إعدادات الشبكة يتطلبها.

هذا كل شيء. البرنامج هو ملف الـ exe وحده، والأيقونة والشعار مدمجان بداخله. أما
ملف PDF وهذه الورقة فهما شرح يمكنك الاحتفاظ به أو حذفه.

أدوات التشخيص (في شريط القائمة)
  مراقب الاتصال - يرسل ping لعدة أهداف (بوابة المودم، عنوان الشريحة WAN، الجهاز/RTU،
    سيرفر بعيد) كل ثانية ويسجل ملف CSV بطابع زمني، فيمكن عزل موضع انقطاع الرابط بدليل
    موضوعي. ICMP فقط - لا يفتح أي اتصال بمعداتك.
  التحقق من عنوان IP - يثبت هل آي بي معدتك مدخل صحيحا في مركز التحكم، دون الحاجة إلى
    أحد في المركز. مع فصل المعدة، يأخذ اللابتوب عنوانها ويستمع: وصول اتصال يثبت أن
    الإدخال صحيح، والصمت يثبت أنه خاطئ أو أن المعدة غير مضافة. يستمع فقط - لا يفتح
    أي اتصال نحو معدة، فلا يمكن أن يسحب جلسة الـ RTU الوحيدة.
  اكتشاف الأجهزة - يفحص الشبكة المحلية عبر ARP ويسرد كل جهاز بعنوانه و MAC وصانعه،
    فتجد RTU لا تعرف عنوانه. متاح من مراقب الاتصال ومن التحقق من عنوان IP.

الدليل المصور الكامل
  Network-Toolkit-PRO-Guide.pdf - دليل ثنائي اللغة (عربي وإنجليزي) بالصور
  يشرح كل زر وخيار. افتحه بأي قارئ PDF.

المتطلبات
  - ويندوز 11 أو 10 أو 8.1  (.NET Framework 4.x موجود فيها أصلا)
  - مستخدمو ويندوز 7 قد يحتاجون تنزيل "Microsoft .NET Framework 4.8" مجانا من microsoft.com
  - صلاحيات المسؤول عند التشغيل

اللغة والمظهر
  يفتح البرنامج مطابقا لإعدادات ويندوز تلقائيا. إذا كان ويندوز على الوضع الداكن
  فسيفتح داكنا، وإذا كانت لغة ويندوز عربية فسيفتح بالعربية. ويمكنك تغيير اللغة
  والمظهر داخل البرنامج في أي وقت.

ملفات ينشئها البرنامج (بجانبه، عند أول استخدام)
  settings.json         ملفات تعريف الشبكة المحفوظة
  original-config.json  نسخة من إعدادات المحول الأصلية، ليعمل زر التراجع حتى بعد
                        إغلاق البرنامج وإعادة فتحه

لأن البرنامج محمول، ضعه في مجلد تملك صلاحية الكتابة فيه. يعمل من مكان للقراءة فقط
لكن لن تُحفظ ملفاتك.

مشاركة الإعدادات مع شخص آخر
  لا ترسل ملف settings.json الخاص بك، فسيستبدل ملفاته.
  استخدم  ملف > تصدير ملفات التعريف  لإنشاء ملف مشاركة وأرسله، ويستخدم الطرف
  الآخر  ملف > استيراد ملفات التعريف  ويختار "دمج".
