# Seda

Windows ve macOS (Apple Silicon) için yerel **Türkçe sesli okuma**, canlı kelime takibi, yayın seviyesi (`-17 dBFS`) ses/altyazı dışa aktarma, okuma istatistikleri, uygulama içi otomatik güncelleme ve canlı telaffuz sözlüğü uygulaması.

## Tek Tıkla İndirme (macOS & Windows)

Her iki işletim sisteminin hazır kurulum paketleri [Sürümler (Releases)](https://github.com/sezgintoptas/Seda/releases) sayfasında yayınlanır:

| Platform | Paket | Açıklama |
| --- | --- | --- |
| **Windows 10 / 11 (`x64`)** | [**Seda-Setup-1.0.7.exe**](https://github.com/sezgintoptas/Seda/releases/download/v1.0.7/Seda-Setup-1.0.7.exe) | Tek tıkla Windows kurulum sihirbazı (ekran kartı / GPU gerektirmez) |
| **Windows Taşınabilir Paket (`x64`)** | [**Seda-win.zip**](https://github.com/sezgintoptas/Seda/releases/latest/download/Seda-win.zip) | Mevcut Python 3.11+ kurulumları için hafif kurulum paketi (`scripts\kur_win.bat`) |
| **macOS Apple Silicon (`arm64`)** | [**Seda-macOS-arm64.dmg**](https://github.com/sezgintoptas/Seda/releases/latest/download/Seda-macOS-arm64.dmg) | Apple Silicon Mac sürümü; ses modeli gömülü, uygulama içi tek tıkla güncelleme destekli |
| **macOS Taşınabilir Arşiv (`arm64`)** | [**Seda-mac.zip**](https://github.com/sezgintoptas/Seda/releases/latest/download/Seda-mac.zip) | Doğrudan `Seda.app` uygulama arşivi (`macOS 14.0+`) |

> Tüm sürümleri ve değişiklik notlarını tek sayfada görmek için: **[github.com/sezgintoptas/Seda/releases](https://github.com/sezgintoptas/Seda/releases)**

## Öne Çıkan Özellikler

- **Yerel Türkçe Seslendirme:** İnternet veya bulut bağlantısı gerektirmeden bilgisayarınızda akıcı ve doğal Türkçe konuşma üretir; ayrıca çevrimdışı sistem sesi yedek motorunu destekler.
- **Doğal Türkçe Okuma Zekâsı:** Madde başlıkları (`1.`, `2.`), şık harfleri (`A)`, `B)`), parantez içi ara sözler, sıra sayıları, Romen rakamları (`IV. Murat`), kısayollar (`Alt+T`), teknik birimler (`4K`, `4-8 GB RAM`, `60-120 fps`), sürümler, para birimleri, tarihler, saatler ve web adresleri doğal akışta okunur.
- **Uygulama İçi Güncelleme:** Hem macOS hem Windows günlük sessiz güncelleme kontrolü yapar; yeni sürüm yayınlandığında tek tıkla indirip kurar.
- **Canlı Telaffuz Sözlüğü:** Ortak çekirdek telaffuz sözlüğü her 2 saatte bir otomatik olarak eşitlenir. Kişisel sözlüğünüze dilediğiniz kelimelerin okunuşunu ekleyebilirsiniz.
- **Ses Profilleri, Mini Oynatıcı ve Dışa Aktarma:** Doğal / Net Konuşma / Podcast ses profilleri, sürüklenebilir mini oynatıcı, medya tuşları, WAV/MP3 ses ve `.srt` altyazı dışa aktarma.

## Varsayılan Kısayollar

| İşlem | macOS | Windows |
| --- | --- | --- |
| Seçili metni oku / durdur | `⌃ ⌥ Q` (`Ctrl+Opt+Q`) | `Alt + Q` |
| Okumayı duraklat / devam et | `⌃ ⌥ P` (`Ctrl+Opt+P`) | `Alt + P` |
| Seçili kelimeyle Telaffuz Sözlüğünü aç | `⌃ ⌥ T` (`Ctrl+Opt+T`) | `Alt + T` |
| Seçili kelimeyi Önerilenlere ekle | `⌃ ⌥ ⇧ T` (`Ctrl+Opt+Shift+T`) | `Alt + Shift + T` |
