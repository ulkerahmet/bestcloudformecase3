# Bestcloudfor.me Akademi 2023 Case 3. Görev
- Daha önce oluşturulmuş olan Dockerfile'ın, Docker Image'a dönüştürülmesi görevi tamamlandı.
- Bu görevi tamamlarken Docker Image oluşturmayı, Docker Hub'ı daha detaylı kullanmayı, Docker Hub'da repo oluşturmayı, Docker push komutu ile repoya image göndermeyi ve Docker pull komutu ile repodan image almayı çok daha kapsamlı şekilde öğrendim.
- Docker Hub'da oluşturduğum ve Docker Image yüklediğim repo: https://hub.docker.com/repository/docker/ahmetulker/case-uygulamasi/general

Case'in bu görevinde çalıştırdığım bütün komutla "img" dosyası içinde mevcuttur. Aşağıda yazılı şekilde de açıklamış bulunmaktayım.

1- img dosyasında img1.png adlı ekran kaydında da görüldüğü üzere docker build -t case-uygulamasi . komutu ile case-uygulamasi adında bir Docker Image oluşturdum.

2- Daha sonra docker images komutu ile image'leri kontrol ettim. img2.png adlı ekran kaydında mevcuttur.

3- docker login komutu ile Docker Hub hesabıma CLI üzerinde giriş yaptım ve image'a etiket vermek için docker tag case-uygulamasi ahmetulker/case-uygulamasi:latest komutunu kullandım. img3.png adlı kayıtta mevcuttur.

4- docker push ahmetulker/case-uygulamasi komutu ile oluşturmuş olduğum image'i Docker Hub reposuna yükledim. img4.png adlı kayıtta mevcuttur. 

5- Oluşturduğum Docker Hub reposunun kaydı img6.png adlı ekran görüntüsünde mevcuttur.
