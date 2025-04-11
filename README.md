# Atividade Avaliativa GitHub

## Alunos:
- Gabriel Moreno
- Gustavo Souza
- Maria Luiza

## Objetivo
Desenvolver uma calculadora de soma, subtração e multiplicação

## Etapas Realizadas por cada membro

### Gustavo Souza
- Criei o repositório usando GitHub
- Criei uma chave SSH e clonei o repositório
- Criei o arquivo algoritmo.por, fiz a estrutura de soma e modifiquei o README

### Gabriel Moreno
- Criei uma chave SSH
- Clonei o repositório após o Gustavo fazer o código base
- Criei a função de subtração na nossa calculadora e adicionei no arquivo base, também atualizei as informações do README

### Maria Luiza
- criei uma chave SSH
- clonei o repositório do gabriel
- criei a conta de multiplicação no portugoul e alterei o README


## Comandos utilizados
### Gustavo:
compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ d
bash: d: command not found

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ ssh-keygen -t rsa -b 4096 -C
ssh-keygen: option requires an argument -- C
usage: ssh-keygen [-q] [-a rounds] [-b bits] [-C comment] [-f output_keyfile]
                  [-m format] [-N new_passphrase] [-O option]
                  [-t dsa | ecdsa | ecdsa-sk | ed25519 | ed25519-sk | rsa]
                  [-w provider] [-Z cipher]
       ssh-keygen -p [-a rounds] [-f keyfile] [-m format] [-N new_passphrase]
                   [-P old_passphrase] [-Z cipher]
       ssh-keygen -i [-f input_keyfile] [-m key_format]
       ssh-keygen -e [-f input_keyfile] [-m key_format]
       ssh-keygen -y [-f input_keyfile]
       ssh-keygen -c [-a rounds] [-C comment] [-f keyfile] [-P passphrase]
       ssh-keygen -l [-v] [-E fingerprint_hash] [-f input_keyfile]
       ssh-keygen -B [-f input_keyfile]
       ssh-keygen -D pkcs11
       ssh-keygen -F hostname [-lv] [-f known_hosts_file]
       ssh-keygen -H [-f known_hosts_file]
       ssh-keygen -K [-a rounds] [-w provider]
       ssh-keygen -R hostname [-f known_hosts_file]
       ssh-keygen -r hostname [-g] [-f input_keyfile]
       ssh-keygen -M generate [-O option] output_file
       ssh-keygen -M screen [-f input_file] [-O option] output_file
       ssh-keygen -I certificate_identity -s ca_key [-hU] [-D pkcs11_provider]
                  [-n principals] [-O option] [-V validity_interval]
                  [-z serial_number] file ...
       ssh-keygen -L [-f input_keyfile]
       ssh-keygen -A [-a rounds] [-f prefix_path]
       ssh-keygen -k -f krl_file [-u] [-s ca_public] [-z version_number]
                  file ...
       ssh-keygen -Q [-l] -f krl_file [file ...]
       ssh-keygen -Y find-principals -s signature_file -f allowed_signers_file
       ssh-keygen -Y check-novalidate -n namespace -s signature_file
       ssh-keygen -Y sign -f key_file -n namespace file ...
       ssh-keygen -Y verify -f allowed_signers_file -I signer_identity
                  -n namespace -s signature_file [-r revocation_file]

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ d
bash: d: command not found

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ ssh-keygen -t rsa -b 4096 -C gustavo.berg.machado@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
/c/Users/compuni/.ssh/id_rsa already exists.
Overwrite (y/n)?

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ y
bash: y: command not found

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ git clone d
fatal: repository 'd' does not exist

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ git clone git@github.com:gustavobergz/super-duper-fiesta.git
Cloning into 'super-duper-fiesta'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ ^C

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ ^C

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ ^C

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ git status
fatal: not a git repository (or any of the parent directories): .git

compuni@Lab6m42 MINGW64 ~/Documents/atividade
$ cd

compuni@Lab6m42 MINGW64 ~
$ pwd
/c/Users/compuni

compuni@Lab6m42 MINGW64 ~
$ cd Documentos
bash: cd: Documentos: No such file or directory

compuni@Lab6m42 MINGW64 ~
$ cd documents

compuni@Lab6m42 MINGW64 ~/documents
$ cd atividade

