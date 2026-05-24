========================================================================
⚡ NovaDebloat - Windows Performans & Gizlilik Optimizasyon Aracı ⚡
========================================================================

Geliştirici : Kadir (made by Kadir)
Sürüm       : v1.2.0
Lisans      : MIT Açık Kaynak Lisansı

Bu araç, Windows 10 ve Windows 11 işletim sistemlerinizi gereksiz UWP 
uygulamalarından temizlemek, gizliliğinizi ihlal eden telemetri verilerini 
engellemek, arka plan yapay zeka/Copilot bileşenlerini kapatmak, oyun içi 
gecikmeleri düşürmek ve sistem sağlığını onarmak amacıyla tasarlanmış üst 
düzey, modern bir optimizasyon panelidir.

------------------------------------------------------------------------
📌 ANA ÖZELLİKLER VE YAPABİLDİKLERİ:
------------------------------------------------------------------------
1. UWP Uygulamaları Temizliği: Cortana, Haritalar, Solitaire, Hava Durumu 
   ve Xbox gibi arka planda RAM kullanan sistem uygulamalarını kaldırır.
2. YZ & Copilot Devre Dışı Bırakma: Windows Recall, Copilot kenar çubuğu, 
   Paint/Notepad AI araçları ve arka plan YZ hizmetlerini kapatır.
3. Gizlilik & Telemetri Koruması: Müşteri Deneyimi programı veri iletimini, 
   hata bildirimlerini, reklam kimliği takibini ve bulut aramalarını engeller.
4. Oyun Performans Ayarları: Xbox DVR arka plan kaydını durdurur, fare 
   hızlandırmayı kapatır, donanım GPU zamanlamasını açar, 1ms sistem süresini 
   tetikler ve internet gecikmesini (Nagle algoritması) azaltır.
5. Performans Artışı: Görsel animasyon ve saydamlık efektlerini kapatır, 
   hizmetleri manuel çalışmaya ayarlar ve RAM kullanımını optimize eder.
6. Arayüz ve Kullanılabilirlik: Klasik sağ tık menüsünü geri yükler, gizli 
   dosyaları ve uzantıları kalıcı gösterir, 'Sahipliği Al' sağ tık seçeneği ekler.
7. Sistem Onarımı & Araçlar: Temp geçici dosyalarını temizler, SFC ve DISM 
   sistem bütünlüğü taramaları çalıştırır ve Olay Günlüklerini temizler.

------------------------------------------------------------------------
🚀 UYGULAMANIN ÇALIŞTIRILMASI (NASIL ÇALIŞIR?):
------------------------------------------------------------------------
Bu uygulama, bir PowerShell arka uç sunucusu ve modern bir HTML5/CSS3/JS 
kullanıcı arayüzü ile çalışmaktadır. İki farklı şekilde başlatabilirsiniz:

Yöntem A - Hazır Derlenmiş EXE ile (Önerilen):
  1. Klasördeki `NovaDebloat.exe` dosyasını bulun.
  2. Sağ tıklayın ve "Yönetici Olarak Çalıştır" (Run as Administrator) seçin.
  3. Sistem otomatik olarak arka planda sunucuyu başlatacak ve web tarayıcınızda 
     (Microsoft Edge uygulama modunda) optimizasyon panelini açacaktır.

Yöntem B - PowerShell Betiği ile:
  1. `Start-Debloater.ps1` dosyasına sağ tıklayıp "PowerShell ile Çalıştır" deyin 
     veya PowerShell konsolundan yönetici olarak çağırın.
  2. Sunucu başladıktan sonra tarayıcınızda panel yüklenecektir.

⚠️ ÇOK ÖNEMLİ NOT: Arayüz dosyalarının bulunduğu "ui" klasörü her zaman 
`NovaDebloat.exe` veya `Start-Debloater.ps1` ile aynı dizinde bulunmalıdır! 
Aksi halde sunucu arayüzü yükleyemez.

------------------------------------------------------------------------
🛡️ GÜVENLİK VE TEDBİR UYARILARI:
------------------------------------------------------------------------
* Aracı ilk kez çalıştırdığınızda optimizasyonlara başlamadan önce en üstte 
  yer alan yeşil "Geri Yükleme Noktası Oluştur" (Create Restore Point) butonuna 
  basmanız önemle tavsiye edilir. Bir sorun yaşarsanız sisteminizi eski haline 
  kolayca getirebilirsiniz.
* 'Kritik Risk' (Danger) veya 'Yüksek Risk' (Caution) etiketli ayarları 
  (Windows Güncellemelerini veya Windows Defender Antivirüsünü kapatmak gibi) 
  yalnızca ileri düzey bir kullanıcıysanız ve alternatiflerinizi yapılandırdıysanız 
  etkinleştirin.

------------------------------------------------------------------------
🌐 DİL DESTEĞİ VE HAKKINDA BİLGİSİ:
------------------------------------------------------------------------
* Uygulama tamamen Türkçe ve İngilizce dillerini destekler. Arayüzün sağ 
  üst köşesindeki `🌐 EN / TR` butonuna basarak anında dil değiştirebilirsiniz.
* Sol taraftaki menünün en altında yer alan "Hakkında" (About) sekmesinden 
  geliştirici Kadir'in imzasına ve lisans sertifikalarına erişebilirsiniz.

------------------------------------------------------------------------
📄 AÇIK KAYNAK VE KATKI SAĞLAMA:
------------------------------------------------------------------------
Bu proje açık kaynaklı olup MIT Lisansı altındadır. Kodları serbestçe 
inceleyebilir, değiştirebilir ve kendi GitHub profilinizde paylaşabilirsiniz.
Projeyi geliştirmek veya katkıda bulunmak için lütfen `LICENSE` dosyasını 
inceleyin.

------------------------------------------------------------------------
NovaDebloat - Daha Hızlı, Daha Güvenli ve Daha Temiz Bir Windows Deneyimi!
========================================================================
