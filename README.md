# TwitchClip-Indirme
Tüm Twitch Kliplerinizi İndirme


Tarayıcınızdan kanalın klipler kısmını açıp binebildiğiniz kadar aşağı inin 
Sonra  sağ tıklayıp "İncele" seçeneğini seçip konsola kodu yapıştırın.
Linkler listelenecek sadece cliplerin linlerini istediğimiz için filtre kısmına clips yaz.(Resim 4)
Listelenen linkleri şekildeki gibi bir dosyaya kayıt edin. ve boş bir klasöre koyun.(Resim 5)

Yerlerini biliyoruz şimdi indirme zamanı

[YoutubeDL](https://yt-dl.org/downloads/2020.06.06/youtube-dl.exe) indirip linklerin olduğu klasöre koyun.
Çalışması İçin [Microsoft Visual C++ 2010 Redistributable Package (x86)](https://www.microsoft.com/en-US/download/details.aspx?id=5555) Gerek yok ise indirip kurun.

Daha sonra youtube-dl.exe olduğu klasöre shifte basılı tutup sağ tıklayın Powershell pencerisini burda açın diyin.(Resim 6)

Powershelle aşağıdaki komutu girin. (Clips.txt siz artık ne isim verdiyseniz.)
///
.\youtube-dl.exe -c --batch-file .\clip.txt
///

İndirme youtube-dl.exe olduğu klasöre yapılacak teker teker biraz sürebilir.(Resim 7)
Bittiğinde konsol durur ve direk kapatabilirsiniz.

**RESIM 1**
![GitHub Logo](/images/ss1.png)

![GitHub Logo](/images/ss2.jpg)

![GitHub Logo](/images/ss3.png)

![GitHub Logo](/images/ss4.png)

![GitHub Logo](/images/ss5.png)

![GitHub Logo](/images/ss6.png)

![GitHub Logo](/images/ss7.png)
