### Linode - Guide til kursister

Denne guide beskriver hvordan man forbinder til de virtuelle
Linux maskiner, som SuperUsers stiller til rådighed for kursister.

Der er to metoder:
1. [En udvidelse til Google Chrome browseren](#metode-1)
2. [Programmet putty](#metode-2)

## Metode 1

1. Installerer en udvidelse til Google Chrome https://chrome.google.com/webstore/detail/secure-shell-app/pnhechapfaindjhompbnflcldabbghjo  
![ssh01.png][ssh01]
2. Angiv det maskinenavn og den bruger, som du har fået udleveret  
![ssh02.png][ssh02]
3. Under punktet ***Identify*** skal du vælge ***Import*** 
![ssh03.png][ssh03]
4. Peg på den fil, som du har fået udleveret
5. Tryk på ***Enter*** for at forbinde
![ssh04.png][ssh04]


## Metode 2

1. Gå ind på siden: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
2. Download og kør 64-bit MSI (‘Windows Installer’) versionen
3. Start putty
4. Skriv det maskinenavn som du har fået udleveret under ***Host Name (or IP address)***  
![putty01.png][putty01]  

5. Under menupunktet ***SSH*** skal du åbne ***Auth***.  
![putty02.png][putty02]

6. Tryk på ***Browse*** knappen og peg på den fil, som du har fået udleveret.  
![putty03.png][putty03]

7. Under menupunktet ***Connection*** skal du åbne ***Data*** og tilføje ***user*** til ***Auto-login username***,  
så slipper du for at angive brugernavnet, når du logger ind.  
![putty04.png][putty04]

8. Skriften er per default ganske lille. Her kan du ændre størrelsen, hvis du ønsker det.  
![putty05.png][putty05]

9. Gå tilbage til *Session* og skriv maskinenavnet under ***Saved Sessions*** og tryk ***Save*** for at gem din opsætning.  
![putty06.png][putty06]

10. Vælg den gemte opsætning og tryk på ***Open*** for at forbinde til din serveren.  
![putty07.png][putty07]

11. Først gang du forbinder vil du få denne ***PuTTY Security Alert***. Bare tryk ***Accept***  
Den vil ikke fremkomme mere.  
![putty08.png][putty08]

12. Du skulle gerne være ind på serveren nu og få dette frem. **Tillykke**  
![putty09.png][putty09]

[putty01]: figures/putty01.png 
[putty02]: figures/putty02.png 
[putty03]: figures/putty03.png 
[putty04]: figures/putty04.png 
[putty05]: figures/putty05.png 
[putty06]: figures/putty06.png 
[putty07]: figures/putty07.png 
[putty08]: figures/putty08.png 
[putty09]: figures/putty09.png 
[ssh01]: figures/secure_shell_app01.png 
[ssh02]: figures/secure_shell_app02.png 
[ssh03]: figures/secure_shell_app03.png 
[ssh04]: figures/secure_shell_app04.png 




