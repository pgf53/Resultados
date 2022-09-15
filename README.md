# tfm-detecciones

Repositorio con los resultados de procesar los Datasets presentes en: http://ait08.us.es/invest/02-Datasets/

-De_ataques:
    
          0days_A-420	 
          0days_revisado
          Fwaf-2200 
          Fwaf-badqueries	 
          ataques-800
          ataques-1100
          osvdb
          rdb

-Reales:

          INVES
          BIBLIO-anonimizado
          BIBLIO-etiquetado

Haciendo uso de las herramientas desarrolladas en el proyecto (Cloud + Framework) con los detectores integrados:

-IL (offline):

         ModSecurity
         Snort
         Nemesida  
      
-ModSecurityV3 (offline)

-ModSecurityV2 (online) (Apache)

-Nemesida1.8 (online) (Ngnix)

Nota: los detectores 'online' son aquellos que precisan de un servidor para realizar la detección, mientras que los 'offline' funcionan de forma autónoma, es decir, en ausencia de servidor.
