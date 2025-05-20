# ArivaHackV2

🌟 **ArivaHackV2**, siber güvenlik meraklıları, geliştiriciler ve araştırmacılar için tasarlanmış, tamamen eğitim amaçlı bir çok işlevli Python tabanlı bir araçtır. Bu araç, şifre oluşturma, sahte kimlik üretme, web sitesi bilgisi alma gibi çeşitli özellikler sunar.

⚠️ **Sorumluluk Reddi**: Bu araç yalnızca eğitim ve etik kullanım içindir. Yasadışı kullanım kesinlikle yasaktır ve geliştiriciler yanlış kullanımdan sorumlu değildir.

📚 **Depo**: [https://github.com/siberdunyaniz/arivahackv2](https://github.com/siberdunyaniz/arivahackv2)

## Özellikler
- **DOS Saldırısı Simülasyonu**: Test amaçlı HTTP isteklerini simüle eder.
- **Veritabanı Arama**: Bir dosyada belirli bir metni arar.
- **Karmaşık Şifre Oluşturucu**: Özelleştirilebilir karmaşıklıkta güvenli şifreler üretir.
- **Sahte Kimlik Oluşturucu**: Test için gerçekçi sahte kimlikler oluşturur.
- **Web Tarayıcı**: Web sitelerini tarayarak belirtilen derinlikte bağlantıları çıkarır.
- **Web Sitesi Bilgisi Alma**: Verilen bir alan adı için WHOIS verilerini getirir.
- **Mullvad Anahtar Oluşturucu**: Rastgele Mullvad anahtarları üretir ve kaydeder.
- **IP Sorgulama**: Bir IP adresi için coğrafi konum ve diğer detayları getirir.
- **Port Tarayıcı**: Yaygın veya belirli portları tarar.
- **Alt Alan Adı Tarayıcı**: Kelime listesi kullanarak alt alan adlarını keşfeder.
- **Web Sitesi Dökümü**: Bir web sitesinin HTML içeriğini yerel olarak kaydeder.
- **Telefon Numarası Bilgisi**: Telefon numarasının konumu ve operatörü gibi detayları getirir.

## Gereksinimler
ArivaHackV2'yi çalıştırmadan önce aşağıdaki yazılımların yüklü olduğundan emin olun:
- Python 3.8 veya daha yüksek sürüm
- pip (Python paket yöneticisi)

## Kurulum
ArivaHackV2'yi sisteminize kurmak için şu adımları izleyin:

1. **Depoyu Klonlayın**:
   ```bash
   git clone https://github.com/siberdunyaniz/arivahackv2.git
   cd arivahackv2
   ```

2. **Bağımlılıkları Yükleyin**:
   Gerekli Python paketlerini pip ile yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

   Eğer `requirements.txt` dosyası yoksa, aşağıdaki paketleri manuel olarak yükleyin:
   ```bash
   pip install requests beautifulsoup4 python-whois phonenumbers pystyle fake-useragent faker
   ```

3. **Aracı Çalıştırın**:
   Ana betiği çalıştırarak aracı başlatın:
   ```bash
   python arivahackv2.py
   ```

## Kullanım
1. Aracı `python arivahackv2.py` komutuyla başlatın.
2. Renkli bir ASCII banner ve mevcut seçenekleri (1-16) listeleyen bir menü görüntülenecektir.
3. İstediğiniz fonksiyonun numarasını girin (örneğin, Sahte Kart Oluşturucu için `6`).
4. Gerekli bilgileri girmek için ekrandaki talimatları takip edin (örneğin, URL, şifre uzunluğu vb.).
5. Her işlemden sonra devam etmek için `Enter` tuşuna basın veya çıkmak için `16` seçeneğini seçin.

### Örnek Kullanımlar
- **Şifre Oluşturma**:
  - `3` seçeneğini seçin.
  - Şifre uzunluğunu girin (örneğin, `12`).
  - Karmaşıklık seviyesini seçin (örneğin, `yüksek`).
  - Çıktı: `X7@kL9#mP2$q` gibi güvenli bir şifre.

- **Web Sitesi Tarama**:
  - `5` seçeneğini seçin.
  - Bir URL girin (örneğin, `https://example.com`).
  - Çıktı: Belirtilen alan adındaki taranmış bağlantıların listesi.

- **Telefon Numarası Bilgisi Sorgulama**:
  - `15` seçeneğini seçin.
  - Bir telefon numarası girin (örneğin, `+905555555555`).
  - Çıktı: Konum, operatör ve zaman dilimleri gibi detaylar.

## Notlar
- **Yalnızca Eğitim Amaçlı**: Bu araç, kontrollü ortamlarda öğrenme ve test için tasarlanmıştır. Kötü niyetli amaçlarla kullanmayın.
- **Bağımlılıklar**: Çalışma zamanı hatalarını önlemek için tüm gerekli kütüphanelerin yüklü olduğundan emin olun.
- **Ağ Kısıtlamaları**: Port tarama, WHOIS sorgulama gibi bazı özellikler aktif bir internet bağlantısı gerektirir ve ağ kısıtlamalarından etkilenebilir.
- **Özel Kelime Listeleri**: Alt alan adı tarama için geçerli bir kelime listesi dosyası sağlayın.

## Katkıda Bulunma
Katkılarınızı bekliyoruz! Katkıda bulunmak için:
1. Depoyu çatallayın (fork).
2. Yeni bir dal oluşturun (`git checkout -b ozellik-dali`).
3. Değişikliklerinizi yapın ve kaydedin (`git commit -m 'Yeni özellik eklendi'`).
4. Dalı itin (`git push origin ozellik-dali`).
5. Bir Pull Request açın.

Lütfen kodunuzun projenin kodlama standartlarına uygun olduğundan ve uygun belgeleri içerdiğinden emin olun.

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

## İletişim
- **Geliştirici**: @AtahanArslan
- **Kanal**: @ArivaTools
- **GitHub Sorunları**: Hatalar, özellik talepleri veya sorular için bir sorun (issue) açabilirsiniz.

🌟 **Etik Olarak Mutlu Hacklemeler!** 🌟