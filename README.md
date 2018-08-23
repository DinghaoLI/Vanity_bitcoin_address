# Vanity_bitcoin_address

## Vanity bitcoin address generator

### Compilation
g++ -std=c++11 -o VanityBitcoin VanityBitcoin.cpp $(pkg-config --cflags libbitcoin --libs libbitcoin)

### Usage
./VanityBitcoin \<whatever you want\>

ex:

```
$ ./VanityBitcoin 1Love
Address: 1LoveCem6mp27jLvK9WhTadydM21UeSHUG
Secret: de3363ae916b0a66155022a50a0c9ee524ec8147f0b5065a8faa60522c294d59
```
