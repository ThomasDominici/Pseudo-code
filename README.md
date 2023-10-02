Début achatBonbons (réel prix, réel argent, réel quantité)

      Si réel prix > 0 ET réel argent > 0
      
               tant que prix < argent
                     argent <- argent - prix
                     quantité <- quantité + 1
               Fin tant que 
               retourner quantité
       Sinon
              Retourner pas d'achat
       Fin Si
Fin achatBonbons
