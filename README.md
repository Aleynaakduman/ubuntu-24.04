# Ubuntu Sistem Gereksinimleri :
- 2 GHz çift çekirdek işlemci <br>
- 4 GB RAM bellek <br>
- 25 GB boş sabit disk alanı <br>
- 1024 x 768 piksel VGA destekli ekran <br>
- İnternet erişimi tavsiye edilir <br>

Gerekli minimum sistem gereksinimlerini karşılayamayan eski bilgisayarlar için, resmî olarak tanınan Ubuntu türevlerinden Lubuntu ya da Xubuntu kullanılabilir. Bu türevleri, hafif bir masaüstü ortamı (LXQt, Xfce) ile geldiklerinden dolayı epey düşük sistem kaynağı tüketirler.

# 1.Ubuntu Download
1.1
Ubuntu resmi sitesine giriyoruz. bu [linkten](www.ubuntu.com) ubuntu resmi sitesine girebilirsiniz.Desktop için Download butonuna tıklıyoruz <br><br>
![resim](resim1.png)

1.2
LTS sürümünü yüklüyoruz.Ubuntu'nun LTS ve LTS olmayan sürümleri arasındaki fark ; LTS, uzun vadeli destek anlamına gelir. LTS sürümleri her iki yılda bir (2020, 2022, vb.) Nisan ayında, LTS olmayan sürümler ise her yıl Ekim ayında ve LTS olmayan yıllarda Nisan ayında yayınlanır.Daha eski bir Ubuntu sürümü yüklüyorsanız, yükleyicinin görsel sunumunun farklı olduğunu göreceksiniz, ancak genel akış benzer kalacaktır.<br><br>
![resim](resim2.png)

# 2.Rufus Download 
Rufus, USB anahtar/bellekler, hafıza kartları vb. gibi USB sürücüleri biçimlendirmeye ve önyüklemeli hale getirmeye yardımcı olan bir araçtır. Rufus kullanarak Ubuntu 24.04 LTS için önyüklenebilir bir USB oluşturmak basit bir işlemdir.<br>
Bu [linkten](www.rufus.com) rufusun resmi sitesine gidebirisiniz.<br><br>
![resim](resim3.png)

# 3.Rufusu önyüklemeye hazır hale getirme
Rufusu açıyoruz.Flash belleğimizi takıyoruz.Aygıtımızı flash belleğimizi seçiyourz. Önyükleme seçimine bilgisayarımıza indirdiğimiz ubuntu yu seçiyoruz.Başlat butonuna tıklıyoruz.Diske yazma işlemleri başlıyor.<br><br>
![resim](resim_2024-10-26_231839525.png)

# 4.Disk Bölümü Ayarlama 
Ubuntu yu windows dan farklı bir yere kuracağımız için ssd mizde bir disk ayırmamız gerekiyor.Bunu isterseniz Windows içinde isterseniz Boot menüsünden sonra yapabilirsiniz.Ben windows da yapmayı tercih ediyorum. O yüzden öncelikle başlata sağ tık yapıp disk yönetimine girmemiz gerekiyor.
Gözüken boş alandan istediğimiz kadarını küçültüp bunu Ubuntu için ayıracağım.<br><br>
![resim](resim5.png)

Şimdi sırada bilgisayarı kapatıp Ubuntu yu kurmak var.Öncelikle bilgisayarı boot menüsüne sokmamız gerekiyor.

# 5.Ubuntu Kurulum 
- Flash belleğimizi bilgisayar kapalıyken takalım
- bilgisayarımızı boot menüsüne sokalım
- karşımıza çıkan seçeneklerden USB üzerinden başlatacağımız için UEFI: USB DISK olan seçeneği seçiyoruz.
- Karşımıza grup versiyon açılacak.Bize ne yapmak istedğimizi soruyor. Biz Ubuntu yu indireceğimiz için Yry or Install Ubuntu seçeneğine gelip enter a basıyoruz.

5.1 Yükleyici başlatıldığında dilinizi seçmeniz istenecektir.<br><br>
![resim](u1.jpeg)<br><br>
5.1 Daha sonra ihtiyaç duyduğunuz erişebilirlik ayarlarını seçme seçeneği sunulur.<br><br>
![resim](u2.jpeg)<br><br>
5.3 Klavye Düzeninizi Seçin <br><br>
![resim](u3.jpeg)<br><br>
5.4 Ubuntuyu kurma veya deneme seçeneği karşımıza çıkacak. Kurma seçeneğine tıklıyoruz<br><br>
![resim](u4.jpeg)<br><br>
5.5 etkileşimli kurulum veya otomatik kurulum arasında seçim yapmamız istenecektir.Etkileşimli seçenek standart yoldur, ancak daha ileri düzey kullanıcılar, birden fazla kurulumu standartlaştırmak ve daha fazla özelleştirme eklemek için bir web sunucusundan bir yapılandırma dosyasını içe aktarmak üzere otomatik kurulum seçeneğini kullanabilirler. <br><br>
![resim](u5.jpeg)<br><br>
5.6 Varsayılan seçim ve genişletilmiş seçim seçenekleri arasında seçim yapmanız istenecektir.Biz varsayılanı seçiyoruz. <br><br>
![resim](u6.jpeg)<br><br>
5.7 Aşağıdaki ekranda, cihaz desteği ve performansı , ek medya desteğini arttırabilecek üçüncü taraf yazılımları yüklemeniz istenecektir. Bu kutuların her ikisini de işaretlemeniz önerilir.<br><br>
![resim](u7.jpeg)<br><br>
5.8 Kurulum Türü <br>
Bu ekran kurulumunuzu yapılandırmanıza olanak tanır.Ubuntu nun sabit diskinizdeki tek işletim sistemi olmasını istiyorsanız, Erase disk and install Ubuntu yu seçin. Biz diskimizde yer ayırdık ve halıhazırda başka bir işletim sistemimiz var o yüzden manuel seçiyoruz.<br><br>
![resim](r1.jpeg)<br><br>
5.9 Bilgilerimizi giriyoruz <br><br>
![resim](r2.jpeg)<br><br>
5.10 Giriş ayrıntılarını oluşturun <br>
Bu ekranda, adınız, kullanıcı adı ve güçlü bir parola istenecektir. <br><br>
![resim](r3.jpeg)<br><br>
5.11 Harita ekranında konumunuzu ve saat diliminizi seçin.Bilgisayarınız internete bağlıysa otomatik olarak seçecektir. <br><br>
![resim](r4.jpeg)<br><br>
5.12 Kuruluma Hazır. Ekranda kurulum özeti bulunuyor.Install a basıp devam ediyoruz. <br><br>
![resim](r5.jpeg)<br><br>
5.13 Kurulum tamamlandıktan sonra bilgisayarınızı yeniden başlatmanız istenecektir.Bunun için restart now a tıklayın. <br><br>
![resim](r6.jpeg)<br><br>
5.14 Yeniden başlattığınızda USB flash sürücünüzü cihazdan çıkarmanız istenecektir.Bunu yaptıktan sonra ENTER a basın.<br><br>
![resim](r7.png)<br><br>
5.15 Adımlarımız bitti. Ubuntu kuruldu. <br><br>
![resim](r8.jpeg)<br><br>













