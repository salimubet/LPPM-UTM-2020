# QUICK TEST

Oleh: **MOCHAMAD SALIM UBAIDILLAH**

!<img src="UTM_DIKBUD.png" style="zoom:25%;" />





## KULIAH KERJA NYATA

TEMATIK “ADAPTASI KEBIASAAN BARU” SEMESTER GASAL TAHUN AKADEMIK 2020/2021

LEMBAGA PENELITIAN DAN PENGABDIAN KEPADA MASYARAKAT

UNIVERSITAS TRUNOJOYO MADURA Jl. Raya Telang PO BOX. 2 Kamal Bangkalan 69162 Telp. (031) 3012391 Laman: http://lppm.trunojoyo.ac.id Email: lppm@trunojoyo.ac.id

### Constructing Graph
1. Once it has finished, open Gephi and click `new project`.
2. Go to `Data Laboratory`, then `edges`. Now, `import spreadsheet`. Select `facebook.csv`.
3. Go to `Overview`. Choose the `Force Atlas` layout and press play.
4. Just kinda play around with Gephi until you get something you like :) you can even colour nodes.

### Saving Graph
1. Go to `preview` to make sure you like how it looks.
2. `File > Export >` whatever filetype you want.
3. Finally you can go to an image editor to draw labels and stuff.

## Requirements:
- Chrome browser
- Selenium: `pip install Selenium`
- TQDM: `pip install tqdm`
- DotEnv: `pip install python-dotenv`
- Driver according to your Chrome version and OS: https://chromedriver.chromium.org/downloads
- Gephi, unless you have some other plan for drawing your graph

## More info:
Currently does not detect facebook friends who do not have usernames.
For example, `www.facebook.com/user_name` is detected, but `www.facebook.com/profile.php?id=123456789` is not.

Also ignores friends who have no mutual friends, and those whose accounts are deactivated.

Waits a few seconds before going to different profiles.
This makes it slow, but if we go too fast, Facebook will give a temporary ban.

I have tried to reduce the risk of getting a temporary ban, but I can't guarantee anything.
If you get banned, it is not my responsibility.
