# Araştırma Soruları

1. Git nedir?
Git yazılım projelerini geliştirirken hız katarken verimliliği artırmak amacıyla oluşturulmuş açık kaynaklı bir sürüm kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
Git,sürüm kontrol sistemi iken Github Git tabanlı projelerin depolanma,paylaşılma ve düzenlemeye açma ortamıdır.

3. Neden bir branch oluşturuyoruz?
Kullanıcının üzerinde çalışıyor olduğu projenin farklı versiyonlarına ve özelliklerine erişmek için oluşturulur. Projeye yenilik eklenmesi gerektiğinde yeni eklenen özelliğin eğer projeyi kötü duruma getirme ihtimali varsa önceki sürüme geri dönülebilmesi açısından önemlidir.

4. Pull Request'in amacı nedir?
Branch'ten sorumlu kişiye eklentiler yapılan kodların eklenmesini istemek amacı ile kullanılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Branch değiştimek için "git checkout" komutu kullanılır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch Uzak depodan yerel depolamaya çekmek için kullanılır.
git pull Uzak depoda yakın zamanda yapılan değişiklikleri indirerek yerel depoda birleştirir.
git merge Başka brach'deki değişiklikleri üzerinde çalışılan branche aktarır.
7. Merge conflict nedir?
Birden fazla kullanıcının aynı dosya ve aynı satırları değiştirip merge edilememesi durumunda olan çakışma.

8. Merge conflict'i nasıl çözeriz?
Çakışmaların kaynağını öğrenerek çakışmanın yaşandığı kullanıcılarla temasa geçip çakışma çözme işleine geçilir.