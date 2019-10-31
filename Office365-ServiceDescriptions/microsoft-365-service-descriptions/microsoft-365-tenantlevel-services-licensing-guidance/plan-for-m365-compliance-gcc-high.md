---
title: Plan para Microsoft 365 Compliance-GCC High
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades del gobierno federal de Estados Unidos u otras entidades que administran datos sujetos a las regulaciones y los requisitos gubernamentales, donde el uso de Microsoft 365 Government-GCC High es apropiado para cumplir estos requisitos.
ms.openlocfilehash: 4ddc98b4784741e62d0cdabefb9d36d7b11ac560
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890530"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a><span data-ttu-id="96dd3-103">Plan para Microsoft 365 Compliance – GCC High</span><span class="sxs-lookup"><span data-stu-id="96dd3-103">Plan for Microsoft 365 Compliance – GCC High</span></span>

<span data-ttu-id="96dd3-104">Esta guía está dirigida a los profesionales de ti que imponen las implementaciones de Office 365 en entidades del gobierno federal de Estados Unidos u otras entidades que administran datos sujetos a las regulaciones y los requisitos gubernamentales, donde el uso de Microsoft 365 Government-GCC High es apropiado para cumplir estos requisitos.</span><span class="sxs-lookup"><span data-stu-id="96dd3-104">This guidance is for IT pros who are driving deployments of Office 365 in US Federal Government entities or other entities that handle data that’s subject to government regulations and requirements, where the use of Microsoft 365 Government – GCC High is appropriate to meet these requirements.</span></span>

> [!NOTE]
><span data-ttu-id="96dd3-105">Si su organización ya ha cumplido con los requisitos de elegibilidad elevados de Microsoft 365 gubernamentales – GCC y ha sido aceptado en el programa, puede omitir los pasos 1 y 2 e ir directamente al paso 3.</span><span class="sxs-lookup"><span data-stu-id="96dd3-105">If your organization has already met the Microsoft 365 Government – GCC High eligibility requirements and applied for and been accepted into the program, you can skip steps 1 and 2 and go directly to step 3.</span></span>
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a><span data-ttu-id="96dd3-106">Paso 1.</span><span class="sxs-lookup"><span data-stu-id="96dd3-106">Step 1.</span></span> <span data-ttu-id="96dd3-107">Determinar si su organización necesita Microsoft 365 Government – GCC High y cumple los requisitos de elegibilidad</span><span class="sxs-lookup"><span data-stu-id="96dd3-107">Determine whether your organization needs Microsoft 365 Government – GCC High and meets eligibility requirements</span></span>

<span data-ttu-id="96dd3-108">El entorno alto de Microsoft 365 Government-GCC cumple con los requisitos del gobierno de Estados Unidos para los servicios en la nube.</span><span class="sxs-lookup"><span data-stu-id="96dd3-108">The Microsoft 365 Government - GCC High environment complies with US Government requirements for cloud services.</span></span> <span data-ttu-id="96dd3-109">Además de disfrutar de las características y capacidades de Office 365, las organizaciones se benefician de las siguientes características exclusivas de Microsoft 365 Government – GCC High:</span><span class="sxs-lookup"><span data-stu-id="96dd3-109">In addition to enjoying the features and capabilities of Office 365, organizations benefit from the following features that are unique to Microsoft 365 Government – GCC High:</span></span>

- <span data-ttu-id="96dd3-110">El contenido del cliente de la organización se separa lógicamente del contenido del cliente en los servicios comerciales de Office 365 de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="96dd3-110">Your organization’s customer content is logically segregated from customer content in the commercial Office 365 services from Microsoft.</span></span>
- <span data-ttu-id="96dd3-111">El contenido del cliente de la organización se almacena dentro de los Estados Unidos.</span><span class="sxs-lookup"><span data-stu-id="96dd3-111">Your organization’s customer content is stored within the United States.</span></span>
- <span data-ttu-id="96dd3-112">El acceso al contenido del cliente de la organización está restringido a personal específico de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="96dd3-112">Access to your organization’s customer content is restricted to screened Microsoft personnel.</span></span>
- <span data-ttu-id="96dd3-113">Microsoft 365 Government – GCC High cumple con las certificaciones y acreditaciones necesarias para los clientes del sector público de los Estados Unidos.</span><span class="sxs-lookup"><span data-stu-id="96dd3-113">Microsoft 365 Government – GCC High complies with certifications and accreditations that are required for US public sector customers.</span></span>

