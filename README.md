# Beräkning elbesparing
Ett "package" för home assistant som beräknar besaring av kostnadsoptimeringar baserad på kvartspriser

*Förutsättningar*
* Du behöver mätning på din elimport
* https://www.home-assistant.io/integrations/nordpool/

# Dokumentation

Du kan läsa om bakgrund, beräkingar mm på https://ontour.ollivergarden.se ( snart )

Home Assistant kan konfigureras på 3 oliika sätt, dessa kan även kombineras.
Denna fil avser hantering via paket. Om du inte jobbat med det tidigare kan du läsa om 
vad som krävs på denna sida https://ontour.ollivergarden.se ( snart )

# Dashboard
Det finns med kod för en exempeldashboard. 
Tanken är att du i Home Assistant går till inställningar/System/Kontrollpaneler och skapar en ny
Gå till redigera kontrollpanel via pennan upp till höger
I redigeringsläge får du tre prickar uppe till höger klicka där och välj "Redigera i YAML"
Markera allt och klistra in koden härifrån
**OBS gör inte detta i din vanliga dashboard**

Sen kan du kopiera de element du är intresserade av till din ordinarie dashboard
