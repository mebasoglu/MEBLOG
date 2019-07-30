---
title: "Bazı GNU/Linux Komutları"
date: 2019-07-30T12:20:59+03:00
draft: false
---

~ (tilda) ev dizininizi ifade eder.

`whoami`  kullanıcı adınızı gösterir.

`cat /etc/passwd`  kayıtlı kullanıcıların tutulduğu dosyayı gösterir.

`cat /etc/shells`  yüklü kabukları (shell) gösterir.

`echo $SHELL`  aktif kabuğu gösterir.

`history`  komut geçmişini gösterir.

`!<komut numarası>`  history' deki numaraya göre komut çalıştırır.

`!!`  en son çalıştırılan komutu çalıştırır.

`Ctrl + A`  satır başına gider.

`Ctrl + E`  satır sonuna gider.

`komut > dosya`  komutun çıktısını dosyanın üzerine yazar. Dosyanın eski içeriği silinir.

`komut >> dosya`  komutun çıktısını dosyanın sonuna ekler. Dosyanın eski içeriği kalır.

`komut 1>> dosya`  yukarıdaki komut ile aynı. Varsayılan ifade 1 olduğu için yazmaya gerek yok.

`komut 2> dosya`  komutun çıktısını ekrana yazar, hata varsa dosyaya yazar.

`komut 2>> dosya`  Hata varsa dosyanın sonuna ekler.

`echo Merhaba Dünya!`  ekrana "Merhaba Dünya!" yazar.

`echo Merhaba Dur{muş,sun,an}`  ekrana "Merhaba Durmuş Dursun Duran" yazar.

`komut&`  komutu arkaplanda çalıştırır.

`jobs`  arkaplanda çalışanları gösterir.

`kill %<sıra no>`  jobs' un çıktısındaki sıra numarasına göre işlemi sonlandırır.

