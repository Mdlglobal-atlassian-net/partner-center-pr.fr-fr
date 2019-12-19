---
title: Principal de service Azure AD | Espace partenaires
ms.topic: article
ms.date: 12/11/2019
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Ajouter un principal de service à votre locataire Azure AD
author: LauraBrenner
ms.author: labrenne
Keywords: Azure, plan Azure, principal de service, application Azure AD
robots: ''
ms.localizationpriority: High
ms.openlocfilehash: 1fe4211879df2063f7b865c249870c49a346f518
ms.sourcegitcommit: 369aceafc54e960ac0bd3a023edc85b06361492b
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/12/2019
ms.locfileid: "75010380"
---
# <a name="add-an-azure-ad-application-service-principal-in-partner-center"></a><span data-ttu-id="82420-104">Ajouter une application Azure AD (principal de service) dans l’Espace partenaires</span><span class="sxs-lookup"><span data-stu-id="82420-104">Add an Azure AD application (service principal) in Partner Center</span></span>

<span data-ttu-id="82420-105">Dans le programme Place de marché commerciale de l’Espace partenaires, vous pouvez désormais ajouter une application Azure AD (principal de service) en tant qu’utilisateur de votre client Azure AD.</span><span class="sxs-lookup"><span data-stu-id="82420-105">In the Commercial Marketplace program in Partner Center, you are now able to add an Azure AD application (service principal) as a user in your Azure AD tenant.</span></span> <span data-ttu-id="82420-106">(Avant, vous pouviez le faire dans votre compte Portail Cloud Partner, mais maintenant que vous avez migré vers l’Espace partenaires, ce compte est en lecture seule.) Notez que principal de service et application Azure AD sont synonymes.</span><span class="sxs-lookup"><span data-stu-id="82420-106">(You were able to do this previously in your Cloud Partner Portal (CPP) account, but now that you have migrated to Partner Center, the CPP acount is read-only.) Note that service principal is synonymous with Azure AD application.</span></span>

## <a name="add-an-azure-ad-application-service-principal"></a><span data-ttu-id="82420-107">Ajouter une application Azure AD (principal de service)</span><span class="sxs-lookup"><span data-stu-id="82420-107">Add an Azure AD application (service principal)</span></span>

1. <span data-ttu-id="82420-108">Dans le tableau de bord de l’Espace partenaires, sélectionnez **Paramètres**, puis **Paramètres de développeur**.</span><span class="sxs-lookup"><span data-stu-id="82420-108">From the Partner Center dashboard, select **Settings** and then select **Developer settings**.</span></span>

2. <span data-ttu-id="82420-109">Sélectionnez **Utilisateurs**, puis **Ajouter des applications Azure AD**.</span><span class="sxs-lookup"><span data-stu-id="82420-109">Select **Users** and then select **Add Azure AD Applications**.</span></span>

3. <span data-ttu-id="82420-110">Sélectionnez une application Azure AD existante ou créez-en une.</span><span class="sxs-lookup"><span data-stu-id="82420-110">Select an existing Azure AD application or create a new one.</span></span>

4. <span data-ttu-id="82420-111">Si vous créez une nouvelle application Azure AD, incluez les informations suivantes :</span><span class="sxs-lookup"><span data-stu-id="82420-111">If you create a new Azure AD Application, include the following information:</span></span>  
<span data-ttu-id="82420-112">  
\**Nom\*\* : Semblable au champ « nom convivial » dans le Portail Cloud Partner.</span><span class="sxs-lookup"><span data-stu-id="82420-112">  
\*\*Name\*\*: This is similar to the ‘friendly name’ field in the CPP portal.</span></span>

<span data-ttu-id="82420-113">**URL de réponse** : URL avec laquelle les utilisateurs peuvent se connecter pour utiliser votre application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="82420-113">**Reply URL**: This is the URL where users can sign in to use your Azure AD application.</span></span> 

<span data-ttu-id="82420-114">**URI d’ID d’application** : Il s’agit d’un identificateur logique pour l’application Azure AD qui est présenté lors de l’envoi d’une demande d’authentification unique à Azure AD.</span><span class="sxs-lookup"><span data-stu-id="82420-114">**App ID URI**: This is a logical identifier for the Azure AD application that is presented when it sends a single sign-on request to Azure AD.</span></span> 

<span data-ttu-id="82420-115">**Rôles de sécurité** : Les rôles **Responsable** (identique au rôle « Propriétaire » dans le Portail Cloud Partner) et **Développeur** (identique au rôle « Contributeur » dans le Portail Cloud Partner) s’appliquent au programme Place de marché commerciale dans l’Espace partenaires et peuvent être associés à cette application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="82420-115">**Security roles**: The roles **Manager** (the same as  ‘Owner’ role in CPP) and **Developer** (the same as ‘Contributor’ role in CPP) apply to the Commercial Marketplace program in Partner Center, and they can be associated with this Azure AD Application.</span></span>  

<span data-ttu-id="82420-116">Lorsque vous sélectionnez **Enregistrer** pour créer cela dans l’Espace partenaires, les informations sont également synchronisées avec le système du Portail Cloud Partner.</span><span class="sxs-lookup"><span data-stu-id="82420-116">When you select **Save**,  to create this in Partner Center, the information is also synced back to the CPP system.</span></span>  