compuni@Lab6m42 MINGW64 ~/documents/atividade
$ cd super-duper-fiesta

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   algoritmo.por

no changes added to commit (use "git add" and/or "git commit -a")

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git add .
warning: LF will be replaced by CRLF in algoritmo.por.
The file will have its original line endings in your working directory

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git commit
Aborting commit due to empty commit message.

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git push
Everything up-to-date

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git commit
Aborting commit due to empty commit message.

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git commit
[main 9c033dc] modifiquei o readme e adicionei sistema de adição em portugol
 2 files changed, 48 insertions(+), 1 deletion(-)
 rewrite README.md (100%)

compuni@Lab6m42 MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 772 bytes | 386.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:gustavobergz/super-duper-fiesta.git
   59400b2..9c033dc  main -> main

### Gabriel Moreno
Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global user.name
gabrielmoreno

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global user.email
gm21122006@gmail.com

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global --unset user.name

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global --unset user.email

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ ls -al ~/.ssh
total 33
drwxr-xr-x 1 Usuario 197121    0 Mar 28 18:33 ./
drwxr-xr-x 1 Usuario 197121    0 Apr 11 19:16 ../
-rw-r--r-- 1 Usuario 197121 3434 Mar 28 18:15 id_rsa
-rw-r--r-- 1 Usuario 197121  746 Mar 28 18:15 id_rsa.pub
-rw-r--r-- 1 Usuario 197121  828 Mar 28 18:33 known_hosts
-rw-r--r-- 1 Usuario 197121   92 Mar 28 18:33 known_hosts.old

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global user.name gabrielmoreno

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ git config --global user.email gm21122006@gmail.com

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C gm21122006@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Usuario/.ssh/id_rsa):
Enter passphrase for "/c/Users/Usuario/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Usuario/.ssh/id_rsa
Your public key has been saved in /c/Users/Usuario/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:3ra1PruInWeZSmpR1U84wNwkR4Vwyx1HIT8OuNF0wb8 gm21122006@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|           o+X*X*|
|            B=X++|
|           + oo*o|
|          . o o +|
|        S. .   ..|
|       ...     E |
|        ..+ .o   |
|        .* =*.   |
|       .o *==+   |
+----[SHA256]-----+

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1561

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/Usuario/.ssh/id_rsa (gm21122006@gmail.com)

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ ssh -T git@github.com
Hi Gabrielzcoder! You've successfully authenticated, but GitHub does not provide shell access.

Usuario@DESKTOP-2B7IPGR MINGW64 ~
$ cd documents

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents
$ cd atividade

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents/atividade
$ git clone git@github.com:gustavobergz/super-duper-fiesta.git
Cloning into 'super-duper-fiesta'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 10 (delta 0), reused 4 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (10/10), done.

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents/atividade
$ git status
fatal: not a git repository (or any of the parent directories): .git

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents/atividade
$ cd super-duper-fiesta

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents/atividade/super-duper-fiesta (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   algoritmo.por

no changes added to commit (use "git add" and/or "git commit -a")

Usuario@DESKTOP-2B7IPGR MINGW64 ~/documents/atividade/super-duper-fiesta (main)
### Maria Luiza

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ ssh-keygen -t rsa -b 4096 -C marialuizinha.mma@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:jynISC1Cu78pVjIQulmVThWczO85tOxeq36fPxAvras marialuizinha.mma@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|     *oo         |
|.   + =          |
|.o +   .         |
|+ o..   o   .    |
|o=o .  +So   +   |
|o=.= .  *+  o o  |
| .= o ..o.o  +   |
| o. .  ........  |
|. .+.  o+oEo+o.. |
+----[SHA256]-----+

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ eval "$(ssh-agent -s)"
Agent pid 1258

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (marialuizinha.mma@gmail.com)

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ ssh -T git@github.com
Hi maluos! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m43 MINGW64 ~/Documents/atividade
$ git clone git@github.com:gustavobergz/super-duper-fiesta.git
Cloning into 'super-duper-fiesta'...
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 14 (delta 2), reused 6 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (14/14), 5.20 KiB | 532.00 KiB/s, done.
Resolving deltas: 100% (2/2), done.



## Observações
deu problema na chave da maria luiza mas conseguimos arrumar
