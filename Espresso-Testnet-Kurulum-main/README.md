# Espresso-Testnet-Kurulum
Espresso Testnet Kurulum Rehberi

1- sudo apt install docker ( komut tamamlandığında Y/n seçeneğine Y yazıp enterliyoruz.)  
  
2- apt install docker.io ( komut tamamlandığında Y/n seçeneğine Y yazıp enterliyoruz.)  
  
3- curl https://www.espressosys.com/cape/docker-compose.yaml --output docker-compose.yaml  
  
![first](https://cdn.discordapp.com/attachments/933304569943957514/988963574070263838/1.png)  
  
bu çıktıyı aldığımızda adımlara devam ediyoruz.  
  
4- apt install docker-compose ( komut tamamlandığında Y/n seçeneğine Y yazıp enterliyoruz.)  
  
5- docker-compose pull  
  
![first](https://cdn.discordapp.com/attachments/933304569943957514/988963574363869184/2.png)  
    
bu çıktıyı aldığımızda adımlara devam ediyoruz.  
  
6- apt-get install screen  
  
7- screen -S Espresso (komutunu yapıştırınca görseldeki gibi yeni ekrana geçiyoruz.  
  
![first](https://media.discordapp.net/attachments/933304569943957514/988963574720364544/3.png)  
  
8- docker-compose up  
  
![first](https://media.discordapp.net/attachments/933304569943957514/988963575139807302/4.png)  

9- Bilgisayarınızın başlat menüsüne ‘’ Komut İstemi’’ yazıp yönetici olarak çalıştırıyoruz.  

![image](https://user-images.githubusercontent.com/107777584/174918504-85ab4043-4a03-4729-821a-a8a349434cc5.png)  

Açılan ekranın aşağıdaki gibi olması gerekiyor.  

![image](https://user-images.githubusercontent.com/107777584/174918625-a8123149-599c-497f-a6e6-2d8ef690ba88.png)  

10- Digital oceanda aşağıda işaretlediğimiz İpv4 kısmındaki ip adresini kopyalıyoruz ve 10-11 numaralı kodlarda sunucu ip yerine yazıyoruz. Ardından komut isteminde açtığımız ekrana bu kodları sırayla yapıştırıyoruz. (Her komuttan sonra enterlemeyi unutmuyoruz)  

![image](https://user-images.githubusercontent.com/107777584/174918722-0aedc45d-d577-4245-b75a-4942af959156.png)  

11- netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=80 connectaddress=sunucu ip connectport=80  

12- netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=60000 connectaddress=sunucu ip connectport=60000  
Ekranda bu şekilde görünmeli (mavi çizgi olan yere kendi iplerinizi yazıyorsunuz)  

![image](https://user-images.githubusercontent.com/107777584/174918793-dbbd927a-9c67-460d-9a62-a4f868ec70e7.png)  

13- Tarayıcımıza girip yeni sekme açarak arama paneline localhost yazıp enterliyoruz.  
Ekran aşağıdaki gibi gözükecektir.  

![image](https://user-images.githubusercontent.com/107777584/174918835-ecccffb8-ff8c-46a5-a5a1-5399f7da8ef5.png)  

14- Set up a new wallet butonuna tıklayıp devam ediyoruz.  

![image](https://user-images.githubusercontent.com/107777584/174918922-33578b82-77da-4c43-b854-f138699f1ae0.png)  

15- Reveal Keys butonuna tıklayarak devam ediyoruz.  

![image](https://user-images.githubusercontent.com/107777584/174919078-c1d036e0-7713-4f82-b6a0-4606233ad3a3.png)  

16- Üstü çizili 12 kelimeyi güvenli bir yere kaydedip continue butonuna basalım.  

![image](https://user-images.githubusercontent.com/107777584/174919401-27596867-8c19-4583-8909-664325c03ec4.png)  

17- Bir önceki adımda kopyaladığımız sıraya göre kelimeleri butonlara tıklayarak seçelim ve continue diyelim.   

![image](https://user-images.githubusercontent.com/107777584/174919474-d0d3a027-87e9-498d-a7c5-9cdc9a89beda.png)  

18- Keystore name kısmını doldurup not alalım ve continue butonuna basalım.  

![image](https://user-images.githubusercontent.com/107777584/174919518-1caf7ed4-a133-47e1-acdb-9ced86c4d5dc.png)  

19- Şifre oluşturup continue butonuna basalım. (Şifreyi kaydetmeyi unutmayın !)  

20- Sonraki ekranda create wallet diyerek işlemi tamamlanmasını bekliyoruz. (Biraz zaman alabilir)  

![image](https://user-images.githubusercontent.com/107777584/174919555-f91fe66d-c534-4352-ab8c-b55d32b92466.png)  

![image](https://user-images.githubusercontent.com/107777584/174919570-dd089704-c4f3-4df8-b342-6c9ac100b2a0.png)  

![image](https://user-images.githubusercontent.com/107777584/174919598-464c6710-7aea-443e-a831-3f3e084b8c62.png)  

![image](https://user-images.githubusercontent.com/107777584/174919623-ab8400c6-97a9-4248-bf33-0eb75b136254.png)  

21- Şifremizle giriş yapıyoruz.  

![image](https://user-images.githubusercontent.com/107777584/174919661-e4fe9b22-91e8-4d22-a5e9-ca4f8425e085.png)  

22- Sırasıyla 1 ve 2 nolu adımlara tıklıyoruz.  

![image](https://user-images.githubusercontent.com/107777584/174919734-70cf9756-817b-40e3-9ac4-4cd6179cf1ae.png)  

23- Oluşturduğumuz cüzdan adresini kopyalayıp aşağıdaki tweete cevap olarak gönderiyoruz. Böylece tokenleri talep etmiş olacağız.  

https://twitter.com/EspressoSys/status/1537447721916698625  

![image](https://user-images.githubusercontent.com/107777584/174919774-d96123bc-5d4c-42a2-8e0f-4b1fc89b0a2f.png)  