<span data-ttu-id="96dd3-114">Puede encontrar más información sobre la oferta de Microsoft 365 Government – GCC High offer for US Government customers en [Office 365, planes gubernamentales](https://products.office.com/government/compare-office-365-government-plans), incluidos los requisitos de elegibilidad.</span><span class="sxs-lookup"><span data-stu-id="96dd3-114">You can find more information about the Microsoft 365 Government – GCC High offering for US Government customers at [Office 365 Government plans](https://products.office.com/government/compare-office-365-government-plans), including eligibility requirements.</span></span>

<span data-ttu-id="96dd3-115">La [Descripción del servicio Office 365 US Government](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describe los beneficios de la plataforma, que se centran en cumplir con los requisitos de cumplimiento en los Estados Unidos.</span><span class="sxs-lookup"><span data-stu-id="96dd3-115">The [Office 365 US Government service description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describes the platform’s benefits, which are centered on meeting compliance requirements within the United States.</span></span>

> [!TIP]
> <span data-ttu-id="96dd3-116">Es posible que desee transferir las tablas de información de la descripción del servicio a un libro de Excel y agregar dos columnas: **importante para mi organización y/n** y **que satisfaga las necesidades de la organización y/n**.</span><span class="sxs-lookup"><span data-stu-id="96dd3-116">You might want to transfer the tables of information in the service description into an Excel workbook and add two columns: **Relevant for my organization Y/N** and **Meets the needs of my organization Y/N**.</span></span> <span data-ttu-id="96dd3-117">A continuación, puede revisar esta lista con sus colegas para confirmar que este servicio cumple con las necesidades de su organización.</span><span class="sxs-lookup"><span data-stu-id="96dd3-117">Then you can review this list with your colleagues to confirm that this service meets your organization’s needs.</span></span>

<span data-ttu-id="96dd3-118">**Puntos de decisión**:</span><span class="sxs-lookup"><span data-stu-id="96dd3-118">**Decision points**:</span></span><br/>
- <span data-ttu-id="96dd3-119">*Decida si Microsoft 365 Government – GCC-High es adecuado para su organización.*</span><span class="sxs-lookup"><span data-stu-id="96dd3-119">*Decide whether Microsoft 365 Government – GCC-High is appropriate for your organization.*</span></span>
- <span data-ttu-id="96dd3-120">*Confirmar que la organización cumple los requisitos de elegibilidad.*</span><span class="sxs-lookup"><span data-stu-id="96dd3-120">*Confirm that your organization meets eligibility requirements.*</span></span>

> [!NOTE]
> <span data-ttu-id="96dd3-121">Microsoft 365 Government-GCC High solo está disponible en Estados Unidos.</span><span class="sxs-lookup"><span data-stu-id="96dd3-121">Microsoft 365 Government - GCC High is only available in the United States.</span></span> <span data-ttu-id="96dd3-122">Los clientes que no son del gobierno de Estados Unidos pueden elegir entre varios [planes de Office 365 administración pública](https://products.office.com/government/compare-office-365-government-plans).</span><span class="sxs-lookup"><span data-stu-id="96dd3-122">Non–US Government customers can choose from a number of [Office 365 Government plans](https://products.office.com/government/compare-office-365-government-plans).</span></span>

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a><span data-ttu-id="96dd3-123">Paso 2.</span><span class="sxs-lookup"><span data-stu-id="96dd3-123">Step 2.</span></span> <span data-ttu-id="96dd3-124">Solicitud para Microsoft 365 Government – GCC-High</span><span class="sxs-lookup"><span data-stu-id="96dd3-124">Apply for Microsoft 365 Government – GCC-High</span></span>

<span data-ttu-id="96dd3-125">Tras haber decidido que este servicio es adecuado para su organización, inicie el proceso de [solicitud para este servicio](https://products.office.com/government/eligibility-validation).</span><span class="sxs-lookup"><span data-stu-id="96dd3-125">Having decided that this service is right for your organization, start the process of [applying for this service](https://products.office.com/government/eligibility-validation).</span></span>
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a><span data-ttu-id="96dd3-126">Paso 3.</span><span class="sxs-lookup"><span data-stu-id="96dd3-126">Step 3.</span></span> <span data-ttu-id="96dd3-127">Descripción de la configuración de seguridad predeterminada de Microsoft 365 Government – GCC-High</span><span class="sxs-lookup"><span data-stu-id="96dd3-127">Understand Microsoft 365 Government – GCC-High default security settings</span></span>

<span data-ttu-id="96dd3-128">Le recomendamos que tenga tiempo para revisar minuciosamente la configuración de administración y seguridad antes de modificarla y tenga en cuenta el impacto en el cumplimiento antes de realizar cambios en la configuración de seguridad predeterminada.</span><span class="sxs-lookup"><span data-stu-id="96dd3-128">We recommend that you take time to carefully review your admin and security settings before you modify them and consider the impact on compliance before you make any changes to the default security settings.</span></span>

<span data-ttu-id="96dd3-129">**Punto de decisión**: *decida si va a modificar cualquiera de los valores predeterminados de configuración de Microsoft 365 Government-High Security, que se resuelven para comprender primero el impacto de los cambios que puede realizar.*</span><span class="sxs-lookup"><span data-stu-id="96dd3-129">**Decision point**: *Decide whether you’ll modify any of the default Microsoft 365 Government – GCC-High security settings, resolving to first understand the impact of any changes you might make.*</span></span>

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-high"></a><span data-ttu-id="96dd3-130">Paso 4.</span><span class="sxs-lookup"><span data-stu-id="96dd3-130">Step 4.</span></span> <span data-ttu-id="96dd3-131">Comprenda las funcionalidades que actualmente no están disponibles o deshabilitadas de forma predeterminada en Microsoft 365 Government – GCC-High \* \*</span><span class="sxs-lookup"><span data-stu-id="96dd3-131">Understand which capabilities are currently unavailable or disabled by default in Microsoft 365 Government – GCC-High\*\*</span></span>

<span data-ttu-id="96dd3-132">Para cumplir con los requisitos de nuestros clientes de la nube de administración pública, existen algunas diferencias entre los planes de Microsoft 365 administración pública – GCC-High y Enterprise.</span><span class="sxs-lookup"><span data-stu-id="96dd3-132">To meet the requirements of our government cloud customers, there are some differences between Microsoft 365 Government – GCC-High and enterprise plans.</span></span> <span data-ttu-id="96dd3-133">Consulte la tabla siguiente para ver las características que están disponibles.</span><span class="sxs-lookup"><span data-stu-id="96dd3-133">Refer to the following table to see which features are available.</span></span>

|                                         | <span data-ttu-id="96dd3-134">Característica</span><span class="sxs-lookup"><span data-stu-id="96dd3-134">Feature</span></span>                                         | <span data-ttu-id="96dd3-135">Estado alta de GCC</span><span class="sxs-lookup"><span data-stu-id="96dd3-135">GCC High Status</span></span>        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| <span data-ttu-id="96dd3-136">**Protección de la información & gobernanza**</span><span class="sxs-lookup"><span data-stu-id="96dd3-136">**Information protection & governance**</span></span> | <span data-ttu-id="96dd3-137">Archivado</span><span class="sxs-lookup"><span data-stu-id="96dd3-137">Archiving</span></span>                                       | <span data-ttu-id="96dd3-138">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-138">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-139">Etiquetas y directivas manuales</span><span class="sxs-lookup"><span data-stu-id="96dd3-139">Manual labels and policies</span></span>                      | <span data-ttu-id="96dd3-140">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-140">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-141">Aplicación automática de etiquetas</span><span class="sxs-lookup"><span data-stu-id="96dd3-141">Auto application of labels</span></span>                      | <span data-ttu-id="96dd3-142">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-142">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-143">Etiquetas basadas en tipos de datos confidenciales</span><span class="sxs-lookup"><span data-stu-id="96dd3-143">Labels based on sensitive data types</span></span>            | <span data-ttu-id="96dd3-144">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-144">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-145">Etiquetas y directivas asociadas basadas en consultas</span><span class="sxs-lookup"><span data-stu-id="96dd3-145">Labels and associated policies based on queries</span></span> | <span data-ttu-id="96dd3-146">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-146">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-147">Plan de archivos</span><span class="sxs-lookup"><span data-stu-id="96dd3-147">File plan</span></span>                                       | <span data-ttu-id="96dd3-148">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-148">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-149">Directivas recomendadas</span><span class="sxs-lookup"><span data-stu-id="96dd3-149">Recommended policies</span></span>                            | <span data-ttu-id="96dd3-150">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-150">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-151">Filtros de importación inteligente</span><span class="sxs-lookup"><span data-stu-id="96dd3-151">Smart import filters</span></span>                            | <span data-ttu-id="96dd3-152">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-152">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-153">Acerca de la retención basada en eventos</span><span class="sxs-lookup"><span data-stu-id="96dd3-153">Event-based retention</span></span>                           | <span data-ttu-id="96dd3-154">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-154">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-155">Revisión de disposición</span><span class="sxs-lookup"><span data-stu-id="96dd3-155">Disposition review</span></span>                              | <span data-ttu-id="96dd3-156">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-156">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-157">Barreras de información</span><span class="sxs-lookup"><span data-stu-id="96dd3-157">Information barriers</span></span>                            | <span data-ttu-id="96dd3-158">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-158">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-159">Prevención de pérdida de datos (DLP) para archivos y correo electrónico</span><span class="sxs-lookup"><span data-stu-id="96dd3-159">Data loss prevention (DLP) for files and email</span></span>  | <span data-ttu-id="96dd3-160">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-160">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-161">DLP para las conversaciones de canales y chat de Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="96dd3-161">DLP for Teams chat and channel conversations</span></span>    | <span data-ttu-id="96dd3-162">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-162">On engineering backlog</span></span> |
| <span data-ttu-id="96dd3-163">**Administración de riesgos de Insider**</span><span class="sxs-lookup"><span data-stu-id="96dd3-163">**Insider risk management**</span></span>             | <span data-ttu-id="96dd3-164">Cifrado de mensajes avanzado</span><span class="sxs-lookup"><span data-stu-id="96dd3-164">Advanced Message Encryption</span></span>                     | <span data-ttu-id="96dd3-165">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-165">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-166">Cumplimiento de la comunicación</span><span class="sxs-lookup"><span data-stu-id="96dd3-166">Communication compliance</span></span>                        | <span data-ttu-id="96dd3-167">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-167">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-168">Caja de seguridad del cliente</span><span class="sxs-lookup"><span data-stu-id="96dd3-168">Customer Lockbox</span></span>                                | <span data-ttu-id="96dd3-169">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-169">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-170">Clave del cliente</span><span class="sxs-lookup"><span data-stu-id="96dd3-170">Customer Key</span></span>                                    | <span data-ttu-id="96dd3-171">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-171">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-172">Administración del acceso con privilegios</span><span class="sxs-lookup"><span data-stu-id="96dd3-172">Privileged access management</span></span>                    | <span data-ttu-id="96dd3-173">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-173">On engineering backlog</span></span> |
| <span data-ttu-id="96dd3-174">**Detección de & responder**</span><span class="sxs-lookup"><span data-stu-id="96dd3-174">**Discover & respond**</span></span>                  | <span data-ttu-id="96dd3-175">Reserva local</span><span class="sxs-lookup"><span data-stu-id="96dd3-175">In-place reservation</span></span>                            | <span data-ttu-id="96dd3-176">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-176">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-177">Administración de casos</span><span class="sxs-lookup"><span data-stu-id="96dd3-177">Case management</span></span>                                 | <span data-ttu-id="96dd3-178">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-178">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-179">Búsqueda</span><span class="sxs-lookup"><span data-stu-id="96dd3-179">Search</span></span>                                          | <span data-ttu-id="96dd3-180">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-180">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-181">Exportar</span><span class="sxs-lookup"><span data-stu-id="96dd3-181">Export</span></span>                                          | <span data-ttu-id="96dd3-182">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-182">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-183">Descifrado de RMS</span><span class="sxs-lookup"><span data-stu-id="96dd3-183">RMS decryption</span></span>                                  | <span data-ttu-id="96dd3-184">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-184">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-185">Exportación nativa</span><span class="sxs-lookup"><span data-stu-id="96dd3-185">Native export</span></span>                                   | <span data-ttu-id="96dd3-186">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-186">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-187">Procesamiento avanzado</span><span class="sxs-lookup"><span data-stu-id="96dd3-187">Advanced processing</span></span>                             | <span data-ttu-id="96dd3-188">Disponible</span><span class="sxs-lookup"><span data-stu-id="96dd3-188">Available</span></span>              |
|                                         | <span data-ttu-id="96dd3-189">Subprocesos de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="96dd3-189">Email threading</span></span>                                 | <span data-ttu-id="96dd3-190">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-190">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-191">Identificación casi duplicada</span><span class="sxs-lookup"><span data-stu-id="96dd3-191">Near duplicate identification</span></span>                   | <span data-ttu-id="96dd3-192">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-192">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-193">Temas</span><span class="sxs-lookup"><span data-stu-id="96dd3-193">Themes</span></span>                                          | <span data-ttu-id="96dd3-194">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-194">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-195">Codificación predictiva</span><span class="sxs-lookup"><span data-stu-id="96dd3-195">Predictive coding</span></span>                               | <span data-ttu-id="96dd3-196">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-196">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-197">Exportación procesada con archivo de carga</span><span class="sxs-lookup"><span data-stu-id="96dd3-197">Processed export with load file</span></span>                 | <span data-ttu-id="96dd3-198">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-198">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-199">Etiquetado</span><span class="sxs-lookup"><span data-stu-id="96dd3-199">Tagging</span></span>                                         | <span data-ttu-id="96dd3-200">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-200">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-201">Lectores</span><span class="sxs-lookup"><span data-stu-id="96dd3-201">Viewers</span></span>                                         | <span data-ttu-id="96dd3-202">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-202">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-203">Redacciones</span><span class="sxs-lookup"><span data-stu-id="96dd3-203">Redactions</span></span>                                      | <span data-ttu-id="96dd3-204">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-204">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-205">Filtrado</span><span class="sxs-lookup"><span data-stu-id="96dd3-205">Filtering</span></span>                                       | <span data-ttu-id="96dd3-206">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-206">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-207">Asignación de custodio a carga de trabajo</span><span class="sxs-lookup"><span data-stu-id="96dd3-207">Custodian to workload mapping</span></span>                   | <span data-ttu-id="96dd3-208">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-208">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-209">Comunicaciones de custodios</span><span class="sxs-lookup"><span data-stu-id="96dd3-209">Custodian communications</span></span>                        | <span data-ttu-id="96dd3-210">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-210">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-211">Revisar conjuntos</span><span class="sxs-lookup"><span data-stu-id="96dd3-211">Review sets</span></span>                                     | <span data-ttu-id="96dd3-212">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-212">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-213">Revisión y anotaciones</span><span class="sxs-lookup"><span data-stu-id="96dd3-213">Review and annotate</span></span>                             | <span data-ttu-id="96dd3-214">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-214">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-215">Recopilación no de Office 365</span><span class="sxs-lookup"><span data-stu-id="96dd3-215">Non-Office 365 ingestion</span></span>                        | <span data-ttu-id="96dd3-216">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-216">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="96dd3-217">Informe de términos de búsqueda</span><span class="sxs-lookup"><span data-stu-id="96dd3-217">Search Term report</span></span>                              | <span data-ttu-id="96dd3-218">Sobre el trabajo pendiente de ingeniería</span><span class="sxs-lookup"><span data-stu-id="96dd3-218">On engineering backlog</span></span> |

<span data-ttu-id="96dd3-219">**Punto de decisión**: *decida si las características de cumplimiento satisfacen las necesidades de su organización.*</span><span class="sxs-lookup"><span data-stu-id="96dd3-219">**Decision point**: *Decide whether the compliance features meet your organization’s needs.*</span></span>