# VERİ BİLİMİNE GİRİŞ

Veri Bilimi: Veriyi toplama,temizleme,analiz etme ve ondan anlamlı sonuçlar çıkarma sürecini ifade eder.Bu disiplin; matematik,istatistik,bilgisayar bilimi ve alan bilgisi gibi birçok farklı dalın birleşiminden oluşur.
- Veri bilimi,büyük veri setlerini anlamlandırarak iş kararlarını güçlendirme,müşteri davranışlarını anlama veya bilimsel araştırmalar yürütme gibi birçok amaca hizmet eder.
Veri bilimi süreci; veri toplama,veri ön işleme,model oluşturma,model değerlendirme ve sonuç sunma aşamalarından oluşur.

Veri: Ham,işlenmemiş ve anlamsız bilgi parçacıklarıdır.Örneğin bir web sitesinin ziyaretçi sayısı,anket sonuçları,bir sensörden alınan ölçümler "veri"dir.
Bilgi: Verinin belirli bir bağlama yerleştirilmesi ve anlaşılabilir hale gelmesi ile oluşur.
İçgörü: Bilgiyi derinlemesine analiz ederek ve belirli kalıplar keşfederek elde edilen değerli sonuçlardır. Örneğin müşterilerin hangi ürünleri hangi koşullarda daha çok satın aldığını anlamak.

NOT: İçgörü doğuştan değil verilerden gelir.

# Veri Bilimi Alanında Kullanılan Araçlar
1. Programlama Dilleri: Python,kullanım kolaylığı ve geniş kütüphane desteği avantajlarıyla veri bilimciler arasında popülerdir.R dili de veri biliminde kullanılmaktadır.
2. Veri Görselleştirme Araçları: Matplotlib,Seaborn,Plotly gibi Python kütüphaneleri;Tableau,Power BI gibi görselleştirme araçları veriyi görselleştirerek içgörülerin daha anlaşılır olmasını sağlar.
3. Veri Analiz Araçları: Pandas ve Numpy,veri analizi ve manipülasyonu için kullanılan güçlü kütüphanelerdir.Jupyter Notebook;kodlama,analiz yapma,sonuçları belgeler halinde saklama açısından önemli bir araçtır.
4. Makine Öğrenmesi Kütüphaneleri: Scikit-learn,TensorFlow,Keras gibi kütüphaneler;model oluşturma,eğitme ve geliştirme süreçlerinde kullanılır.

Veri bilimi,veri analitiğinden farklı olarak TAHMİNLEME de yapar.

Model,bir desendir.Amacımız verideki desenleri yakalamaya çalışmak.Makineye birçok veri veriyoruz.Makine buradan desen çıkarıyor.İşte buna makine öğrenmesi denir.

Yapay zeka asla bilmez,sadece tahmin eder -> Next Token Prediction
Yapay zeka modeli parametrelerden oluşur ve bu parametrelerin nasıl kullanıldığı bu modelin içindedir.
Yapay zeka modeli,hesap mkakinesiyle bulunamayan ve tecrübeye dayanan verilerden oluşur.

Halüsinasyon: Yapay zekanın yanlış yaptığı bilgidir.
Yapay zeka,makine öğrenmesinin daha da üstündedir.

Model: Kuralların ve parametrelerin bir bütün olarak bulunmasıdır.Hiçbir makine öğrenmesi modeli %100 bilmez.

kayıp miktarı=cost(loss) function
W=weight=parametre

## RELU Aktivasyon Fonksiyonu: 0'ın altındaki tüm sayıları sıfırlar.0'ın üstündekilere dokunmaz.

Hataların yönleri(negatif/pozitif)önemli.Bu yüzden hataların karelerini alacağız.[Mean Squared Error(MSE)]

### Softmax Fonksiyonu: Verilen sayıların toplamı 1 olacak şekilde işleme sokar.
### Sigmoid Fonksiyonu: verilen bütün sayıları 0 ve 1 arasına yerleştirir. Örn : 16/17 gibi sağ taraf,sol taraftaki sayıdan 1 fazla olacak.

