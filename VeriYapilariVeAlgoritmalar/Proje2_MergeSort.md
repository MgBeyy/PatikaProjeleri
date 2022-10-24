[16,21,11,8,12,22] -> Merge Sort

#01 Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    [16,21,11,8,12,22]
    [16,21,11] [8,12,22] 
    [16] [21,11] [8,12] [22]
    [16] [21] [11] [8] [12] [22]
    [16,21] [8,11] [12,22]
    [8,11,16,21] [12,22]
    [8,11,12,16,21,22]

#02 Big-O gösterimini yazınız.

    Her satır için:
    2^x=n
    logn=x
    O(logn)
    .
    Satır sayısı= O(n)
    
    ==> O(n*logn)

