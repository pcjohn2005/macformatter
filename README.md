# macformatter
Linux cli PHP-script to format MAC-addresses
Can be called with only MAC-address as argument or with extra second "dhcp" argument to format the MAC-address as the way MS-DHCP wants it to be.
If called with no arguments it displays some basic instructions how to use the script
The script also looks up the vendor of the MAC-address using the api at macvendors.com
Requires php-cli php-curl