Boyut (Dimension) genellikle veri kümesindeki özellik (Feature) sayısını ifade eder.Örneğin: bir veri kümesinde yaş, maaş, eğitim seviyesi gibi 3 özellik varsa, veri 3 boyutludur.

Feature(Özellik): Veri setindeki sütunlardır.Özellik sayısı arttıkça daha fazla detay olur ancak işlem sayısı artar.

## Makine Öğrenmesi ve Geleneksel Programlamanın Farkı
-> Makine,çarpma işlemi yapacağını asla öğrenmez.Biz makineye işlemi vermeliyiz.
-> Geleneksel programlamada ise neyle çarpım yapacağını biliyoruz.
-> Makine öğrenmesinde verilen örüntüden yararlanılıyor.Makine; bu işlemlerde kullanacağı sayıyı yani "parametre"yi öğrenmeye çalışıyor.
Makine öğrenmesi modeli; makine öğrenmesi algoritmalsı ve algoritmada kullanılan değer/değerlerden oluşur.

## Lineer Regresyon 
Denklem her zaman y=ax+b şeklindedir.Bağımsız değişkenler (özellikler) ile bağımlı değişken (hedef) arasındaki doğrusal ilişkiyi modelleyen bir regresyon tekniğidir. Lineer regresyon, basit ve yorumlanabilir olmasıyla veri bilimi ve makine öğrenmesinde temel bir modeldir. 
Özetle lineer regresyon,doğru çizerek çözülebilen regresyon problemleridir.Fakat sadece lineer regresyonla çözülebilen problem sayısı gerçek dünyada oldukça azdır.

## K-Means Algoritması
K-Means algoritması, veri noktalarını K adet kümeye ayıran bir kümeleme (clustering) yöntemidir.
Unsupervised(gözetimsiz)learning algoritmalarındandır.

### K-Means Algoritmasının Adımları:
1. Başlangıçta K adet merkez (centroid) rastgele seçilir.
2. Her veri noktası, en yakın merkeze atanır.
3. Her küme için yeni merkezler, kümedeki noktaların ortalaması alınarak güncellenir.
4. Adımlar tekrar edilir (küme merkezleri değişmeyene veya belirli bir iterasyon sayısına ulaşılana kadar).

K değeri önceden belirlenmelidir.
K-means, Öklid mesafesini kullanarak noktaları gruplar.

Regresyon: Sayı veririm,bana sayı verir(numeric to numeric).Geçmiş verilerden öğrenir.
Sınıflandırma Problemleri:Grupların bir ismi var.
Kümeleme Problemleri:Grupların bir ismi  yok.

NOT: Next token prediction bir tür sınıflandırma problemidir.
Model, bir dizideki sonraki token'ı belirlemeye çalışırken tüm kelime haznesi (vocabulary) içindeki olasılıkları hesaplar.
Her token bir sınıf gibi düşünülebilir.
Model, en yüksek olasılığa sahip token’ı seçerek sınıflandırma yapar.

Örneğin:
Eğer bir dil modeli "Ben kahve içmek..." ifadesini görüyorsa, sonraki kelimenin "istiyorum" olma olasılığı 0.85, "sevmem" olma olasılığı 0.10, "yapıyorum" olma olasılığı 0.05 olabilir.
Model, en yüksek olasılığa sahip olan "istiyorum" kelimesini tahmin eder.
Softmax gibi olasılıksal yöntemler kullanılır.

🔹 Geleneksel sınıflandırmada genellikle sabit özellikler üzerinden sınıflandırma yapılırken, Next Token Prediction'da girdi dinamik olarak değişir.
🔹 Önceki token'lar, sonraki token tahminini etkiler.
🔹 GPT, BERT gibi Transformer tabanlı dil modelleri bu yöntemi kullanarak öğrenir.

