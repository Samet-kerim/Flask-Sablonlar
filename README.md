## Flask- Sablonlar
 Bu uygulammamızda html dosyalarını döndüren fonksiyon yani template yazacağız.Bunun için ilk önce template yani html sayfasını döndürmemizi sağlayan render_template fonksiyonunu projemize ekliyoruz.
 "From flask import Flask, render_template" yaparak render_template i import ediyoruz. Html kodlarımızı templates klasörünün içine yazdığımıza dikkat ediyoruz.
 Html kodlarımızda head /head arasına başılığımızı yazıyoruz. body/body arasınada sayfamızda yazıcağımız metni yazıyoruz. Bunuda şu şekilde yapıyoruz.h2 /h2 arasına sayfadaki başlığı p /p arasınada normal metni yazdım.Html kodlarını bu şekilde tamamladım.
 Daha sonra app.py a gelerek kodlarımı yazmaya başladım.Burada
 "def index():
    return  render_template("index.html")" yaparak Html kodlarının yazılı olduğu index.html dosyasını belirterek fonksyounumu doldurdum ve sayfamı tamamlamış oldum.
