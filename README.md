# Project_Cisco_BKP_Cron
Automatización de Backups - Utilizando Python / Docker GNS3 NetworkAutomation / Crontab

#Entornos:
En mi caso lo replique con GNS3 2.2.8 //
Ubicar container ubuntu for GNS3: https://www.gns3.com/marketplace/appliance/network-automation //
CiscoIOSv

#Pasos:
1.- Generar carpetas que detallen backups diarios/mensuales/anuales.//
2.- Cada carpeta generada debe contener los archivos (script.py / Lanzador.sh / Archivo host)//
3.- Ahora mediante la herramienta Cron, llamaremos cada lanzador dentro de cada carpeta para programar su ejecucion segun se desee.
(tener en cuenta la ruta del lanzador que debe ser editada segun sea el script; es decir, diario/mensual/anual)



