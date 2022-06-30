# INSERTION SORT
* Patika Profil Linkim : https://app.patika.dev/okkes

[22,27,16,2,18,6]->Insertıon Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
* En küçük sayı bulunur ve ilk baştaki sayı ile yer değiştirir. [2,27,16,22,18,6]->2 ile 22 yer değiştirdi.
* Daha sonra 2.küçük sayı bulunur ve 2.sıraya alınarak yer değiştirme işlemi devam eder.

  ->[2,6,16,22,18,27] 
* 3.sıradaki sayı zaten olması gereken yerde olduğu için yer değiştirme yapmıyoruz.->[2,6,16,22,18,27]
* 18 ile 22 nin yerini değiştiriyoruz.

  ->[2,6,16,18,22,27]
* 5.sıradaki sayı 18 den sonra gelen en küçük sayı olduğundan yer değiştirme yapmıyoruz.

  ->[2,6,16,18,22,27]
* 6.sıradaki sayı en büyük olduğundan sayılarımız küçükten büyüğe sıralanmış oldu.

  ->[2,6,16,18,22,27]

   
2. Big-O gösterimini yazınız.

   O(n²)=O(6²)=O(36)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.  
* Best Case = 2
* Average Case =16,18
* Worst Case = 27

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

   ->Average Case kapsamına girer.

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  
* 1.adım->[2,3,5,8,7,9,4,15,6]
* 2.adım->[2,3,5,8,7,9,4,15,6] (3 sayısı 2 den sonraki en küçük sayı olduğundan yerini değiştirmedik.) 
* 3.adım->[2,3,4,8,7,9,5,15,6]
* 4.adım->[2,3,4,5,7,9,8,15,6] 

