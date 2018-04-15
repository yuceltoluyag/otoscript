# Otomatik Script Oluşturucu

Merhaba, script dosyaları oluştururken kısayollar için oluşturduğun bash scripttir. Örneğin eğlence için kullandığınız bir scripti yada düzenlediğiniz bir fonksiyona sürekli aynı dizine gidip çalıştırmak yerine fonksiyon ismini yazarak çalıştırabilirsiniz.

# Kullanım.

Ben ana dizine script adında bir klasör oluşturup içerisine tüm scriptlerimi atıyorum. (düzenli olması açısından)

 1. EV dizininize script adında bir klasör oluşturun (ismini isterseniz değiştirin)
 2. İçerisine repodan indirdiğiniz autoscripti atın ve sudo chmod +x autoscript  diyerek çalıştırma yetkisi verin.
 3. Şimdi bu yolu her seferinde yazmamak için bashrc içine yolu belirtiyoruz. Örnek bashrc dosyasını yukarıdan inceleyebilirsiniz. 

    PATH="$HOME/script:$PATH"
    export PATH

Örneğin yukarıda ki örnek banner scriptiyle figlet ve lolcat çıktılarını birleştirip  ortaya renkli bannerler çıkardık :)
banner yucel #şeklinde 

![enter image description here](https://raw.githubusercontent.com/yuceltoluyag/otoscript/master/screenshot.png)
