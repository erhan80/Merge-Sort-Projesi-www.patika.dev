# Merge-Sort-Projesi-www.patika.dev
Proje 2 [16,21,11,8,12,22] -> Merge Sort


                                                      (16,21,11,8,12,22) 
                                                        
                                            (16,21,11)                  (8,12,22)
                                          
                                          (16)   (21,11)              (8)   (12,22)
                                          
                                        (16)   (21)   (11)          (8)   (12)   (22)
                                        
                                          (16)   (11,21)              (8)   (12,22)
                                    
                                            (11,16,21)                   (8,12,22)
                                            
                                                       (8,11,12,16,21,22)
                                                       
                                                     
Big-O gösterimini yazınız.

n= dizi sayısı ise n= 6 olur. n/2 , n/4 , n/6 ... şeklinde 2 üzeri 6 şeklinde bölünerek gideceği için Big-O = (n.logn) olacaktır. yani (6.log6) 