## Lojistik Regresyon

Lojistik regresyon, ikili (binary) ya da çok sınıflı (multiclass) sınıflandırma problemlerinde kullanılan istatistiksel bir yöntemdir. 
Regresyon kelimesi geçse de temelde bir sınıflandırma algoritmasıdır.
Bağımlı değişkenin kategorik olduğu durumlarda kullanılan bir istatistiksel modeldir.
2 faktör vardır(Bağımlı değişken yalnızca 2 kategoriye sahiptir.).
Birinin değerini tahmin etmek için bu ilişkiyi kullanır. "Evet/hayır" gibi sınırlı tahmin sonucu vardır.
Tahmin edilen sonucu 0 ve 1 arasında sınırlandırmak için sigmoid fonksiyonunu kullanır.y'yi x'in sigmoid fonksiyonu olarak eşler.

σ(z)=1/(1+e^-z)
σ(z) → Çıktıyı olasılığa dönüştüren sigmoid fonksiyonu
p(eşik değeri)genelde 0.5'tir.Eğer çıktı 0.5’ten büyükse "1", küçükse "0" olarak sınıflandırılır.

örn:Bir e-postanın spam olup olmadığını belirleme (Çıktı: "Spam" veya "Spam değil")

## Kümeleme(Clustering)

Kümeleme, verileri benzerliklerine göre gruplara (kümelere) ayıran bir gözetimsiz öğrenme yöntemidir.

Örnekleri: 
### 1.K-Means Kümeleme:

Küme sayısı (K) baştan belirlenir.
NOT:K'nın max değeri,veri sayısı kadar olabilir.
Veri noktaları, en yakın küme merkezine (centroid) atanır.
Küme merkezleri güncellenerek işlem tekrar edilir.
Örnek kullanım: Müşteri segmentasyonu, anomali tespiti

### 2. Hiyerarşik Kümeleme:

n tane birey,n tane küme olmak üzere işlemlere başlanır.
Verileri birbirine benzer olan küçük gruplara ayırarak zamanla bu grupları birleştirir ve kümeleme yapar.
Veri setindeki benzerlikleri ortaya çıkarır.
Küçük kümeler oluşturulur ve bunlar zamanla daha büyük kümelerle birleştirilir (agglomerative).
Agglomerative(birleştirici) ve divisive(bölücü) yöntemler ile uygulanabilir.
Başlangıçta tüm nesneler birbirinden ayrı.Her bir veriyi ayrı bir küme olarak kabul ediyoruz.Benzer özelliklere sahip kümelere birleştiriyoruz.(Tümevarım)
Ya da büyük bir küme alınır ve bölünerek alt kümelere ayrılır (divisive).
Hiyerarşik kümeleme, verileri gruplandırırken bir ağacın (dendrogram) şeklinde hiyerarşik bir yapı oluşturur.
Başlangıçta her eleman bir küme olsun.Burada mesafe=0'dır.Ardından mesafe=1 olan her eleman bir kümedir.Bu şekilde mesafeyi artıra artıra ilerliyoruz.
Örnek kullanım: Genetik veri analizi, sosyal ağ analizi

### İki kümeleme yönteminin farkları
Kümeleme: Küme sayısı önceden belirlenir ve veriler sabit sayıda kümeye ayrılır.
Hiyerarşik Kümeleme: Küme sayısı başlangıçta belirsizdir ve veriler hiyerarşik bir yapıya göre kümelenir, sonuçta bir ağaç yapısı elde edilir.
Kümeleme problemleri genelde gözetimsiz öğrenme.Sınıflandırma problemleri ise genellikle gözetimli öğrenmedir.

### Kümelemede kategorik veriler bulunabilir mi?

