---
title: Common monthly billing scenarios | Partner Center
ms.topic: article
ms.date: 11/21/2019
description: Common scenarios in Partner Center when you use monthly billing (such as adding new subscriptions, changing license quantity, and suspending subscriptions.)
ms.assetid: ''
author: MaggiePucciEvans
ms.author: evansma
Keywords: billing, payments, orders, usage, monthly billing, subscriptions, reconciliation file
ms.localizationpriority: medium
ms.openlocfilehash: 95a535ecdd20614e8809d6304609b1a678859efc
ms.sourcegitcommit: 1c3d3b95135e1daad5ba5585a090e84ab0b97594
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/22/2019
ms.locfileid: "74389617"
---
# <a name="monthly-billing-scenarios"></a>Monthly billing scenarios

These example [common billing scenarios](common-billing-scenarios.md) are applicable if you use monthly billing in Partner Center.

## <a name="new-monthly-subscription"></a>New monthly subscription

Votre date de facturation est le 15 de chaque mois. Vous achetez le 13 janvier un nouvel abonnement avec une licence pour 4 $/mois et sélectionnez une facturation mensuelle. Le 15 janvier, le fichier de rapprochement basé sur les licences contiendra les lignes de facturation suivantes :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|13/01/2018         |12/02/2018    |Frais de cycle   |4,00       |1        |4,00 |

Le 15 février, le fichier de rapprochement basé sur les licences contiendra la ligne de facturation suivante :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|13/02/2018         |12/03/2018    |Frais de cycle   |4,00       |1        |4,00 |

## <a name="change-license-quantity"></a>Change license quantity

Votre date de facturation est le 15 de chaque mois. Vous achetez le 13 janvier un nouvel abonnement avec une licence pour 4 $/mois et sélectionnez une facturation mensuelle. Le 15 janvier, le fichier de rapprochement basé sur les licences contiendra les lignes de facturation suivantes :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|13/01/2018         |12/02/2018    |Frais de cycle   |4,00       |1        |4,00    |

Le 1er février, vous ajoutez une licence supplémentaire. Le 15 février, le fichier de rapprochement basé sur les licences contiendra les lignes de facturation suivantes :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
| 13/01/2018        |12/02/2018    |Instance de cycle au prorata   |-4,00       |1        |-4,00   |
|13/01/2018         |31/01/2018    | Instance de cycle au prorata   |2,45       |1        |2,45    |
|01/02/2018         |12/02/2018    | Instance de cycle au prorata   |1,55       |2        |3,10    |
|13/02/2018         |12/03/2018    | Instance de cycle au prorata   |4,00       |2        |8,00    |

Le prix mensuel est de 4,00 dollars et il y a 31 jours dans la période de service (du 13/01/2018 au 12/02/2018). Cela équivaut à un prix journalier de 0,129 (4/31).

Il y a 19 jours dans la période de prorata (du 13/01/2018 au 31/01/2018).

Prix unitaire au prorata = 2,451 = 19 x 0,129

Il y a 12 jours dans la période de prorata (du 1/02/2018 au 2/12/2018).

Prix unitaire au prorata = 1,54 = 12 x 0,129

## <a name="suspend-before-30-days"></a>Suspend before 30 days

Votre date de facturation est le 15 de chaque mois. Vous achetez le 13 janvier un nouvel abonnement avec une licence pour 4 $/mois et sélectionnez une facturation mensuelle. Le 15 janvier, le fichier de rapprochement basé sur les licences contiendra les lignes de facturation suivantes :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|13/01/2018         |12/02/2018    |Frais de cycle   |4,00       |1        |4,00    |

On February 1 you suspend a subscription. Le 15 février, le fichier de rapprochement basé sur les licences contiendra la ligne de facturation suivante :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
13/01/2018|12/02/2018|Frais d'annulation|-4,00|1|-4,00

## <a name="suspend-after-30-days"></a>Suspend after 30 days

Votre date de facturation est le 15 de chaque mois. Vous achetez le 13 janvier un nouvel abonnement avec une licence pour 4 $/mois et sélectionnez une facturation mensuelle. Le 15 janvier, le fichier de rapprochement basé sur les licences contiendra les lignes de facturation suivantes :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
13/01/2018|12/02/2018|Frais de cycle|4,00|1|4,00

Le 15 février, le fichier de rapprochement basé sur les licences contiendra la ligne de facturation suivante :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
13/02/2018|12/03/2018|Frais de cycle|4,00|1|4,00

Le 1er mars vous suspendez l'abonnement. Le 15 mars, le fichier de rapprochement basé sur les licences contiendra la ligne de facturation suivante :

|Date de début de facturation |Date de fin de facturation |Type de facturation |Prix unitaire |Quantité |Montant |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
01/03/2018|12/03/2018|Frais d'annulation|-1,72|1|-1,72

Le prix mensuel est de 4,00 dollars et il y a 28 jours dans la période de service (du 13/02/2018 au 12/03/2018). Cela équivaut à un prix journalier de 0,143 (4/28).

Prix unitaire = jours dans la période de service x prix journalier x nombre de licences.

Il y a 12 jours dans la période d'annulation (du 01/03/2018 au 12/03/2018).

Therefore, the unit price = -1.716 (12 x 0.143 x (-1)).