# HS-Gold
ctf gold task

Gold.py oversetter fra binary til keystrokes(filen hexout.txt). Må bare finne connection mellom de to(hvilket keyboard sett er brukt)


gold -
usbmon1 usb
Looks like a Keyboard

https://abawazeeer.medium.com/kaizen-ctf-2018-reverse-engineer-usb-keystrok-from-pcap-file-2412351679f4

((usb.transfer_type == 0x01) && (frame.len == 79)) && !(usb.capdata == 00:00:00:00:00:00:00:00)
values int 0-255 is the values i get from the data.

https://www.utf8-chartable.de/unicode-utf8-table.pl?names=-&utf8=dec&addlinks=1




other tasks from HS:

purple -
VGhlIFBJTiBjb2RlIGlzOiAxODI2
base 64 decoded
The PIN code is: 1826

sølv -
BildeAvSkapet =  "curl http://heltsikker.no/public/skap.jpg --output skap.jpg"
exiftool skap.jpg 
fant i description tag:
~~~The silver PIN code is 5113~~~

