# **Git Nedir?**
Git, bir versiyon kontrol sistemidir. Lokal veya remote çalıştığınız projeleri versiyonlamak, bilgisayarınıza veya sanal depoya yüklemenizi sağlar.

---

## **Git Komutları**

### **Genel Komutlar:**
- `git diff` -> Commit'ten önceki değişiklikleri gösterir.
- `git clone https://github.com/1yakupoguz/learnGit.git` -> Linkteki repoyu locale kopyalar.
- `git remote set-url origin https://youruser:password@github.com/user/repo.git` -> Hangi hesapla yükleyeceğinizi belirtebilirsiniz.
- `git add README.md` -> Belirtilen dosyayı **stage area**'ya ekler.
- `git commit -a -m 'test'` -> Tüm dosyaları "test" mesajıyla commit eder.
- `git push` -> Ortak repoya localdeki dosyaları yükler.
- `git pull` -> Ortak repodan dosyaları çeker.
- `git log` -> Commit'leri listeler.

### **Branch Yönetimi:**
- `git checkout` -> Branch'ler arasında geçiş yapmayı sağlar.
- `git checkout -b developer1` -> "developer1" branch'ini oluşturur ve geçiş yapar.
- `git push --set-upstream origin yak47` -> Remote'ta var olmayan bir branch oluşturur ve içine commitleri pushlar.
- `git merge developer1` -> **Main** branch'i ile **developer1** branch'ini birleştirir.

### **Kullanıcı Bilgileri Ayarlama:**
- `git config --global user.name "Yakup OĞUZ"`
- `git config --global user.email "1yakupoguz@gmail.com"`

### **Dosya ve Dizin İşlemleri:**
- `cd ..` -> Bir üst dizine gider.
- `touch deneme.txt` -> Bulunduğun dizinde yeni bir dosya oluşturur.
- `git add "index.html"` -> "index.html" dosyasını **stage area**'ya ekler.
- `git status` -> Bulunduğun konumdaki dosyaların commit durumunu gösterir.
- `git commit -m "commit1"` -> "commit1" mesajıyla commit işlemi yapar.
- `git log --oneline` -> Kısaltılmış commit listesi sunar.
- `git checkout <log_numarası> -- .` -> Belirtilen commit'e geri döner.

### **Değişiklikleri Yönetme:**
- `git diff` -> Dosya içerisinde yapılan değişiklikleri + / - olarak gösterir.
- `git checkout -- dosya.adi` -> Geri alma işlemi yapar.
- `git reset HEAD deneme4.txt` -> Dosya **staging area**'daysa geri çeker.
- `git rm dosya.txt` -> Dosyayı siler.
- `git rm -r test/` -> "test" klasörünü içindekilerle beraber siler.
- `git mv deneme.txt test.txt` -> "deneme.txt" dosyasını "test.txt" olarak değiştirir.
- `git mv deneme.txt dd/` -> "deneme.txt" dosyasını "dd" klasörüne taşır.
- `git mv deneme.txt dd/abc.txt` -> "deneme.txt" dosyasını "dd" klasörüne "abc.txt" ismiyle taşır.

### **Alias Kullanımı:**
- `git config --global alias.st status` -> `git status` komutunu `git st` olarak kısaltır.

### **Remote İşlemleri:**
- `git remote add origin https://github.com/xxxxxx` -> Remote bağlantısı ekler.
- `git push -u origin master` -> Master branch'ine push yapar.
- `git pull` -> Github'a eklenenleri locale çeker.

### **Gitignore Nedir?**
- `.gitignore` dosyası, **Git deposuna eklenmeyecek dosyaları** belirler.
- **Projenin başında oluşturulması tavsiye edilir.**

### **Branch Yönetimi:**
- `git branch -all` -> Remote ve local tüm branch'leri gösterir.
- `git fetch` -> Remote branch'leri çeker.
- `git pull` -> Remote değişiklikleri alır.
- `git checkout dev` -> "dev" branch'ine geçer.
- `git merge dev` -> "dev" branch'inden "master" branch'ine dosyaları alır (canlıya alır).
- `git fetch -p` -> Remote'ta olmayan branch'leri temizler.
- `git branch -D test` -> Lokaldeki "test" branch'ini siler.
- `rm -rf EOGC` -> Git deposunu silmeye yarar.

---

## **Stage Area Nedir?**
Commit'lenmesini istediğiniz dosyaları eklediğiniz alan.

---

## **Tavsiye Kaynaklar:**
- [Git Atlassian Eğitimleri](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
- [Learn Git Branching](https://learngitbranching.js.org/)

