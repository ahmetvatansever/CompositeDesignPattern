# Composite Design Pattern


 ![composite](https://github.com/ahmetvatansever/CompositeDesignPattern/assets/24367205/6ffc270c-5a6b-45b2-b20a-1fee505b84cb)

Composite design pattern, bileşik nesne ve parçaları ile istemci arasındaki ilişkiyi karmaşıklıktan uzak bir
şekilde yönetmek amacıyla kullanılır. İstemcinin bileşik nesnedeki tüm parçalar ile tek tek uğraşmasındansa
yalnızca bileşik nesne ile uğraşmasını ve böylece parçalara da ulaşabilmesini hedefler.
Yapısal(Structural) tasarım desenlerinden biridir ve kullanımı ile birlikte istemci rahatlığı açısından önemli
avantajlar elde edilir.

Composite kalıbında öncelikle parçalarla bütünün ortak bir arayüze sahip olması sağlanır. Bu durumda istemci
bileşik nesneyi de parçaları da aynı şekilde kullanır.

Sonrasında bileşik nesne ile bileşik nesne ile parçalar arasındaki ilişki düzenlenir.
Bu amaçla bileşik nesnenin bir torba(collection) arayüze sahip olması sağlanır.

Dolayısıyla istemci, bütün-parça ilişkisinin karmaşıklığından uzak tutulur ve parçalarla uğraşmayıp,
sadece bütün ile iletişimde bulunur.

Sisteme yeni parçalar eklemek kolaydır.

Örnek olarak bir siparişin toplam fiyatının hesaplanacağını varsayalım. Bu durumda bir konteynır içerisindeki
kutuların, her kutu içerisindeki daha küçük kutular ya da bir veya birden fazla
ürüne ait fiyatların ayrı ayrı toplanması gerekir. Kaldıki bu her durumda değişkenlik gösteren bir yapıda olabilir.
(Konteynır içerisinde 3 ya da 5 kutu olması, kutular içerisindeki ürün sayısının değişkenlik gösterebilmesi gibi)

Çözüm olarak konteynır, kutu ya da ürün bizim bir ağaç yapısı şeklinde çalışmamız gerekenler her ne ise ortak bir
arayüz üzerinde çalışarak hepsine aynı şekilde davranabiliriz. Bu nesnenin ne olduğunu(konteynır, kutu, ürün)
bilmemize gerek kalmadan işlem yapmamıza olanak tanır.


