# VeriYapilari2

1.SORU
[16,21,11,8,12,22]
Verilen diziyi ikiye ayırıyoruz

[16,21,11] [8,12,22] sonra bunları da aralarında ayırıyoruz.
1.[16,21] [11] [8] 2.[12,22]
sağdaki sayı büyük olmalı (1. ve 2. olarak ayırılan dizilerde sağdaki sayılar büyük.)

16>11 => [11,16,21]  12>8 => [8,12,22]
[11,16,21] [8,12,22]
şimdi bu iki arrayde karşılaştırma yaparız.

21>8 21>12 21<22 ve 16>8 16>12 16<22 ve 11>8 11<12 11<22 => 

[8,11,16,21,22] -> Dizinin son hali


2. SORU

Big O notation : O(nlogn)
