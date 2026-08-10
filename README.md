# TR-PromptAttackSet
TR-PromptAttackSet Büyük Dil Modellerine yönelik prompt saldırılarının tespit edilmesi amacıyla insan denetiminde oluşturulmuş Türkçe bir veri setidir.

Veri seti, hem zararsız (Benign) hem de Prompt Attack sınıfına ait Türkçe prompt örneklerini içermektedir. Veri seti, Türkçe LLM güvenliği ve makine öğrenmesi tabanlı prompt saldırısı tespiti çalışmalarında kullanılmak üzere geliştirilmiştir.

Veri setinde aşağıdaki alanlar bulunmaktadır:

Alan	    Açıklama

Prompt   	Türkçe prompt metni
Label	    İkili sınıf etiketi
Category	Prompt kategorisi

Sınıf Etiketleri
0 — Benign
1 — Prompt Attack

Kategoriler
Prompt_Leakage
Educational
Role_Play
System_Information_Extraction
General_Query
Instruction_Override
Jailbreak
Hard_Negative
Veri Setinin Oluşturulması

Veri seti, mevcut yabancı dildeki bir prompt saldırısı veri setlerinin doğrudan Türkçeye çevrilmesiyle oluşturulmamıştır. Türkçe dil yapısına uygun özgün prompt örneklerinin oluşturulması amaçlanmıştır.


Yazarlar

Ayşe Aktuğ & Merve Kemerci

Fatih Sultan Mehmet Vakıf Üniversitesi
Bilgi Güvenliği Teknolojisi Programı
İstanbul, Türkiye

Atıf
TR-PromptAttack veri setini akademik çalışmalarınızda kullanmanız durumunda, veri setiyle ilişkili akademik yayın yayımlandıktan sonra ilgili çalışmaya atıf verilmesi önerilmektedir.

Lisans
Bu veri seti için şu anda belirli bir açık kaynak veya açık veri lisansı tanımlanmamıştır.
