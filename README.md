# Windows ve Ofis Yardımcı Araçları

Ofis ve üretim ortamındaki küçük ama tekrarlayan sorunlar için yazılmış Windows araçları koleksiyonu.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Araçlar

| Araç | Açıklama |
|---|---|
| **CPU/GPU sıcaklık widget'ı** | Masaüstünde her zaman üstte duran, şeffaf ve tıklamayı geçiren sıcaklık göstergesi. Veriyi LibreHardwareMonitor kütüphanesinden ve GPU-Z paylaşımlı belleğinden okur. |
| **Yazıcı paylaşım ajanı** | Sistem tepsisinde çalışan ajan. Merkezi sunucudan gelen yazdırma işlerini bilgisayara bağlı yerel yazıcıya gönderir. Yönetim uygulaması da var, ikisi de tek dosyalık `.exe` olarak dağıtılır. |
| **Endüstriyel yazıcı iş döngüleyici** | Markem-Imaje kodlama yazıcısında kayıtlı işleri sırayla seçen, aktif işi doğrulayan araç |
| **Illustrator otomasyonu** | CSV verisiyle etiket ve katalog tasarımlarında toplu metin ve renk değiştiren, katmanları adlandıran ExtendScript betikleri |
| **AI sohbet dışa aktarıcı** | DeepSeek ve Gemini sohbetlerini JSON veya ZIP olarak indiren tarayıcı eklentisi |

## Teknolojiler

`Python` · `PyQt6` · `pythonnet` · `LibreHardwareMonitor` · `Tkinter` · `pystray` · `pywin32` · `PyInstaller` · `ExtendScript` · `Chrome Extension API`
