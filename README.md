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
git config --global user.name "Yakup OĞUZ"
git config --global user.email "1yakupoguz@gmail.com"
Kullanıcı adı ve mail belirlenir.
Cd .. -> istenilen dosya yoluna gitmek için
Touch deneme.txt bulunduğun yola dosya oluşturur
Git add “index.html” -> bu dosyayı stage areaya gönderir
Git status-> bulunduğun konumdaki dosyaların commit durumunu gösterir
Git commit –m “commit1”-> commit1 mesajıyla beraber commit işlemini yapar
Git log ->commitleri listeler
Git log –oneline -> kısaltılmış bir commit listesi sunar
Git checkout ‘dönmek istediğin log numarasını git log’dan al’ -- . -> istediğin loga dön
Git diff -> dosya içerisinde yapılan değişiklikleri + - halinde gösterir
Git checkout – dosya.adi -> geri alma işlemi yapar
git reset HEAD deneme4.txt dosya staging areada ise dosyayı geri çeker
Git rm dosya.txt -> silme işlemi yapacağınız
Git rm –r test/ -> test klasörünü içindekilerle beraber siler
Git mv deneme.txt test.txt -> bu sekilde deneme dosyasını test dosyasına çevirir
Git mv deneme.txt dd -> bu şekilde deneme.txt’yi dd klasörünün içine atar
Git mv deneme.txt dd/abc.txt -> deneme.txt ‘ yi dd klasörünün içine abc ismiyle atar
Git config –global alias.st status -> git status islemi git st’Ye dönüşür
Git remote add origin https://github.com/xxxxxx -> yüklenecek hesabı seçer
Git push –u origin master -> master branchına pushlar
Git pull -> githuba eklenenleri lokale çeker
Dosya içinde gitignore açılır ve repoda paylaşılmayacak dosyalar buraya yazılır. Bu dosya projenin başında açılmalıdır.
Gitignore nedir?
Git deposuna eklenmeyecek dosyalar .gitignore klasörü içine yazılır
Master branch canlıda olan
Dev branch geliştirilen
Git branch –all (remote, local tüm branchlari gösterir)
Git fetch (remote branch çekmeye yarar)
Git pull
Git checkout dev ->dev branchine geçer
Git merge dev ->devden mastera dosyaları alır // canlıya alır
Git fetch –p git branchlere bak olmayanları sil
Git branch –D test lokaldeki test branchini siler
rm -rf EOGC -> Git deposunu silmeye yarar

Stage Area: Commitlenmesini istediğiniz dosyaları eklediğiniz alan.
Tavsiye kaynaklar : 
https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud 
https://learngitbranching.js.org/
