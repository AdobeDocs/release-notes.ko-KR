---
title: 최신 릴리스 정보
description: Adobe [!DNL Experience Cloud] 제품 및 서비스에 대한 최신 릴리스 정보 및 기술 자료 문제를 살펴보십시오. Experience League에서 예정된 이벤트 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud] 애플리케이션의 최신 튜토리얼 및 교육 과정을 살펴보십시오.
doc-type: release notes
last-update: June 2025
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: a77d5bea72561f95c07ca0a1427034dd82f30ee0
workflow-type: tm+mt
source-wordcount: '6430'
ht-degree: 95%

---

# Experience Cloud 릴리스 정보 - 2025년 6월

<!-- badgeReview: label="Internal Review" type="Negative" -->

<!-- ![Banner](assets/release-notes-header.png) -->

이 페이지는 Experience Cloud 제품에 대한 중앙 릴리스 정보 리소스입니다. Experience League의 애플리케이션별 릴리스 정보, 예정된 이벤트, 새로운 튜토리얼 및 최신 지원 문서에 대한 링크를 찾아보십시오. Experience League의 맞춤형 홈 페이지는 관심사에 맞춰 제공됩니다.

<!-- * [Customize your learning](https://experienceleague.adobe.com/ko/home/profile-settings): Help us customize your learning experience. Select your role, industry, and the products that interest you.
* [Browse and discover](https://experienceleague.adobe.com/ko/browse): Find popular content, new tutorials, documentation, upcoming events, and more!
* [Get fresh perspectives](https://experienceleague.adobe.com/ko/perspectives): We've gathered a variety of real-world use cases and best practices, written by your peers and Adobe product experts. 
* [Get certified](https://experienceleague.adobe.com/ko/certification-home): The new Adobe Certification Portal makes honing your skills and getting certified a simple process.
* [Engage with a community of peers](https://experienceleaguecommunities.adobe.com/?profile.language=ko): Join groups, meet our Experience League Community Advisors, and even learn how to become one. -->

이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오.

**2025년 7월 7일 업데이트됨**

+++제품 링크 보기

* [[!DNL Adobe System Status]](#status)
* [[!DNL Adobe Experience Cloud] - 중앙 인터페이스 및 관리](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Real-Time CDP]](#rtcdp)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Adobe Customer Journey Analytics]](#cja)
* [[!DNL Adobe Streaming Media Analytics]](#sma)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Journey Optimizer B2B Edition]](#ajo-b2b)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe GenStudio for Performance Marketing]](#genstudio-marketing)
* [[!DNL Adobe Mix Modeler]](#mix-modeler)
* [[!DNL Adobe Advertising]](#advertising)
* [[!DNL Adobe Pass]](#pass)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [고객 데이터 관리 - Voices](#voices)
* [Digital Experience 블루프린트](#blueprints)
* [Adobe에서의 인증](https://experienceleague.adobe.com/ko/certification-home)
* [Adobe 제품 보안 취약점](https://helpx.adobe.com/kr/security.html)

+++

<!-- ## June updates

| Product   | Release / Announcement Date            | Key Highlights |
|-------|------------|----------------|
| Experience Cloud admin & central interface   | [June 1, 2025](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/current) | Generative AI support in Admin Console, improved user/product license management |
| Adobe Experience Platform | [June 18, 2025](https://experienceleague.adobe.com/ko/docs/experience-platform/release-notes/latest)  | New dashboard email exports, updated tutorials & support articles |
| Adobe Real-Time CDP  | [June 12, 2025](https://experienceleague.adobe.com/ko/docs/real-time-cdp-collaboration/using/latest) | Self-serve destination support, audience refresh frequency |
| Adobe Analytics  | [June 18-24, 2025](https://experienceleague.adobe.com/ko/docs/analytics/release-notes/latest)  | Secure cloud exports, new preview bar chart, enhanced attribution |
| Adobe Customer Journey Analytics | [June 2-18, 2025](https://experienceleague.adobe.com/ko/docs/analytics-platform/using/releases/latest)  | Fixed panel hover, new B2B Edition GA with account-level modeling |
| Adobe Streaming Media Analytics  | _(Not updated)_  | No new release notes - last updated December 2024 | 
| Adobe Experience Manager | [June 10, 2025](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/release-notes/maintenance/2025/2025-6-0)  | Maintenance release 21193, feature release 2025.6.0 scheduled June 26 |
| Adobe Commerce (Magento)  | [June 10, 2025](https://experienceleague.adobe.com/ko/docs/commerce-operations/release/versions)  | Commerce 2.4.9‑alpha & patch 2.4.8‑p1, security fixes via APSB25‑50 |
| Adobe Commerce B2B Edition | [June 10, 2025](https://experienceleague.adobe.com/ko/docs/commerce-admin/b2b/release-notes)  | B2B module v1.5.2‑p1 and v1.4.2‑p6 released with security compatibility |
| Adobe Target   | _(Not updated)_  | No new official release info published in June 2025 |
| Adobe Campaign   | _(Not updated)_   | Bundled under central Experience Cloud updates |
| Adobe Journey Optimizer  | [June 18, 2025](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes) | Beta: AEP dataset decisioning |
| Adobe Journey Optimizer B2B Edition  | *Included in Journey Optimizer June GA* via CJA B2B mention  | Account-level journey insights |
| Adobe Marketo Engage   | _(Not updated)_ | No public release notes published in June |
| Adobe Workfront | _(Not updated)_ | No public release notes published in June |
| Adobe GenStudio for Performance Marketing    | *(Included in central AI updates)* | Announced along with LLM Optimizer (June 16) |
| Adobe Mix Modeler   | [June 18, 2025](https://experienceleague.adobe.com/ko/docs/mix-modeler/using/releases/latest)  | Introduced goal-based plans and spend pattern configurations |
| Adobe Advertising   | _(Not updated)_ | No separate public June notes |
| Adobe Pass   | _(Not updated)_   | No public release notes published in June |
| Adobe Document Cloud  | _(Not updated)_    | No public release notes published in June | -->

## [!DNL Experience League] 이벤트 {#events}

관심 있는 [이벤트](https://experienceleague.adobe.com/ko/events)를 찾아 등록하십시오.

+++예정된 이벤트

* **Adobe Workfront** | _3분기 릴리스 웨비나_ | 2025년 7월 릴리스로 예정된 최신 Workfront 기능을 소개합니다. | [2025년 7월 10일 - 오전 9시(MT)] | [등록](https://events.teams.microsoft.com/event/0481924a-fc34-4781-b7fc-ed4a54e6fa1f@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Marketo Engage** | _사용자 그룹_ | 이 기본 세션에서 Marketo Personalization을 사용하여 캠페인을 강화하는 방법을 알아봅니다. | 2025년 7월 10일 | [등록](https://mugs.marketo.com/events/details/marketo-foundational-marketo-user-group-presents-foundations-of-marketo-engage-powering-campaigns-with-marketo-personalization/)

* **Adobe Workfront** | _연결: 마케팅 및 Creative의 관리자 채팅_ | Workfront 관리자를 위한 모범 사례와 팁에 대해 동료와 논의합니다. | 2025년 7월 11일 - 오전 10시(MT) | [등록](https://events.teams.microsoft.com/event/14f0c251-136d-4a61-befc-54673bf58cd6@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Commerce(다중 솔루션)** | _최신 정보: App Builder_ | App Builder을 사용하는 다른 플랫폼과 Adobe Commerce을 통합하는 방법에 대해 설명합니다. | 2025년 7월 17일 - 오전 11시(MT) | [등록](https://adobeevents.adobeconnect.com/erocxh4d6bbu/event/registration.html?campaign-id=ExL)

* **Adobe Workfront** | _Workfront 집합_ | 기능 공유, 브레인스토밍 및 문제 해결을 위한 월별 만남 | 2025년 7월 17일 - 오전 7시(MT) | [등록](https://events.teams.microsoft.com/event/cce5eabe-e2e7-435f-aefb-14956ec192d0@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Workfront** | _Workfront에서 콘텐츠 승인 재검토_ | 향후 승인 워크플로, Frame.io 통합 및 로드맵에 대해 자세히 알아보십시오. | 2025년 7월 22일 - 오전 9시(MT) | [등록](https://events.teams.microsoft.com/event/0d5f80d1-9cb1-42f9-a199-ea0ca6f8fe99@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Experience Manager Assets** | _AEM Content Hub의 강력한 기능을 잠금 해제_ | 지역 간 브랜드 콘텐츠를 재사용, 활성화 및 중앙 집중화하는 방법에 대해 알아봅니다. | 2025년 7월 22일 - 오전 9시(MT) | [등록](https://events.teams.microsoft.com/event/04f70202-48dc-4ddb-954b-5b60fad1b693@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Experience Manager Forms** | _결제자 등록 여정 현대화_ | AEM Forms을 사용하여 멤버 등록을 자동화하고 향상시킬 수 있습니다. | 2025년 7월 23일 - 오전 11시(MT) | [등록](https://events.teams.microsoft.com/event/958401be-1c2c-4e4b-87b0-a3939ff8ff6b@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Workfront** | _Workfront 계획: Smart Start_ | Workfront 제품 관리 팀에서 기본 설정 모범 사례에 대해 알아봅니다. | 2025년 7월 31일 - 오전 10시(MT) | [등록](https://events.teams.microsoft.com/event/adbabe72-e591-464e-87f8-1f1947d49f38@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Adobe Marketo Engage(다중 솔루션)** | _Marketo 및 Mochas: Salesforce 동기화_ | Salesforce + Marketo을 동기화하고 최적화하는 팁과 전략입니다. | 2025년 7월 31일 - 오전 10시(MT) | [등록](https://adobeevents.adobeconnect.com/eeb0ucvtg1l0/event/registration.html?campaign-id=ExL)

* **Adobe Workfront** | _단순성 디자인: Kohler가 Creative Brief를 다시 상상하는 방법_ | Workfront의 창의적 개요 프로세스 혁신에 대한 사례 연구. | 2025년 8월 6일 - 오후 12시(MT) | [등록](https://events.teams.microsoft.com/event/fbfa9ecf-7042-4ed8-b7a5-58351dae561f@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

Experience League에서 [예정된 이벤트](https://experienceleague.adobe.com/ko/events)의 전체 목록을 보거나 [온디맨드](https://experienceleague.adobe.com/ko/docs/events/experience-league-recorded-events/overview) 이벤트를 찾아보십시오.

+++

## [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. 중단 및 유지 관리 이벤트에 대한 알림을 받습니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

+++릴리스 정보

[!DNL Adobe System Status]에 대한 이전 릴리스 정보:

* [2025년 4월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2025/04162025#status)
* [2024년 8월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2024/09142023#status)
* [2024년 5월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2024/05152024#status)
* [2024년 1월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2024/02142024#status)
* [2023년 10월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/10042023#status)
* [2023년 8월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/08092023#status)
* [2023년 3월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/03082023#status)
* [2023년 1월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/02082023#status)

+++

## [!DNL Experience Cloud] 관리 및 중앙 인터페이스 {#ecloud}

[!DNL Experience Cloud] 관리 및 중앙 인터페이스 구성 요소의 업데이트에 대해 알아봅니다.

+++새로운 기능

다음에 대한 도움말은 [Experience Cloud 인터페이스 및 관리 안내서](https://experienceleague.adobe.com/ko/docs/core-services/interface/experience-cloud)를 참조하십시오.

* [Experience Cloud 애플리케이션의 생성형 AI](https://experienceleague.adobe.com/ko/docs/core-services/interface/features/generative-ai)
* [사용자 관리 및 제품 라이선스](https://experienceleague.adobe.com/ko/docs/core-services/interface/administration/admin-console) (Admin Console)
* [고객 속성, 대상자 라이브러리, 자산](https://experienceleague.adobe.com/ko/docs/core-services/interface/services/overview) 등

+++

## [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 및 [!UICONTROL Mobile SDK]에 대한 최신 릴리스 정보와 새로운 설명서를 살펴보십시오. 새로운 튜토리얼 및 기술 자료 지원 문서를 살펴보십시오.

+++릴리스 정보, 튜토리얼 및 지원 문서

예정 릴리스: **2025년 6월 18일**

* [[!DNL Experience Platform] 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-platform/release-notes/latest)

* [[!DNL Experience Platform] Mobile SDK 릴리스 정보](https://developer.adobe.com/client-sdks/documentation/release-notes/)

### 새로운 [!DNL Experience Platform] 튜토리얼{#tutorials-aep}

Experience League에 새로운 Adobe [!DNL Experience Platform] 튜토리얼이 게시되었습니다.

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025년 6월 | [!DNL Experience Platform] | [ID 그래프 연결 규칙 - ID 설정](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/identities/graph-linking-rules/identity-settings) | 새 비디오 | Adobe Experience Platform에서 ID 그래프 연결 규칙을 활성화하고 구성하여 정확한 고객 프로필을 빌드하는 방법에 대해 알아봅니다. 이 비디오에서는 네임스페이스 우선순위 지정, 고유성 설정 및 유효성 검사에 대해 다루므로 샌드박스에서 이러한 기능을 효과적으로 사용할 수 있습니다. |

### 새 [!DNL Experience Platform] 지원 기술 자료{#kb-aep}

[!DNL Experience Platform]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2025년 5월 | [[!DNL Snowflake] AEP에서 [!UICONTROL 소스] 데이터 흐름을 편집할 때 연결 시간 초과](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26451) | 신규 문서 | Adobe Experience Platform에서 **[!UICONTROL 선택 데이터]** 단계에서 [!DNL Snowflake] [!UICONTROL 소스] 데이터 흐름을 편집할 때 [!DNL Snowflake] 연결 시간 초과 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Experience Platform - **[!UICONTROL 파트너 ID]** 프로필 조회 결과가 표시되지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26462) | 신규 문서 | ID 그래프의 작동 방식으로 인해 Adobe Experience Platform에서 **[!UICONTROL 파트너 ID]** 프로필 조회 결과가 표시되지 않는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEP는 특정 IP 주소를 기반으로 한 API 액세스 제한을 지원하지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26471) | 신규 문서 | Adobe Experience Platform(AEP) 내의 특정 IP 주소에 대한 API 액세스를 제한할 수 없는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [*UIS-0002-400: Adobe Experience Platform에서 배치 ID 해결 실패* 오류](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26520) | 신규 문서 | *UIS-0002-400: Adobe Experience Platform(AEP)에서 배치 ID 해결 실패 오류*&#x200B;가 발생할 때 이 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEP에서 [!UICONTROL Privacy Service API] 400 오류 수정: 일일 업로드 제한 설명](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26552) | 신규 문서 | Adobe Experience Platform(AEP) [!UICONTROL Privacy Service API]는 서비스 남용을 방지하기 위해 엄격한 일일 업로드 제한을 적용하여 GDPR과 같은 규제 준수를 위해 대규모 사용자 프로필 삭제를 시도할 때 400 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Experience Platform에서 세그먼트 생성 중 시간 초과 오류 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26606) | 신규 문서 | Adobe Experience Platform에서 대상자 세그먼트를 생성하는 동안 시간 초과 오류를 해결하는 방법을 알아봅니다. |
| 2025년 5월 | [[!DNL Facebook] [!UICONTROL 사용자 정의 대상자] 커넥터가 처리 상태에 멈춤](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26615) | 신규 문서 | [!DNL Facebook] [!UICONTROL 사용자 정의 대상자] 대상이 처리 상태에서 멈춰 대상자 활성화가 차단되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Experience Platform에서 프로필 수 불일치 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26648) | 신규 문서 | 프로필 스냅샷 수가 Adobe Experience Platform(AEP)의 소스 시스템 보기와 다를 때 [!UICONTROL Real-Time Customer Data Platform]&#x200B;(CDP)에서 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEP Offer Decisioning에서 배치 간 캡핑 로직 불일치](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26682) | 신규 문서 | Adobe Experience Platform의 **[!UICONTROL Offer Decisioning]** 기능에서 캡핑 로직이 1:1 메시지와 이메일 배치 사이에서 일관성 없이 작동하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEP: 요청 페이로드가 최대 허용 크기를 초과하여 데이터 수집 오류 발생](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26712) | 신규 문서 | 스트리밍 수집 중 요청이 1MB 제한을 초과할 때 Adobe Experience Platform(AEP)에서 페이로드 크기 오류를 반환하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEP - 서비스 가용성 요청 - [!UICONTROL 스트리밍 수집 API]](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26456) | 신규 문서 | Adobe Experience Platform 내에서 [!UICONTROL 스트리밍 수집 API &#x200B;]의 서비스 가용성에 관한 문의 사항에 대해 알아봅니다. |
| 2025년 5월 | [AEP -  [!DNL Microsoft Dynamics] 소스 커넥터](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26458)를 통한 데이터 수집 필터링 | 신규 문서 | 기본 소스 커넥터를 사용하여 [!DNL Microsoft Dynamics]에서 특정 데이터를 필터링하려는 경우 AEP 사용자가 문제를 겪을 때의 해결 방법에 대해 알아봅니다. |

+++

## [!DNL Real-Time CDP] {#rtcdp}

[!DNL Real-Time CDP]에 대한 최신 튜토리얼을 살펴보십시오.

+++새로운 튜토리얼

| 게시일 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- |---------- |
| 2025년 6월 | [세그먼트 매치 수신 데이터](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/audiences/segment-match-receiving-data) | 새 비디오 | 세그먼트 일치 기능을 사용하면 전략적 파트너가 데이터를 공유할 수 있습니다. 이 비디오에서는 데이터를 승인하고 수신하는 방법 및 데이터를 보고 고유한 세그먼트에 추가할 수 있는 위치에 대해 알아봅니다. |
| 2025년 6월 | [세그먼트 매치 연결 설정](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/audiences/segment-match-connection-setup) | 새 비디오 | 대상자를 공유할 수 있도록 귀하와 파트너 간의 연결을 설정하는 방법에 대해 알아보십시오. 이 세그먼트 일치 기능을 구성한 후 데이터 파트너와 데이터를 주고받을 수 있습니다. |
| 2025년 6월 | [세그먼트 매치 구성 플로우](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/audiences/segment-match-configuration-flow) | 새 비디오 | 데이터 파트너와의 세그먼트 공유가 연결되면 파트너와 데이터 공유를 탐색하고 시작할 수 있습니다. 이 비디오는 데이터 공유를 위한 세그먼트 매치 인스턴스를 구성하는 과정을 안내합니다. |

자세한 내용은 다음 문서를 참조하십시오.

* 비디오 튜토리얼: [Real-Time Customer Data Platform 이해](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform)

* 제품 설명서: [Real-Time Customer Data Platform](https://experienceleague.adobe.com/ko/docs/real-time-customer-data-platform)

+++

## [!DNL Analytics] {#analytics}

[!DNL Adobe Analytics] 및 [!DNL AppMeasurement]에 대한 최신 릴리스 정보를 살펴보십시오. 새로운 튜토리얼 및 지원 문서를 확인합니다.

+++릴리스 정보 및 새로운 튜토리얼

[!DNL Analytics] 릴리스 일자: **2025년 6월 18일**

* [!DNL Analytics] [릴리스 정보](https://experienceleague.adobe.com/ko/docs/analytics/release-notes/latest)

* [!DNL Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/analytics)

### AppMeasurement {#appm}

* [JavaScript용 AppMeasurement 릴리스 정보](https://github.com/adobe/appmeasurement/releases)

<!-- ### New Analytics tutorials {#tutorials-analytics}

New or updated video tutorials published for Adobe Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2025|[Configure variables in Report Suite Manager](https://experienceleague.adobe.com/ko/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-variables-in-the-admin-console)| New video |Configure variables and events in [!UICONTROL Report Suite Manager], ensuring that the reports, dimensions, and metrics have the right names and behavior.| -->

### 새 [!DNL Analytics] 지원 기술 자료{#kb-analytics}

[!DNL Analytics]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|--------|---------|---------|
| 2025년 5월 | [분석 공유 대상자가 **[!UICONTROL 대상 라이브러리]**&#x200B;에서 데이터 수집 중으로 표시](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26635) | 신규 문서 | 사용자 정의 변수에 대해 데이터가 수집되지 않을 때 문제에 대한 해결 방법을 알아봅니다(예: `eVar1`). 이 값은 **[!UICONTROL Analysis Workspace]** 자유 형식 테이블에 “`未指定`”으로 표시됩니다. |
| 2025년 5월 | [Adobe Analytics 및 CJA에서  [!DNL iPhone] 에 대한 모바일 디바이스 모델 추적](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26568) | 신규 문서 | Adobe Analytics 및 CJA에서 [!DNL iPhone]에 대한 모바일 디바이스 모델 추적에 대해 알아봅니다. |
| 2025년 5월 | [`Contains` 연산자가 너무 많으면 세그먼트 오작동](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-25262) | 신규 문서 | 너무 많은 `Contains` 연산자로 인해 세그먼트가 잘못 작동하는 문제에 대한 해결 방법을 알아봅니다. |

+++

## [!DNL Customer Journey Analytics] {#cja}

[!DNL Customer Journey Analytics]에 대한 최신 릴리스 정보를 살펴보십시오. 새로운 Experience League 튜토리얼을 살펴보십시오.

+++릴리스 정보 및 새로운 튜토리얼

* [릴리스 정보](https://experienceleague.adobe.com/ko/docs/analytics-platform/using/releases/latest#releases)

  [!DNL Customer Journey Analytics]에 대한 릴리스는 지속적으로 이루어집니다. 따라서 릴리스 정보는 매달 여러 차례 업데이트됩니다. 이들 릴리스 정보를 정기적으로 확인하십시오.

* [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics)

### 새로운 [!DNL Customer Journey Analytics] 튜토리얼 {#tutorials-cja}

새로운 [!DNL Customer Journey Analytics] 튜토리얼이 게시되었습니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2025년 6월 | [Data Insights 에이전트 소개](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/data-insights-agent/introduction-to-the-data-insights-agent) | 새 비디오 | Customer Journey Analytics에서 Data Insights 에이전트에 대해 알아봅니다. 이 AI 기반 솔루션은 마케터에게 즉각적이고 투명한 인사이트를 제공하여 기업의 병목 현상을 해소합니다. |
| 2025년 6월 | [Data Insights 에이전트 사용](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/data-insights-agent/use-the-data-insights-agent) | 새 비디오 | 자연어 프롬프트를 사용하여 데이터를 분석하고, 자유 형식 테이블, 시각화 및 데이터 비교를 생성하여 데이터 분석가에 대한 의존도를 줄입니다. |
| 2025년 6월 | [Data Insights 에이전트 사용 사례](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/data-insights-agent/data-insights-agent-use-cases) | 새 비디오 | 자연어 쿼리, 실시간 시각화, 자유 형식 테이블을 사용하여 분석을 간소화합니다. 마케팅 전략 개발, 캠페인 관리, 비즈니스 성과 보고 전반에 걸쳐 효율성을 높입니다. |
| 2025년 6월 | [콘텐츠 분석 - 구성 만들기](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/content-analytics/create-configuration) | 새 비디오 | 안내가 있는 콘텐츠 분석 워크플로를 사용하는 방법을 알아봅니다. 마케터의 설정 프로세스를 간소화하여 Customer Journey Analytics에서 효율적인 데이터 수집, 처리 및 보고가 가능합니다. |
| 2025년 6월 | [자유 형식 패널에 구성 요소 추가](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/panels/add-components-to-the-freeform-panel) | 새 비디오 | 자유 형식 패널을 사용하여 유연한 드래그 앤 드롭 인터페이스를 통해 고객 경험 데이터를 탐색하고 비교하며 상관관계를 분석합니다. |
| 2025년 6월 | [콘텐츠 분석 - 구성 편집](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/content-analytics/edit-configuration) | 새 비디오 | 이름, 데이터 보기, 경험 캡처 설정을 조정하여 콘텐츠 분석 구성을 효율적으로 편집합니다. 이 액션은 자동으로 지표를 업데이트하고 콘텐츠 분석 태그 확장 기능을 통해 세부 조정을 수행하여 인사이트를 최적화합니다. |
| 2025년 6월 | [권한 설정](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics-learn/tutorials/access-control/set-up-permissions) | 새 비디오 | Customer Journey Analytics에서 역할 기반 권한을 설정하는 방법을 알아봅니다. 사용자 할당, 제품 프로필 구성, 액세스 수준 관리 방법을 알아봅니다. 데이터 보기 내 세그먼트를 사용하여 행 수준 및 지표 수준 필터링과 같이 세분화된 데이터 제어를 적용하는 방법 살펴보기 |

+++

## [!DNL Streaming Media Analytics] {#sma}

[!DNL Streaming Media Analytics]에 대한 최신 릴리스 정보를 살펴보십시오. 새로운 Experience League 튜토리얼을 살펴보십시오.

+++릴리스 정보

업데이트되지 않았습니다.

* [!DNL Streaming Media Analytics] [릴리스 정보](https://experienceleague.adobe.com/ko/docs/media-analytics/using/release-notes/release-notes)

* [!DNL Streaming Media Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/media-analytics/using/media-overview)

+++

## [!DNL Experience Manager] {#aem}

[!DNL Experience Manager]의 새로운 기능, 수정 내용 및 업데이트. Adobe는 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 고객의 경우 온프레미스 배포를 사용할 것을 권장합니다.

+++릴리스 정보, 새로운 튜토리얼 및 지원 문서

### Experience Manager 릴리스 정보

[!DNL Experience Manager as a Cloud Service] 유지 관리 릴리스 [2025.6.0](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current).

예정 릴리스: **2025년 6월 26일**.

모든 [!DNL Experience Manager] 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [as a Cloud Service [!DNL Experience Manager] 최신 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)
* [최신 릴리스 개요 비디오](https://experienceleague.adobe.com/ko/docs/events/aemcs-release-update-recordings/overview)
* [[!DNL Experience Manager] 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/ko/docs/experience-manager-release-information/aem-release-updates/home)
* [[!DNL Experience Manager] 6.5 서비스 팩 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-65/content/release-notes/release-notes)
* [[!DNL Experience Manager] Cloud Manager 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-manager/content/release-notes/current)
* [Automated Forms Conversion Service 릴리스 정보](https://experienceleague.adobe.com/ko/docs/aem-forms-automated-conversion-service/using/release-notes)
* [[!DNL Experience Manager] Assets Dynamic Media 릴리스 정보](https://experienceleague.adobe.com/ko/docs/dynamic-media-developer-resources/release-notes/s7rn2017)
* [[!DNL Experience Manager] Brand Portal 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes)
* [[!DNL Experience Manager] 데스크탑 앱 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-desktop-app/using/release-notes)
* [[!DNL Experience Manager] Dispatcher 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-manager-dispatcher/using/getting-started/release-notes)

### 새로운 [!DNL Experience Manager] 튜토리얼 {#tutorials-aem}

[!DNL Experience Manager]에 새로운 [!DNL Experience Manager] 튜토리얼이 게시되었습니다.

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025년 6월 | [!DNL Experience Manager] | [경험 최적화 및 가치 실현](https://experienceleague.adobe.com/ko/playlists/experience-manager-all-experience-optimization-and-value-realization) | 새 비디오 | Adobe Summit 2025의 짧은 클립. |
| 2025년 6월 | [!DNL Experience Manager] | [Experience Manager의 생성형 AI 및 AI 기반 혁신](https://experienceleague.adobe.com/ko/playlists/experience-manager-all-gen-ai-driven-innovations) | 새 비디오 | Adobe Summit 2025의 짧은 클립. |
| 2025년 6월 | [!DNL Experience Manager Assets] | [투명성과 콘텐츠 자동화 일괄 처리를 위한 Dynamic Media](https://experienceleague.adobe.com/ko/docs/experience-manager-learn/assets/dynamic-media/images/dynamic-media-image-automation) | 새 비디오 | AEM에서 Dynamic Media를 사용하여 가상 렌디션을 만들고, 투명성을 관리하며, 확장 가능한 콘텐츠 재사용을 위해 이미지 처리를 자동화하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Experience Manager Sites] | [ [!DNL Sites]에서 라이브 작성 안내서 만들기](https://experienceleague.adobe.com/ko/docs/experience-manager-learn/sites/expert-resources/authoring-guide-in-sites) | 새 비디오 | AEM 챔피언 Brett Birschbach가 Adobe Experience Manager(AEM) 사이트에서 라이브 작성 안내서를 구축하기 위한 모범 사례를 공유합니다. |

### 새 [!DNL Experience Manager] 지원 기술 자료{#kb-aem}

[!DNL Experience Manager]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|--------|---------|---------|
| 2025년 5월 | [ [!DNL Adobe Cloud Manager]에서 SSL 인증서 만료 검색 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26339) | 신규 문서 | [!DNL Adobe Cloud Manager] API를 사용하여 SSL 인증서 만료일을 검색할 때, API 엔드포인트의 부적절한 사용과 도메인 매핑 및 인증서 간의 링크 누락으로 인해 프로세스가 중단되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM에서 동시 사용자 로그인 제한 불가](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26398) | 신규 문서 | Adobe Experience Manager(AEM)에서 동시 로그인 제한이 없는 문제를 해결하기 위한 해결 방법을 알아봅니다. |
| 2025년 5월 | [ [!DNL Adobe Experience Manager]에서 여러 [!UICONTROL ID 공급자]와의 인증 실패 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26441) | 신규 문서 | 여러 [!UICONTROL ID 제공자]&#x200B;(IDP)를 Adobe Experience Manager(AEM)에 통합할 때 사용자가 인증에 실패하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM 6.5.21의 저장된 크로스 사이트 스크립팅(XSS) 취약점](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26452) | 신규 문서 | Adobe Experience Manager(AEM) 버전 6.5.21 및 이전 버전에서 저장된 크로스 사이트 스크립팅(XSS) 취약점(**[!DNL CWE-79]**)으로 특징지어지는 보안 취약점인 **[!DNL CVE-2024-43726]**&#x200B;에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [[!DNL AI] AEM Guides에 지원이 표시되지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26453) | 신규 문서 | Adobe Experience Manager(AEM) Guides 내에서 [!DNL AI] 지원 기능을 사용할 수 없는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [PDF 파일에 대한 AEM 환경 전반의 [!DNL Scene7] 자산 이름 불일치 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26461) | 신규 문서 | PDF 처리 설정의 차이로 인해 AEM 환경에서 PDF 자산의 이름이 서로 다른 [!DNL Scene7] 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [ [!DNL ACS Commons] Query Packager](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26575)를 사용하여 콘텐츠 델타 마이그레이션 | 신규 문서 | Adobe Experience Manager(AEM)를 업그레이드하거나 마이그레이션할 때 이 문제에 대한 해결 방법을 알아봅니다. 업데이트된 태그, 자산 또는 페이지와 같이 변경된 콘텐츠만 이동하면 됩니다. |
| 2025년 5월 | [AEM as a Cloud Service에서 대용량 MP4 파일에 대한 자산 처리 실패](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26610) | 신규 문서 | 대용량 MP4 비디오 파일(~6.8 GB)을 Adobe Experience Manager(AEM) as a Cloud Service에 업로드할 때 *자산 처리 실패* 오류가 발생하는 경우의 해결 방법을 알아봅니다. |
| 2025년 5월 | [ [!DNL TIFF] Dynamic Media의 이미지 렌디션](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26637)에 대한 배경색 변경 문제 | 신규 문서 | Dynamic Media API 매개변수(예: `bgc`, `clippathe`, `croppathe`)를 사용할 때 Dynamic Media 배경색 변경 사항이 [!DNL TIFF] 이미지 렌디션에 적용되지 않는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [[!DNL OAuth] 기반 클라이언트 자격 증명 회전이 [!UICONTROL 작성자]에서는 작동하지만 [!UICONTROL 게시]에서는 작동하지 않습니다.](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26706) | 신규 문서 | Adobe Experience Manager(AEM) Forms에서 [!DNL OAuth] 클라이언트 자격 증명을 회전할 때, [!UICONTROL 작성자]에서 작동하지만 [!UICONTROL 게시] 인스턴스에서 인증이 실패하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | AEM 서비스 팩 21 업그레이드 후 [빈 페이지와 *확인되지 않은 SlingException* 오류](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26321) | 신규 문서 | Adobe Experience Manager(AEM)를 서비스 팩 21(버전 6.5.21)로 업그레이드한 후 [!UICONTROL 게시자] 인스턴스에 빈 페이지가 표시되고 *확인되지 않은 SlingException* 오류가 로그에 기록되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM에서 **[!UICONTROL PDFG]** 및 **[!UICONTROL PageOverlay]**&#x200B;를 사용하여 Word에서 PDF로 변환할 때 하이퍼링크 누락](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26343) | 신규 문서 | AEM **[!UICONTROL PDFG]** 서비스를 사용하여 [!UICONTROL 어셈블러 서비스]의 **[!UICONTROL PageOverlay]** 옵션을 사용하여 워드 문서를 PDF로 변환할 때 발생하는 문제에 대한 해결 방법을 알아봅니다. 결과 PDF에 하이퍼링크가 나타나지 않습니다. |
| 2025년 5월 | [Adobe Experience Manager 6.5 Dynamic Media의 **[!UICONTROL 스마트 자르기]**&#x200B;로 인해 손상된 이미지 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26367) | 신규 문서 | Adobe Experience Manager 6.5 Dynamic Media에서 **[!UICONTROL 스마트 자르기]** 버튼을 클릭하면 깨진 이미지가 표시되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM Sites에서 **[!UICONTROL 수정됨]** 열을 기준으로 정렬할 때 *데이터 로드 실패* 오류 수정](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26443) | 신규 문서 | Adobe Experience Manager(AEM) Sites에서 **[!UICONTROL 수정됨]** 열을 기준으로 콘텐츠를 정렬할 때 *데이터 로드 실패* 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM의 비디오 업로드, 처리 및 렌더링 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26533) | 신규 문서 | Adobe Experience Manager(AEM)에서 과도한 비디오 길이, 일치하지 않는 인코딩 사전 설정 또는 Dynamic Media 워크플로 시간 초과와 같은 문제로 인해 비디오 업로드, 처리, 게시 또는 렌더링 중에 실패하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [업그레이드 후 AEM [!DNL Forms Designer] 6.5가 열리지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26558) | 신규 문서 | 업그레이드 후 Adobe Experience Manager(AEM) [!DNL Forms Designer] 6.5가 열리지 않고 *애플리케이션을 올바르게 시작할 수 없습니다(0xc000007b)*&#x200B;라는 오류가 발생하여 제거할 수 없는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [서비스 팩 업그레이드 후 AEM Forms에 표시되는 숨겨진 필드 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26532) | 신규 문서 | 서비스 팩 업그레이드 후 Adobe Experience Manager(AEM) Forms에서 숨겨진 필드가 표시되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [내부 네트워크를 통한 AEM 신속한 개발 환경의 연결 문제](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26315) | 신규 문서 | Adobe Experience Manager(AEM) as a Cloud Service를 사용하면 VPN 또는 내부 네트워크를 통해 신속한 개발 환경(RDE)에 액세스할 때 연결 문제가 발생하는 경우의 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM Cloud Services Dispatcher의 `auth_checker` 구성 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26392) | 신규 문서 | Adobe Experience Manager(AEM) Cloud Services Dispatcher의 `auth_checker` 구성으로 Dispatcher 코드를 배포할 때 유효성 검사 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [*403 금지* 오류로 인해 Adobe CLI에 연결할 수 없음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26412) | 신규 문서 | Adobe Experience Manager(AEM) as a Cloud Service에서 Cloud Manager API를 통해 프로그램을 검색할 때 발생하는 문제에 대한 해결 방법에 대해 알아봅니다. *403 금지* 오류가 발생합니다. |
| 2025년 5월 | [Edge Delivery Services Sites에서 올바른 AEM **스테이징**/**프로덕션** 콘텐츠가 렌더링되지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26425) | 신규 문서 | Adobe Experience Manager (AEM) as a Cloud Service의 저장소 없는 구성에서 Edge Delivery Services(EDS)를 사용할 때 렌더링된 콘텐츠가 **스테이징** 및 **프로덕션** 환경에서 예상대로 표시되지 않는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEMaaCS에서 중첩된 Adobe I/O 웹 액션 인증 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26427) | 신규 문서 | 인증이 필요한 경우 다른 웹 액션 내에서 Adobe I/O 웹 액션을 호출할 때 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEMaaCS에서 기술 계정을 생성할 때 발생하는 *HTTP 403* 오류 수정](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26431) | 신규 문서 | Adobe Experience Manager as a Cloud Service(AEMaaCS)에서 *HTTP 403* 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Photoshop Firefly API 통합을 위한 단일 파트 자산 업로드 제한 증가](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26450) | 신규 문서 | Photoshop Firefly에서 Adobe Experience Manager as a Cloud Service(AEMaaCS)로 100MB보다 큰 자산을 업로드하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Experience Manager에서 도메인 유효성 검사(DV) SSL 인증서 유효성 검사 보류](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26472) | 신규 문서 | 도메인 유효성 검사(DV) SSL 인증서가 ACME 유효성 검사에 성공했음에도 불구하고 *보류 중* 상태에 있는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Experience Manager에서 콘텐츠 조각 액세스 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26500) | 신규 문서 | Adobe Experience Manager as a Cloud Service - Sites의 콘텐츠 조각이 잘못된 저장소 구성 및 외부화 설정으로 인해 **개발**, **스테이징**, **프로덕션** 환경에서 액세스할 수 없는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [*도메인이 사용 중입니다.* AEM as a Cloud Service에서 관련 도메인 매핑을 먼저 삭제해 주십시오](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26525) 오류 | 신규 문서 | *도메인이 아직 사용 중입니다. Adobe Experience Manager(AEM) as a Cloud Service에서 관련 도메인 매핑을 먼저 삭제해 주십시오* 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM as a Cloud Service로 캐시 키 삭제를 구성할 때 인증되지 않은 삭제 오류](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26526) | 신규 문서 | Adobe Experience Manager (AEM) as a Cloud Service에서 캐시 키 삭제를 구성할 때 *인증되지 않은 삭제. 삭제 키를 얻으려면 고객 지원에 문의하십시오* 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEMaaCS 자산 회전 문제로 인해 후속 회전이 보이지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26528) | 신규 문서 | Adobe Experience Manager as a Cloud Service(AEMaaCS) - Assets에서 이미지 자산을 회전할 때 발생하는 문제에 대한 해결 방법을 알아봅니다. 자산이 첫 번째 회전만 즉시 표시되고, 이후의 회전은 백그라운드 자산 처리 워크플로로 인해 표시되지 않습니다. |
| 2025년 5월 | [AEMaaCS에서 페이지를 게시 취소할 수 없음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26551) | 신규 문서 | Adobe Experience Manager as a Cloud Service(AEMaaCS)의 페이지가 게시 취소되거나 삭제된 후에도 다른 페이지를 가리키는 사용자 정의 URL 또는 별칭으로 인해 액세스할 수 있는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM as a Cloud Service에서 전용 송신 IP로 인한 연결 시간 초과 오류 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26556) | 신규 문서 | Adobe Experience Manager as a Cloud Service(AEMaaCS)에서 전용 송신 IP를 구성하여 외부 API 호출을 안전하게 라우팅할 때 연결 시간 초과 오류가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM Developer Console에서 게시 인스턴스에 대한 저장소 브라우저 가시성 문제](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26599) | 신규 문서 | Adobe Experience Manager(AEM) as a Cloud Service - Sites의 **게시** 인스턴스에 대해 개발자 콘솔에서 저장소 브라우저가 누락되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [IP 허용 목록으로 인해 AEMaaCS에서 UI 테스트 실패](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26654) | 신규 문서 | 엔드투엔드 또는 UI 테스트 중 파이프라인 액세스를 차단하는 AEM **작성자** 및 **게시** 서버의 IP 제한 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEMaaCS에서 관리자가 아닌 사용자의 메타데이터 스키마 가시성 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26655) | 신규 문서 | AEM as a Cloud Service(AEMaaCS) - Assets, 기여자 또는 디지털 액세스 관리(DAM)와 같은 사용자가 스키마 폴더에 대한 읽기 권한이 없어 사용자 정의 메타데이터 스키마를 볼 수 없는(관리자는 볼 수 있음) 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM 빌드에서 `jcr:mixinTypes ValueFormatException` 수정](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26660) | 신규 문서 | 오래된 `org.apache.sling.jcr.repoinit` 번들로 인해 Adobe Experience Manager(AEM) as a Cloud Service의 파이프라인 빌드가 실패할 때 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM as a Cloud Service에 대한 RTO 및 RPO 이해](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26664) | 신규 문서 | AEM Cloud의 복구 시간 목표(RTO)와 복구 지점 목표(RPO)에 대해 알아봅니다. |
| 2025년 5월 | [AEMaaCS 파이프라인 빌드 중 간헐적인 StackOverflow 오류 발생](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26669) | 신규 문서 | 클라우드 공급자 간의 일관성 없는 종속성 해결로 인해 Adobe Experience Manager as a Cloud Service(AEMaaCS) 빌드 단계에서 *StackOverflowError*&#x200B;가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM Managed Services에서 사전 설정 편집기가 빈 화면 표시](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26643) | 신규 문서 | Adobe Experience Manager(AEM)에서 **[!UICONTROL 이미지 사전 설정 편집기]** 및 **[!UICONTROL 뷰어 사전 설정 편집기]**&#x200B;가 로드되지 않고 빈 화면 또는 끝없는 로딩 회전기가 표시되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [AEM의 DMC(Dynamic Media Classic)에서 PDF 및 AI 자산 처리 실패](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26636) | 신규 문서 | DMS7 측이나 DMC UI에서 PDF 처리에 실패할 경우 발생하는 문제에 대한 해결 방법을 알아봅니다. |

+++

## [!DNL Commerce] {#commerce}

[!DNL Adobe Commerce]에 대한 릴리스 정보, 새로운 튜토리얼과 기술 자료 지원 문서를 이용할 수 있습니다.

+++릴리스 정보, 새로운 튜토리얼 및 지원 문서

* 최신 정보는 [ [!DNL Adobe Commerce] 및 [!DNL Magento Open Source]의 릴리스 정보](https://experienceleague.adobe.com/ko/docs/commerce-operations/release/notes/overview)를 참조하십시오.
* Commerce Services 릴리스 정보 및 설명서를 보려면 [Adobe [!DNL Commerce] Services 안내서](https://experienceleague.adobe.com/ko/docs/commerce/user-guides/home)를 참조하십시오.
* 개별 제품 릴리스 정보에 액세스하고 사용 가능 여부를 확인하려면 [제품 가용성](https://experienceleague.adobe.com/ko/docs/commerce-operations/release/product-availability)을 참조하십시오.

### [!DNL Adobe Commerce]에 대한 새로운 튜토리얼 {#tutorials-commerce}

Experience League의 새로운 [!DNL Adobe Commerce] 튜토리얼입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2025년 6월 | [신규 제품 공지](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/webinars-and-events/future-of-commerce/new-product-announcements) | 새 비디오 | Adobe Commerce as a Cloud Service와 Adobe Commerce Optimizer에 대해 알아봅니다. |
| 2025년 6월 | [공동 책임](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/shared-responsibility) | 새 비디오 | Adobe와 판매자가 Adobe Commerce Cloud의 보안을 유지하기 위해 어떤 책임을 공유하는지 알아봅니다. |
| 2025년 6월 | [슈퍼차지 전환율](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/webinars-and-events/future-of-commerce/supercharge-conversion-rates) | 새 비디오 | Adobe Commerce가 전자 상거래 성과를 향상시키기 위해 설계된 다양한 기능과 도구를 어떻게 제공하는지 알아봅니다. |
| 2025년 6월 | [대폭적인 비용 절감](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/webinars-and-events/future-of-commerce/drastically-cut-costs) | 새 비디오 | Adobe Commerce as a Cloud service로 비용을 대폭 절감할 수 있는 방법을 알아봅니다. |
| 2025년 6월 | [빠른 확장](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/webinars-and-events/future-of-commerce/fast-track-expansion) | 새 비디오 | Adobe Commerce의 확장 가능한 카탈로그, B2B 도구 및 다중 채널 확장 기능을 통해 디지털 성장을 빠르게 추적하십시오. |
| 2025년 6월 | [Adobe Commerce의 HIPAA 지원 호스팅](https://experienceleague.adobe.com/ko/docs/commerce-learn/tutorials/adobe-commerce-cloud/hippa-ready-hosting) | 새 비디오 | HIPPA 지원 호스팅에 대해 알아봅니다. Adobe Commerce의 HIPAA 지원 솔루션은 헬스 케어 비즈니스를 위해 안전하면서 규정을 준수하는 전자 상거래를 보장합니다. |

### 새 [!DNL Commerce] 지원 기술 자료{#kb-commerce}

Adobe Commerce에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|--------|---------|---------|
| 2025년 5월 | [[!DNL Quality Patches Tool] (QPT)](https://experienceleague.adobe.com/ko/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | 신규 문서 | QPT 1.1.62, QPT 1.1.63 및 QPT 1.1.64에서 사용할 수 있는 패치를 적용하는 방법에 대한 새로운 문서가 게시되었으며 해당 섹션에서 찾을 수 있습니다. |
| 2025년 5월 | [GraphQL을 통해 노출되는 고객 그룹 이름, 세그먼트 및 프로모션 규칙 정보](https://experienceleague.adobe.com/ko/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/hotfix-for-exposed-customer-group-segments-promo-rules-information) | 신규 문서 | 이 문서에서는 GraphQL을 통해 고객 그룹 이름, 고객 세그먼트 및 프로모션 규칙 정보가 노출되는 것을 방지하기 위한 핫픽스를 제공합니다. |
| 2025년 5월 | [[!DNL Cron] 클라우드 인프라의 Adobe Commerce에서 색인 문제](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26409) | 신규 문서 | [!DNL cron]을 통한 자동 색인화 문제가 반복적으로 발생하여 매장 운영이 중단되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [클라우드 인프라의 Adobe Commerce에서 발생하는 그리드 액세스 오류 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26440) | 신규 문서 | 클라우드 인프라의 Adobe Commerce에서 그리드 기반 페이지를 탐색할 때 발생하는 오류 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [클라우드 인프라 배포 중 Adobe Commerce 확장 기능 다운로드 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26600) | 신규 문서 | 서로 다른 계정의 [!DNL Composer] 인증 키가 확장 기능 또는 상거래 코드에 액세스할 수 있지만 둘 다 액세스할 수 없는 경우 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [클라우드 인프라의 Adobe Commerce에서 과금 명세서에 액세스하고 코드베이스를 다운로드할 수 없음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26611) | 신규 문서 | 판매자가 최신 과금 청구서에 액세스하고 클라우드 인프라 버전에서 최신 Adobe Commerce의 공식 릴리스를 다운로드하는 데 겪는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [클라우드 인프라의 Adobe Commerce에서 서비스가 업그레이드되지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26668) | 신규 문서 | `services.yaml` 파일에 정의된 서비스 구성 변경 사항이 클라우드 인프라의 Adobe Commerce에서 **프로덕션** 및 **스테이징** 클러스터에서 적용되지 않는 문제에 대한 해결 방법을 알아봅니다. |

+++

## [!DNL Target] {#target}

프리릴리스 정보, 최신 릴리스 정보 및 [!DNL Adobe Target]의 새로운 튜토리얼을 이용할 수 있습니다.

+++릴리스 정보

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* 프리릴리스에 대한 자세한 내용은 [[!DNL Adobe Target] 프리릴리스](https://experienceleague.adobe.com/ko/docs/target/using/release-notes/target-release-notes)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [[!DNL Adobe Target] 릴리스 정보](https://experienceleague.adobe.com/ko/docs/target/using/release-notes/release-notes)를 참조하십시오.

+++

## [!DNL Campaign] {#ac}

[!DNL Adobe Campaign]의 최신 업데이트를 다운로드합니다. Experience League에서 새로운 튜토리얼과 기술 자료 지원 문서를 살펴보십시오.

+++릴리스 정보 및 지원 문서

### 최신 Campaign 제품 릴리스

* [!DNL Web User Interface]: 2025년 5월 - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8: 2025년 4월 - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/releases/release-notes#release-8-7-4) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Standard]: 25.1 - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/campaign-standard-home)

* [!DNL Campaign Classic] 7.4.2: 2025년 5월 12일 - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/release-notes/latest-release#release-7-4-2) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/campaign-classic-home)

### 새로운 [!DNL Campaign] 튜토리얼 {#tutorials-campaign}

Adobe Campaign용으로 게시된 새로운 또는 업데이트된 비디오 튜토리얼

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025년 6월 | | [콘텐츠 생성용 AI 어시스턴트를 사용하여 콘텐츠 만들기](https://experienceleague.adobe.com/ko/docs/campaign-web-learn/tutorials/messages-and-deliveries/create-content-using-the-ai-assistant) | 새 비디오 | Adobe의 AI 어시스턴트 콘텐츠 가속기를 사용하여 제목 줄, 본문 텍스트 및 이미지를 포함하는 마케팅 이메일을 생성하고 맞춤 설정하며 일관성과 규정 준수를 위해 브랜드 승인 자산을 통합하는 방법에 대해 알아봅니다. |

### 새 [!DNL Campaign] 지원 기술 자료{#kb-campaign}

[!DNL Campaign]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2025년 5월 | [**[!UICONTROL Adobe Campaign Classic의 데이터베이스 구조 업데이트&#x200B;]**&#x200B;마법사가 스키마를 표시하지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26407) | 신규 문서 | Adobe Campaign Classic에서 **[!UICONTROL 데이터베이스 구조 업데이트]** 마법사를 사용할 때 발생하는 문제에 대한 해결 방법을 알아봅니다. 외부 데이터베이스에 연결된 스키마가 표시되지 않습니다. |
| 2025년 5월 | [Adobe Campaign Managed Cloud의 스케줄러 설정에도 불구하고 워크플로가 예기치 않게 실행됨](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26415) | 신규 문서 | Adobe Campaign Managed Cloud에서 스케줄러 업데이트가 적용되지 않고 예기치 않은 워크플로 실행이 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Campaign Classic에서 타기팅 및 워크플로 탭을 볼 수 없음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26632) | 신규 문서 | Adobe Campaign Classic에서 **[!UICONTROL 타기팅 및 워크플로]** 탭이 표시되지 않는 경우 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Campaign Standard **[!UICONTROL 동적 보고서]**&#x200B;의 10,000개 레코드 제한으로 인해 게재 통계 필터가 작동하지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26697) | 신규 문서 | 게재 통계 **[!UICONTROL 다음 포함]** 필터가 특정 키워드를 적용했을 때 전체 결과를 반환하지 않는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Campaign Classic에서 게재 활동 후 수신자 수가 감소](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26446) | 신규 문서 | 게재 활동 후 기록 수가 감소하는 문제에 대한 해결 방법을 알아봅니다. |

+++

## [!DNL Journey Optimizer] {#journey-opt}

[!DNL Journey Optimizer]의 최신 릴리스 정보에 대해 알아봅니다. Experience League에서 최신 튜토리얼과 기술 자료 지원 문서를 살펴보십시오.

+++릴리스 정보 및 새로운 튜토리얼

### [!DNL Journey Optimizer] 제품 릴리스 업데이트

최근 릴리스: **2025년 6월**

* 업데이트 및 도움말은 [Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes)를 참조하십시오.

**참고:** [Journey Optimizer for B2B Edition](#journey-optimizer-b2b-edition)는 별도 제품입니다.

### 새로운 [!DNL Journey Optimizer] 튜토리얼 {#tutorials-ajo}

Experience League에 새로운 Adobe [!DNL Journey Optimizer] 튜토리얼이 게시되었습니다.

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2025년 6월 | [!DNL Journey Optimizer] | [Adobe Experience Manager 콘텐츠 조각 사용](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/content-management/fragments/aem-content-fragments) | 새 비디오 | Adobe Experience Manager(AEM)를 Adobe Journey Optimizer와 원활하게 통합하여 콘텐츠 관리를 간소화하고 여러 채널에서 브랜드의 일관성을 보장하는 방법을 살펴봅니다. 콘텐츠 조각을 만들고 승인하고 렌더링하고, 간편하게 콘텐츠를 바꾸고 새 콘텐츠를 시뮬레이션하는 방법에 대해 알아봅니다. 효율적인 콘텐츠 관리와 일관된 브랜딩을 원하는 사용자에게 적합합니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [Adobe Experience Manager Dynamic Media 통합](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/content-management/assets/aem-dynamic-media-integration) | 새 비디오 | Adobe Experience Manager Dynamic Media를 Adobe Journey Optimizer와 통합하여 실시간 콘텐츠 업데이트 및 개인화를 활성화하는 방법에 대해 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [사용자 정의 SMS 공급자 구성](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/sms-mms-channel/configure-custom-sms-provider) | 새 비디오 | Adobe Journey Optimizer에서 Sinch, Twilio 또는 Infobip 이외의 SMS 공급자를 구성하고, 인바운드 메시징을 위한 API 자격 증명 및 웹후크를 설정하고, 옵트인/옵트아웃 키워드를 관리하고, 기본 도구 및 사용자 정의 페이로드를 사용하여 개인화된 SMS 캠페인을 시작하는 방법에 대해 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [IP 풀 만들기](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/email-channel/create-ip-pool) | 새 비디오 | 발신자 신뢰도를 보호하고 이메일 전달성을 높이기 위한 IP 풀을 만드는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [하위 도메인 설정](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/email-channel/set-up-subdomain) | 새 비디오 | Adobe Journey Optimizer에서 이메일 채널에 대한 하위 도메인 설정하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [잠재적 충돌 확인](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/conflict-management/identify-potential-conflicts) | 새 비디오 | 중복되는 대상자, 동시 발생 타임라인, 공유된 커뮤니케이션 채널, 여정과 캠페인 전반의 빈도 제한 등 잠재적 갈등을 식별 및 관리하고, 원활하면서 고객 친화적인 커뮤니케이션 경험을 보장하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [여정 상한 설정 및 우선순위 지정](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/conflict-management/journey-frequency-capping-and-prioritization) | 새 비디오 | 동일한 채널 구성을 사용하여 여러 인바운드 액션에 적합할 때 고객에게 최우선 순위의 콘텐츠가 전달되도록 인바운드 액션의 우선순위를 정하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [인바운드 액션에 우선순위 점수 할당](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/conflict-management/assign-priority-score) | 새 비디오 | 동일한 채널 구성을 사용하여 여러 인바운드 액션에 적합할 때 고객에게 최우선 순위의 콘텐츠가 전달되도록 인바운드 액션의 우선순위를 정하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [AEP에서 ID 결합](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorial-on-identity-stitching-in-aep/introduction) | 새 비디오 | Adobe Journey Optimizer(AJO)의 실시간 개인화 및 오퍼 결정을 위한 통합 프로필을 제공하여 알려진 사용자(CRMID)와 익명의 웹 방문자(ECID) 간의 ID 결합을 설정합니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [이메일 채널 구성](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/email-channel/configure-email-channel) | 새 비디오 | Adobe Journey Optimizer.에서 이메일 채널을 구성하는 방법에 대해 알아봅니다. 이 비디오는 하위 도메인, IP 풀, 구독 취소 관리, 발신자 개인화, BCC 및 시드 목록, 재시도 논리, 추적 매개변수 등 이메일 구성 설정 과정을 다룹니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [Adobe Journey Optimizer의 수식 작성기 인터페이스 안내서](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/decision-capabilities/decisioning/formula-builder-ui) | 새 비디오 | 제안, 프로필 또는 컨텍스트와 관련된 조건에 따라 Adobe Decisioning AI 모델의 실시간 점수를 조정하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [사용 사례 설명](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/personalizing-offers-with-real-time-weather-data/introduction) | 신규 문서 | 실시간 상황별 데이터와 Adobe Web SDK 개인화 API를 사용하여 Adobe Journey Optimizer에서 날씨에 따른 동적인 혜택을 제공하는 방법을 알아봅니다. |
| 2025년 6월 | [!DNL Journey Optimizer] | [사용자 우편번호 및 소득을 기반으로 한 순위 공식을 사용하여 오퍼 개인화](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/personalizing-offers-with-ranking-formulas-based-on-user-zip-code-and-income/introduction) | 신규 문서 | 순위 공식을 사용하여 각 사용자의 우편번호와 소득 수준에 맞춰 가장 관련성 높은 금융 혜택을 동적으로 제공하여 참여도를 높이고 더 스마트한 개인화를 실현합니다. |

### 새 [!DNL Journey Optimizer] 지원 기술 자료{#kb-ajo}

[!DNL Journey Optimizer]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2025년 5월 | [AJO에서 게시되지 않은 여정에서 이메일 템플릿과 콘텐츠가 사라짐](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26738) | 신규 문서 | Adobe Journey Optimizer(AJO)에서 게시되지 않은 여정의 이메일 템플릿을 편집할 때 특정 이메일의 콘텐츠와 템플릿이 예기치 않게 사라져 재작업해야 하고 지연이 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Journey Optimizer에서 여러 푸시 토큰이 포함된 프로필](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26457) | 신규 문서 | Adobe Journey Optimizer(AJO)를 사용하여 푸시 알림을 구현할 때 여러 디바이스에서 프로필을 관리하는 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Journey Optimizer에서 대상자 수 불일치 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26297) | 신규 문서 | Adobe Journey Optimizer의 **[!UICONTROL 대상자 읽기]** 기능에서 처리된 항목 수가 예상 대상자 수보다 적을 때 발생하는 문제에 대한 해결 방법을 알아봅니다. |

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [[!DNL Journey Optimizer] 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/ajo-home) - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes) - [사용 방법 비디오](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/overview)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes) - [사용 방법 비디오](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management) - [최신 설명서 업데이트](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

[!DNL Journey Optimizer B2B Edition]의 최신 릴리스 정보에 대해 알아봅니다.

+++릴리스 정보 및 설명서

최신 릴리스: **2025.5**

* [[!DNL Journey Optimizer B2B Edition]](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b)&#x200B;(모든 자체 도움말)
* [!DNL Journey Optimizer B2B Edition]의 [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b/user/release-notes)
* [!DNL Journey Optimizer B2B Edition]의 [제품 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b/user/guide-overview)
* [!DNL Journey Optimizer B2B Edition]에 대한 [비디오 개요 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b-learn/tutorials/overview)
* [!DNL Journey Optimizer B2B Edition] [제품 설명 및 라이선스](https://helpx.adobe.com/kr/legal/product-descriptions/adobe-journey-optimizer-b2b.html#_blankl)

<!-- New videos, tutorials, or courses published for Journey Optimizer B2B Edition.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2025|[Account Journeys](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b-learn/tutorials/account-journeys/introducing-account-journeys)|New videos |Visit the Account Journeys tutorial home. Learn about Account Journeys and how to use them to engage your target audience.|
|February 2025|[Use Case Playbook - Abandoned shopping cart](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/use-cases/abandoned-cart)|New video |Learn how to implement the abandoned shopping cart use case, using the Playbook feature in Adobe Journey Optimizer.|
|February 2025|[Import and activate an audience by uploading a CSV file](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/profiles-audiences-subscriptions/import-and-activate-an-audience-by-uploading-a-csv-file)|New video |Discover how to efficiently import and activate an audience by uploading a CSV file. Learn to personalize your content using enrichment attributes from the CSV file, ensuring a more tailored experience for your audience.| -->

자세한 내용은 다음 문서를 참조하십시오.

* [[!DNL Journey Optimizer B2B Edition]](https://business.adobe.com/products/journey-optimizer-b2b-edition.html)에서 제품 정보를 참조하십시오.

+++

## [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage]의 최신 릴리스 정보와 릴리스 일정을 살펴보십시오.

+++릴리스 정보, 튜토리얼 및 지원 문서

### 주요 Marketo Engage 업데이트

릴리스: **2025년 5월**

* 최신 정보는 [최신 릴리스 정보](https://experienceleague.adobe.com/ko/docs/marketo/using/release-notes/current)를 참조하십시오.
* 최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/ko/docs/marketo/using/release-notes/release-schedule)을 참조하십시오.

<!-- ### New Marketo tutorials {#tutorials-marketo}

New tutorials published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 2025|[Best practices to implement live chat](https://experienceleague.adobe.com/ko/docs/marketo-learn/tutorials/dynamic-chat/live-chat-best-practices)| New video |Learn about the best practices to follow when you're implementing the live chat feature in Dynamic Chat.| -->

최신 제품 설명서를 보려면 [Marketo 제품 설명서](https://experienceleague.adobe.com/ko/docs/marketo/using/home) 홈을 참조하십시오.

### 새 [!DNL Marketo] 지원 기술 자료

[!DNL Marketo]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2025년 5월 | [콘솔에 Marketo Measure 401 오류 메시지](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26569) | 신규 문서 | 스크립트가 검증된 도메인이 아닌 URL에서 활성화를 시도할 때 Marketo Measure에서 *401 인증되지 않은 오류*&#x200B;가 발생하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Marketo Measure의 **[!UICONTROL 전략적 이벤트]** 채널 매핑 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26535) | 신규 문서 | Marketo Measure의 오프라인 터치포인트가 [!DNL Salesforce]&#x200B;(SFDC) 내 채널에 잘못 매핑되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Marketo Measure에서 오프라인 채널 이름 바꾸기](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26444) | 신규 문서 | Marketo Measure에서 오프라인 채널의 이름을 바꾸는 방법에 대해 알아봅니다. |
| 2025년 5월 | [Marketo Measure에서 활동 유형 터치포인트 누락](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26434) | 신규 문서 | 논리 구성의 불일치로 인해 Marketo Measure에 **[!UICONTROL 통화 연결됨]** 및 **[!UICONTROL 회의 완료]**&#x200B;와 같은 활동 터치포인트가 표시되지 않는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Marketo Measure에서 누락된 오프라인 채널 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26397) | 신규 문서 | 구성하는 동안 특정 오프라인 채널이 누락되는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Marketo Measure에서 채널 삭제 문제 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26396) | 신규 문서 | Adobe Marketo Measure에서 채널을 관리할 때 터치포인트나 오프라인 값에 연결된 채널은 삭제할 수 없는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Marketo Measure에서 단일 캠페인에 대한 여러 터치포인트 생성 해결](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26359) | 신규 문서 | Marketo Measure에서 단일 이메일 주소에 대해 터치포인트 중복되는 문제를 해결하는 방법을 알아봅니다. |

+++

## [!DNL Workfront] {#workfront}

[!DNL Adobe Workfront]의 최신 릴리스 정보에 대해 알아봅니다. 새로운 Experience League 튜토리얼을 살펴보십시오.

+++릴리스 정보 및 새로운 튜토리얼

### [!DNL Adobe Workfront] 업데이트

* [2025년 2분기 릴리스 개요](https://experienceleague.adobe.com/ko/docs/workfront/using/product-announcements/product-releases/release-25-q2/25-q2-release-overview)

모든 릴리스 정보는 다음과 같습니다.

* [!DNL Workfront] 릴리스 일정 정보 및 릴리스 정보는 [Adobe [!DNL Workfront] 제품 릴리스](https://experienceleague.adobe.com/ko/docs/workfront/using/product-announcements/product-releases/product-releases) 페이지를 참조하십시오.

* Fusion에 대한 최신 정보는 [Adobe [!DNL Workfront] Fusion 릴리스 활동 개요](https://experienceleague.adobe.com/ko/docs/workfront-fusion/using/fusion-release-activity/fusion-release-activity)를 참조하십시오.

### 새로운 Adobe [!DNL Workfront] 튜토리얼 {#tutorials-workfront}

Experience League의 새로운 [!DNL Workfront] 튜토리얼 및 이벤트

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2025년 6월 | [보고서 복사](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/copy-a-report) | 새 비디오 | 유사한 보고서를 복사 및 편집하여 새 보고서를 신속하게 만드는 방법을 알아봅니다. |
| 2025년 6월 | [기본 필터 활동 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-filter-activity) | 신규 문서 | 이 활동에서는 “마케팅 포트폴리오의 모든 프로젝트”라는 기존 필터 환경의 프로젝트 필터를 만듭니다. 그러면 상태에 상관없이 “마케팅 포트폴리오”라는 포트폴리오의 모든 프로젝트가 표시됩니다. |
| 2025년 6월 | [매트릭스 보고서 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-matrix-report) | 새 비디오 | Workfront에서 매트릭스 보고서가 유용할 수 있는 경우 및 매트릭스 보고서를 만드는 방법을 알아봅니다. |
| 2025년 6월 | [보고서 보내기 및 공유](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/how-to-send-and-share-reports) | 새 비디오 | 사용자, 팀 또는 이메일 주소로 보고서를 보내는 방법 및 Workfront의 사용자와 보고서를 공유하는 방법을 알아봅니다. |
| 2025년 6월 | [대시보드 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-dashboards) | 새 비디오 | Workfront 대시보드를 사용하여 프로젝트 데이터를 구성하고 표시하십시오. 대시보드는 맞춤화하고, 쉽게 액세스하고, 공유하고, 인쇄할 수 있어 프로젝트를 원활하게 관리하고 공동 작업을 수행할 수 있습니다. |
| 2025년 6월 | [보고서 설정 이해](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/report-settings) | 새 비디오 | Workfront 보고서 설정에 액세스하는 방법 및 몇 가지 일반적인 보고서 설정이 사용되는 용도에 대해 알아보십시오. |
| 2025년 6월 | [기본 보기 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-view) | 새 비디오 | Workfront에서 보기란 무엇인지와 보기를 만드는 방법, 다른 사용자와 보기를 공유하는 방법을 알아봅니다. |
| 2025년 6월 | [증명 진행 상황 추적](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/workfront-proof/review-and-approve-work-for-proof/track-proof-progress) | 신규 문서 | Workfront에서 SOCD 표시기, 증명 진행 상황 및 보고서를 사용하여 증명 진행 상황을 추적하는 방법에 대해 알아봅니다. |
| 2025년 6월 | [작업 보고서 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-task-report) | 새 비디오 | 복잡한 필터로 작업 보고서를 만들고 Workfront에서 만든 보고서를 찾는 방법을 알아봅니다. |
| 2025년 6월 | [레코드 유형 연결](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/workfront-planning/connect-record-types) | 새 비디오 | Workfront 계획 수립에서 레코드 유형을 연결하여 워크플로를 간소화하고, 명확성을 높이며, 팀의 책임성과 효율성을 향상시키는 방법을 알아봅니다. |

### 새 [!DNL Workfront] 지원 기술 자료

[!DNL Workfront]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2025년 5월 | [Workfront의 새 프로젝트에 사용자 정의 기본 계획 수립 상태가 적용되지 않음](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26366) | 신규 문서 | Adobe Workfront에서 사용자 정의 기본 계획 수립 상태를 구성할 때 새로 생성된 프로젝트가 사용자 정의 대신 여전히 시스템의 기본 계획 수립 상태를 사용하는 문제에 대한 해결 방법을 알아봅니다. |
| 2025년 5월 | [Adobe Workfront 및  [!DNL Fusion] SSO](https://experienceleague.adobe.com/ko/docs/experience-cloud-kcs/kbarticles/ka-26646)와 [!DNL Azure] 서비스 주체 계정의 호환성 | 신규 문서 | 인증을 위해 [!DNL SiteMinder]에서 [!DNL Azure] SSO(Single Sign-On)으로 전환이 [!DNL Azure] 서비스 주체 계정을 사용하여 이메일 주소에 연결된 기존 서비스 계정을 대체하여 Adobe Workfront 및 [!DNL Fusion]으로 인증할 수 있는지에 대해 알아봅니다. |

최신 제품 설명서를 보려면 [Adobe [!DNL Workfront] 홈 페이지](https://experienceleague.adobe.com/ko/docs/workfront/using/home)를 참조하십시오.

+++

## GenStudio for Performance Marketing {#genstudio-marketing}

[!DNL GenStudio for Performance Marketing]에 대한 최신 릴리스 정보와 새로운 설명서를 살펴보십시오.

+++릴리스 정보 및 설명서

* [2025.06 - ](https://experienceleague.adobe.com/ko/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest)GenStudio for Performance Marketing 릴리스 정보
* [GenStudio for Performance Marketing](https://experienceleague.adobe.com/ko/browse/genstudio-for-performance-marketing) (모든 자체 도움말)
* GenStudio for Performance Marketing [제품 설명서](https://experienceleague.adobe.com/ko/docs/genstudio-for-performance-marketing/user-guide/home)
* [GenStudio for Performance Marketing](https://business.adobe.com/products/genstudio-for-performance-marketing.html) 제품 정보

+++

## [!DNL Mix Modeler] {#mix-modeler}

+++릴리스 정보 및 설명서

최신 정보는 다음 페이지를 참조하십시오.

* Mix Modeler [2025년 5월 - 6월 - 릴리스 정보](https://experienceleague.adobe.com/ko/docs/mix-modeler/using/releases/latest)
* Mix Modeler [제품 설명서](https://experienceleague.adobe.com/ko/docs/mix-modeler)

+++

## Adobe [!DNL Advertising] {#advertising}

[!DNL Adobe Advertising]에 대한 최신 릴리스 정보와 새로운 설명서를 살펴보십시오.

+++릴리스 정보

Adobe [!DNL Advertising] 도움말을 살펴보려면 [Adobe Advertising 설명서](https://experienceleague.adobe.com/ko/docs/advertising)를 확인하십시오.

### [!DNL Advertising DSP]의 새로운 기능 {#advertising-dsp}

2025년 6월 4일

[ [!DNL Advertising DSP]의 새로운 기능](https://experienceleague.adobe.com/ko/docs/advertising/dsp/home)을 참조하십시오.

### [!DNL Advertising Search, Social, & Commerce]의 새로운 기능 {#advertising-search}

2026년 3월 26일

[ [!DNL Advertising Search, Social, & Commerce]의 새로운 기능](https://experienceleague.adobe.com/ko/docs/advertising/search-social-commerce/home)을 참조하십시오.

+++

## [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass]는 매력적이고 개인화된 시청 경험을 통해 수익을 창출할 수 있도록 방송사와 케이블 네트워크 및 서비스 제공업체를 지원하는 멀티스크린 TV 플랫폼입니다.

+++설명서

릴리스별 정보, 시스템 요구 사항, 제한 사항, 해결된 문제 및 알려진 문제는 [Adobe Pass 설명서](https://experienceleague.adobe.com/ko/docs/pass)를 참조하십시오.

+++

## [!DNL Document Cloud] {#doc-cloud}

새로운 [!DNL Document Cloud] 튜토리얼이 게시되었습니다([!DNL Acrobat Services] 및 [!DNL Acrobat Sign] 포함).

+++ 최신 튜토리얼

<!-- New tutorials published for Adobe Document Cloud.

| Published | Application | Name | Type | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| May 2025 | Applications | [Comment on a PDF](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/acrobat-learning/getting-started/comment-on-pdf-files) |  Updated video | Learn how to add comments on a shared PDF using just a web browser. Whether you're collaborating with a team or proofreading a document, Acrobat's commenting tools make it simple to provide clear and actionable feedback.  | -->

[!DNL Document Cloud] 튜토리얼을 찾아보려면 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/acrobat-learning/overview)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/sign-learning-hub/overview)
* [Adobe Acrobat API 튜토리얼](https://experienceleague.adobe.com/ko/docs/acrobat-services-learn/tutorials/overview)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

+++

## [!DNL Creative Cloud] (기업용) {#creative-cloud}

[!DNL Adobe Creative Cloud for enterprise]의 앱에 대한 새로운 튜토리얼이 게시되었습니다.

+++ 최신 튜토리얼

<!-- | Published | Application | Name | Type | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| February 2025 | Applications | [Effortless brand consistency with templates](https://experienceleague.adobe.com/ko/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/use-templates) | New video | Learn how to create on-brand content quickly and efficiently across your entire organization. This tutorial walks through how to create fresh new on-brand content that can immediately be shared and localized.|
| February 2025 | Applications | [Maximize efficiency: Create reusable templates](https://experienceleague.adobe.com/ko/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates) | New video | Learn how to bring brand consistency, efficiency, professionalism, and cost savings to your organization with Adobe Express templates. | -->

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/ko/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview)을 참조하십시오.

+++

## 고객 데이터 관리 - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/ko/docs/events/customer-data-management-voices-recordings/overview)는 고객 데이터 관리 기술 및 마케팅 실무 리더 및 전문가를 위한 공간입니다. 이 튜토리얼 컬렉션을 통해 동료의 의견을 듣고, 영감을 얻고, MarTech의 개발에 대해 종합적으로 배울 수 있습니다. 등록이 필요하지 않습니다. 클릭하여 시청하십시오.

## Digital Experience 블루프린트 {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/ko/docs/blueprints-learn/architecture/overview)는 전략을 수립하고 기존 비즈니스 문제를 신속하게 해결할 수 있는 반복 가능한 구현 방식입니다. 각 블루프린트는 고가치 비즈니스 문제, 아키텍처, 구현 단계, 기술 고려 사항 및 관련 문서 링크를 설명하는 일련의 아티팩트를 제공합니다.

<!-- |Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2025|[Guardrails](https://experienceleague.adobe.com/ko/docs/blueprints-learn/architecture/architecture-overview/deployment/guardrails)|Updated article |Learn about guardrails, the performance expectations and impact for the components and services within Adobe Experience Platform and Applications.| -->

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/ko/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/ko/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/ko/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->

