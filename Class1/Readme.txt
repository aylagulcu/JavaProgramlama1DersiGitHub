En basit class örneğidir.
İşlenen konu inheritance ve abstraction konularıdır. 

Bu class tasarımı senaryosu şu şekildedir:
Bir konferansa katılan her bir kişinin bazı bilgilerinin tutulması istenmektedir. Katilimcilar öğrenci, öğretmen ya da yöneticilerdir. Her katılımcının ayrı bir nesne olarak tutulması istenmekte ve bir nesneye kendiniTanit() dendiğinde o nesnenin ad soyad ve kurum bilgilerini döndürmesi istenmektedir.
Bütün katılımcıların ad soyad, telefon ve geldikleri kurum/okul bilgileri saklanmaktadır.  
Öğrencilerin ise ek olarak başarı notları tutulmaktadır.
Öğretmenlerin ise ek olarak konuşma konusu ve ders verdikleri öğrenci sayıları bilgisi tutulmaktadır.
Yöneticilerin ise ek olarak çalışan sayıları ve gene konuşma konuları tutulmaktadır.

Tasarımımız aşağıdaki şekildedir:
İlk önce ortak ve ortak olmayan özellikler saptanır.
Ortak özellikler ayrı bir class içine koyulur (Katilimci class) 
Ogrenci, Ogretmen ve Yonetici classları nın her biri Katilimci classından türetilir. Ek özellikler var ise eklenir.


