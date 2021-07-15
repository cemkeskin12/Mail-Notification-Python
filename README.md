# Mail Notification On Python

Sabahları mail okuma alışkanlığı edinmek için basit bir program yazdım. Şimdi bu programı nasıl kendinize uyarlayabilirsiniz onu anlatacağım.

Öncelikle main.py dosyası içindeki "hours" kısmına hangi saatlerde bildirim almak istediğinizi ekleyebilirsiniz.
"urls" kısmına ise kendi mail adresinizin ve ya adreslerinizin(kaç tane olduğu farketmez) linkini bırakabilirsiniz.
"icons" kısmına ise kendinizce iconlar ekleyebilirsiniz(bir mailimde google diğerinde trakyamail iconu var) !!Önemli!! logolar .ico formatında olmalıdır.


Programı bir exe dosyası haline getirmek için: 
pip install pyinstaller
indirdikten sonra projenin olduğu dosya yoluna cd ile girerek,

pyinstaller --onefile --noconsole python_dosya_adı
yazarak .exe dosyanızı alabilirsiniz.

Programın bilgisayar çalıştığında çalışması için ise:
Win + R tuşlarına basarak Çalıştır kutucuğunu açın.
shell:startup yazıp, Enter'a basın. Başlangıç klasörü ekrana gelecek.
.exe dosyasının kısayolunu bu klasöre sürükleyin.
