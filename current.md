---
title: 최신 릴리스 정보
description: Adobe [!DNL Experience Cloud] 제품 및 서비스에 대한 최신 릴리스 정보 및 기술 자료 문제를 확인합니다. Experience League에서 예정된 이벤트 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud] 애플리케이션의 최신 튜토리얼 및 교육 과정을 살펴보십시오.
doc-type: release notes
last-update: September 2024
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 486a4b7fd14463d4caa0ab8f7c5857284728bb49
workflow-type: tm+mt
source-wordcount: '4127'
ht-degree: 40%

---

# Experience Cloud 릴리스 노트 - 2024년 9월

<!-- badgeReview: label="Internal Review" type="Negative" -->

<!-- ![Banner](assets/release-notes-header.png) -->

이 페이지를 통해 Experience Cloud 및 Adobe 엔터프라이즈 애플리케이션에 대한 다음과 같은 자가 진단 리소스를 찾을 수 있습니다.

* 릴리스 정보 및 제품 설명서
* 지원 기술 자료 문서
* 다가오는 Experience League 이벤트
* 최신 비디오 튜토리얼

최고의 자가 진단 경험을 위해 [Experience League](https://experienceleague.adobe.com/#home)에 로그인한 다음 Adobe 무료 라이브러리의 [설명서](https://experienceleague.adobe.com/ko/docs), [과정](https://experienceleague.adobe.com/#courses), [이벤트](https://experienceleague.adobe.com/events/), [커뮤니티 포럼](https://experienceleaguecommunities.adobe.com/?profile.language=en) 및 [지원](https://experienceleague.adobe.com/?support-tab=home#support)에서 검색 환경을 사용자 정의합니다.

**피드백 남기기**

**_을(를) 찾으십시오. 이 내용이 유용했습니까?각 페이지 하단에_**&#x200B;개의 팝업이 있습니다. 피드백은 선별되어 콘텐츠 작성자에게 전달됩니다.

**알림 받기**

이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오.

## 2024년 9월

마지막 업데이트: **2024년 9월 11일 목요일**

* [[!DNL Experience League] 이벤트 및 업데이트](#events)(업데이트됨: **9월 10일**)
* [[!DNL Adobe System Status]](#status)
* [[!DNL Adobe Experience Cloud] - 중앙 인터페이스 및 관리](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Real-Time Customer Data Platform]](#rtcdp)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Adobe Customer Journey Analytics]](#cja)
* [[!DNL Adobe Streaming Media Analytics]](#sma)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Optimizer B2B Edition]](#ajo-b2b)
* [[!DNL Adobe Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Mix Modeler]](#mix-modeler)
* [[!DNL Adobe Advertising]](#advertising)
* [[!DNL Adobe Content Supply Chain Tutorials]](#content-supply-chain)
* [[!DNL Adobe Pass]](#pass)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [고객 데이터 관리 - 음성](#voices)
* [Digital Experience 블루프린트](#blueprints)
* [Adobe에서의 인증](https://experienceleague.adobe.com/ko/docs/certification/program/overview)
* [Adobe 제품 보안 취약점](https://helpx.adobe.com/kr/security.html)

## ![아이콘](/assets/experience-league.png) [!DNL Experience League] 이벤트 및 업데이트 {#events}

Experience League의 흥미로운 이벤트에 대해 알아봅니다. 이는 Adobe의 제품 전문가로부터 배우고, 상호 작용하고, 답변을 얻을 수 있는 유용한 공간입니다.

### Experience League의 재생 목록(새로운 기능!)

Experience League에서 새 비디오 [재생 목록](https://experienceleague.adobe.com/en/playlists)을 사용할 수 있습니다. 재생 목록은 원하는 기술과 지식을 얻을 수 있도록 설계된 선별된 비디오 컬렉션입니다.

재생 목록 기능은 다음과 같습니다.

* 자동 재생 비디오
* 챕터 선택 및 재생 속도
* 중단한 지점에서 다시 시작
* 비디오 트랜스크립트

재생 목록을 찾아보려면 **[!UICONTROL 학습]** > **[!UICONTROL 모든 재생 목록 찾아보기]**&#x200B;로 이동하십시오.

>[!NOTE]
>
>**과정**&#x200B;이(가) Experience League에서 중단됩니다. 과정을 책갈피로 표시한 경우, 해당 재생 목록이 있는 경우 해당 재생 목록으로 리디렉션됩니다. 경우에 따라 찾고 있는 주제를 다루는 새 재생 목록으로 이동해야 할 수 있습니다.

### Experience League 이벤트

+++세부 사항

* **[!DNL MARKETO ENGAGE]** | 커뮤니티 이벤트 | _Marketo 및 Mochas: Marketo 사용 최적화(완성도 Pt 2)_ | Marketo 완성도 시리즈의 2부에서 Marketo 사용을 최적화하는 방법을 알아보십시오. 이 세션은 데이터 관리, 통합 및 향상된 개인화를 위한 프로그램 최적화에 대한 모범 사례에 중점을 둡니다. | **9월 12일 @ 오전 11시(MT)** | [등록](https://adobeevents.adobeconnect.com/eaawduywkndj/event/registration.html?campaign-id=ExL)

* **[!DNL WORKFRONT]** | 고객 워크숍 | _학습: Adobe 제품이 있는 Workfront 보드로 돌아가기_ | Workfront 보드를 사용하는 새롭고 창의적인 방법을 찾고 계십니까? 제품 관리자와 함께 보드 모범 사례와 이 기능을 사용하여 채택률을 향상시키는 방법에 대해 알아보십시오. | **9월 12일 @ 오후 12시(MT)** | [등록](https://events.teams.microsoft.com/event/e1e4a956-0115-4a60-b7f8-f519e6f26013@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL WORKFRONT]** | 커뮤니티 이벤트 | _연결: Workfront 집합_ | 월간 월요일에 열리는 Workfront Collective 이벤트에 참여하여 다른 고객과 소통하고 Workfront 기능에 대해 논의하며, 일반적인 문제를 해결하기 위해 함께 브레인스토밍합니다. | **9월 16일 @ 오전 7시(MT)** | [등록](https://events.teams.microsoft.com/event/ecc08357-a15e-4058-a062-8efe038c81cc@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL WORKFRONT]** | 고객 워크숍 | _관리자 101: Workfront 질문 가져오기_ | Workfront을 처음 사용하십니까? 이전 관리 101 세션 중에 누락된 것이 있습니까? 요약 세션에 참여하여 질문을 하고, 리소스 및 권장 사항을 얻고, 다른 새로운 관리자를 만나보십시오. | **9월 17일 @ 오전 9시(MT)** | [등록](https://events.teams.microsoft.com/event/ea6802af-b1dc-441a-aedb-79ed8607e02d@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL MARKETO ENGAGE]** | 웨비나 | _다중 스트림 참여 프로그램을 통한 복잡한 고객 여정 기본_ | Adobe Marketo Engage Champion Max Garrett와 함께 여정의 모든 단계에서 멀티 터치 및 멀티 스트림 참여 프로그램을 통해 고객 관계를 체계적으로 참여하고 육성하는 방법을 살펴보십시오. | **9월 17일 @ 오전 9시(MT)** | [등록](https://engage.adobe.com/Master-Muti-Stream-Engagement-Program-Marketo-Engage.html?trackingid=CJ1327K1&amp;mv=email)

* **[!DNL WORKFRONT]** | 고객 워크숍 | _학습: 가치 실현 - Workfront 활용_ | Workfront의 노력으로 가장 큰 가치를 창출하는 방법에 대한 지침을 찾고 계십니까? 수석 고객 성공 관리자인 Kait Winchell과 함께 Workfront을 최대한 활용하기 위한 업계 모범 사례를 공유합니다. | **9월 19일 @ 오전 9시(MT)** | [등록](https://events.teams.microsoft.com/event/6fae993e-73b5-49e6-97a1-1aa0a64b83c8@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL COMMERCE]** | 웨비나 | _Commerce 및 커피: 성수기 준비_ | Corey Gelato와 함께 매년 성수기에 사이트를 준비하는 방법에 대한 개요를 살펴보십시오. 웹 사이트 성능을 최적화하고, 인벤토리를 관리하고, 주문을 이행하고, 능동적으로 램프 업(ramp up) 지원을 수행하는 방법에 대해 알아봅니다. | **9월 19일 @ 오전 11시(MT)** | [등록](https://adobeevents.adobeconnect.com/e47se7d9nn63/event/registration.html?campaign-id=ExL)

* **[!DNL DYNAMIC MEDIA CLASSIC],[!DNL EXPERIENCE MANAGER ASSETS]** | 웨비나 | _Dynamic Media 환경: 최신 혁신 기술 공개_ | 이제 AEM Dynamic Media의 새로운 혁신을 통해 고객 경험을 향상시킬 수 있습니다! 가치에 초점을 맞춘 개요와 최신 기술을 기반으로 구축된 매력적인 사용자 경험에 대해 살펴보십시오. | **9월 25일 @ 오전 10시(MT)** | [등록](https://events.teams.microsoft.com/event/043c6637-cfaf-486b-8924-2e562d28c833@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

등 Experience League에서 모든 [예정된 이벤트](https://experienceleague.adobe.com/events/)를 확인하거나 [지난 이벤트 녹화](https://experienceleague.adobe.com/ko/docs/events/experience-league-recorded-events/overview)를 검색하십시오.

+++

## ![아이콘](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]의 최신 기능 및 업데이트에 대해 알아봅니다.

+++세부 사항

[!DNL Adobe System Status]는 Adobe 제품 및 서비스에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. 중단 및 유지 관리 이벤트에 대한 알림을 받습니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인합니다.

릴리스 날짜: **2024년 8월 19일**

**새로운 기능**

* 제품 기반 유지 관리 알림, 버그 수정 및 개선 사항

| 기능 | 설명 |
| ------- | ------- |
| 제품 기반 유지 관리 | <ul><li>유지 관리별 대신 제품별 UI 및 알림이 개선되었습니다.</li><li>각 업데이트의 영향 속성은 영향의 제품별 세부 정보를 제공합니다.</li></ul> |
| 버그 수정 및 개선 사항 | <ul><li>_구독하는 방법_ 도움말 페이지 현지화</li><li>[!DNL Slack] 설치 지침 페이지에 지원 연락처 정보를 추가했습니다.</li><li>상태 API를 사용하여 이벤트 상태별로 올바르게 필터링되지 않은 인시던트의 버그를 수정했습니다.</li></ul> |

최근 릴리스 정보는 다음을 참조하십시오.

* [2024년 5월 15일](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2024/05152024#status)
* [2024년 1월 30일](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2024/02142024#status)
* [2023년 10월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/10042023#status)
* [2023년 8월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/08092023#status)
* [2023년 3월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/03082023#status)
* [2023년 1월](https://experienceleague.adobe.com/ko/docs/release-notes/experience-cloud/previous/2023/02082023#status)

+++

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Experience Cloud] - 중앙 인터페이스 및 관리 {#ecloud}

[!DNL Experience Cloud] 중앙 인터페이스 구성 요소 및 관리에 대해 알아봅니다. 제품 및 사용자를 관리하고, 프로필 설정 및 환경 설정을 구성하고, Experience Cloud 오브젝트를 검색하고, 쿠키를 관리합니다.

+++세부 사항

릴리스: **2024년 9월 10일**

| 기능 | 설명 |
| -----------| ---------- |
| [!DNL Experience Cloud]에서 [!DNL Slack]개의 알림 | Slack에게 [!DNL Experience Cloud]개의 알림을 보내도록 계정 환경 설정을 구성할 수 있습니다. 자세한 내용은 [Slack 알림 구독](https://experienceleague.adobe.com/en/docs/core-services/interface/features/account-preferences)을 참조하세요. |

[!DNL Experience Cloud] 중앙 인터페이스 구성 요소에 대한 도움말은 [Experience Cloud 인터페이스 및 관리 안내서](https://experienceleague.adobe.com/ko/docs/core-services/interface/experience-cloud)([!UICONTROL 고객 특성], [!DNL Experience Cloud Assets] 및 [!UICONTROL 대상] 포함)를 참조하십시오.

+++

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 및 [!UICONTROL Mobile SDK]에 대한 최신 릴리스 정보와 새로운 설명서를 확인합니다. Experience League에서 새로운 튜토리얼과 Knowledge BASE 문서를 확인합니다.

+++세부 사항

* [[!DNL Experience Platform] 릴리스 정보](https://experienceleague.adobe.com/ko/docs/experience-platform/release-notes/latest)

* [[!DNL Experience Platform] Mobile SDK 릴리스 정보](https://developer.adobe.com/client-sdks/documentation/release-notes/)

### 새로운 [!DNL Experience Platform] 튜토리얼{#tutorials-aep}

Experience League에 새로운 Adobe [!DNL Experience Platform] 튜토리얼이 게시되었습니다.

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2024년 9월 | [!DNL Experience Platform] | [Federated Audience 컴포지션 개요]](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/audiences/overview-of-federated-audience-composition)[!UICONTROL  | 비디오 | Experience Platform Federated Audience Composition이 Adobe Real-Time CDP 및 Adobe Journey Optimizer 사용자에게 데이터 관리의 유연성과 효율성을 제공하는 방법을 알아봅니다. |
| 2024년 9월 | [!DNL Experience Platform] | [[!UICONTROL Federated Audience 컴포지션 만들기]](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/audiences/create-a-federated-audience-composition) | 비디오 | Federated Audience Composition을 만드는 방법과 UI에서 Data Warehouse에 도달하여 올바른 데이터를 선택하는 쿼리를 만드는 방법을 알아봅니다. |
| 2024년 9월 | [!DNL Experience Platform] | [연결 및 구성 [!UICONTROL Federated Audience 구성]](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/audiences/connect-and-configure-federated-audience-composition) | 비디오 | 데이터 웨어하우스에 연결하고 [!UICONTROL Federated Audience Composition]에 대한 연결을 구성하는 방법에 대해 알아봅니다. |
| 2024년 9월 | [!DNL Experience Platform] | [플레이북 인스턴스 만들기 및 게시](https://experienceleague.adobe.com/en/docs/platform-learn/tutorials/use-case-playbooks/create-and-publish-a-playbook-instance) | 비디오 | 이 전체적인 데모 비디오에서 사용 사례 플레이북의 인스턴스를 검색, 만들고, 게시하고, 문제를 해결하는 방법을 알아봅니다. |

### 새 [!DNL Experience Platform] 지원 기술 자료{#kb-aep}

[!DNL Experience Platform]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2024년 8월 | [스키마 업데이트 액세스 오류 위치 [!DNL Adobe Experience Platform]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24746) | 신규 문서 | [!DNL Adobe Experience Platform]에서 *[!DNL XDM Schema]업데이트가 허용되지 않음* 오류를 해결하는 방법에 대해 알아봅니다. |

+++

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Real-Time Customer Data Platform] {#rtcdp}

Experience League에서 [!DNL Real-Time Customer Data Platform]에 대한 최신 튜토리얼을 확인합니다.

+++세부 사항

* 비디오 튜토리얼: [Real-Time Customer Data Platform 이해](https://experienceleague.adobe.com/ko/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform)

* 제품 설명서: [Real-Time Customer Data Platform](https://experienceleague.adobe.com/ko/docs/real-time-customer-data-platform)

+++

## ![아이콘](/assets/analytics.png) [!DNL Analytics] {#analytics}

[!DNL Adobe Analytics] 및 [!DNL AppMeasurement]에 대한 최신 릴리스 정보를 확인합니다. Experience League의 새로운 튜토리얼을 확인합니다.

+++세부 사항

[!DNL Analytics] 릴리스 일자: **2024년 9월 11일 목요일**

* [!DNL Analytics] [릴리스 정보](https://experienceleague.adobe.com/ko/docs/analytics/release-notes/latest) <!-- * [!DNL Analytics] [release notes](https://experienceleague-review.corp.adobe.com/docs/analytics/release-notes/latest.html)  -->

* [!DNL Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/analytics)

### AppMeasurement {#appm}

릴리스 버전: **2.26.0**

* [JavaScript용 AppMeasurement 릴리스 정보](https://experienceleague.adobe.com/ko/docs/analytics/implementation/appmeasurement-updates)

### 새로운 [!DNL Analytics] 튜토리얼 {#tutorials-analytics}

Experience League에 새로운 Adobe [!DNL Analytics] 튜토리얼이 게시되었습니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2024년 9월 | [Adobe Analytics에서 [!UICONTROL 분류 규칙 빌더] 사용](https://experienceleague.adobe.com/en/docs/analytics-learn/tutorials/components/classifications/using-the-classification-rule-builder) | 비디오 | [!UICONTROL 분류 규칙 빌더]를 사용하여 규칙 기반 분류를 Adobe Analytics에서 자동으로 적용하는 방법을 알아봅니다. |


### 새로운 Adobe [!DNL Analytics] 지원 기술 자료{#kb-analytics}

[!DNL Analytics]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2024년 8월 | [확장](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24569)에서 서버측 전달 비활성화 [!DNL Analytics Mobile SDK]  | 신규 문서 | [!DNL Mobile SDK]에서 [!DNL Audience Manager](으)로 [!DNL Analytics] 히트의 서버측 전달을 비활성화하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [[!DNL Android 10] 차원 **[!DNL Operating System]**&#x200B;에서 2023년 5월부터 트래픽 증가](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24442) | 신규 문서 | [!DNL Adobe Analytics]의 **[!DNL Operating System]** 차원에서 [!DNL Android 10] 트래픽이 증가한 이유에 대해 알아봅니다. |


+++

## ![아이콘](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

[!DNL Customer Journey Analytics]에 대한 최신 릴리스 정보를 확인합니다. 새로운 Experience League 튜토리얼을 확인합니다.

+++세부 사항

[!DNL Customer Journey Analytics] 릴리스 일자: **2024년 9월 11일 목요일**

* [!DNL Customer Journey Analytics] [릴리스 정보](https://experienceleague.adobe.com/ko/docs/analytics-platform/using/releases/latest#releases) <!-- * [!DNL Customer Journey Analytics] [release notes](https://experienceleague-review.corp.adobe.com/docs/analytics-platform/using/releases/latest.html) -->

* [!DNL Customer Journey Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/customer-journey-analytics)

<!-- ### New [!DNL Customer Journey Analytics] tutorials {#tutorials-cja}

New tutorials published for [!DNL Customer Journey Analytics]. 

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|August 2024|[Overview of stitching](https://experienceleague.adobe.com/en/docs/customer-journey-analytics-learn/tutorials/visitor-id/overview-of-stitching)|Video |View a quick overview into the process of stitching. With many individuals interacting with your content across multiple channels and devices, it becomes ever more important to connect these unauthenticated events to authenticated ones. |
|August 2024|[Funnel friction analysis](https://experienceleague.adobe.com/en/docs/customer-journey-analytics-learn/tutorials/guided-analysis/funnel/funnel-friction-analysis)|Updated video |Learn how to use the funnel friction view in Customer Journey Analytics. This view provides a visual representation of a critical user journey in your product and helps you determine where there is friction in it.| -->

+++

## ![아이콘](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

[!DNL Streaming Media Analytics]에 대한 최신 릴리스 정보를 확인합니다. 새로운 Experience League 튜토리얼을 확인합니다.

+++세부 사항

* [!DNL Streaming Media Analytics] [릴리스 정보](https://experienceleague.adobe.com/ko/docs/media-analytics/using/release-notes/release-notes)

* [!DNL Streaming Media Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/ko/docs/media-analytics/using/media-overview)

+++

## ![아이콘](/assets/aem.png) Adobe [!DNL Experience Manager] {#aem}

[!DNL Experience Manager]의 새로운 기능, 수정 내용 및 업데이트. Adobe는 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 고객의 경우 온프레미스 배포를 사용할 것을 권장합니다.

+++세부 사항

### Experience Manager 릴리스 정보

모든 [!DNL Experience Manager] 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [최신 릴리스 개요 비디오](https://experienceleague.adobe.com/en/docs/events/aemcs-release-update-recordings/2024/2024-7-0)
* [[!DNL Experience Manager] 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/ko/docs/experience-manager-release-information/aem-release-updates/home)
* [ [!DNL Experience Manager] as a Cloud Service](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current) 최신 릴리스 정보
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
| 2024년 9월 | AEM CS | [Adobe CDN - 캐싱 이상의 고급 기능](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/content-delivery/adobe-cdn-beyond-caching) | 비디오 | CDN(Adobe Content Delivery Network)에서 트래픽 구성, 토큰 및 자격 증명 설정, CDN 오류 페이지 등과 같은 캐싱을 넘어선 CDN의 고급 기능에 대해 알아봅니다. |
| 2024년 9월 | AEM CS | 고객 관리 CDN을 사용하는 [사용자 지정 도메인 이름](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/content-delivery/custom-domain-names-with-customer-managed-cdn) | 비디오 | 고객 관리 CDN을 사용하는 AEM as a Cloud Service 웹 사이트에 사용자 정의 도메인 이름을 추가하는 방법에 대해 알아봅니다. |
| 2024년 9월 | AEM CS | [CDN 캐시를 제거하는 방법](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/caching/how-to/purge-cache) | 비디오 | AEM as a Cloud Service CDN에서 캐시된 HTTP 응답을 제거하거나 제거하는 방법을 알아봅니다. Purge API Token이라는 셀프서비스 기능을 사용하여 특정 리소스, 리소스 그룹 및 전체 캐시에 대한 캐시를 제거할 수 있습니다. |
| 2024년 9월 | AEM CS | [HTL에서 Sling 모델 매개 변수화](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/developing/advanced/sling-model-parameters) | 비디오 | 매개 변수가 있는 Sling 모델을 만드는 방법에 대해 알아봅니다. HTL(HTML 템플릿 언어)에서 사용하여 다이내믹 콘텐츠를 렌더링합니다. |
| 2024년 9월 | AEM Sites | [Adobe CDN을 사용하는 사용자 지정 도메인 이름](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/content-delivery/custom-domain-name-with-adobe-managed-cdn) | 여러 비디오 | Adobe CDN(Content Delivery Network)을 사용하는 AEM as a Cloud Service 웹 사이트에 대한 사용자 정의 도메인 이름을 구현하는 방법을 알아봅니다. |
| 2024년 9월 | AEM Sites | [사용자 지정 도메인 이름 옵션](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/content-delivery/custom-domain-names) | 비디오 | AEM as a Cloud Service 호스팅 웹 사이트의 도메인 이름을 관리하고 구현하는 방법을 알아봅니다. |
| 2024년 9월 | AEM Sites | [Edge Delivery Services이 있는 AEM Sites으로 사이트 가져오기](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/expert-resources/cloud-5/season-3/cloud5-import-sites-to-edge-delivery-services) | 비디오 | Edge Delivery Services을 사용하여 기존 사이트를 AEM Sites으로 쉽게 가져올 수 있도록 가져오기 도구를 사용하고 맞춤화하기 위한 모범 사례에 대해 알아봅니다. |
| 2024년 9월 | AEM Forms | [세로 탭 소개](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/forms/using-vertical-tabs/introduction) | 비디오 | 세로 탭을 사용하여 적응형 양식을 만듭니다. |
| 2024년 9월 | AEM Forms | [클릭 가능한 이미지 소개](https://experienceleague.adobe.com/en/docs/experience-manager-learn/cloud-service/forms/clickable-image-component/introduction) | 비디오 | AEM Forms Cloud Service에서 클릭 가능한 이미지 구성 요소를 만듭니다. |
| 2024년 9월 | Foundation | [AEM에 대한 JWT-To-OAuth 자격 증명 마이그레이션](https://experienceleague.adobe.com/en/docs/experience-manager-learn/foundation/authentication/jwt-to-oauth-migration) | 비디오 | 더 이상 사용되지 않는 JWT(서비스 계정) 자격 증명에서 다른 Adobe 솔루션을 새 OAuth 서버 간 자격 증명으로 마이그레이션하는 방법에 대해 알아봅니다. |
| 2024년 9월 | AEM Assets | [자산 업로드 및 승인 프로세스](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/uploading-assets-and-approval-process) | 비디오 | Adobe Experience Manager Assets Content Hub에서 에셋을 업로드하고, 태그를 적용하고 승인 워크플로를 이해하는 방법에 대해 알아봅니다. |
| 2024년 9월 | AEM Assets | [에셋 액세스 및 다운로드](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/accessing-and-downloading-assets) | 비디오 | Adobe Experience Manager Assets Content Hub에서 에셋을 탐색, 검색, 필터링 및 다운로드하는 방법을 알아봅니다. |
| 2024년 9월 | AEM Assets | [Dynamic Media의 비디오 폐쇄 캡션](https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/advanced/video-closed-captions) | 비디오 | Dynamic Media의 폐쇄 캡션에 대해 알아봅니다. 비디오 파일이 Dynamic Media을 사용하여 AEM Assets에 업로드되면 닫힘 캡션이 자동으로 생성됩니다. |
| 2024년 9월 | AEM Assets | [보고서](https://experienceleague.adobe.com/ko/docs/experience-manager-learn/assets-essentials/basics/reports) | 비디오 | AEM Assets의 자산 보고서를 사용하여 DAM 활동에 대한 통찰력을 얻는 방법을 알아보십시오. |
| 2024년 9월 | AEM Assets | [Creative Cloud Libraries 및 AEM Assets](https://experienceleague.adobe.com/ko/docs/experience-manager-learn/assets-essentials/creative-cloud) | 비디오 | AEM Assets을 Adobe Creative Cloud 라이브러리와 통합하는 방법에 대해 알아봅니다. |

### 새 [!DNL Experience Manager] 지원 기술 자료{#kb-aem}

[!DNL Experience Manager]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|--------|---------|---------|
| 2024년 8월 | [!UICONTROL 콘텐츠 조각]의 [CF 참조는 언어 사본에 따라 조정되지 않습니다](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24819) | 신규 문서 | [!DNL AEM]의 [!UICONTROL 언어 사본]을 기반으로 [!UICONTROL 콘텐츠 조각]의 참조가 업데이트되지 않는 경우 문제를 해결하는 방법을 알아봅니다. |
| 2024년 8월 | [[!DNL Akamai] 을 통해 캐시 지우기 [!DNL API]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24795) | 신규 문서 | [!DNL Akamai]에서 부모 자산의 모든 자식 캐시를 지우는 동안 [!DNL Dynamic Media Classic]에서 [!DNL CDN] 무효화를 프로그래밍 방식으로 동기화하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [[!DNL PDF] 파일이 자동으로 게시되지 않음](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24689) | 신규 문서 | [!DNL PDFs]이(가) [!DNL Adobe Experience Manager as a Cloud Service (AEMaaCS)]의 미리 보기와 함께 자동으로 게시되지 않는 문제를 해결하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [버전을 확인하는 방법 [!DNL Apache Jackrabbit Oak]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24785) | 신규 문서 | [!DNL AEM]에서 사용하는 [!DNL Apache Jackrabbit Oak]의 버전을 식별하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [ [!DNL AEM as a Cloud Service]에서 [!UICONTROL 워크플로 제거 구성]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24590) | 신규 문서 | [!DNL Adobe Experience Manager as a Cloud Service (AEMaaCS)]에서 단계별로 [!UICONTROL 워크플로 제거] 설정을 구성하는 방법을 알아봅니다. |

+++

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Experience League의 [!DNL Adobe Commerce]에 대한 릴리스 정보, 새로운 튜토리얼과 Knowledge BASE 문서를 이용할 수 있습니다.

+++세부 사항

* 최신 정보는 [ [!DNL Adobe Commerce] 및 [!DNL Magento Open Source]의 릴리스 정보](https://experienceleague.adobe.com/ko/docs/commerce-operations/release/notes/overview)를 참조하십시오.
* Commerce Services 릴리스 정보 및 설명서를 보려면 [Adobe [!DNL Commerce] Services 안내서](https://experienceleague.adobe.com/ko/docs/commerce-merchant-services/user-guides/home)를 참조하십시오.
* 개별 제품 릴리스 정보에 액세스하고 사용 가능 여부를 확인하려면 [제품 가용성](https://experienceleague.adobe.com/ko/docs/commerce-operations/release/product-availability) 을 참조하십시오.

### [!DNL Adobe Commerce]에 대한 새로운 튜토리얼 {#tutorials-commerce}

Experience League의 새로운 [!DNL Adobe Commerce] 튜토리얼입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2024년 9월 | [감시자 추가 및 제거, 티켓 닫기 및 다시 열기](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/getting-started/help-and-support/add-remove-watchers-close-reopen-support-ticket) | 비디오 | Adobe Commerce용 Experience League 내에서 지원 티켓을 닫거나 다시 열 수 있을 뿐만 아니라 감시자를 추가 및 제거하는 방법에 대해 알아봅니다. |
| 2024년 9월 | [지원 티켓 관리](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/getting-started/help-and-support/search-track-comment-escalate-support-ticket) | 비디오 | Adobe Commerce Experience League 내에서 지원 티켓을 검색, 검토, 추천 및 에스컬레이션하는 방법을 알아봅니다. |
| 2024년 9월 | [New Relic 경고 알림 설정](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/tools/new-relic/new-relic-alert-notification-setup) | 비디오 | New Relic에서 경고, 정책, 워크플로우 및 대상을 찾는 방법을 알아봅니다. 기존 정책에 이메일을 추가하는 것이 얼마나 쉬운지 관찰하십시오. |
| 2024년 9월 | [Experience League을 사용하여 지원 티켓 만들기](https://experienceleague.adobe.com/en/docs/commerce-learn/tutorials/getting-started/help-and-support/create-a-support-ticket) | 비디오 | Adobe Commerce용 Experience League을 사용하여 지원 티켓을 만드는 방법을 알아봅니다. |

### 새 [!DNL Commerce] 지원 기술 자료{#kb-commerce}

Adobe Commerce에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|--------|---------|---------|
| 2024년 8월 | [[!DNL Quality Patches Tool (QPT)]](https://experienceleague.adobe.com/ko/docs/commerce-knowledge-base/kb/support-tools/patches/patches-available-in-qpt-tool-overview) | 신규 문서 | [!DNL QPT] 1.1.49 및 [!DNL QPT] 1.1.50에서 사용할 수 있는 패치를 적용하는 방법에 대한 새로운 문서가 게시되었으며 해당 섹션에서 찾을 수 있습니다. |
| 2024년 8월 | [[!DNL Live Search] 패싯이 알파벳순으로 정렬되지 않음](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/miscellaneous/live-search-facets-not-sorted) | 신규 문서 | [!DNL Live Search] 패싯이 알파벳순으로 정렬되지 않은 경우의 해결 방법에 대해 알아봅니다. |
| 2024년 8월 | [서비스 해제 [!DNL Adobe Commerce Help Center]](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/announcements/news/decommissioning-of-adobe-commerce-help-center) | 신규 문서 | Adobe Commerce에서 지원 접수 프로세스를 [!DNL Adobe Commerce Help Center]에서 [!DNL Adobe Experience League](으)로 마이그레이션했습니다. 2024년 7월 29일에 [!DNL Adobe Commerce Help Center]이(가) 읽기 전용 상태가 되었으며 모든 새 지원 사례가 이제 [[!DNL Adobe Experience League]](https://experienceleague.adobe.com)을(를) 통해 제출됩니다. |
| 2024년 8월 | [데이터가 업데이트되지 않음 [!DNL Commerce Data Exporter] 피드 및 [!DNL cron] 변경 로그 테이블의 로그 오류가 존재하지 않음](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/miscellaneous/mdee-table-does-not-exist) | 신규 문서 | [!DNL Data Exporter] [[!DNL Mview]](https://developer.adobe.com/commerce/php/development/components/indexing/#mview) 구독에서 잘못된 보기 ID를 사용하여 발생한 데이터 동기화 문제를 해결하기 위한 솔루션에 대해 알아봅니다. |
| 2024년 8월 | [Adobe Commerce에서 보안 업데이트를 사용할 수 있음 - [!DNL APSB24-61]](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/security-update-available-for-adobe-commerce-apsb24-61) | 신규 문서 | 2024년 8월 13일에 Adobe이 Adobe Commerce, [!DNL Magento Open Source] 및 [!DNL Adobe Commerce Webhooks Plugin]에 대해 정기적으로 예약된 보안 업데이트를 릴리스한 시기에 대해 알아봅니다. |
| 2024년 8월 | [암호화 키 회전 문제 해결: [!DNL CVE-2024-34102]](https://experienceleague.adobe.com/ko/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/troubleshooting-encryption-key-rotation-cve-2024-34102) | 신규 문서 | [!DNL CVE-2024-34102]의 이 [article](https://experienceleague.adobe.com/ko/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/security-update-available-for-adobe-commerce-apsb24-40-revised-to-include-isolated-patch-for-cve-2024-34102)에 설명된 단계를 이미 수행한 후 암호화 키 순환의 문제를 해결하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [저장소 보안 및 암호화 키 회전에 대한 지침: [!DNL CVE-2024-34102]](https://experienceleague.adobe.com/en/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/guidance-on-securing-your-store-and-rotating-encryptionkeys-cve-2024-34102) | 신규 문서 | [!DNL CVE-2024-34102]에 대한 저장소 보안 및 암호화 키 회전에 대한 추가 지침을 알아봅니다. |

+++

## ![아이콘](/assets/target.png) [!DNL Target] {#target}

프리릴리스 정보, 최신 릴리스 정보 및 [!DNL Adobe Target]의 새로운 튜토리얼을 이용할 수 있습니다.

+++세부 사항

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* 프리릴리스에 대한 자세한 내용은 [[!DNL Adobe Target] 프리릴리스](https://experienceleague.adobe.com/ko/docs/target/using/release-notes/target-release-notes)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [[!DNL Adobe Target] 릴리스 정보](https://experienceleague.adobe.com/ko/docs/target/using/release-notes/release-notes)를 참조하십시오.

+++

## ![아이콘](/assets/campaign.png) [!DNL Campaign] {#ac}

[!DNL Adobe Campaign]의 최신 업데이트를 다운로드합니다. Experience League에서 새로운 튜토리얼과 기술 자료 지원 문서를 확인합니다.

+++세부 사항

### 최신 Campaign 제품 릴리스

* [!DNL Web User Interface]: **9월 3일** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8: **9월 3일** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/releases/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Classic] v7: [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/release-notes/latest-release) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/campaign-classic-home)

* [!DNL Campaign Standard]: **2024년 8월** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/campaign-standard-home)

### 새로운 [!DNL Campaign] 튜토리얼 {#tutorials-campaign}

Adobe Campaign용으로 게시된 새로운 또는 업데이트된 비디오 튜토리얼

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| ----------| ---------- | ---------- | ---------- |---------- |
| 2024년 9월 | | [Campaign Web 사용자 인터페이스 살펴보기](https://experienceleague.adobe.com/en/docs/campaign-web-learn/tutorials/getting-started/explore-the-web-ui) | 비디오 | [!UICONTROL Campaign 웹] 사용자 인터페이스에 액세스하고 탐색하는 방법과 인벤토리 목록을 사용자 지정하는 방법을 알아봅니다. |

### 새 [!DNL Campaign] 지원 기술 자료{#kb-campaign}

[!DNL Campaign]에 대한 신규 문서 및 기존 문서 업데이트

| 게시일 | 이름 | 유형 | 설명 |
|---------|----|----|-----------|
| 2024년 8월 | [[!DNL Web Analytics] 연결 실패](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24657) | 신규 문서 | [!DNL web analytics]개의 외부 연결에 연결할 때 [!DNL Web Analytics]에서 [!DNL Adobe Analytics]에 대한 연결 오류가 발생하는 경우의 문제 해결 방법에 대해 알아봅니다. |
| 2024년 8월 | 게재 또는 게재 템플릿을 열 때 [느림 및 [!DNL 500 Timeout] 오류 발생](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24723) | 신규 문서 | [!DNL Oracle]을(를) 데이터베이스로 사용하는 온-프레미스 인스턴스에서 게재 또는 게재 템플릿을 열 때 속도가 느려지고 [!DNL 500 Timeout] 오류가 발생하는 문제에 대한 해결 방법에 대해 알아봅니다. |
| 2024년 8월 |  [!DNL Campaign Classic v8]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24762)(으)로 업그레이드한 후 [디렉터리 만들기 | 신규 문서 | v7에서 v8로 [!DNL Adobe Campaign Classic]을(를) 업그레이드한 후 워크플로우에서 누락된 디렉터리 경로로 오류가 발생하는 문제의 해결 방법에 대해 알아봅니다. |
| 2024년 8월 | [키 기반 연결 구성 [!DNL FTP] - [!DNL Adobe Campaign]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24447) | 신규 문서 | [!DNL FTP (File Transfer Protocol)] 키 기반 연결을 구성하는 방법에 대해 알아봅니다. |
| 2024년 8월 | [[!DNL Campaign Classic v7]: 워크플로 &quot;장치 오류 시 남은 공간 없음&quot;](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24557) | 신규 문서 | 데이터베이스 서버에 더 이상 공간이 없고 워크플로우/게재로 인해 *장치에 공간이 없음* 오류가 발생하는 경우 수행할 작업에 대해 알아봅니다. |

### [!DNL Campaign] 도움말 리소스

* [!DNL Web User Interface]: **9월 3일** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8: **9월 3일** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/releases/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Classic] v7: [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/release-notes/latest-release) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-classic/using/campaign-classic-home)

* [!DNL Campaign Standard]: **2024년 8월** - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/release-notes/release-notes) | [제품 설명서](https://experienceleague.adobe.com/ko/docs/campaign-standard/using/campaign-standard-home)

+++

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Journey Optimizer] {#journey-opt}

[!DNL Journey Optimizer]의 최신 릴리스 정보에 대해 알아봅니다. Experience League에서 최신 튜토리얼과 Knowledge BASE 지원 문서를 확인합니다.

+++세부 사항

### [!DNL Journey Optimizer] 제품 릴리스 업데이트

* 업데이트 및 도움말은 [Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes)를 참조하십시오.

### 새로운 [!DNL Journey Optimizer] 튜토리얼 {#tutorials-ajo}

Experience League에 새로운 Adobe [!DNL Journey Optimizer] 튜토리얼이 게시되었습니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2024년 9월 | [안내 채널 설정](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/guided-channel-setup) | 비디오 | 샘플 iOS 모바일 마케팅 앱에서 푸시 채널 알림을 설정하고 확인하는 방법을 알아봅니다. |
| 2024년 9월 | [채널 구성](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/configure-channels) | 비디오 | 채널 구성이 무엇인지, Adobe [!DNL Journey Optimizer]에서 채널 구성을 사용하는 방법을 알아봅니다. |
| 2024년 9월 | [IP 준비 계획 설정 및 실행](https://experienceleague.adobe.com/en/docs/journey-optimizer-learn/tutorials/configuration/channel-configuration/set-up-and-execute-an-ip-warmup-plan) | 비디오 | IP 준비 방법을 이해하고 Adobe [!DNL Journey Optimizer]에서 IP 준비 계획을 설정하고 실행하는 방법을 알아봅니다. |

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [[!DNL Journey Optimizer] 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/ajo-home) - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes) - [사용 방법 비디오](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/overview)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) - [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/release-notes) - [사용 방법 비디오](https://experienceleague.adobe.com/ko/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management) - [최신 설명서 업데이트](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## ![아이콘](/assets/ajo-b2b.png) [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

[!DNL Journey Optimizer B2b Edition] Adobe에 대한 릴리스 노트 및 새 설명서를 찾습니다.

+++세부 사항

* 릴리스 노트 및 자체 도움말은 [[!DNL Journey Optimizer B2B Edition] 설명서](https://experienceleague.adobe.com/ko/docs/journey-optimizer-b2b/user/guide-overview)를 참조하십시오.
* 제품 정보는 [[!DNL Journey Optimizer B2B Edition]](https://business.adobe.com/products/journey-optimizer-b2b-edition.html)을(를) 참조하세요.

+++

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience League에서 [!DNL Journey Orchestration]에 대한 최신 릴리스 정보에 액세스하십시오.

+++세부 사항

### 최신 [!DNL Journey Orchestration] 제품 릴리스

[[!DNL Journey Orchestration] 릴리스 정보](https://experienceleague.adobe.com/ko/docs/journeys/using/release-notes/release-notes)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

#### [!DNL Journey Orchestration]를 위한 추가 리소스

* [Journey Orchestration 설명서](https://experienceleague.adobe.com/ko/docs/journeys/using/journey-orchestration-home)

* [릴리스 정보](https://experienceleague.adobe.com/ko/docs/journeys/using/release-notes/release-notes)

* [사용 방법 비디오](https://experienceleague.adobe.com/ko/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration)

* [최신 설명서 업데이트](https://experienceleague.adobe.com/ko/docs/journeys/using/release-notes/documentation-updates)

+++

## ![아이콘](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage]의 최신 릴리스 정보와 릴리스 일정을 확인합니다.

+++세부 사항

### 주요 Marketo Engage 업데이트

* 최신 정보는 [2024년 6월 - 최신 릴리스 정보](https://experienceleague.adobe.com/ko/docs/marketo/using/release-notes/current)를 참조하십시오.
* 최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/ko/docs/marketo/using/release-notes/release-schedule)을 참조하십시오.

### 새로운 Marketo 튜토리얼 {#tutorials-marketo}

새로운 Adobe Marketo 튜토리얼이 게시되었습니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2024년 9월 | [Attribution AI 개요](https://experienceleague.adobe.com/en/docs/marketo-measure-learn/tutorials/marketo-measure-ultimate/attribution-ai-overview) | 비디오 | Adobe의 Attribution AI이 정교한 AI/ML 모델링을 통해 B2B 마케팅 측정을 개선하여 정확한 속성 통찰력을 제공하고 정확한 분석을 위한 편향을 제거하는 방법에 대해 알아보십시오. |
| 2024년 9월 | [Marketo Measure Ultimate 개요](https://experienceleague.adobe.com/en/docs/marketo-measure-learn/tutorials/marketo-measure-ultimate/overview) | 비디오 | Marketo Measure Ultimate를 통해 B2B 마케터가 철저한 속성을 위해 동일한 유형의 여러 소스를 포함하여 거의 모든 소스에서 데이터를 수집하는 방법에 대해 알아봅니다. |
| 2024년 9월 | [API 도움말 - 변수에 액세스 토큰을 설정하는 방법](https://experienceleague.adobe.com/ko/docs/marketo-learn/tutorials/integrations/api-set-access-token-variable) | 비디오 | Postman 애플리케이션을 설정하는 방법과 변수를 활용하여 데이터를 재사용하기 위해 변수에 저장하는 방법에 대해 알아봅니다. 또한 액세스 토큰을 가져오기 위해 첫 번째 Marketo Engage REST API를 호출하는 방법을 알아봅니다. |
| 2024년 9월 | [15분 후에 Dynamic Chat 실행](https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/dynamic-chat/go-live-in-15-minutes) | 비디오 | 15분 안에 Dynamic Chat을 사용하여 첫 번째 대화 상자를 시작하는 데 도움이 되는 단계별 안내서를 시청하십시오. |

최신 제품 설명서를 보려면 [Marketo 제품 설명서](https://experienceleague.adobe.com/ko/docs/marketo/using/home) 홈을 참조하십시오.

<!-- ### New [!DNL Marketo] support knowledge base

New articles and updates to existing articles for [!DNL Marketo].

|Published|Name|Type|Description|
| -----------| ---------- | ---------- | ---------- |
|April 2024|[What happens when the [!UICONTROL Default Dashboard] object is changed in [!DNL Marketo Measure]](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-24085)|New article| Learn about the effects of changing the [!UICONTROL Default Dashboard] object in [!DNL Marketo Measure] settings.|

{style="table-layout:auto"} -->

+++

## ![아이콘](/assets/workfront.png) [!DNL Workfront] {#workfront}

[!DNL Adobe Workfront]의 최신 릴리스 정보에 대해 알아봅니다. 새로운 Experience League 튜토리얼을 확인합니다.

+++세부 사항

### [!DNL Adobe Workfront] 업데이트

* [!DNL Workfront] 릴리스 일정 정보 및 릴리스 정보는 [Adobe [!DNL Workfront] 제품 릴리스](https://experienceleague.adobe.com/ko/docs/workfront/using/product-announcements/product-releases/product-releases) 페이지를 참조하십시오.

* Fusion에 대한 최신 정보는 [Adobe [!DNL Workfront] Fusion 릴리스 활동 개요](https://experienceleague.adobe.com/ko/docs/workfront/using/product-announcements/product-releases/fusion-release/fusion-release-activity)를 참조하십시오.

### 새로운 Adobe [!DNL Workfront] 튜토리얼 {#tutorials-workfront}

Experience League의 새로운 [!DNL Workfront] 튜토리얼 및 이벤트

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2024년 9월 | [사용자 정의 양식에 섹션 구분 및 논리 추가](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/add-section-breaks-and-logic-to-a-custom-form) | 비디오 | 섹션 구분을 추가하여 사용자 정의 양식 필드를 구성하는 방법과 필요한 경우 건너뛰기 및 표시 논리를 사용하여 필드를 사용 가능하게 하는 방법에 대해 알아봅니다. |
| 2024년 9월 | [승인 완료](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/manage-work/close-a-project/complete-approvals) | 비디오 | [!DNL Workfront]에서 프로젝트를 닫을 수 있도록 완료되지 않은 승인을 식별하고 해결하는 방법을 알아봅니다. |
| 2024년 9월 | [사용자 지정 필드 공유](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/share-custom-fields) | 비디오 | 사용자 정의 필드를 보거나 편집할 수 있는 사용자를 결정하는 방법을 알아봅니다. |
| 2024년 9월 | [요청 흐름에 대한 설정 이해](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/understand-settings-for-a-flow-request) | 비디오 | 요청 흐름과 라우팅 규칙, 주제 그룹 및 대기열 주제를 사용하여 요청 흐름을 만드는 방법에 대해 알아봅니다. |
| 2024년 9월 | [요청 대기열 만들기](https://experienceleague.adobe.com/ko/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-request-queue) | 비디오 | 요청 대기열을 설정하고 대기열 세부 정보를 구성하는 방법에 대해 알아봅니다. 다음 단계에 따라 조직에서 작업 접수를 관리할 수 있습니다. |
| 2024년 9월 | [개체에 사용자 정의 양식을 첨부합니다](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/custom-forms-using-a-custom-form) | 비디오 | 사용자 정의 양식을 오브젝트에 첨부하고 사용자 정의 필드를 보고서에 표시하는 방법에 대해 알아봅니다. |
| 2024년 9월 | [사용자 정의 양식 만들기 및 공유](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/custom-forms-creating-and-sharing-a-custom-form) | 비디오 | 사용자 정의 양식을 만들고, 양식에 고유한 필드를 추가하고, 사용자와 양식을 공유하는 방법을 알아봅니다. |
| 2024년 9월 | [자동화된 워크플로 템플릿 편집](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/workfront-proof/proof-workflows/edit-an-automated-workflow-template) | 비디오 | Workfront에서 기존 자동화된 증명 워크플로 템플릿을 변경하는 방법에 대해 알아봅니다. |

<!--
### New [!DNL Workfront] support knowledge base

New articles and updates to existing articles for [!DNL Workfront].

|Published|Name|Type|Description|
| -----------| ---------- | ---------- | ---------- |
|December 2023|[[!DNL Workfront]: Apply layout template](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-23173.html)|New article| Learn how to apply the layout template in four ways: [!UICONTROL User profile], [!UICONTROL Job Role], [!UICONTROL Home Team], and [!UICONTROL Home Group].|
|December 2023|[[!DNL Workfront]: proof failed to generate](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-23149.html)|New article| Learn how to resolve the `Proof Failed to Generate` error when you upload a new proof.|
|December 2023|[[!DNL Fusion]: `Failed to verify connection '52174'. Status Code Error: 500`](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-23142.html)|New article| Learn how to resolve the [!DNL Workfront Fusion] error, `Failed to verify connection '52174'. Status Code Error: 500`.|
|December 2023|[[!DNL Workfront]: Stuck export](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-23080.html)|New article| Learn how to resolve the issue if your [!UICONTROL Kick-start] export or a [!UICONTROL Resource Planner] export is stuck.|
|December 2023|[[!DNL Workfront Fusion]: `JWT Connection Error` for [!DNL AEM Assets Fusion]](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-22911.html)|New article| Learn how to resolve if a `JWT connection error` occurs while configuring a connection for [!DNL AEM Assets as a Cloud Service] using the [!DNL Fusion AEM Assets] module.|
|December 2023|[Project sharing lists are automatically pre-populated on creating new projects](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-23045.html)|New article| Learn how to resolve if project sharing lists get automatically pre-populated.|

{style="table-layout:auto"}
-->

최신 제품 설명서를 보려면 [Adobe [!DNL Workfront] 홈 페이지](https://experienceleague.adobe.com/ko/docs/workfront/using/home)를 참조하십시오.

+++

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Mix Modeler] {#mix-modeler}

+++세부 사항

최신 정보는 다음 페이지를 참조하십시오.

* Mix Modeler [릴리스 정보](https://experienceleague.adobe.com/ko/docs/mix-modeler/using/releases/latest)
* Mix Modeler [제품 설명서](https://experienceleague.adobe.com/ko/docs/mix-modeler)

+++

## ![아이콘](/assets/advertising-cloud.png) Adobe Advertising {#advertising}

[!DNL Adobe Advertising]의 릴리스 정보

+++세부 사항

### [!DNL Advertising DSP]의 새로운 기능 {#advertising-dsp}

[ [!DNL Advertising DSP]의 새로운 기능](https://experienceleague.adobe.com/ko/docs/advertising/dsp/home)을 참조하십시오.

### [!DNL Advertising Search, Social, & Commerce]의 새로운 기능 {#advertising-search}

[ [!DNL Advertising Search, Social, & Commerce]의 새로운 기능](https://experienceleague.adobe.com/ko/docs/advertising/search-social-commerce/home)을 참조하십시오.

+++## ![아이콘](/assets/experience-league.png) Adobe 콘텐츠 공급망 {#content-supply-chain}

Experience League에 대한 최신 튜토리얼은 [콘텐츠 공급망](https://experienceleague.adobe.com/ko/docs/content-supply-chain-learn/tutorials/overview)을 참조하십시오.

<!-- +++Details

| Published | Name | Type | Description |
| -----------| ---------- | ---------- | ---------- |
|February 2024|[Content Supply Chain Tutorials](https://experienceleague.adobe.com/docs/content-supply-chain-learn/tutorials/overview.html)|Videos |View content supply chain tutorials on Experience League. Content supply chain is Adobe's an end-to-end solution to accelerate and simplify your content supply chain with generative AI and intelligent automation.|

{style="table-layout:auto"}

+++ -->

## ![아이콘](/assets/pass.png) [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass]는 매력적이고 개인화된 시청 경험을 통해 수익을 창출할 수 있도록 방송사와 케이블 네트워크 및 서비스 제공업체를 지원하는 멀티스크린 TV 플랫폼입니다.

+++세부 사항

릴리스별 정보, 시스템 요구 사항, 제한 사항, 해결된 문제 및 알려진 문제는 [Adobe Pass 설명서](https://experienceleague.adobe.com/ko/docs/pass)를 참조하십시오.

+++

## ![아이콘](/assets/document-cloud-24.png) [!DNL Document Cloud] {#doc-cloud}

새로운 [!DNL Document Cloud] 튜토리얼이 게시되었습니다([!DNL Acrobat Services] 및 [!DNL Acrobat Sign] 포함).

+++세부 사항

| 게시일 | 애플리케이션 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2024년 9월 | Acrobat | [사용자를 관리자 역할로 승격하는 방법](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/promote-admin.html?lang=en) | 비디오 | Adobe Admin Console을 사용하여 사용자를 Acrobat Sign 관리자 역할로 승격시키는 방법을 알아봅니다. |
| 2024년 9월 | Acrobat | [여러 프로필을 사용하는 방법](https://experienceleague.adobe.com/en/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/multiple-profiles) | 비디오 | 프로필 선택기를 사용하여 여러 Acrobat Sign 계정으로 작업하는 방법을 알아봅니다. |
| 2024년 9월 | Acrobat Sign | [감사 보고서](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/audit-reports) | 비디오 | 조직의 요구 사항에 맞게 감사 보고서에 액세스하고, 사용하고, 구성하는 방법을 알아봅니다. Acrobat Sign의 모든 문서는 거래의 진행 상황을 정의하는 일련의 이벤트 &quot;이정표&quot;를 전달합니다. 이러한 이정표는 모든 트랜잭션에 대한 감사 보고서에 철저히 문서화되어 있습니다. |
| 2024년 9월 | Acrobat Sign | [일괄 다운로드 도구](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/bulk-download-tool) | 비디오 | 일괄 다운로드 도구를 사용하여 서명된 계약을 모두 빠르게 다운로드하는 방법에 대해 알아봅니다. 상당한 시간을 절약할 수 있습니다. 벌크 다운로드 도구는 Windows 및 Mac OS X에서 사용할 수 있습니다. |
| 2024년 9월 | Acrobat Sign | [자동 업데이트 설정](https://experienceleague.adobe.com/en/docs/document-cloud-learn/sign-learning-hub/integrations/salesforce/salesforce-automatic-updates) | 비디오 | 계정을 Salesforce에 쉽게 연결하여 자동 업데이트를 얻는 방법에 대해 알아봅니다. 이를 통해 작업과 정확도를 간소화할 수 있습니다. |
| 2024년 9월 | Acrobat Sign | [개인 정보 관리자를 설정하는 방법](https://experienceleague.adobe.com/en/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/privacy) | 비디오 | Admin Console에서 Acrobat Sign 워크플로에 대한 개인 정보 관리자를 설정하고 사용하는 방법을 알아봅니다. |
| 2024년 9월 | Acrobat Sign | [대용량 파일 및 푸시 매핑 설정](https://experienceleague.adobe.com/en/docs/document-cloud-learn/sign-learning-hub/integrations/salesforce/salesforce-large-files) | 비디오 | Acrobat Sign for Salesforce에서 대용량 문서를 설정하고 계약 서비스를 푸시하는 방법을 알아봅니다. 푸시 동의를 사용하면 문서를 전송하고 웹 양식을 만들 수 있으며 Salesforce에서 만든 것처럼 계약을 푸시할 수 있습니다. |
| 2024년 9월 | Acrobat Sign | [웹 후크 설정 방법](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/sign-learning-hub/develop/custom/webhooks) | 비디오 | 일반적으로 수동 개입이 필요한 프로세스를 자동화하는 웹 후크를 만드는 방법에 대해 알아봅니다. 웹 후크는 구독한 이벤트가 발생할 때 트리거되는 사용자 정의 HTTPS 요청입니다. |
| 2024년 9월 | Acrobat Sign | [보고 및 트랜잭션 사용](https://experienceleague.adobe.com/en/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/creating-a-report) | 비디오 | 보고서를 생성하고 트랜잭션 사용을 추적하는 방법에 대해 알아봅니다. 이러한 보고서에는 서명된 계약의 비율 또는 서명에 소요되는 평균 시간과 같은 정보가 포함될 수 있습니다. 보고서 및 추적 사용을 생성하면 문서 서명 프로세스를 볼 수 있습니다. |
| 2024년 9월 | Acrobat | [안내 작업](https://experienceleague.adobe.com/en/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action) | 비디오 | 최상의 고객 경험을 제공하려면 콘텐츠를 그 어느 때보다 빠르게 만들어야 합니다. 한 번의 클릭으로 여러 문서에서 하나 이상의 명령을 실행하여 시간과 키 입력을 절약하는 가이드 작업을 사용하는 방법에 대해 알아봅니다. |

다음 링크를 통해 [!DNL Document Cloud] 튜토리얼을 살펴보십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/acrobat-learning/overview)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/ko/docs/document-cloud-learn/sign-learning-hub/overview)
* [Adobe Acrobat API 튜토리얼](https://experienceleague.adobe.com/ko/docs/acrobat-services-learn/tutorials/overview)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

+++

## ![아이콘](/assets/creative-cloud-24.png) [!DNL Creative Cloud] for enterprise {#creative-cloud}

[!DNL Adobe Creative Cloud for enterprise]의 앱에 대한 새로운 튜토리얼이 게시되었습니다.

+++세부 사항

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/ko/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview)을 참조하십시오.

+++

## ![Icon](/assets/experience-league.png) 고객 데이터 관리 - 음성 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/ko/docs/events/customer-data-management-voices-recordings/overview)는 고객 데이터 관리 기술 및 마케팅 실무 리더이자 전문가의 대상입니다. 이 튜토리얼 컬렉션을 통해 동료의 의견을 듣고, 영감을 얻고, MarTech의 개발에 대해 종합적으로 배울 수 있습니다. 등록이 필요하지 않습니다. 클릭하여 시청하십시오.

## ![아이콘](/assets/experience-league.png) Digital Experience 블루프린트 {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/ko/docs/blueprints-learn/architecture/overview)는 전략을 다루고 기존 비즈니스 문제를 빠르게 해결하기 위한 반복 가능한 구현입니다. 각 블루프린트는 고가치 비즈니스 문제, 아키텍처, 구현 단계, 기술 고려 사항 및 관련 문서 링크를 설명하는 일련의 아티팩트를 제공합니다.

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/en/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->

