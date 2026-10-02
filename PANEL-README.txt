========================================
KMJ TIPS — KEY PANEL (v2)
RENDER PE HOST KARO
========================================

Ye panel ek STATIC website hai (sirf 1 HTML file).
Koi server/database nahi chahiye — key offline
verify hoti hai, isliye Render ka FREE static site
kaafi hai.

TARIQA (5 minute):
------------------
1. GitHub pe naya PRIVATE repo banao
   (naam: kmj-tips-key-panel). PRIVATE zaroor.

2. Is zip ki 2 files repo me dalo:
     panel.html
     render.yaml
   (MASTER-SECRET.txt KABHI repo me mat dalna —
    wo sirf tumhare paas rahegi.)

3. Render.com → GitHub login → "New +"
   → "Blueprint" → apna repo select karo.
   render.yaml khud detect ho jayega → "Apply".

4. 1-2 minute me live link milegi, jaise:
     https://kmj-tips-key-panel.onrender.com

PANEL KAISE USE KARO:
--------------------
1. Master Secret dalo (MASTER-SECRET.txt wali)
   → UNLOCK. (File me secret save nahi hota.)

2. Buyer app kholega → usko uski DEVICE ID
   dikhegi (COPY button ke saath). Wo ID tumhe
   bhejega (Telegram pe).

3. Device ID yahan dalo + Days/Hours dalo
   (jaise 30 days, ya 0 days 12 hours) →
   GENERATE KEY → COPY → buyer ko bhejo.

4. Buyer key daalega → key uske phone me SAVE
   ho jayegi → dobara nahi maangegi (expiry tak).

5. Dashboard me dekho: TOTAL / ACTIVE / EXPIRED
   keys, search box se koi bhi key dhoondo,
   "Key Check Karo" se key verify karo.

SOUND: Har button pe click sound, key banne par
success tune. Upar 🔊 button se on/off.

ZAROORI BAATEIN:
----------------
- Master secret KISI KO MAT DO. Jiske paas ye
  hai wo khud key bana sakta hai.
- Repo PRIVATE rakho.
- Dashboard me un keys ka record hai jo TUMNE
  banayi hain. Key offline hai isliye panel ko
  ye nahi pata kaunsi key kis phone pe actually
  USE ho rahi hai — uske liye server chahiye
  hoga (v2 me bana dunga jab chaho).
- Device ID khaali chhodoge to key jis phone pe
  pehli baar lagegi usi se auto-lock ho jayegi.
