# **Insertion-Sort**



## *[22,27,16,2,18,6] -> Insertion Sort*



###   *1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.* 

~~~
1- [22,27,16,2,18,6]  
2- [2,27,16,22,18,6]  
3- [2,6,16,22,18,27]  
4- [2,6,16,22,18,27]  
5- [2,6,16,18,22,27]
~~~  

### *2.Big-O gösterimini yazınız.*

~~~
n + (n-1) + ... + 1 
= (n * (n - 1)) / 2
= (n^2 - n) => Big-O 
= O(n^2)
~~~

### *3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*

~~~
Average case : O(n^2)
Worst case : O(n^2)
Best case : O(n)
~~~

### *4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.* 

~~~
Dizi sıralandığında 18 dizinin ortalarında olacağından Avarege case kapsamına girer.
~~~

***

## ***[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.***


1- [**2**,3,5,8,**7**,9,4,15,6]  
2- [2,3,**4**,8,7,9,**5**,15,6]  
3- [2,3,4,**5**,7,9,**8**,15,6]  
4- [2,3,4,5,**6**,9,8,15,**7**]
***

