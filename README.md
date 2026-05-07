🎓 Sınavım - Yerli Akademi platformu

Sınavım, öğretmenler ve öğrenciler için tasarlanmış, Yapay Zeka (Gemini AI) destekli, oyunlaştırılmış ve tam entegre bir modern eğitim platformudur. Bu platform, klasik dosya paylaşım sistemlerinin ötesine geçerek interaktif HTML oyunları, Wordwall entegrasyonları, gerçek zamanlı deneyim puanı (XP) ve seviye (Level) sistemleri sunar.

 Not: Logo projenin ana dizininde yer almaktadır.

🚀 Öne Çıkan Özellikler

🤖 AI Mentor Pro (Gemini 2.5 Flash): Öğrencilere 7/24 rehberlik eden, Markdown destekli (kalın yazılar, listeler) akıllı yapay zeka asistanı.

✨ AI İçerik Stüdyosu: Öğretmenlerin sadece bir konu başlığı yazarak Gemini AI'a anında deneme sınavları ve ders notları ürettirebildiği akıllı stüdyo.

🎮 Etkileşimli Oyun Merkezi: Sadece PDF ve video değil; özel HTML kodlu oyunlar ve Wordwall etkinliklerinin doğrudan platform içinde oynatılabildiği merkez.

🏆 Oyunlaştırma (Gamification):

Giriş yapılan her ardışık gün için Günlük Seri (Streak) takibi.

İçerik paylaştıkça ve etkileşime girdikçe kazanılan XP'ler.

XP sınırları aşıldıkça atlanan Seviyeler (Level) ve dinamik profil kartları.

👁️ Site İçi Görüntüleyici (In-Site Viewer): Hiçbir dış linke gitmeden YouTube videolarının, PDF'lerin ve oyunların platform üzerinde açıldığı şık Overlay sistemi.

📸 Gelişmiş Profil Yönetimi: Kullanıcıların kendi cihazlarından doğrudan profil fotoğrafı yükleyebildiği (Base64) ve anında tüm sisteme senkronize edilen profil altyapısı.

🔐 Rol Bazlı Yetkilendirme (RBAC): Öğrenci, Öğretmen ve Yönetici rolleri sayesinde güvenli içerik yönetimi. Öğrenciler yönetim panellerini göremez, sadece içeriğe odaklanırlar.

🛠 Kullanılan Teknolojiler

Bu proje, yüksek performanslı ve modern bir Single Page Application (SPA) olarak tek bir HTML dosyasında inşa edilmiştir.

Frontend: HTML5, CSS3, JavaScript (ES6+ Module)

Stil & UI: Tailwind CSS (CDN), Glassmorphism tasarım dili, Material Symbols.

Backend & Veritabanı: Firebase v11.6.1 (Authentication & Firestore)

Yapay Zeka: Google Gemini API (Gemini 2.5 Flash Preview)

👥 Kullanıcı Rolleri ve Yetkiler

Yönetici (Admin): Sistemin kurucularıdır. Belirli e-posta adreslerine (örn. sunaycapa3@gmail.com) otomatik olarak atanır. Tüm istatistikleri, logları görebilir ve her türlü içeriği yönetebilir.

Öğretmen (Teacher): İçerik Stüdyosu'na erişebilir; sınav, belge, video ve oyun paylaşabilir. Öğrenci loglarını göremez.

Öğrenci (Student): Kayıt sırasında seçilebilir. Sadece İçerik Havuzu, Oyun Merkezi ve AI Mentor'a erişebilir. İçerik yükleyemez.

⚙️ Kurulum ve Çalıştırma

Proje, herhangi bir Node.js veya derleme aracı gerektirmeyen saf bir HTML dosyasıdır. Ancak ES6 modülleri (Firebase importları) kullanıldığı için doğrudan file:// protokolü ile açıldığında tarayıcı güvenliği (CORS) nedeniyle çalışmayabilir.

Yerel Ortamda Çalıştırma (Localhost)

Projeyi bilgisayarınıza indirin veya klonlayın.

Klasör içinde image_2cd20a.jpg adlı logonun bulunduğundan emin olun.

Visual Studio Code kullanıyorsanız Live Server eklentisini kurun ve index.html dosyasına sağ tıklayıp Open with Live Server seçeneğini tıklayın.

Veya Python kuruluysa terminalde şu komutu çalıştırın: python -m http.server 8000

🔑 API ve Firebase Yapılandırması
