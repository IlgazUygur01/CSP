To watch the video please click on this link : https://drive.google.com/file/d/18qGlqYcHu2FM5JZE7ANIP-bsG52zZv6F/view



📌 Program Purpose and Function (Programın Amacı ve İşlevi)
Programınızın amacı nedir?
Day Planner uygulamasının amacı, kullanıcıların günlük görevlerini planlayarak zamanlarını daha verimli kullanmalarını sağlamaktır.

Hangi problemi çözmeyi hedefliyor?
Birçok kişi gün içinde yapması gereken işleri unutur ya da organize etmekte zorlanır. Bu uygulama, görev takibi ve zaman yönetimi problemini çözmeyi hedefliyor.

Programınız kullanıcılara ne sağlar?
Kullanıcılar gün içinde yapacakları işleri ekleyebilir, düzenleyebilir ve tamamlandıkça işaretleyebilir. Böylece görevlerini görsel olarak takip edebilirler.

Programın temel işlevleri nelerdir?

Yeni görev ekleme

Görevleri saatlere göre organize etme

Görevleri tamamlandı olarak işaretleme

Görevleri silme veya düzenleme

Kullanıcı bu programı nasıl kullanır?
Uygulama açıldığında, kullanıcı bir görev adı ve saati girerek yeni bir görev oluşturur. Görev listesinde tamamlanan görevler işaretlenebilir veya silinebilir.

🛠️ Program Development Process (Program Geliştirme Süreci)
Bu program fikrine nasıl ulaştınız?
Kendi günlük planlamamda yaşadığım karışıklık ve unutkanlık sorunları beni böyle bir uygulama yazmaya yönlendirdi.

Programı geliştirirken nasıl bir planlama yaptınız?
İlk olarak kullanıcı arayüzünü kağıt üzerinde çizdim, sonra SwiftUI ile tasarladım. Ardından görev ekleme, silme ve güncelleme gibi temel işlevleri sırasıyla kodladım.

Geliştirme sürecinde kimden geri bildirim aldınız?
Ailem ve birkaç arkadaşım uygulamayı test etti ve bazı özelliklerin eksik olduğunu söyledi (örneğin görev sıralama).

Bu geri bildirimler doğrultusunda ne gibi değişiklikler yaptınız?
Görevleri saat sırasına göre sıralama ve tamamlanmış görevleri liste sonunda gösterme özelliklerini ekledim.

Programınızı test ederken nasıl bir yöntem kullandınız?
Manuel testler yaptım. Farklı saatlerde ve isimlerde görevler ekleyip bunların doğru sıralanıp sıralanmadığını ve tamamlandıkça liste dışına çıkıp çıkmadığını kontrol ettim.

🔁 Algorithm Implementation (Algoritma Açıklaması)
Programınızda hangi algoritmayı kullanıyorsunuz?
Görevleri saat bilgisine göre sıralayan bir algoritma kullanıyorum.

Bu algoritma nasıl çalışıyor (adım adım açıklayınız)?

Kullanıcı bir görev eklediğinde, görev bir listeye ekleniyor.

Bu liste saat bilgisine göre sıralanıyor (örneğin: 09:00, 11:00, 14:00 gibi).

Liste her görev ekleme/silme sonrası tekrar sıralanıyor.

Bu algoritmanın içinde koşul (if), döngü (loop) ve işlev (procedure) nasıl kullanılıyor?

if koşulları ile görev saati karşılaştırılıyor.

for döngüsü ile görev listesi sıralanıyor.

sortTasks() adlı bir işlev bu sıralamayı gerçekleştiriyor.

Bu algoritma programın hangi bölümünde önemli rol oynuyor?
Görevlerin doğru sırada gösterilmesini ve kullanıcıya net bir plan sunmasını sağlıyor.

🧱 Abstraction (Soyutlama Kullanımı)
Programınızda bir işlev (function/method) tanımladınız mı?
Evet, addTask(), removeTask(), markAsDone() ve sortTasks() gibi işlevler var.

Bu işlev ne işe yarıyor?
Her işlev tek bir görevi üstleniyor; böylece kod tekrarından kaçınılmış oluyor.

Hangi tekrar eden görevleri soyutlayarak daha sade kod elde ettiniz?
Görev ekleme ve sıralama işlemlerini ayrı işlevlerle tanımlayarak bu işlemleri tekrar tekrar yazmak zorunda kalmadım.

Bu soyutlama, kodun okunabilirliğini nasıl artırdı?
Kod daha modüler ve okunabilir hale geldi. Hangi satırın ne yaptığını anlamak kolaylaştı.

🌍 Impact and Reflection (Etki ve Geri Bildirim)
Programınızın sosyal, etik veya ekonomik bir etkisi olabilir mi?
Evet, bu uygulama kişisel üretkenliği artırarak kullanıcıların daha planlı bir yaşam sürmesini sağlayabilir.

Kullanıcılar program hakkında size ne tür geri bildirim verdi?
Görevleri renklendirme, hatırlatma bildirimi ve günlük motivasyon mesajı gibi ek özellik önerileri geldi.

Programınızın sınırlılıkları nelerdir?
Şu anda hatırlatma bildirim sistemi yok. Ayrıca, görevler sadece manuel olarak silinebiliyor.

Gelecekte programınızı nasıl geliştirmeyi düşünüyorsunuz?
Hatırlatma bildirimleri, haftalık plan görüntüsü ve görev kategorilendirme gibi gelişmiş özellikler eklemeyi planlıyorum.

🐞 Debugging and Problem Solving (Hatalar ve Çözümler)
Kodunuzu yazarken hangi hatalarla karşılaştınız?
Görev saatlerini sıralarken bazı görevlerin yanlış sırada görünmesi gibi hatalar oldu.

Bu hatalar ne zaman ve nasıl ortaya çıktı?
Görevleri farklı saatlerde eklediğimde sıralama algoritmam düzgün çalışmadı.

Hataları tespit etmek için ne yaptınız?
print() komutlarıyla listeyi test ettim. Saat değerlerinin String olarak değil, Date objesi olarak karşılaştırılması gerektiğini fark ettim.

Hatanın kaynağını nasıl belirlediniz?
Veri tipi kontrolü ve sıralama fonksiyonunun adımlarını inceleyerek hatanın türsel bir hata olduğunu anladım.

Hataları çözmek için denediğiniz yöntemler nelerdir?
Saatleri DateFormatter ile dönüştürüp karşılaştırmayı bu şekilde yaptım.

Bu süreçte araştırma yapmanız gerekti mi? Hangi kaynaklardan faydalandınız?
Evet, Swift dokümantasyonu ve Stack Overflow’dan faydalandım.

Bu hatalardan ne öğrendiniz?
Veri tiplerinin doğru seçilmesinin programın işleyişi için çok önemli olduğunu öğrendim.
