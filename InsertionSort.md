# Patika.dev Insertion Search Projesi
[Patika.dev](https://www.patika.dev/tr)

# Proje
[22,27,16,2,18,6] -> Insertion Sort

*Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
*Big-O gösterimini yazınız.
*Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
*Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Aşamalar

bir key[i] egeri belirlenir burada i adım sayımız olsun.
amacımız dizimizi küçükten büyüğe sıralamak olacaktır.

1. adım: key[1]=27 olur ve sayımızı solunda kalan değerlerimizle kıyaslayarak yer deiştirme yaparız.

         27>22 o halde bir değişiklik yaşanmaz.
         
         [22,27,16,2,18,6]

2. adım: key[2]=16

         16<27
         
         16<22
         
         [16,22,27,2,18,6]
         
3. adım: key[3]=2

         2<27
         
         2<22
         
         2<16
         
        [2,16,22,27,18,6]

4.adım: key[4]=18

        18<27
        
        18<22
        
        18>16
        
        [2,16,18,22,27,6]

5. adım:key[5]=6

        6<27
        
        6<22
        
        6<18
        
        6<16
        
        6>2
        
        [2,6,16,18,22,27] 
        
dizimiz büyükten kücüğee sıralanmış olur. key[6] olamayacağından dizinin sonuna gelindiği anlaşılır. 

## Big-O Gösterimi:

her defasında adım sayısı kadar kıyaslama yaptığından 1+2+3+..+n = n*(n+1)/2  O(n2) olmaktadır. 

## Time Complexity
*  Avarage Case:Aradığımız sayının ortada olması
*  Worst Case:Aradığımız sayının sonda olması
*  Best Case:Aradığımız sayının dizinin en başında olması.

 Dizi sıralandıktan sonra 18 sayısı avarage case kapsamına girmektedir.
 
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


 1. aşama: [3,7,5,8,2,9,4,15,6]
 
 2. aşama: [3,5,7,8,2,9,4,15,6]
 
 3. aşama: [3,5,7,8,2,9,4,15,6]
 
 4. aşama: [2,3,5,7,8,9,4,15,6]
 