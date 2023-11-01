# Pentesting com Hydra - Guia Educacional

Este repositório é criado estritamente para fins educacionais.

## Introdução
<justify>
Neste repositório abordarei mais a respeito do Hydra, que é um software conhecido em segurança da informação e pentest. Não é exatamente uma ferramenta "hacker", mas sim uma ferramenta que pode ser usada por profissionais para testar a segurança de sistemas e redes e analisar suas vulnerabilidades.

**Se você se conhece, mas não conhece o inimigo, para cada vitória ganha. sofrerá também uma derrota. - Antigo proverbio chinês.**
</justify>

 ##  1. instalação do Hydra
**Verifique se o Hydra já está instalado: Alguns sistemas Linux, como o Kali Linux, já possuem o Hydra pré-instalado. Você pode verificar se ele está instalado digitando o seguinte comando no terminal:**
-  ```bash
    hydra --version
Se o Hydra estiver instalado, ele mostrará a versão. Se não estiver instalado, siga as etapas abaixo para instalar.

## 2. Instale as dependências: O Hydra requer algumas bibliotecas e pacotes para funcionar corretamente. Para instalá-las, você pode usar o gerenciador de pacotes do seu sistema. Abaixo estão os comandos para instalar as dependências em sistemas populares:

1. ### Para sistemas baseados no Debian (como o Ubuntu):
-  ```bash
    sudo apt update
-  ```bash
    sudo apt install libssl-dev libssh-dev libidn11-dev libpcre3-dev libgtk2.0-dev libmysqlclient-dev libpq-dev libsvn-dev libncp-dev
  
2. ### Para sistemas baseados no Red Hat (como o CentOS e o Fedora):
-  ```bash
    sudo yum install openssl-devel libssh-devel libidn-devel pcre-devel gtk2-devel mysql-devel postgresql-devel subversion-devel libncp-devel

## 3 Baixe e compile o Hydra:

### 3.1. Vá para o site oficial do Hydra (https://github.com/vanhauser-thc/thc-hydra) para obter o código-fonte mais recente. Você pode clonar o repositório usando o Git:
-  ```bash
    git clone https://github.com/vanhauser-thc/thc-hydra.git
### 3.2. Navegue até o diretório do Hydra:
-  ```bash
    cd thc-hydra
### 3.3. Compile o Hydra:
-  ```bash
    ./configure
     make
    sudo make install
**Verifique a instalação:**
Após a instalação, você pode verificar se o Hydra está funcionando corretamente executando o comando:
-  ```bash
    hydra --version
## 4. Comandos Básicos do Hydra
<justify>
Nos comandos o “username” é o nome do usuário que você deseja atacar e “password_list.txt” é o nome do arquivo de lista de senhas que você deseja usar para o ataque. O “target_ip” é o endereço IP do servidor que você deseja atacar.
</justify>

4.1 Força Bruta em FTP:
-  ```bash
    hydra -l username -P password_list.txt ftp://target_ip
4.2 Força Bruta em HTTP:
- ```bash
    hydra -L user_list.txt -P password_list.txt http://target_ip
4.3 Força Bruta em POP3:
- ```bash
    hydra -l username -P password_list.txt pop3://target_ip
4.4 Força Bruta em SMB:
- ```bash
    hydra -l username -P password_list.txt smb://target_ip
4.5 Força Bruta em Telnet:
- ```bash
   hydra -l username -P password_list.txt telnet://target_ip
4.6 Força Bruta em SMTP:
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
