[22,27,16,2,18,6] -> Insertion Sort

#01 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.   

        [22,27,16,2,18,6] Başla
        [2,27,16,22,18,6] En küçük eleman 2'dir. 1.Sıraya taşındı.
        [2,6,16,22,18,27] Geri kalanların içinde en küçük eleman 6'dır. 2.Sıraya taşındı. 
        [2,6,16,22,18,27] Sıradaki eleman 16'dır. Doğru sıradadır. İşlem yapılmadı.
        [2,6,16,18,22,27] Sıradaki eleman 18'dir. 4.Sıraya taşındı. 
        [2,6,16,18,22,27] Sıradaki eleman 22'dir. Doğru sıradadır. İşlem yapılmadı.
        [2,6,16,18,22,27] Son.



#02 Big-O gösterimini yazınız.

    n+(n-1)+(n-2)+...=
    n*(n+1)/2= (n^2+n)/2
    O(n^2)



#03 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

    Dizinin sıralanmış hali: [2,6,16,18,22,27]
    18 sayısı ortada kaldığı için ne en kötü ne de en iyi ihtimaldir. 
    -> Average case



#04 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    [7,3,5,8,2,9,4,15,6] Başla
    [2,3,5,8,7,9,4,15,6] En küçük eleman 2'dir. 1.Sıraya taşındı.
    [2,3,5,8,7,9,4,15,6] Sıradaki eleman 3'tür. Doğru sıradadır. İşlem yapılmadı.
    [2,3,4,8,7,9,5,15,6] Sıradaki eleman 4'tür. 3.Sıraya taşındı.
    [2,3,4,5,7,9,8,15,6] Sıradaki eleman 5'tir. 4.Sıraya taşındı.
