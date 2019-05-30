# ESP32_Bitcoin
A small SHA256 miner with an ESP32

I adapted the code from https://github.com/joric/arduino-bitcoin-miner 

works with Lolin D32 Pro with Lolin TFT 2.4 LCD

Implements icarus protocol v3 with midstate support
Works with bitcoin pools and bitcoin-in-a-box via bfgminer:
bfgminer -o http://localhost:19001 -u admin1 -p 123 -S icarus:\\.\COM5

Makes about 18 Kh/second on one core