Evet, kümelemede kategorik veriler kullanılabilir, ancak doğrudan Öklid mesafesi gibi sayısal yöntemlerle işlenemezler. 
Bu yüzden kategorik verileri uygun bir şekilde dönüştürmek veya kategorik verilerle çalışabilen özel algoritmalar kullanmak gerekir.

Kategorik verilerle çalışma yöntemleri nelerdir?
1. Kategorik Verileri Sayısal Hale Getirme
Eğer kümelemede K-Means gibi sayısal verilerle çalışan algoritmalar kullanılacaksa, kategorik veriler önce dönüştürülmelidir:

✅ One-Hot Encoding
Her kategori için ayrı bir sütun oluşturur.
Örnek:
Renk: ["Kırmızı", "Mavi", "Yeşil"]
Dönüştürme:
Kırmızı	Mavi	Yeşil
1	    0	      0
0	    1	      0
0	    0	      1

✅ Label Encoding
Her kategoriye bir sayı atanır (örn: Kırmızı → 0, Mavi → 1, Yeşil → 2).

✅ Ortaklık (Frequency) veya Hedef Kodlama (Target Encoding)
Kategorilerin veri içindeki frekansına veya hedef değişkenle ilişkisine göre sayısal değer atanır.
Örnek: Eğer "Araba Markası" özelliğinde Toyota %30, BMW %50, Ford %20 oranında geçiyorsa, bu oranlar kullanılabilir.

NOT:Nümerik veriler sıralanabilir,birbirine bölünebilir vb. Fakat kategorik verilerde bu,mümkün değildir.

### Kümelemede cluster sayısı nasıl belirlenir?

Kümeleme algoritmalarında doğru küme sayısını (K) belirlemek kritik bir adımdır. 
Eğer K çok küçükse kümeler anlamlı olmayabilir, çok büyükse aşırı bölünmüş kümeler oluşabilir.

Dirsek (Elbow) Yöntemi
Küme sayısı arttıkça kümeler içindeki veri noktalarının birbirine olan yakınlığı artar (içsel tutarlılık). Ancak bir noktadan sonra kazanç azalır ve bu nokta optimal K olabilir.
Farklı K değerleri için WCSS (Within-Cluster Sum of Squares) hesaplanır.
WCSS, kümeler içindeki veri noktalarının merkezlerine olan uzaklıklarının karesel toplamıdır.
WCSS değerleri grafiğe dökülür, kırılma (dirsek) noktası optimal K değeridir.

Elbow yönteminin yanı sıra;

- Silhouette Score: Bir veri noktasının kendi kümesine olan yakınlığı ile diğer kümelere olan uzaklığı karşılaştırılır.
Silhouette skoru+1’e yakınsa kümeler iyi ayrılmıştır, 0’a yakınsa kümeler karışmıştır, -1’e yakınsa yanlış kümelenme vardır.
- Gap Statistic yöntemi:Gerçek veri seti ile rastgele dağıtılmış veri setindeki kümeleme skorları karşılaştırılır.
Gerçek verideki kümeleme kalitesi rastgele veriye göre en fazla arttığında optimal K bulunur.
- Dendogram:  Hiyerarşik kümeleme sonucu dendrogram (ağaç yapısı) çizilerek kümeler arası mesafeye göre uygun K seçilir.
Kesişim noktası,optimal küme sayısını verir.


### Kümelemede Standardizasyon Neden ve Nasıl Yapılır?

Standardizasyon, kümeleme algoritmalarının daha iyi performans göstermesi için veri setindeki özellikleri ortak bir ölçeğe getirme işlemidir.
Özellikle K-Means gibi Öklid mesafesi tabanlı algoritmalarda büyük ölçekli değişkenler (örneğin "gelir" gibi büyük sayılar) küçük ölçekli değişkenleri (örneğin "yaş") baskılayabilir. Bu nedenle özelliklerin farklı ölçeklerde olması kümeleme sonuçlarını bozabilir.
Kümeleme tek bir sütuna göre yapılmıyor.Büyük sayılar,kümelemeyi daha çok etkiliyor.
Elemanların,kümeye aidiyet oranları farklıdır.
Seçilen kümelerin yeni merkezi,yer değiştirmeler azalana kadardır.
Z-score standardizasyonu,min-max normalizasyonu,robust scaling gibi yöntemlerle uygulanabilmektedir.
Standardizasyon yaparken sayılarla değil,birimlerle oynuyoruz.
Bilgi geliyor,onu kümeye oturtuyoruz.
Yapılan değişiklikler mutlaka label'da belirtilmelidir.
Bu işlem,mesafeye dayalı algoritmaların (K-Means, DBSCAN) performansını artırır.


