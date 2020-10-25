cat

curl

curl -o myBike.txt https://www.specialized.com/us/en/mens-diverge-e5-sport/p/133799?color=&searchText=95418-7148

cat myBike.txt | grep data-price= | head -n 1 | cut -c53-56

history

