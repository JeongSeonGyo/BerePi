
## LINKS 
  - cygwin
    - https://github.com/digitallamb/apt-cyg


## COMMAND

lsusb

iwconfig

iwlist wlan0 scan
  Cell 01 - Address: 맥주소
    ESSID:"여기를 꼭 기억하세요"
    Protocol:IEEE 802.11bgn
    
wpa_passphrase SSID이름 암호 >> /etc/wpa_supplicant/wpa_supplicant.conf

network={
  ssid="여기에 접속하겠어"
  #psk="원래암호가 그대로 써있다"
  psk=암호화된내용
}

