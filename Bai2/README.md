Copy các câu lệnh này để test bai 2

Các test từ 8 den 11 la tu nghi ra de test cac yeu cau moi

Test so 7 se ra khac so voi result7.txt do da xu ly them string

#! /bin/bash

./scanner ../test/example1.kpl | diff ../test/result1.txt -

./scanner ../test/example2.kpl | diff ../test/result2.txt -

./scanner ../test/example3.kpl | diff ../test/result3.txt -

./scanner ../test/example4.kpl | diff ../test/result4.txt -

./scanner ../test/example5.kpl | diff ../test/result5.txt -

./scanner ../test/example6.kpl | diff ../test/result6.txt -

./scanner ../test/example7.kpl | diff ../test/result7.txt -

./scanner ../test/example8.kpl 

./scanner ../test/example9.kpl 

./scanner ../test/example10.kpl 

./scanner ../test/example11.kpl 