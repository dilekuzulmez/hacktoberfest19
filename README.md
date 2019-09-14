# İlk Pull Request Nasıl Oluşturulur?
Bu depo, sizlere Github'da ilk pull requestinizi göndermenize yardımcı olmak amacıyla oluşturulmuştur. 
Becerilerinizi, projelerinizi ekleyerek burada kalıcı olarak kalmasını sağlayabilirsiniz. 
Herkes bu depoya katkıda bulunabilir.
En önemli amaç yaklaşmakta olan Hacktoberfest19 etkinliğine Türk katılımını arttırmak ve Türkçe kaynak olarak herkese yardımcı olabilmektir.
Hadi durmayın !! Çekinmeden,utanmadan ilk pull requestinizi gönderin. 😏

Sizde bu depoda yer almak istiyorsanız aşağıdaki adımları takip edin :

## Adımlar

1. Bu depoyu **Fork**'layın.

2. Bu depoyu klonlayın ve aşağıdaki komutu bilgisayarınızdaki terminale kopyalayarak Git aracılığıyla kaynak kodu alın.
```
git clone https://github.com/<github-kullanıcıadı>/ilk-pull-request
```

3. Yapacağınız değişiklikler için yeni bir branch oluşturmalı ve değişiklikleri bu brancha eklemelisiniz.
```
git checkout -b <yeni-branch-adı>
```

4. Geliştiriciler klasörüne bilgilerinizi `<adın-soyadın>.md` dosyası oluşturarak kaydedin.

Bilgilerinizi Geliştiriciler klasörüne ekledikten sonra, adınızı Geliştiriciler.md dosyasındaki Github profilinizin bağlantısıyla birlikte aşağıdaki biçimde ekleyin.
(Sadece Adınız Soyadınız ve Github Kullanıcı Adınızla değiştirin).
Böylece herkesin katkılarınızdan haberi olmasını sağlayacağız.

```
* [<Adı Soyad>](https://github.com/<github-kullanıcıadı>)
```

5. Değişiklikleri ekle, ilk commit mesajını oluştur ve GitHub'a gönder.
```
git add .

git commit -m "Bilgilerim Eklendi."

git push origin <branch-adı>
```

6. Şimdi Pull Request isteği oluşturun ve pull requestinizin bu depoya kabul edilmesini bekleyin.

Bu adımdan sonra proje anasayfasına gittiğimizde Pull Request açmak için aşağıdaki gibi bir buton göreceksiniz.
![Resim](https://github.com/dilekuzulmez/ilk-pull-request/blob/master/Resimler/pull-request.png)

_Not: Eğer bu butonu göremiyorsanız depo anasayfasından “Pull Requests” sekmesine tıklayın, ardından sağ tarafta bulunan “New pull request” butonunu kullanın._

7. Başardınız ! İlk pull requestinizi gönderdiniz. :smile:

Markdown yazım kurallarını öğrenmek isterseniz [buraya](https://guides.github.com/features/mastering-markdown/).
