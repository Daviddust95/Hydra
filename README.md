#Pentesting com Hydra - Guia Educacional

Este repositório é criado estritamente para fins educacionais.

## Introdução
<justify>
Neste repositório abordarei mais a respeito do Hydra, que é um software conhecido em segurança da informação e pentest. Não é exatamente uma ferramenta "hacker", mas sim uma ferramenta que pode ser usada por profissionais para testar a segurança de sistemas e redes e analisar suas vulnerabilidades.

Se você se conhece, mas não conhece o inimigo, para cada vitória ganha. sofrerá também uma derrota. - antigo proverbio chinês.
</justify>
  
## Comandos Básicos do Hydra
<justify>
Nos comandos o “username” é o nome do usuário que você deseja atacar e “password_list.txt” é o nome do arquivo de lista de senhas que você deseja usar para o ataque. O “target_ip” é o endereço IP do servidor que você deseja atacar.
</justify>
### Verificação de Hosts Ativos


Força Bruta em FTP:

-  ```bash
    hydra -l username -P password_list.txt ftp://target_ip

Força Bruta em HTTP:
- ```bash
    hydra -L user_list.txt -P password_list.txt http://target_ip

Força Bruta em POP3:
- ```bash
    hydra -l username -P password_list.txt pop3://target_ip

Força Bruta em SMB:
- ```bash
    hydra -l username -P password_list.txt smb://target_ip

Força Bruta em Telnet:
- ```bash
   hydra -l username -P password_list.txt telnet://target_ip

Força Bruta em SMTP:
- ```bash
   hydra -l username -P password_list.txt smtp://target_ip

## Aviso
<justify>
Este repositório é apenas para fins educacionais. Não promovemos atividades ilegais ou antiéticas. Certifique-se de obedecer às leis locais e diretrizes éticas ao usar o Hydra e outras ferramentas de segurança.
Lembre-se de usar esses comandos de maneira responsável e ética. A segurança cibernética é um campo sério e deve ser usada para fins legítimos, como testar a segurança de seus próprios sistemas ou com permissão legal.
Sinta-se à vontade para explorar os comandos acima e aprofundar seu conhecimento em testes de penetração com o Hydra. Lembre-se de usá-los de maneira responsável e respeitando a privacidade e a segurança de terceiros.
<justify>

## Contato
Se você tiver alguma dúvida, comentário ou feedback, sinta-se à vontade para entrar em contato:

- **Email:** alissondaviddev@gmail.com
- **LinkedIn:** [alisson-melo95](https://www.linkedin.com/in/alisson-melo95/) 
- **Site Pessoal:** [Portifólio](https://alissondev.tech)
- **GitHub:** [@Daviddust95](https://github.com/Daviddust95)