### TPU(Tensor Processing Unit) nedir?
Google tarafından özel olarak yapay zeka ve makine öğrenmesi işlemlerini hızlandırmak için geliştirilen
bir donanım birimidir. 
Özellikle TensorFlow kütüphanesiyle uyumlu olacak şekilde optimize edilmiştir.
CPU ve GPU'lara kıyasla daha hızlı ve enerji verimli çalışır.
Google Cloud TPU sayesinde uzaktan erişimle büyük ölçekli modeller eğitilebilir.
GPU'lara kıyasla daha az enerji tüketerek büyük verileri işleyebilir.

Veri setinde sütun sayısını artırmak,özellik sayısını artırmak anlamına gelir.Bu durum,daha iyi sonuç almamızı sağlar ancak işlem yükü artar.
Veri seti oluşturulurken sütun isimleri "en küçük anlamlı isimler" olmalıdır.
Örneğin sütun isimlerinin "Beğeni Sayısı" ve "Yorum Sayısı" olmasındansa "Beğeni" ve "Yorum" şeklinde olması tercih edilmelidir.

### Birine bir kitap verirken kitabı kişiye göre mi vereceğiz yoksa kitaba göre mi?
Burada öneri sistemleri ve birliktelik kuralları öne çıkar.
Öneri sistemleri(recommendation systems):kullanıcı bazlı bakış açısı.
Birliktelik kuralları(association rules):ürün bazlı bakış açısı.

## Decision Trees(Karar Ağaçları)

Veri setindeki özellikleri (features) kullanarak sınıflandırma veya regresyon yapan bir makine öğrenmesi modelidir. Ağaç yapısını kullanarak veriyi dallara ayırır ve her düğümde bir karar verilir.
Kök düğüm (Root Node): En iyi ayıran özellik seçilir.
Dallanma (Branches): Veriye göre dallara ayrılır.
Yaprak düğümler (Leaf Nodes): Son karar noktalarıdır (sınıf etiketi veya tahmin edilen değer).
Karar ağacı modelleri, hem sınıflandırma hem regresyon problemlerinde güçlü bir araçtır.

Senkron programlama:Bir üst satırdaki kod bitmeden bir sonraki kod çalışmaz.Asenkron programlamada ise buna gerek yoktur.

### Ders sürecinde deneyimlediğimiz araçlar:

