Öğrenci ve Ders Yönetim Sistemi
Bu proje, öğrenci ve ders yönetimini kolaylaştırmak için tasarlanmış bir konsol uygulamasıdır. Kullanıcılar öğrenci, öğretim görevlisi ve ders bilgilerini ekleyebilir, derslere öğrenci kaydedebilir, ders ve öğretim görevlisi bilgilerini listeleyebilir.

İçerik
Öğrenci ekleme ve listeleme
Öğretim görevlisi ekleme ve listeleme
Ders ekleme ve derslere öğrenci kaydetme
Ders bilgilerini listeleme (Ders adı, kredi, öğretim görevlisi ve öğrenci listesi)
Veriler JSON formatında saklanır (Öğrenciler, Öğretim Görevlileri, Dersler)
Kullanılan Teknolojiler
C# (C-Sharp): Konsol uygulaması geliştirmek için kullanılan ana programlama dili.
JSON: Verileri saklamak için kullanılan veri formatı.
.NET: Uygulamanın geliştirilmesinde kullanılan framework.
Özellikler
Öğrenci Yönetimi:

Öğrenci ID'si ve adı soyadı ile öğrenci ekleme.
Öğrencileri listeleme.
Öğretim Görevlisi Yönetimi:

Öğretim görevlisi ID'si, adı soyadı ve unvanı ile öğretim görevlisi ekleme.
Öğretim görevlilerini listeleme.
Ders Yönetimi:

Ders adı ve kredisi ile ders ekleme.
Derslere öğretim görevlisi atama.
Öğrencilere ders kaydettirme.
Ders bilgilerini listeleme (Ders adı, kredi, öğretim görevlisi ve kayıtlı öğrenciler).
Veri Saklama:

Veriler JSON dosyalarında saklanır.
Uygulama başlatıldığında, önceki veriler dosyalardan yüklenir.
Yeni veriler ekledikçe dosyalara kaydedilir.
Kullanım
Başlangıç:
Uygulamayı çalıştırdığınızda, ana menüde seçenekler listelenecektir:
1: Yeni Öğrenci Ekle
2: Yeni Öğretim Görevlisi Ekle
3: Yeni Ders Ekle
4: Derslere Öğrenci Ekle
5: Ders Bilgilerini Listele
6: Öğrencileri Listele
7: Öğretim Görevlilerini Listele
0: Çıkış
Örnek Akış:
Yeni Öğrenci Ekleme:

Öğrenci ID'si ve adı soyadı istenir.
Öğrenci başarıyla eklenir.
Yeni Öğretim Görevlisi Ekleme:

Öğretim görevlisi ID'si, adı soyadı ve unvanı istenir.
Öğretim görevlisi başarıyla eklenir.
Yeni Ders Ekleme:

Ders adı ve kredisi istenir.
Mevcut öğretim görevlileri listelenir ve dersin hangi öğretim görevlisi tarafından verileceği seçilir.
Derse Öğrenci Ekleme:

Mevcut dersler listelenir.
Ders seçildikten sonra mevcut öğrenciler listelenir ve hangi öğrencinin derse kaydedileceği seçilir.
Ders Bilgilerini Listeleme:

Ders adı, kredi, öğretim görevlisi ve dersin kayıtlı öğrencileri listelenir.
Öğrencileri ve Öğretim Görevlilerini Listeleme:

Mevcut öğrenciler ve öğretim görevlileri listelenir.
Veri Kaydetme:
Program kapanmadan önce, yapılan tüm değişiklikler JSON dosyalarına kaydedilir. Bu dosyalar, uygulama tekrar açıldığında yüklenecektir.
