# omurcelik
kodlama.io
# Veri Tipi Çeşitleri
* ### Metin tipleri: str 
str= çift ya da tek tırnak içerisine yazılabilen bir ya da daha fazla harf, sayı veya özel karakterlerden oluşan bir dizidir.
* ### Sayısal tipler: int , float 
<br> int= Pozitif veya negatif tam sayılardan oluşan veri tipidir.<br>
float= Ondalık sayılardan oluşan veri tipidir.<br>
* ### Dizi tipleri:  list , tuple , range
<br> list= Birbirinden farklı veri tipine sahip ögeleri barındırabilen, sıralı ve değiştirilebilir veri tipidir.
<br> tuple= list veri tipi gibi sıralı ögelerden oluşan veri tipidir. Tuple ile list arasındaki fark ise tuple’ın değiştirilemez olmasıdır.
* ### Adresleme tipleri: dict
<br>dict= Sözlük, veri değerlerini (anahtar:değer) çiftlerinde tutmak için kullanılan veri tipidir. 
* ### Küme tipleri: set 
<br> set= Liste, sözlük ve demet veri türü gibi birden çok veri türünü birlikte barındıran veri tipidir. Kümeler ile ilgili yaptığınız her türlü işlevi(birleşme,kesişim vs.) bu veri tipi ile yapabilirsiniz.
* ### Mantıksal tipler: bool
<br> bool= Mantıksal bir veri tipi olan boolean, True ve False olmak üzere iki değere sahiptir. Mantıksal olarak doğru olan duruma True, yanlış olan duruma ise False değeri karşılık gelir.<br>

***

Kelimelerin hepsi "str", dersi tamamlama oranı "int", login sayfası "bool"

***

  kullanıcıAdı = input("Kullanici adinizi giriniz : ")


  sifre = input("Sifrenizi giriniz: ")


  if kullanıcıAdı == "omurcelik":


     if sifre == "123456":
    
    
          print("Şifre ve kullanıcı adı doğru giriş başarılı")
        
       
      else:
    
    
         print("şifreniz hatalı. Lütfen tekrar deneyin")
         
        
  else:


     print("Kullanıcı adı hatalı tekrar deneyin")

