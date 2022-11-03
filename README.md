# Kodluyoruz-Binary-Search-Tree-Projesi
Kodluyoruz Binary Search Tree Proje Ödevi

## Proje 3  
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.  

## Cevap    

1-) İlk olarak 7 rakamından başlayıp, bunun Kök Boğum (Root Node) olduğunu düşünerek en başa yerleştirelim. Ardınan ikinci rakama geçelim. İkinci rakam, ilk rakam olan 7' ye bağlı olmak durumda. Bir başka deyişle onun alt boğumu/çocuk boğumu(Child Node) olacak. 5, 7' den küçük bir rakam. Bu sebepten onu sol alt tarafa alalım.

                                             7
                                            /
                                           5   
2-) 3 ncü rakamımız ise 1. Root Node ile karşılaştırdığımızda ondan küçük olduğunu görüyoruz. Bu yüzden onu 7nin sol alt node' u olacak şekilde grafiğimize yerleştirelim.  

                                             7
                                            /
                                           5
                                          /
                                         1    
## NOT
"Bir node değeri eğer bağlı olduğu node' un içindeki değerden küçükse onun solunda, değilse sağında yer alıyor olmalı."  

3-) 4 ncü rakamdan devam edelim. 8, root node olan 7den büyük. Dolayısıyla sağ dalda yer almalı.  

                                        7
                                       /  \
                                      5    8
                                     /
                                    1  
                                    
4-) 5nci rakamımız ise 3. Yine Root Node' dan aşağıya doğru inmeye başlıyoruz. Kuralımıza göre 3, 7den küçük ve onun sol dalında yer almalı. Bir alt seviyeye indiğimizde 5 ile karşılaşılıyor. 3, 5 ten küçük olduğu için kuralımıza göre sol alt node olmalı ama yol devam ediyor. Çünkü sol alt node' da 1 var. 3, 1den büyük olduğu için kuralımıza göre sağ alt node' olmalı.

                                        7
                                       / \
                                      5   8
                                     /
                                    1
                                     \
                                      3
                                      
5-) 6 ncı rakamımız 6. 6, root node olan 7den küçük olduğu için kuralımıza göre sol dalda yer almalı. Sol daldan aşağıya doğru indiğimizde 1nci seviyede 5 olduğunu görüyoruz. 6, 5 dan büyük olduğu için sağ alt node' unda yer almalı.

                                       7
                                      / \
                                     5   8
                                    / \
                                   1   6
                                    \
                                     3
                                     
6-) 7 nci rakamımız 0. Yine Root Node ile kıyaslayarak başladığımızda kuralımıza göre sol dalda olması gerekiyor. 0, 5 dan küçük olduğu için sol daldan inmeye devam ediyor ve yine 1 dan küçük olduğu için sol alt node olarak 4 ncü seviyedeki yerini alıyor.
                    
                                       7
                                      / \
                                     5   8
                                    / \
                                   1   6
                                  / \
                                 0   3
                                 
7-) 8 nci elemanımız ise 9. Root node olan 7den büyük olduğu için sağ daldan aşağıya doğru akması gerekiyor. Yol üstünde ilk olarak karşılaştığı 8 dan büyük olduğu içinse sağ alt node olarak 2nci seviyedeki yerini alıyor.

                                       7
                                      / \
                                     5   8
                                    / \   \
                                   1   6   9
                                  / \
                                 0   3
                                 
8-) 9ncu elemanımız 4. Root Node olan 7den küçük olduğu için kuralımıza göre sol daldan aşağıya doğru kaydırılması gerekiyor. 1nci seviyede karşılaştığımız 5 ten küçük bir değer olduğu içinse sol alt node olarak 2nci seviyedeki 1 i görüyor. 4 1 den büyük olduğu için onun sağ tarafına yazılması gerekiyor. Ama 3. seviyede 3 var ve 4 3 den büyük. O yüzden 3 ün sağ tarafına 4 ü yerleştireceğiz.
      
                                       7
                                      / \
                                     5   8
                                    / \   \
                                   1   6   9
                                  / \
                                 0   3
                                      \
                                       4
                                       
9-) Son olarak 10. elemanımız 2. 2 root olan elemanımız 7 den küçük olduğu için sol tarafa yazılacak. Sol tarafta 1. seviyede 5 var ve 2 5 den küçük olduğu için onun sol tarafına yazılacak. Ama yine 2.seviyeye indiğimizde orda 1 in olduğunu görüyoruz ve 2 1 den büyük olduğu için onun sağ tarafına yazılacak. 3. Seviyede ise 3 ü görüyoruz. 2 3 den küçük olduğu için 3 ün sol tarafına yazılacak.

                                        7
                                      / \
                                     5   8
                                    / \   \
                                   1   6   9
                                  / \
                                 0   3
                                    / \
                                   2    4
                                 
                                          



                              
                                   
                                    
                                         
                                        
                                                                   
                                   
                                   
                                   
                                   
                            
                            
                            
                            
                            
                            
                            
                            
                            
                                   
                                   
                                   
