# esp_nacl
NaCl crypto lib for the ESP8266

Starting point for user crypto on the ESP8266. Uses the minimal TweetNaCl implementation from https://tweetnacl.cr.yp.to/ and ports it to the esp-open-sdk environment. Adds a "randombytes()" implementation and the ICACHE_FLASH_ATTR attributes.

For documentation of the API see: https://nacl.cr.yp.to/

## Usage
Simply drop the two files into your project and use the API functions.
