# WebView React Native App

## Uygulamayı kendinize göre uyarlamak için yapmanız gereken bazı şeyler var. Adım adım hepsini göstereceğim.

1. SPLASH SCREEN DEĞIŞTIRME:

- Splash Screen değiştirmek için, "**assets**" klasörü içerisine girin, "**images**" isimli gördüğünüz klasörün içerisinde "**splash_image.png**" dosyasını göreceksiniz. Açılış sırasında çıkmasını istediğiniz **".png"** uzantılı dosyanızı yeniden isimlendirerek "**splash_image.png**" yapın ve buraya sürükleyip bırakın. Dosyayı değiştir deyin.
- Ardından ana dizinde bulunan **"app.json"** dosyamız içerisinden **"backgroundColor": "#131c47"** yazan satırdan arkaplan renginizi değiştirin. Görsel bazen tam ekrana sığmayabiliyor. Şu an sarı durumda oraya isterseniz background:"white" gibi ifadeler verebilir ya da hex kodu olarak başına diyez koyup yerleştirebilirsiniz.

2.SAYFALARI AYARLAMA:

- Öncelikli olarak sayfalarımızı ayarlamaya geçmeden önce bilgisayarımızda **nvm** paket yöneticisi yüklü olmalı. 

	[Nvm Windows Zip](https://drive.google.com/file/d/13D7FpGEBQY7TiOgSyXtmAOShByPSxTsW/view?usp=sharing "Nvm Windows Zip")
	
- Linux için ise buradaki kurulum adımlarını izleyelim. 
[Debian](https://tecadmin.net/how-to-install-nvm-on-ubuntu-20-04/ "Debian")
- Arch kullanıyor iseniz zaten Aur repolarında bulunmakta.

- Yükleme sonrası terminal/cmd ekranına "nvm install 15.0.0" ve ardından "nvm use 15.0.0" yazmanız gerekmekte. 
- Şimdi projemizi çalıştırmaya başlayabiliriz. Kullandığınız kod editörü ile dosyamızı açıp terminal ekranına "npm install" yazın. Ardından expo start diyerek uygulamamızı başlatın. Uygulamayı gerçek zamanlı görmek isterseniz ister web, ister android, ister ios olarak görüntüleyebilirsiniz. Android ve Ios için elbetteki emulatorler yüklü olmalı.

- Şimdi geldik değiştirmemiz gereken sayfalara
 1. Screens klasörü altında TabOne,TabTwo,TabThree,TabFour,TabFive dosyaları bulunmakta. Açtığınız zaman uri: yazan kısımda bir internet adresi göreceksiniz. Oradaki adresi kendi sitenizin adresleri ile değiştirin.
 2. Eğer ben 5 Tab kullanmak istemiyorum derseniz yapmanız gereken yine basit.Navigation klasörü altında bulunan index.tsx dosyası içerisinde Buradan başla yazan yerden başlayarak buradan sil veya kopyala yazan yere kadar silebilir ya da kopyalayarak diğer tabların altına yapıştırabilirsiniz. 
 3. Tablar altında gördüğünüz Title etiketi altından ise sayfa başlıklarını değiştirmeniz mümkün. Yine tırnaklar arasına yazarak sayfaları isimlendirebilirsiniz.
 4. Iconları değiştirmek için ise [Iconların isimleri burada](https://icons.expo.fyi/ "Iconların isimleri burada") buradan istediğiniz iconu seçip orada kullanabilirsiniz. Size hangi satırı değiştirmeniz ve hangi satırı eklemeniz gerektiğini söyleyecektir.
 5. Sorularınız için istediğiniz zaman [Instagram](https://instagram.com/nickzsche "Instagram") ve [Linkedin](https://linkedin.com/nickzsche "Linkedin") üzerinden ulaşabilirsiniz. 

