# FocusBoard — Görev Yönetimi ve Odak Zamanlayıcı

## Proje Açıklaması
FocusBoard, kullanıcıların günlük görevlerini kategorilere (Ders, Kulüp, Kişisel) ayırarak planlamalarını, ilerleme oranlarını anlık olarak takip etmelerini ve entegre Pomodoro zamanlayıcısı ile odaklanarak çalışmalarını sağlayan modern bir web uygulamasıdır. Görev verileri tarayıcının `LocalStorage` belleğinde saklandığı için sayfa yenilendiğinde veriler korunur.

## Kullanılan Teknolojiler
- **React:** Bileşen tabanlı kullanıcı arayüzü ve state yönetimi (`useState`, `useEffect`)
- **Tailwind CSS:** Modern, karanlık temalı ve mobil uyumlu (responsive) tasarım
- **LocalStorage API:** Tarayıcı tabanlı kalıcı veri depolama
- **GitHub & GitHub Pages:** Sürüm kontrolü ve canlı yayına alma

## Kurulum ve Çalıştırma
Bu proje harici bir derleme aracı gerektirmeden doğrudan tarayıcı üzerinde çalışacak şekilde yapılandırılmıştır:
1. Depoyu indirin veya klonlayın: `git clone https://github.com/cerensirma12/focusboard.git`
2. Proje klasöründeki `index.html` dosyasını herhangi bir modern web tarayıcısında açın veya canlı link üzerinden erişin.

## Yapay Zekanın Kullanım Aşamaları
Bu projenin geliştirilme sürecinde yapay zeka asistanından (**Google Gemini**) aşağıdaki aşamalarda faydalanılmıştır:
- **Planlama ve Veri Modeli:** Uygulama kapsamının belirlenmesi, ekran yerleşiminin kurgulanması ve `LocalStorage` veri yapısının tasarlanması.
- **Kod Geliştirme:** React bileşenlerinin, görev filtreleme ve ilerleme hesaplama mantığının ve Pomodoro geri sayım sayacının kodlanması.
- **Arayüz Tasarımı:** Tailwind CSS ile karanlık tema (dark mode) renk paletinin ve duyarlı kart tasarımının oluşturulması.
- **Dokümantasyon:** `README.md` ve proje teslim dokümanının yapılandırılması.