1. ChatGPT: OpenAI tarafından geliştirilen, doğal dil işleme (NLP) tekniklerini kullanan bir yapay zeka modelidir. 
2. Sider: Yazılım geliştirme süreçlerinde, kodu otomatik olarak analiz eden ve hataları tespit eden bir araç olarak kullanılır. 
3. Claude.ai: Claude, Anthropic adlı bir yapay zeka şirketi tarafından geliştirilmiştir.Doğal dil işleme (NLP) tekniklerini kullanarak metinleri anlamak ve üretmek için tasarlanmış bir yapay zeka modelidir. 
4. Gemini: Google DeepMind tarafından geliştirilen bir yapay zeka modelidir. DeepMind, Google'ın yapay zeka araştırma laboratuvarıdır ve Gemini, DeepMind'ın Gelişmiş Dil Modelleri alanındaki son çalışmalarından biridir.
5. Google AI Studio: Google'ın yapay zeka (YZ) geliştirme ve eğitme platformlarından biridir. Bu platform, kullanıcıların yapay zeka modelleri oluşturmasına, eğitmesine ve dağıtmasına olanak tanır.Kullanıcıların AI çözümleri geliştirmesini daha erişilebilir hale getirmeyi amaçlar. Bu platformun, özellikle veri bilimi, makine öğrenimi ve yapay zeka projelerinde profesyonellere büyük fayda sağladığı söylenebilir.
6. NotebookLM: Google'ın sunduğu yeni bir yapay zeka modelidir ve temelde Jupyter Notebook gibi interaktif ortamları destekleyerek, doğal dil işleme ve kod yazımı gibi alanlarda yardımcı olur. Bu model, özellikle veri bilimcilerinin ve yazılımcıların verileri analiz etmek, kod yazmak ve çeşitli problemleri çözmek için daha verimli bir şekilde çalışmasını amaçlar.
7. Cursor-The AI Code Editor: Yapay zeka ile kullanıcıların daha etkin kod yazmasını sağlar.
8. TensorFlow: Google tarafından geliştirilen ve açık kaynaklı bir yapay zeka kütüphanesidir. Derin öğrenme (deep learning) modelleri geliştirmek için yaygın olarak kullanılır.
9. PyTorch: Facebook tarafından geliştirilen, özellikle derin öğrenme modelleri için yaygın olarak kullanılan açık kaynaklı bir kütüphanedir.
10. Keras:  Derin öğrenme modelleri için yüksek seviyeli bir API'dir ve TensorFlow üzerine inşa edilmiştir. Keras, kullanımı kolay API’leri ile model oluşturmayı hızlandırır.
11. Scikit-learn:  Python'da veri madenciliği ve makine öğrenimi için en popüler kütüphanelerden biridir. İstatistiksel modeller, regresyon, sınıflandırma ve kümeleme gibi görevlerde kullanılır.
12. Pandas: Veri analizi ve manipülasyonu için kullanılan Python kütüphanesidir.
13. Matplotlib ve Seaborn:Python'da veri görselleştirme için kullanılan popüler kütüphanelerdir.
14. Google Colab: Google'ın sunduğu, Python kodlarını bulut üzerinde çalıştırabileceğiniz bir platformdur. GPU ve TPU desteği ile makine öğrenimi ve derin öğrenme modelleri üzerinde çalışmak kolaylaşır.
15. Git ve Github: Git, yazılım projelerindeki dosya değişikliklerini izleyen ve yönetmeye yarayan dağıtık bir sürüm kontrol sistemidir, GitHub ise Git depolarını çevrimiçi olarak barındıran ve işbirliği yapılmasını sağlayan bir platformdur.
16. Hugging Face: Hugging Face, yapay zeka ve doğal dil işleme (NLP) alanında öncü bir platformdur ve kullanıcıların dil modellerini kolayca eğitmesini, paylaşmasını ve kullanmasını sağlar. Özellikle açık kaynaklı Transformers kütüphanesi ile derin öğrenme modellerinin erişilebilirliğini artırır.
17. Project IDX: Google tarafından geliştirilen bir entegre geliştirme ortamı (IDE) platformudur. Bulut tabanlı bu araç, yazılımcılara uygulama geliştirme, test etme ve dağıtım süreçlerini hızlandırmak için yapay zeka ve otomasyon destekli özellikler sunar, böylece kullanıcılar farklı cihazlarda kod yazabilir ve projeleri kolayca yönetebilir.
18. Google Labs:  Google tarafından sunulan bir platformdur ve genellikle yeni ve deneysel ürünlerin, teknolojilerin test edilip geliştirildiği bir ortamdır. Kullanıcılar, burada Google’ın araştırma ve geliştirme aşamasındaki projeleriyle etkileşime girebilir, yenilikçi araçlar ve hizmetlerle deney yapabilir. Google Labs, genellikle beta aşamasındaki ürünleri denemek ve geri bildirim sağlamak isteyen kullanıcılar için sunulur.
19. Streamlit: Python ile hızlı bir şekilde web uygulamaları oluşturmayı sağlayan açık kaynaklı bir framework'tür. Veri bilimcilerinin ve makine öğrenimi mühendislerinin, projelerini görselleştirmek ve paylaşmak için minimum kodla etkileşimli web uygulamaları geliştirmelerine olanak tanır. Kullanıcılar, veri görselleştirmeleri, model sonuçları ve analizleri görsel olarak sunabilirler.
20. Gradio: Python ile hızlı bir şekilde interaktif web arayüzleri oluşturmayı sağlayan bir açık kaynaklı kütüphanedir. Özellikle makine öğrenimi ve yapay zeka modellerini kullanıcı dostu bir şekilde sunmak için kullanılır. Gradio, veri bilimcilerinin ve geliştiricilerinin modellerini hızlıca test etmelerine ve paylaşmalarına olanak tanır.
21. Google Lens: Google tarafından geliştirilen bir görsel arama ve bilgi sağlama uygulamasıdır. Kullanıcılar, Lens ile telefonlarının kameralarını kullanarak objeleri, metinleri, yerleri ve daha fazlasını tanıyabilir ve bu nesneler hakkında bilgi alabilirler.
22. Sora: OpenAI tarafından geliştirilen ve metin, resim veya mevcut videoları kullanarak kısa videolar oluşturmanıza olanak tanıyan yapay zekâ destekli bir video üretim platformudur. Sora, kullanıcıların hayal gücünü gerçeğe dönüştürmek için ileri düzey analiz ve sentez teknolojileri kullanır.

