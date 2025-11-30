# Teste-em-ambiente-controlado
Esse é o resultado de um teste com kali linux em um ambiente controlado, usando o metaspoitable um sistema propositalmente inseguro para testar comandos de pentest.

Primeiramente utilizamos a o comando de conexão com o servidor simulado, estabelecendo assim a comunicação com o servidor alvo.
utilizando o nmap, para mapear o servidor e assim encontrar alguma porta aberta.

apos o resultado do nmap, podemos ver na imagem 1, que encontramos a seguintes portas abertas.

apos criamos duas wordlist conforme imagem 2 e 3, assim para tentar descobrir o usuario e senha, para usar o FTP do servidor teste.

depois de ter criado as wordlists, executei o primeiro ataque com a ferramenta medusa usando o modulo FTP, conforme imagem 4.
foi encotrado um usuario e uma senha.
assim conforme a imagem 5, consegui acesso ao ftp

acessando o painel do roteador do IP.

usando a ferramenta citada acima, para descobrir a credencial de acesso conforme imagem 6, usando as mesmas wordlist do FTP.
obtive sucesso conforme imagem 7, sendo possivel acessar o painel gerenciador do servidor.

