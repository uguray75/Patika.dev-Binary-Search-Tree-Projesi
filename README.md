# Patika.dev-Binary-Search-Tree-Projesi
Patika.dev 'in "Veri Yapıları ve Algoritmalar" dersinin "Binary-Search-Tree-Projesi" ödevidir.

# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  dizisinin Binary-Search-Tree aşamaları

1. aşama] Kökümüzü(root) 7 olarak belirledik
2. aşama] 5 sayısı 7'den küçük olduğu için sol tarafa aldık.
                            
                            7
                           / 
                          5 
3. aşama] 1 sayısı 7ve 5'den küçük olduğu için sola yazdık.
    
                             7
                           / 
                          5 
                        /
                       1
                       
4. aşama] 8 sayısı 7'den büyük olduğu için sağ tarafa yazdık.
                             7
                           /   \
                          5      8
                        /
                      1 
                      
                      
                      
5. aşama] 3 sayısı 7 ve 5'den küçük olduğu için sollarına 1'den büyük olduğu için sağına yazılır.  

                             7
                           /   \
                          5      8
                        /
                       1
                        \
                          3
                          
                          
 6. aşama] 6 sayısı 7'den küçük olduğu için soluna. 5'den büyük olduğu için sağına yazılır.  


                             7
                           /   \
                          5      8
                        /   \
                       1     6
                        \
                          3
                      
                      
                      
7. aşama] 0 sayısı 7,5ve 1'den küçük olduğundan sollarına yazılır.

                             7
                           /   \
                          5      8
                        /   \
                       1     6
                      / \
                     0    3  
                     
                     
                     
8. aşama] 9 sayısı 7 ve 8'den büyük olduğu için sağlarına yazılır.

                    
                             7
                           /   \
                          5      8
                        /   \      \
                       1     6      9
                      / \
                     0    3  
                     
                     
                     
                     
                     
9. aşama] 4 sayısı 7 ve 5'den küçük olduğu için sollarına. 1 ve 3'den büyük olduğu için sağlarına yazılır.



                     
                             7
                           /   \
                          5      8
                        /   \      \
                       1     6      9
                      / \
                     0    3 
                           \
                             4
                             
                             
                             
                             
                             
10. aşama] 2 sayısı 7 ve 5'den küçük olduğu için sollarına. 1'den büyük olduğu için sağına. 3'den küçük olduğu için soluna yazılır.   


                             7
                           /   \
                          5      8
                        /   \      \
                       1     6      9
                      / \
                     0    3 
                          /\
                         2   4
                             

                     
                     
                     
                     
                                            