#### "Modeli role sokmak" ne anlama gelir?

Veri biliminde "modeli role sokmak" ifadesi, genellikle eğitilen bir modelin gerçek dünyada kullanılacak şekilde devreye alınması anlamına gelir. 
Bu, modelin eğitim sürecinin tamamlanmasından sonra, gerçek verilerle çalışmaya başlaması veya bir uygulama içinde etkin bir şekilde kullanılmasını ifade eder. 
Bu süreç, modelin "deployment" (dağıtımı) olarak da adlandırılabilir.


## Machine Learning Mesafeleri

Temel olarak Öklid mesafesi (Euclidean distance) kullanılsa da daha farklı ölçümler de mevcuttur. 
Tek boyut için Manhattan
2 boyut için Euclidean(Öklid)
3,4,5 boyuta çıktığında ise Minkowski mesafesi kullanılıyor.

Öklid,yüksekliği yok sayar.Yani 3.boyutu ihmal eder.

## Yapay Sinir Ağları(Artificial Neural Network)

Yapay sinir ağları (YSA), insan beyninin özelliklerinden olan öğrenme yolu ile yeni bilgiler türetebilme, yeni bilgiler oluşturabilme ve keşfedebilme gibi yetenekleri, herhangi bir yardım almadan otomatik olarak gerçekleştirebilmek amacı ile geliştirilen bilgisayar sistemleridir.

