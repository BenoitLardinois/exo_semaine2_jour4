### exo_semaine2_jour4

-In the folder exo_ruby_jour5/lib

## A) 00_journalists.rb
We have an array with handles from Twitter and we will treat them.
1) With the method '.length' we know the numbers of handles in this array.
2) With the method '.min_bt' + (&:length), we know who is the shortest handle in this array.
3) With the method '.count' (we know the numbers of handles in this array) we stock the result in a variable 'item' and with the method '.length' we know how many handles contains 5 characters.
4) We create a variable(capital_letters) which takes value ("A".."Z"). With the method '.count' we stock the result in a variable 'x' and with capital_letters + the method '.include?(x[1])we know how many begin with a capital letter.
5) With the method '.sort_by' + (&:downcase) we sort the handle list alphabetically.
6) With the method '.sort_by' + (&:length) we sort the handle by size.
7) With the method '.index' + ('@epenser') we know exactly where the handle '@epenser' is.
8) Actually too difficult for me.

## B) 01_cryptocurrencies.rb
We have two arrays one with currencies and the second with values. This is cryptocurrencies.
1) We must associate currencies with values with the method 'map, to_f and to_h'.
2) The most valuable crypto with the method 'max_by'.
3) The crypto with the lowest value with the method 'min_by'.
4) The currencies priced below 6000 with the method 'filter'.
5) The most expensive currency among those priced below 6000 with the method 'filter and max_by'.


