# Kodluyoruz-Binary-Search-Tree-Projesi
Kodluyoruz Binary Search Tree Proje Ödevi

## Proje 3  
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.  

## Cevap    

-İlk olarak 7 rakamından başlayıp, bunun Kök Boğum (Root Node) olduğunu düşünerek en başa yerleştirelim.   
-Ardınan ikinci rakama geçelim.  
-İkinci rakam, ilk rakam olan 7' ye bağlı olmak durumda. Bir başka deyişle onun alt boğumu/çocuk boğumu(Child Node) olacak.   
-5, 7' den küçük bir rakam. Bu sebepten onu sol alt tarafa alalım.

                                             7
                                            /
                                           5   
-3 ncü rakamımız ise 1. Root Node ile karşılaştırdığımızda ondan küçük olduğunu görüyoruz. Bu yüzden onu 7nin sol alt node' u olacak şekilde grafiğimize yerleştirelim.  

                                             7
                                            /
                                           5
                                          /
                                         1    
## NOT
"Bir node değeri eğer bağlı olduğu node' un içindeki değerden küçükse onun solunda, değilse sağında yer alıyor olmalı."  

4ncü rakamdan devam edelim.1, root node olan 7den küçük. Dolayısıyla sol dalda yer almalı. Ancak sol dalda 4 değeri de var. 1, 4ten küçük olduğundan ve az önce bahsettiğimiz kuraldan dolayı sol alt node olarak grafiğe eklenmeli.
                                         
                                        
                                           

                                           
                                        
