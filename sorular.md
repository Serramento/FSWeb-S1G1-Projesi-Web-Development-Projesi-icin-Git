# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Açık kaynak dağıtılmış sürüm kontrol sistemidir. Yazılım geliştiricilerin proje hazırlarken ve yayınlandıktan sonraki süreçte revizyonları yaparken; herkesin projenin bütün aşamalarını ve ne revizyon yapıldığını takip etmelerini ve indirip, katkı yapabilmelerini sağlayan bir sistemdir.

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol sistemidir, projenin her zaman son haline ulaşmamızı ve güncel tutmamızı sağlayan bir araçtır. GitHub ise projelerimizin depolandığı uzak sunucudur. 

3. Neden bir branch oluşturuyoruz?

Git deposu varsayılan bir master branchten oluşur. Git üzerinde geliştirme yaparken test süreci sonunda hatasız olduğuna emin olunca master branche taşıyabilirsiniz. Böylece orjinal kodu değiştirmeden bağımsız çalışmış oluruz.

4. Pull Request'in amacı nedir?

Bilgisayarda git üzerinde yaptığınız değişiklikleri remote depoda güncellememizi sağlar. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git switch main komutu kullanılır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch= branchteki değişiklikleri indirmek için kullanılır.
git merge= başka bir branchteki değişiklikleri kendi branchine entegre etme.
git pull=depodaki değişiklikleri almak, bunları mevcut çalışma ile birleştirmek.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 

8. Merge conflict'i nasıl çözeriz?

Stash ve rebase komutları kullanılır. Stash değişikliklerin depoya gönderilmeden saklanmasını sağlayan komut. Rebase ise branchler arasında kodları eşitlemeye yarayan komut. Merge gibi ancak ters yönde işliyor.
