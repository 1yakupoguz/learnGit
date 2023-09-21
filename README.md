# learnGit
Kurs 1 notlarim:
Git Nedir?
Git bir versiyon kontrol sistemidir. Local veya remote çalıştığınız projeleri versiyonlamak, bilgisayarınıza veya sanal depoya yüklemenizi sağlar.
Git komutları:
Git diff -> committen önceki değişiklikleri gösterir
Git clone https://github.com/1yakupoguz/learnGit.git -> linkteki repoyu locale kopyalar
Git remote set-url origin https://youruser:password@github.com/user/repo.git -> şeklinde yüklerseniz hangi hesapla yükleyeceğinizide yazabilirsiniz.
Git add README.md  -> Bu komutla istediğiniz dosyayı stage area’ya ekler.
Git commit -a -m ‘test’- > tüm dosyaları test mesajıyla commitler.
Git push -> ortak repoya localdeki dosyalarını yükler. 
Git pull -> ortak repodan dosyaları çeker.
Git log -> commitleri listeler
Git checkout -> branchler arasında geçiş yapmayı sağlar
Git checkout -b developer1 -> developer1 branchini oluşturur ve geçiş yapar
Git push --set-upstream origin yak47 -> remote’ta var olmayan bir branchi önce oluşturup sonra içerisine commitleri pushlamaya yarar.
Git merge developer1 -> main branchiyle developer1 branchini birleştirir. 
Stage Area: Commitlenmesini istediğiniz dosyaları eklediğiniz alan.
Tavsiye kaynaklar : 
https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud 
https://learngitbranching.js.org/
