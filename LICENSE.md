## Verify your download / تحقّق من الملف الذي نزّلته

Windows shows "Windows protected your PC - Unknown publisher" because this app is not
code-signed, not because anything is wrong with it. Verify the file yourself instead:
compare the SHA-256 below with the one on your machine. If they match, the file is
exactly the one published here and nothing altered it on the way.

يُظهر ويندوز تحذير «Windows protected your PC - Unknown publisher» لأن البرنامج غير
موقّع رقميًّا، لا لأن فيه خللًا. تحقّق بنفسك: قارن بصمة SHA-256 أدناه بالبصمة على جهازك،
فإن تطابقتا فالملف هو المنشور هنا نفسه ولم يُعبَث به في الطريق.

**Network-Toolkit-PRO-v1.6.3.29.zip** (514,114 bytes)
```
9D547BBEFAF8A03838D7CADC04885C3576D8AB550B92A88CDEBF9BBF9A5D3683
```

**Network-Toolkit-PRO.exe** (345,088 bytes - inside the zip)
```
DA63672D2D097275D6C5636F2C371A99E8A9B3CB07B649B52AE0D366141168ED
```

Run this in PowerShell on the downloaded file / نفّذ هذا في PowerShell على الملف المنزّل:
```powershell
Get-FileHash .\Network-Toolkit-PRO-v1.6.3.29.zip -Algorithm SHA256
```

### If Windows blocks it / إن منعه ويندوز

Right-click the **zip** before extracting > Properties > tick **Unblock** > OK. Extracting
an unblocked zip gives clean files, so the warning never appears.

كليك يمين على ملف الـ **zip** قبل فكّه > Properties > ضع علامة على **Unblock** > OK.
فكّ أرشيف غير محظور يُخرج ملفات نظيفة، فلا يظهر التحذير أصلًا.

The program then asks for administrator rights - that prompt is expected, it changes
network settings and cannot work without them.

ثم يطلب البرنامج صلاحيات المسؤول - هذه النافذة متوقّعة، فهو يعدّل إعدادات الشبكة ولا
يعمل بدونها.
