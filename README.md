# mikrotik

ip firewall rule virus add dst-address=:4444 protocol=udp action=drop comment="Worm"
ip firewall rule virus add dst-address=:5554 protocol=tcp action=drop comment="Drop Sasser"
ip firewall rule virus add dst-address=:8866 protocol=tcp action=drop comment="Drop Beagle.B"
ip firewall rule virus add dst-address=:10000 protocol=tcp action=drop comment="Drop Dumaru.Y"
ip firewall rule virus add dst-address=:10080 protocol=tcp action=drop comment="Drop MyDoom.B"
ip firewall rule virus add dst-address=:12345 protocol=tcp action=drop comment="Drop NetBus"
ip firewall rule virus add dst-address=:17300 protocol=tcp action=drop comment="Drop Kuang2"
ip firewall rule virus add dst-address=:27374 protocol=tcp action=drop comment="Drop SubSeven"

