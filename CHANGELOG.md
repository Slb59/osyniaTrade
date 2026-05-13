## [0.2.0] - 2026-05-13
### Ajouté
- paramétrage pour calcul des bandes de bollinger


## [0.1.4] - 2026-05-12
### Ajouté
- fonction checkConditionSma : donne les conditions d'achat/vente en fonction du SMA
### Modifié
- checkCondition -> checkConditionRsi
- analyse VIDYA : comparatif checkConditionRsi et checkConditionSma.
checkConditionSma convient mieux à priori 
- ⚠ => continuer à expérimenter

## [0.1.3] - 2026-05-11
### Ajouté
- fonction getNextTimeframe(tf)
- fonction findNearestTPs(all_tps, entry_price, is_long)
- fonction calculateSlopeAngle(src, length), ajout de bar_index >= length car sinon les premières valeurs fausses le calcul de la pente

## [0.1.2] - 2026-05-07
### Ajouté
- ajout conditions achat/vente en fonction de VIDYA/RSI

## [0.1.1] - 2026-05-06
### Ajouté
- ajout du calcul vydia + descriptions dans la fonction

## [0.1.0] - 2026-05-05
### Ajouté
- ajout de l'indicateur CMO

## [0.0.2] - 2026-04-22
### Ajouté
- ajout de l'indicateur SMA
- ajout de condition d'affichage pour macd et RSI

## [0.0.1] - 2026-04-16
### Ajouté
- ajout de l'indicateur RSI

## [0.0.0] - 2026-04-15
### Ajouté
- test simple macd
