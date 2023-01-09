## Reset de senha WSL

----------

Se você assim como eu acha que vai sempre lembrar senhas fáceis e por isso nunca anota, seja bem vindo a esse texto com o passo a passo de como “resetar” a senha no WSL.

**#1 Não entre em pânico, achando que vai precisar instalar tudo de novo;**

**#2 Abra o cmd/terminal e digite o comando:**

~~~shell
ubuntu config — default-user root
ubuntu
whoami (só pra ter certeza que você está no root)
passwd seuUserAqui (informa o user que você precisa fazer o reset)
~~~

**#2.1 Digita a senha nova.**

**#3 Anote, de preferência em algum gerenciador de senhas!!!**

**#4 Apareceu a mensagem password updated successfully, se sim deu tudo certo e você pode sair do root, usando o comando**

`exit`

**#5 Por ultimo, execute o comando abaixo para retornar ao seu user:**

`ubuntu config — default-user seuUserAqui`

------

![Na imagem to usando meu user okarina, por favor não confunda com um comando
](https://miro.medium.com/max/640/1*5ZwLBpEoVsjFfbPZLTen-g.webp)

Agora é só voltar ao Ubuntu(WSL) e se divertir no sudo -su ;)

Esse texto foi um simplificado desse artigo em inglês: https://winaero.com/reset-password-wsl-linux-distro-windows-10/
