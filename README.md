
# Arvasis-In--Line-Kalite-Kontrol-Cihaz-
Arvasis – In-Line Kalite Kontrol Cihazı
Bu depo, Arvasis Bilişim ve Danışmanlık için seçilen In-Line Kalite Kontrol Cihazı üzerine hazırlanmış dört laboratuvar çalışmasını içerir. Çalışmalarda makine emniyeti, endüstriyel siber güvenlik, risk değerlendirmesi ve güvenli uzaktan erişim ele alınmaktadır.
Not: Bu çalışmalar eğitim amaçlıdır; resmî güvenlik denetimi veya cihaz sertifikasyonu değildir. PDF'lerde [V] ile belirtilen bilgiler, cihazın doğrulanmış teknik şartnamesi bulunmadığından varsayımdır.

Laboratuvarlar
Laboratuvar	Konu	Çıktı	Dosya
LAB 1	Safety Architecture	Safety Function Map	[Arvasis_Lab1.pdf](Arvasis_Lab1.pdf)
LAB 2	IEC 62443 Mini Workshop	Zone / Conduit Diagram	[Arvasis_Lab2.pdf](Arvasis_Lab2.pdf)
LAB 3	Threat & Risk + Risk Matrix	Risk Register	[Arvasis_Lab3.pdf](Arvasis_Lab3.pdf)
LAB 4	Secure Remote Access	Secure Architecture	[Arvasis_Lab4.pdf](Arvasis_Lab4.pdf)


Çalışma İçeriği
LAB 1 – Safety Architecture
Konveyör ve ret mekanizmasının tehlikeleri incelenir. Işık perdesi / kapak kilidi → Safety PLC → STO emniyet zinciri, normal PLC ile Safety PLC arasındaki farklar ve güvenli durum (safe state) açıklanır.
LAB 2 – IEC 62443 Mini Workshop
Üretim, emniyet, bakım, uzak erişim ve dış ağ varlıkları zone olarak ayrılır. Bölgeler arası conduit geçişlerinde uygulanacak erişim kontrolleri ve uzaktan bakım kararları değerlendirilir.
LAB 3 – Threat & Risk + Risk Matrix
Üç siber-fiziksel tehdit senaryosu oluşturulur. Riskler L × S × E yöntemiyle puanlanır; ciddi insan güvenliği etkisi taşıyan senaryolar düşük toplam puan alsa da ayrıca önceliklendirilir.
LAB 4 – Secure Remote Access
Mevcut doğrudan internet erişimi ile hedef güvenli mimari karşılaştırılır. Jump server, VPN, MFA, kişisel hesap, oturum kaydı ve varsayılan kapalı erişim ilkeleri ile emniyet sisteminin bağımsızlığı ele alınır.
Dosya Yapısı
.
├── README.md
├── Arvasis_Lab1.pdf
├── Arvasis_Lab2.pdf
├── Arvasis_Lab3.pdf
└── Arvasis_Lab4.pdf
Kullanım
PDF dosyalarını ve bu README.md dosyasını aynı GitHub deposunun ana dizinine yükleyin. Yukarıdaki bağlantılar GitHub üzerinden doğrudan açılacaktır.
Anahtar Kavramlar
Functional Safety · Safety PLC · STO · IEC 62443 · Zone/Conduit · Risk Assessment · Secure Remote Access
