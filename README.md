### PatikaDev Data Structures and Algorithms
 https://app.patika.dev/

#Merge Sort Projesi

##[16,21,11,8,12,22] -> Merge Sort

###Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

|------------------------------------------------------                                                                              |

|diziyi ikiye bölüp parçalayarak ilerleyeceğiz                                                      |  |  |  |  |  |  |  |  |  |  |  |

|                                                                                                   |  |  |  |16|21|11|8 |12|22|  |  |

|her defasında parçalara ayırırız tek parça olana dek                                               |  |  |  |  |  |  |  |  |  |  |  |

|                                                                                                   |  |  |16|21|11|  |8 |12|22|  |  |

|                                                                                                   |  |16|21|  |11|  |8 |  |12|22|  |

|                                                                                                   |16|  |21|  |11|  |8 |  |12|  |22| 

|tamamen parçalara ayırılmış durumda şimdi sıralı hale gelene kadar birleştirme işlemini yapacağız  |16|21|  |11|  |  |8 |  |12|22|  |

|                                                                                                   |  |  |11|16|21|  |8 |12|22|  |  |  

|                                                                                                   |  |  |8 |11|12|16|21|22|  |  |  |        



##Big-O gösterimini yazınız.

* Merge Sort algoritması başlangıçta n kez bölme yaparak logaritmik bir zaman ortaya çıkarırken  n  kez birleştirme yaparak da karşımıza O(nlogn) zamanda bir karmaşıklık çıkarır.
* Bizim n adımımız burada 6 oldugundan karmaşıklığımız O(6log6) olur.


