# Versiyon Kontrol Sistemleri

######

Versiyon kontrol, belirli versiyonların daha sonra çağrılabilmesi için dosya değişikliklerini kaydeden bir sistemdir. Örneğin yazılım kodlarını kaydetmek için kullanılabildiği gibi bilgisayardaki herhangi bir dosya türü için de kullanılabilir. 

Versiyon Kontrol Sistemi, seçili dosyaların ya da tamamının  bir önceki versiyona döndürülmesi sağlayabilmektedir. Projede yapılan değişikliklerin karşılaştırılması, probleme neden olabilecek değişikliklerin en son kimin tarafından yapıldığı gibi bir çok işlemin gerçekleştirilebilmesini sağlamaktadır.

```Git``` : Açık kaynak ve ücretsiz olan bir Dağıtık Sürüm Kontrol Sistemidir.

```Sürüm Kontrol Sistemleri``` : Bir yazılım ekibinin ya da bireyin, üzerinde çalışılan projede, zaman içerisinde oluşan kaynak kodlarındaki değişiklikleri izleyebilmesine ve yönetmesine yardımcı olan araçlardır.


```Git Directory (Repository)``` : Proje üzerinde yaptığınız değişikliklerin depolandığı bölümdür. 

```git clone``` : Var olan bir git repository’sine erişmek, kopyalamak için kullanılır. Bir projeyi indirmek için clone’la başlarız. Erişim çeşitli protokollerle gerçekleşir.


```git init``` : Yeni ve boş bir repository oluşturup, git’in çalışabilmesi için gerekli olan ayarlamaları yapar. Yeni bir projeye başlarken init ile başlarız.

```git status``` : Git üzerinde dosyaların çeşitli durumları vardır. “Tracked, untracked, staged, modified, added gibi..” dosyaların hangi durumda olduğu, hangi branch üzerinde çalıştığımız gibi bilgilere erişmemizi sağlar.

```git pull``` : Çalışılan repository’nin bilgilerini ve yapılan son değişiklikleri local branch’e çeker, merge eder. 

```git fetch``` : Çalışılan repository’nin bilgileri (referanslarını) günceller. Git pull’dan farklı; bilgileri çeker fakat merge yapmaz.

```git add``` : Dosyaların durumunu (status) staged yapar. Git’in commit yapabilmesi için dosyaları hazırlar.

```git commit``` : Yapılan değişiklikleri tek bir commit için sıkıştırır ve repository’e eklenecek hale getirir. 

```git push``` : Uzak sunucuya değişikliklerin gönderildiği komuttur. Push yapılmadan uzak sunucuda hiç bir değişiklik yansımaz, tüm işlemler local ortamda gerçekleşir. 

```git merge``` : İki veya daha çok commit’i bir araya getirir, birleştirir.

[docs](https://www.atlassian.com/git/tutorials)

### Markdown

Web yazarları için tasarlanmıştır ve sadece yazı yazmak için kullanılır. Aynı zamanda birçok döküman formatına çevrilebilmektedir. (pdf, word, html vb.)

![photo](https://ceaksan.com/tr/markdown-nedir/visual-studio-code-markdown.jpg)

[docs](https://www.markdownguide.org/)