Lineer regresyondan yapay sinir ağları oluşuyor.(Derste ilk öğrendiğimiz ve oldukça anlaşılabilir bir konu olan lineer regresyonun,yapay sinir ağları gibi karmaşık bir konunun temelini oluşturması bizi çok şaşırttı.)
nöron=fonksiyon.(ax+b'lerin her biri.b zorunlu değil,doğrudan sapma yoksa b bulunmaz.)
bağlantıların her biri=parametre(ağırlık)
bunların bir araya geldiği hale "ağ" denir.

Bir yapay sinir hücresi beş bölümden oluşmaktadır:

1. Girdiler: Girdiler nöronlara gelen verilerdir. Bu girdilerden gelen veriler biyolojik sinir hücrelerinde olduğu gibi toplanmak üzere nöron çekirdeğine gönderilir.

2. Ağırlıklar: Yapay sinir hücresine gelen bilgiler girdiler üzerinden çekirdeğe ulaşmadan önce geldikleri bağlantıların ağırlığıyla çarpılarak çekirdeğe iletilir. Bu sayede girdilerin üretilecek çıktı üzerindeki etkisi ayarlanabilinmektedir.

3.Toplama Fonksiyonu (Birleştirme Fonksiyonu): Toplama fonksiyonu bir yapay sinir hücresine ağırlıklarla çarpılarak gelen girdileri toplayarak o hücrenin net girdisini hesaplayan bir fonksiyondur

4.Aktivasyon fonksiyonu: Önceki katmandaki tüm girdilerin ağırlıklı toplamını alan ve daha sonra bir çıkış değeri (tipik olarak doğrusal olmayan) üreten ve bir sonraki katmana geçiren bir fonksiyondur. (örneğin, ReLU veya sigmoid ).

y=wx+b
Üst katmandaki her fonksiyon,alt katmandaki her fonksiyondan girdi alır.
Örneğin girdide b'yi düzelttik ama çıktı değişmedi.Bu durumda b'nin hataya etkisi olmadığını gördük.
İlk katmanın girdileri dış dünyadan gelir.(Girdileri biz veririz).Fonksiyonlar ise 2.katmandan itibaren yazılır.
Kimin,fonksiyona ne kadar etkisi olduğunu türevle hesaplıyoruz.

### Backpropagation(Geriye Yayılım)

Bir yapay sinir ağını eğitmek için kullanılan temel bir algoritmadır.
Bu yöntem,ağın çıktısı ile hedeflenen değer arasındaki hatayı minimize etmek için ağırlıkları güncelleme işlemidir.Bu süreçte zincir kuralı uygulanarak hata,geriye doğru yayılır ve ağın her katmanındaki ağırlıkların nasıl güncellenmesi gerektiği hesaplanır.
Çıkan maliyetin,bu maliyete neden olan paydaşlar üzerinden hesaplanmasıdır.

Backpropagation Adımları:
1. İleri Yayılım: Giriş verisi,ağın giriş katmanına verilir.Her nöronda ağırlıklı toplama işlemi yapılır ve aktivasyon fonksiyonu(biz sigmoid fonksiyonu kullandık)uygulanır.Bu işlem,çıkış katmanına kadar devam eder ve tahmin edilen çıktı elde edilir.
Hatırlatma! Sigmoid fonksiyonu,giriş değerini [0,1] aralığına sıkıştırır.

σ(x)=1/(1+e^-x) 
x burada giriş değeri.Çıktı her zaman 0 ve 1 arasında olacak.
σ'(x)=σ(x)*(1-σ(x)) 
Geri yayılım sırasında türevler kolayca hesaplanır.

2. Hata Hesaplama: Tahmin edilen çıktı(Yçıktı) ile gerçek değer(Ygerçek) arasındaki fark hesaplanır.Bu,genellikle bir kayıp fonksiyonu aracılığıyla yapılır.(MSE,Cross Entropy Loss gibi)
3. Hata Geriye Yayılımı: Hata,çıkış katmanından başlayarak giriş katmanına doğru geriye yayılır.Bu süreçte zincir kuralı uygulanarak her katmandaki ağırlıkların gradyanları hesaplanır.
4. Ağırlıkların Güncellenmesi: Hesaplanan gradyanlar kullanılarak ağırlıklar güncellenir.learning rate(öğrenme oranı)kullanılır.
5. Adımların Tekrarlanması: Bu işlemler,kayıp fonksiyonu minimize edilene kadar veya belirlenen bir epoch sayısına ulaşılana kadar tekrarlanır.

NOT: Backpropagation,sinir ağlarını verimli bir şekilde eğitmeye olanak tanır.Birden fazla gizli katmana sahip derin ağlarda kullanılır.
