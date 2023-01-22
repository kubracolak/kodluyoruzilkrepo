# Veri Yapıları ve Algoritmalar
1. [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.

Insertion Sort:

Insertion Sort ile sıralama işlemi, dizideki her bir elemanın kendinden önceki tüm elemanlar arasında yerini alması ile gerçekleşir. Aşağıda verilen dizinin sıralanması için adım adım aşamaları:

    22 ile başlayalım, 22 zaten sıralı olduğu için ilk eleman olarak kalır
    27 eklenir, 27 > 22 olduğu için 27 yerine 22 yerleştirilir
    16 eklenir, 16 < 27 olduğu için ilk eleman olarak kalır
    2 eklenir, 2 < 16 olduğu için ilk eleman olarak kalır
    18 eklenir, 18 > 2 < 16 olduğu için 2 ile yer değiştirilir
    6 eklenir, 6 < 18 < 16 < 27 < 22 olduğu için 6 ile yer değiştirilir

Sıralanmış dizi: [2,6,16,18,27,22]

Big-O Notation:
Insertion Sort'da en kötü durumda O(n^2) zaman alır. En iyi durumda ise dizi zaten sıralı olduğunda O(n) zaman alır.

Time Complexity:

    Average case: Aradığımız sayının ortada olması: O(n^2)
    Worst case: Aradığımız sayının sonda olması: O(n^2)
    Best case: Aradığımız sayının dizinin en başında olması: O(n)

Insertion Sort, dizinin içinde aradığımız sayının nerede olduğuna bağlı olarak farklı zaman karmaşıklıklarına sahip olabilir. En iyi durumda dizinin en başında olan bir sayı arandığında, O(n) zaman alır. Ancak ortalama ve en kötü durumda, dizinin ortasında veya sondasında olan bir sayı arandığında, O(n^2) zaman alır. Bu yüzden, Insertion Sort genellikle küçük boyutlu diziler için kullanılır.

2. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Selection Sort:

Selection Sort ile sıralama işlemi, dizideki en küçük elemanı bulup, dizinin en başına getirerek gerçekleşir. Aşağıda verilen dizinin sıralanması için adım adım aşamaları:

    [7,3,5,8,2,9,4,15,6] dizisinde en küçük eleman 2 olduğu için 2 ile dizinin başındaki 7 yer değiştirilir. [2,3,5,8,7,9,4,15,6]
    [2,3,5,8,7,9,4,15,6] dizisinde en küçük eleman 3 olduğu için 3 ile dizinin ikinci elemanı yer değiştirilir. [2,3,5,8,7,9,4,15,6]
    [2,3,5,8,7,9,4,15,6] dizisinde en küçük eleman 4 olduğu için 4 ile dizinin üçüncü elemanı yer değiştirilir. [2,3,4,8,7,9,5,15,6]
    [2,3,4,8,7,9,5,15,6] dizisinde en küçük eleman 5 olduğu için 5 ile dizinin dördüncü elemanı yer değiştirilir. [2,3,4,5,7,9,8,15,6]

Selection Sort ile bu şekilde dizideki en küçük elemanı aratarak, dizinin en başına getirerek devam eder ve dizi sıralanır.