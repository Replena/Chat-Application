# Chat Uygulaması

Bu proje, kullanıcıların web üzerinden gerçek zamanlı olarak mesajlaşabileceği bir chat uygulaması geliştirmeyi amaçlamaktadır. Uygulama, hızlı geliştirme süreci için **Vite**, **React**, **TypeScript** ve **WebSocket** gibi modern teknolojiler kullanılarak oluşturulmuştur. Proje, kullanıcı dostu bir arayüz ve çeşitli özelliklerle desteklenecektir.

## Özellikler

- Gerçek zamanlı mesajlaşma.
- Kullanıcı giriş/çıkışı.
- Kişisel sohbetler ve grup sohbetleri.
- Mesaj geçmişi.
- Kişi listesi ve çevrimiçi durum.
- Anlık bildirimler.
- Mesaj gönderme ve alma işlevleri.

## Teknolojiler

Bu projede kullanılan başlıca teknolojiler:

- **React**: Kullanıcı arayüzü için.
- **TypeScript**: Tip güvenliğini sağlamak için.
- **Vite**: Hızlı geliştirme sunucusu ve derleme için.
- **WebSocket**: Gerçek zamanlı iletişim için.
- **MongoDB**: Mesaj geçmişi ve kullanıcı verilerini depolamak için.
- **JWT (JSON Web Token)**: Kullanıcı kimlik doğrulaması için.

## Başlangıç

Projenizi başlatmadan önce, gerekli bağımlılıkları yüklemeniz ve geliştirme sunucusunu başlatmanız gerekecek.

### 1. Depoyu Klonlayın

Öncelikle, projeyi kendi bilgisayarınıza klonlamak için aşağıdaki komutu kullanın:

````bash
git clone https://github.com/your-username/chat-uygulamasi.git

### 2. Bağımlılıkları Yükleyin

Proje dizinine girdikten sonra, gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:

```bash
npm install

### 3. Geliştirme Sunucusunu Başlatın

Bağımlılıklar yüklendikten sonra, geliştirme sunucusunu başlatmak için şu komutu kullanabilirsiniz:

```bash
npm run dev

### 4. WebSocket Sunucusunu Başlatın (Opsiyonel)

```bash
npm run start-server

### 5. Tarayıcıda Uygulamayı Görüntüleyin
Geliştirme sunucusu başlatıldıktan sonra, tarayıcınızda şu adresi ziyaret ederek chat uygulamanızı görebilirsiniz:
```bash
http://localhost:3000

##Proje Yapısı
Projenin ana dizin yapısı şu şekildedir:

/chat-uygulamasi
├── /public                  # Statik dosyalar
├── /src
│   ├── /components          # React bileşenleri
│   ├── /contexts            # React context API dosyaları
│   ├── /hooks               # Özel React hook'ları
│   ├── /services            # API ve WebSocket servisleri
│   ├── /styles              # CSS ve stil dosyaları
│   └── App.tsx              # Ana uygulama bileşeni
├── /server                  # WebSocket sunucu dosyaları
│   ├── server.ts            # WebSocket ve API sunucu dosyası
│   └── config.js            # Sunucu konfigürasyon dosyası
├── .gitignore               # Git için hariç tutulan dosyalar
├── package.json             # Proje bağımlılıkları ve scriptler
├── tsconfig.json            # TypeScript konfigürasyonu
└── vite.config.ts           # Vite konfigürasyonu

GitHub Kanban
Proje, geliştirme sürecini izlemek ve yönetmek için GitHub Kanban kullanarak organize edilmektedir. Her bir özellik ve fonksiyon için görevler kanbanda yer almaktadır. Bu sayede, projenin hangi aşamada olduğu ve hangi özelliklerin geliştirildiği açıkça takip edilebilir.

Kanban Kullanımı
Görevlerin Tanımlanması: Proje, To Do, In Progress, ve Done gibi kategorilerle izlenebilir.
Pull Request: Yeni özellikler veya düzeltmeler için bir feature branch oluşturup, Pull Request açarak kodu ana dal ile birleştirebilirsiniz.
Kod İnceleme: Pull Request'ler, takım arkadaşları tarafından incelenebilir ve onaylandıktan sonra ana koda dahil edilir.

Katkı Sağlama
Eğer bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

Bu repo'yu fork edin.
Yeni bir feature branch oluşturun (git checkout -b feature-xyz).
Değişikliklerinizi yapın ve commit'leyin.
Pull request oluşturun.

Lisans
Bu proje, MIT Lisansı altında lisanslanmıştır. Lisans bilgisi için LICENSE dosyasını inceleyebilirsiniz.
Bu markdown içeriği, direkt olarak README dosyanıza kopyalayabileceğiniz şekilde düzenlenmiştir. Projenizle ilgili detaylara göre özelleştirebilirsiniz.

````
