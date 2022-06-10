# Algorithm-Project1
## https://patika.dev Eğitim Patikası- Veri Yapıları ve Algoritmalar  - Insertion Sort-Proje1

## Proje-1
- 1) [22, 27, 16, 2, 18, 6] Dizisinin Insertion Sort Algoritmasına Göre Aşamaları;
- [**2**, 27,16,**22**,18,6]
- [2, **6** , 16, 22, 18, **27**]
- [2, 6 , **16**, 22, 18, 27] <!-- 16 dan küçük array bulunamadı yerinde kalır.-->
- [2, 6, 16, **18**, **22**, 27]
- [2, 6, 16, 18, 22, 27] Array Insertion Sort a göre sıralandı.
- 2) Big O gösterimi: n! = n*(n+1)/2)=(n^2+n)/2 => **O(n^2)**
- 3) Time Comletixy Durumları:
- Average Case: O(n^2)
- Worst Case: O(n^2)
- Best Case : O(n)
- 18 sayısı array sıralandıktan sonra **Average Case** senaryosuna uygun olur. Sebebi 18 sayısının dizinin orta kısmına denk gelmesidir.
- 5) [ 7,3,5,8,2,9,4,15,6 ] dizisinin Insertion Sort'a göre ilk 4 adımı ;
- [**2** ,3,5,8,**7**,9,4,15,6]
- [ 2,**3**,5,8,7,9,4,15,6]
- [2,3,**4**,8,7,9,**5**,15,6 ]
- [2,3,**4**,**5**,7,9,**8**,15,6 ]