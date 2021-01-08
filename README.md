### Linode - Guide til kursister

Denne guide beskriver hvordan man forbinder til de virtuelle
Linux maskiner, som SuperUsers stiller til rådighed for kursister.

Der er to metoder:
1. [En udvidelse til Google Chrome browseren](#metode-1)
2. [Programmet putty](#metode-2)

## Metode 1

1. Installerer en udvidelse til Google Chrome https://chrome.google.com/webstore/detail/secure-shell-app/pnhechapfaindjhompbnflcldabbghjo  
![ssh01.png][ssh01]


## Metode 2

1. Download og installere putty fra: https://putty.org/
2. Start putty
3. Skriv det maskinenavn som du har fået udleveret under ***Host Name (or IP address)***  
![putty01.png][putty01]  

4. Under menupunktet ***SSH*** skal du åbne ***Auth***.  
![putty02.png][putty02]

5. Tryk på ***Browse*** knappen og peg på den fil, som du har fået udleveret.  
![putty03.png][putty03]

6. Under menupunktet ***Connection*** skal du åbne ***Data*** og tilføje ***user*** til ***Auto-login username***,  
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




