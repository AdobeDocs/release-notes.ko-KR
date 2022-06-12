---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 도움말과 튜토리얼을 찾아보십시오.'
doc-type: release notes
last-update: June 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 5d75fb745b2694e31346b27efdb1d5f71fe91449
workflow-type: tm+mt
source-wordcount: '4691'
ht-degree: 53%

---

# Adobe Experience Cloud 릴리스 정보 - 2022년 6월

![배너](assets/experience-cloud-banner-3.png)

[Experience League](https://experienceleague.adobe.com/?lang=en#home)를 통해 성공적인 Experience Maker로서의 길을 시작해 보십시오. 방대한 입문용 문서 라이브러리, 셀프 가이드 튜토리얼, 입문용 비디오, 모든 레벨과 역할을 위한 과정, 동료들의 온라인 커뮤니티, 필요할 경우 전문가 지원을 찾아보십시오.

>[!NOTE]
>
>이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오. Experience League의 최신 상황을 수시로 확인할 수 있습니다.

최신 업데이트: **2022년 6월 12일**

* [[!DNL Experience League] 이벤트](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 중앙 인터페이스 구성 요소 및 관리](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience 블루프린트 - 튜토리얼](#blueprints)

도움이 필요하십니까? [Experience League](https://experienceleague.adobe.com/?lang=ko-KR/#home)에서 제품 및 기술 문서, Adobe에서 제공하는 교육 과정, 비디오 튜토리얼, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 교육을 확인할 수 있습니다.

## ![아이콘](/assets/experience-league.png) [!DNL Experience League] 이벤트 {#events}

Experience League 이벤트는 Adobe의 제품 전문가로부터 배우고, 상호 작용하고, 답변을 얻을 수 있는 유용한 공간입니다.

업데이트 날짜: **2022년 6월 10일**

| 이벤트 | 유형 | 설명 |
| -----------|---------- | ----|
| Adobe Campaign, Journey Optimizer - [크로스 채널 문제: 규모에 따른 개인화](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) | 가상 이벤트 | Research Director at 451 Research의 Sheryl Kingstone에서 변화 속도를 지속적으로 유지하고 마케팅 기술을 중요한 원동력으로서 사용하고 데이터 중심의 성장을 추구하는 방법에 대해 들어보십시오. 또한 다양한 채널에서 규모에 맞게 개인화를 구현하는 방법에 대한 전문가의 의견을 듣는 2022년 Adobe Summit 동안 공유된 중요한 세션과 팁과 요령을 재방문했습니다.<br>**날짜:** 6월 14일 - [세부 사항 및 등록](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) |
| [후드형 - Cloud Manager 2022](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) | AEM Gems - 가상 이벤트 | 지난해 릴리스된 새로운 기능, 비하인드 개발의 업데이트, 2022년 나머지를 살펴보십시오. <br>**날짜:** 6월 15일 -[세부 사항 및 등록](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) |
| [디지털 전략의 확장을 위해 신뢰와 커뮤니케이션을 구축하는 방법](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) | 마스터스 라운드테이블 | 귀하의 디지털 전략의 효과를 효과적으로 전달할 수 있는 방법을 논의할 수 있는 독점적이고 친밀한 대화입니다. <br>**날짜:** 6월 21일 - [세부 사항 및 등록](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) |
| [Experience Makers Live](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) | 비디오 및 가상 이벤트 | Adobe Experience Maker Award는 게임 변경 고객 경험과 놀라운 디지털 혁신을 2022 Adobe Experience Maker Award에서 기념합니다. <br>미주, 일본, 인도, 호주 및 뉴질랜드를 위한 행사에 참가하세요 **6월 22일**<br>&#x200B;유럽, 중동, 아프리카를 위한 행사에 참가하세요 **6월 23일** <br> [세부 정보 및 등록](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) |
| [전문가에게 문의 - Real-Time CDP 연결](https://www.youtube.com/watch?v=hVwtxDYvzw4) | Experience League LIVE | Adobe에서 자주 사용하는 Adobe 전문가는 고객이 서버측 태그 관리 시스템을 사용하여 이벤트를 모든 대상에 전달할 수 있는 Adobe의 Real-Time CDP 연결 제품을 광범위하게 살펴봅니다.<br>**날짜:** 6월 23일 오전 9시 - [세부 사항](https://www.youtube.com/watch?v=hVwtxDYvzw4) |
| [전문가에게 질문하기: Web SDK 기본 사항](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-05-26-22.html) | Experience League 라이브 | 데이터 수집 모범 사례를 이해하고 활용합니다. <br>[예약 및 이전 이벤트](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=ko) |
| [The Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/overview.html?lang=en) | 기록된 세션 | Adobe Experience Cloud 솔루션에 대한 심층적인 작업에 중점을 두고 전 세계 일련의 가상 고객 학습 이벤트를 보려면 Skill Exchange 를 방문하십시오. |
| [Experience Makers 공공기관 포럼](https://adobegovforum.govexec.com/agenda/) | 온디맨드 비디오 | 5월 10일에 개최된 제13회 연례 AEMGF는 가상 참석자와 실제 참석자의 조합으로 성공적으로 진행되었습니다. 메인 스테이지 및 브레이크아웃 세션은 _사람 우선의 디지털 경험_&#x200B;이라는 주제에 초점을 맞췄습니다. 상위 세션에는 _Manhunters: 우리는 어떻게 Pablo Escobar를 무너뜨렸는가_, _CX의 미래_ 및 _창의성의 황금기와 현대적 일터_&#x200B;가 포함되었습니다. |
| [Adobe [!DNL Developers Live]: Commerce](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=kr) | 온디맨드 비디오 | _Adobe Developers Live: Commerce 2022_&#x200B;는 다양한 배경과 하나의 목적을 가진 개발자와 경험 빌더를 한데 모아 놀라운 통합 경험을 만듭니다. 이 하루 동안의 가상 컨퍼런스에서는 중요한 Commerce 및 오픈 소스 개발자 업데이트, 기술 세션, 커뮤니티 네트워킹 기회 등을 제공합니다. |
| [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=kr) | 온디맨드 비디오 | Marketo 로드맵의 중요성과 잘못된 계획을 피하는 방법에 대해 알아보십시오. 현재 Experience League에서 2021년 8월부터 [!DNL Marketo] Skill Exchange에서 프로그램 멤버 맞춤형 필드의 잠재적인 기능을 잠금 해제하는 방법, Marketo Engage 팁 및 트릭 등에 대한 조언을 얻으십시오. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

최신 릴리스 정보는 Adobe 시스템 상태 [릴리스 정보](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ko#status)를 참조하십시오.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud - 중앙 인터페이스 구성 요소 및 관리 {#ecloud}

Experience Cloud [중앙 UI 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko)에는 홈 페이지 및 영구 제품 헤더에서 사용할 수 있는 기능이 포함됩니다. 이러한 기능에는 사용자 프로필 설정, 환경 설정 및 검색이 포함됩니다. 사용자 및 제품 관리, 고객 속성 및 Experience Cloud Audiences에 대한 도움말도 찾을 수 있습니다.

예정된 릴리스: **2022년 7월 11일**

| 기능 | 설명 |
| ------- | ------- |
| 통합 홈 - 빠른 액세스 위젯 | **더욱 빠르게 탐색:** 이제 홈 경험을 추가로 개인화하고 원하는 애플리케이션을 손쉽게 결정할 수 있습니다. 새로운 고정 기능을 사용하여 [!UICONTROL 빠른 액세스]. <br>**고급 피닝으로 계속 정보 제공:** 이제 새 응용 프로그램을 찾기가 쉬워졌습니다. 새로 지정된 응용 프로그램은 _새로 만들기_ 배지 및 자동 고정 [!UICONTROL 빠른 액세스]. |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] 및 관리에 대한 추가 도움말 리소스**

* Experience Cloud Central UI 구성 요소에 대한 [릴리스 정보](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=ko)
* Experience Cloud(관리자)의 [사용자 및 제품 관리](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [릴리스 정보](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko)
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ko)에 대한 제품 설명서
* 오브젝트 및 엔티티에 대한 [통합 검색](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=ko)

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 및 [!UICONTROL Mobile SDK]에 대한 최신 릴리스 정보와 새로운 설명서:

예정된 릴리스: **2022년 6월 22일**

* [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko)

### 새로운 [!DNL Experience Platform] 튜토리얼 및 교육 과정 {#tutorials-platform}

[!DNL Experience Platform]용으로 게시된 새로운 비디오 튜토리얼, 문서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 6월 | [관리자를 위한 실시간 CDP 시작하기](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2022.1.rtcdp) | 교육 과정 | 을 시작하고 실행하는 데 필요한 관리 작업을 소개합니다 [!DNL Real-time Customer Data Platform]. 사용자 관리 및 다른 파트너 및 시스템과의 연결을 설정하는 방법에 대해 알아봅니다. | [!DNL Real-time CDP] |
| 2022년 6월 | [세그먼트 활성화 성공 모니터링](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-the-success-of-segment-activation.html?lang=en) | 비디오 | 대상으로 세그먼트의 흐름을 모니터링하는 두 가지 기본 방법을 알아봅니다. 활성화 파트너에게 세그먼트 프로필을 보낼 때 특히 문제를 해결할 수 있도록 이 데이터 전송의 성공에 대한 정보를 확인해야 합니다. | [!DNL Real-time CDP] |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 정보 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

다음 릴리스: **2022년 6월 15일**

최신 업데이트: **2022년 6월 8일**

* Adobe Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ko)
* Adobe Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html?lang=ko)

### AppMeasurement {#appm}

릴리스 버전: **2.22.4**

* [JavaScript 릴리스 정보의 AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ko)

### 새로운 [!DNL Analytics] 튜토리얼 및 교육 과정 {#tutorials-analytics}

Adobe Analytics용으로 게시된 새로운 비디오 튜토리얼, 문서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 6월 | [Adobe Analytics 데이터 내보내기 및 대중화](https://experienceleague.adobe.com/docs/courses/using/analytics-a-1-2022-1-democratizing.html?lang=en) | 교육 과정 | 디지털 데이터를 민주화할 수 있도록 지원하는 Adobe Analytics의 기능에 대해 알아봅니다. 데이터 민주화는 병목 현상을 제거하고 조직의 주요 직원이 데이터를 편리하게 사용하여 데이터를 지능적으로 의사 결정할 수 있도록 하는 프로세스입니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

마지막 업데이트: **2022년 5월 19일**

* Customer Journey Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ko)
* Customer Journey Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ko)

### 새로운 Customer Journey Analytics 튜토리얼 및 교육 과정 {#tutorials-cja}

CJA용으로 게시된 새로운 비디오, 자습서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 6월 | [데이터 보기의 바인딩 차원](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/binding-dimensions-in-data-views.html?lang=en) | 비디오 | 바인딩 차원에 대해 기울입니다. 이 기능을 사용하면 한 차원을 가져와 다른 차원에 연결하여 보다 세밀하게 지속성 할당을 수행할 수 있습니다. |
| 2022년 6월 | [Customer Journey Analytics 랜딩 페이지](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/cja-basics/customer-journey-analytics-landing-page.html) | 비디오 | Customer Journey Analytics 랜딩 페이지는 프로젝트 및 모바일 스코어카드 기본 보기와 학습 섹션을 통해 더욱 효과적으로 시작할 수 있습니다. |
| 2022년 6월 | [Adobe Analytics 데이터 수집, 매핑 및 변형](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-prep/ingest-map-and-transform-adobe-analytics-data.html) | 비디오 | 에 데이터 준비 기능을 사용하는 방법을 알아봅니다. [!DNL Analytics] 데이터 조작 기능을 포함한 데이터입니다. 예를 들어 Analytics 변수를 새로운 사용자 지정 필드에 매핑하고 변형과 계산을 수행할 수 있습니다. |
| 2022년 6월 | [하위 문자열 구성 요소 설정 구성](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configure-substring-component-settings.html) | 비디오 | Customer Journey Analytics 보고서에서 차원 값의 원하는 부분을 얻기 위해 문자열 조작 방법을 사용하는 방법을 알아봅니다. 적용된 데이터 변환은 소급하여 즉시 수행됩니다. |
| 2022년 6월 | [모바일 스코어카드 만들기](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html) | 비디오 | 경영진 사용자를 위한 대시보드를 구성하고 제공하는 방법을 알아봅니다. |
| 2022년 6월 | [연결 생성 및 편집 경험](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/cja-connections-creation-and-edit-experience.html) | 비디오 | 롤링 데이터 보존 기간을 활성화하고, 이벤트 타임스탬프를 기반으로 데이터 채우기 활성화 및 요청을 수행하고, 데이터 세트별로 기존 데이터를 가져오는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

마지막 업데이트: **2022년 3월 23일**

* [!DNL Streaming Media Analytics] [릴리스 정보](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=ko)
* [!DNL Streaming Media Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=ko)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 수정 및 개선 사항:

| 개선 사항 | 설명 |
| -----------| ---------- |  
| 다른 회사에 속한 대상 데이터 소스의 유효성 검사기 | Audience Manager는 [배치 데이터 온보딩 프로세스](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=ko)에 대한 개선 사항을 발표했습니다. 파일 및 데이터가 실수로 다른 파트너가 소유한 대상 데이터 소스에 온보딩되는 것을 방지하기 위해, Audience Manager는 파트너 ID(PID)와 다른 파트너가 소유한 데이터 소스(DPID) 간의 매핑 요구 사항을 추가했습니다. <ul><li>[인바운드 데이터 파일에 대한 Amazon S3 이름 및 파일 크기 요구 사항](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=ko#name-elements)의 __DPID_TARGET_DATA_OWNER_ 필드도 참조하십시오.</li><li>Adobe 내부 컨설턴트 및 고객 지원 팀에서 새 매핑 요청 방법 및 개선이 필요한 새 매핑에 대한 정보를 보려면 [타사 데이터에 대한 온보딩 액세스 관리](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=ko)를 참조하십시오.</li><li>기존 데이터 공유 관계에 대한 매핑을 요청할 필요는 _없습니다_. PID에 속하는 대상 데이터 소스에 데이터를 온보딩할 때도 매핑이 필요하지 _않습니다_.</li></ul> |

{style=&quot;table-layout:auto&quot;}

자가 진단 리소스에 대한 자세한 내용은 Experience League에서 [Audience Manager 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/audience-manager.html?lang=ko)을 참조하십시오.

## ![아이콘](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온프레미스 배포를 사용하는 것이 좋습니다.

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ko) 페이지를 방문할 것을 권장합니다.

### Experience Manager 제품 업데이트

* **Experience Manager as a Cloud Service**

   보기 [2022년 5월 릴리스 개요 비디오](https://video.tv.adobe.com/v/343321/?quality=12) 2022.5.0(2022년 5월) 릴리스에 추가된 기능에 대한 요약은 를 참조하십시오. <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022년 4월 릴리스 개요 비디오](https://video.tv.adobe.com/v/342612?quality=12)
   * [2022년 3월 릴리스 개요 비디오](https://video.tv.adobe.com/v/341465).
   * [2022년 1월 릴리스 개요 비디오](https://video.tv.adobe.com/v/340120).
   * [2021년 12월 릴리스 개요 비디오](https://video.tv.adobe.com/v/339278).
   * [2021년 10월 릴리스 개요 비디오](https://video.tv.adobe.com/v/338253).
   * [2021년 9월 릴리스 개요 비디오](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _프리릴리스 채널의 새로운 기능_

   * 다양한 GraphQL 기능.
   * A [새 콘솔](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/content-fragments/content-fragment-console.html?lang=en) 컨텐츠 조각의 헤드리스 사용을 위해 최적화되었습니다.

* **Experience Manager Assets as a Cloud Service**

   _새로운 기능_

   * [Dynamic Media 스마트 이미징은 이제 AVIF 파일 형식을 지원합니다](https://medium.com/adobetech/one-solution-fits-all-smart-imaging-with-aem-dynamic-media-be690b62df9f) - WebP에 비해 20% 더 큰 크기를 감소시킨 AVIF를 사용하여 Google Core Web Vital(가장 큰 컨텐츠 페인트)을 더욱 개선합니다. 총 AVIF는 JPEG에 비해 최대 41%의 평균 크기 감소를 제공합니다(일부 이미지에서 76%까지 높이).
   * 이제 Experience Manager Assets Brand Portal은 12시간마다 자동 작업을 실행하여 Experience Manager에 게시된 모든 Brand Portal 자산을 삭제합니다. 따라서 폴더 크기를 임계값 제한 이하로 유지하려면 기여도 폴더에서 자산을 수동으로 삭제할 필요가 없습니다. 자세한 내용은 [Experience Manager Assets Brand Portal의 새로운 기능](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/whats-new.html?lang=ko-KR).

   _프리릴리스 채널의 새로운 기능_

   * Experience Manager Assets은 Adobe Sensei AI 기능을 사용하여 이제 [이미지의 색상을 구별하고 수집 시 자동으로 태그로 차이를 적용합니다](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en). 이러한 태그는 이미지 색상 구성에 따라 향상된 검색 환경을 제공합니다. 1에서 40 범위의 이미지에 태그가 지정된 색상의 수를 구성하여 나중에 해당 색상을 기반으로 이미지를 검색할 수 있도록 할 수 있습니다.


* **Experience Manager Forms as a Cloud Service**

   _사전 릴리스 채널의 새로운 기능_

   * **Microsoft® Power Automate와 적응형 Forms 통합** - 이제 제출 시 Microsoft® Power Automated Cloud Flow를 실행하도록 적응형 양식을 구성할 수 있습니다. 구성된 적응형 양식은 캡처된 데이터, 첨부 파일 및 기록 문서를 Power Automatic Cloud Flow로 전송하여 처리합니다. Microsoft® Power Automate의 기능을 활용하여 사용자 정의 데이터 캡처 경험을 구축하고 캡처된 데이터를 중심으로 비즈니스 로직을 구축하고 고객 워크플로우를 자동화할 수 있습니다.
   * **적응형 양식 만들기 마법사** - 비즈니스 사용자에게 친숙한 마법사를 사용하여 응용 Forms을 빠르게 작성할 수 있습니다. 이 마법사는 적응형 양식을 만들기 위해 사전 구성된 템플릿, 스타일 지정, 필드 및 제출 옵션을 쉽게 선택할 수 있도록 빠른 탭 탐색을 제공합니다.

* **Experience Manager as a Cloud Service 기반**

   _새로운 기능_

   * 다음 **[!UICONTROL 트리 추가]** 복제 에이전트 관리 화면의 옵션 **[!UICONTROL 배포]** 이전에 더 이상 사용되지 않는다고 발표된 탭은 2022년 6월 20일 또는 그 다음 단계에 제거됩니다. 컨텐츠 계층 구조의 패키지를 대신 [게시 관리](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 또는 [컨텐츠 트리 게시 워크플로우](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow).
   * 10MB보다 큰 컨텐츠 패키지(바이너리를 포함하지 않는 속성이 있는 노드)를 배포하기 위해 복제 에이전트 관리 화면 또는 복제 API를 사용하는 것은 더 이상 사용되지 않으며, 2022년 9월 12일 또는 그 다음 단계에 적용됩니다. 대신, [게시 관리](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 또는 [컨텐츠 트리 게시 워크플로우](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow) 이 큰 컨텐츠 패키지를 복제하려면 를 사용해야 합니다. 2022년 7월에 복제 에이전트 관리 화면의 **[!UICONTROL 배포]** 탭. 이 메시지는 이러한 큰 컨텐츠 패키지를 복제하려고 하는 경우, 복제 API를 사용하여 이러한 큰 컨텐츠 패키지를 복제할 때마다 Experience Manager 오류 로그에도 표시됩니다. 9월에는 경고가 오류로 대체됩니다. Adobe은 그에 따라 프로세스를 조정하도록 권장합니다.

   _프리릴리스 채널의 새로운 기능_

   * 이제 Experience Manager as a Cloud Service은 통합 셸과 통합되어 사용자 경험을 향상하고 다른 모든 Experience Cloud 애플리케이션과 통합할 수 있습니다. 자세한 내용은 [통합 셸의 as a Cloud Service Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/overview/aem-cloud-service-on-unified-shell.html?lang=en) 자세한 내용


* **as a Cloud Service Foundation 보안 Experience Manager**

   * **TLS 1.0 및 TLS 1.1 사용 중단** - 2022년 6월 30일부터, Experience Manager as a Cloud Service은 보다 안전한 네트워크 통신과 사용자 시스템과의 데이터 교환을 필요로 합니다. Experience Manager은 TLS(Transport Layer Security) 1.2 프로토콜만 사용합니다. TLS 1.0 및 1.1은 더 이상 사용되지 않습니다.

      TLS 1.0 또는 TLS 1.1을 계속 사용하는 경우 Experience Manager as a Cloud Service에 대한 액세스 권한을 잃을 수 있습니다.

### 커뮤니티

* 재생 [Experience Manager as a Cloud Service 2022.5.0 릴리스 업데이트 비디오](https://adobe.ly/3NDPR8Y) 그것은 발표된 것을 포함합니다. (10분)
* GEM 웨비나 - _후드를 보면 Cloud Manager 2022_
   * 2022년 6월 15일 수요일
   * 08:00 태평양 표준시 17:00 중부 유럽 시간; 20:30 인도 표준시
   * [여기에서 등록](https://adobe.ly/3t4jfgp).
   * [토론 스레드](https://adobe.ly/3O0rdzd).

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022년 6월 | [[!DNL Forms] 포털 구성 요소](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/forms-portal-components.html?lang=en) | 비디오 | 활성화 방법 알아보기 [!DNL AEM Forms] [!UICONTROL 포털] Forms Cloud Service의 구성 요소. | AEM Forms CS |
| 2022년 6월 | [AEM 및 CIF 프레임워크를 통합하여 풍부하고 매력적인 전자 상거래 경험을 구축하십시오](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aem-and-cif-framework-integration.html?lang=en) | 비디오 | Adobe의 CIF 프레임워크를 사용하여 일관된 컨텐츠 및 몰입형 상거래 환경을 구축하는 방법을 이해합니다. | AEM 및 CIF 프레임워크 |
| 2022년 6월 | [SAML 2.0 인증](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/authentication/saml-2-0.html) | 비디오 | 선택한 SAML 2.0 호환 IDP에 최종 사용자(AEM 작성자가 아님)를 설정하고 인증하는 방법을 알아봅니다. | AEM CS |
| 2022년 6월 | [컨텍스트 인식 클라우드 구성](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/context-aware-fdm.html?lang=en) | 비디오 | Cloud Service 시 AEM Forms에서 컨텍스트 인식 클라우드 구성을 정의하는 방법을 알아봅니다. | AEM Forms |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보

모든 Experience Manager 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [Experience Manager as a Cloud Service 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ko)
* [Experience Manager Cloud Manager 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=ko)
* [자동 양식 전환 서비스 릴리스 정보](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ko)
* [Experience Manager 6.5 서비스 팩 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=ko)
* [Experience Manager 6.4 Cumulative Fix Pack 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ko)
* [Experience Manager Assets Dynamic Media 릴리스 정보](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ko)
* [Experience Manager Brand Portal 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ko)
* [Experience Manager 데스크탑 앱 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ko)
* [Experience Manager Dispatcher 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ko)
* [Adobe Primetime 릴리스 정보](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ko)
* [Livefyre 릴리스 정보](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ko)

### Experience Manager용 기타 도움말 리소스

* [Experience Manager as a Cloud Service 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=ko)
* [Cloud Manager 사용 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ko)
* [Experience Manager 6.5 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ko)
* [Experience Manager 6.4 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ko)
* [Experience Manager 6.3 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko)
* [Experience Manager 6.2 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko#previous-updates)
* [이전 버전의 Experience Manager 설명서](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 도움말 홈](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ko)
* [Experience Manager 설명서: 최신 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ko#aem-as-a-cloud-service)

## ![아이콘](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] (이전 [!DNL XML Documentation for Experience Manager])은 AEM에 배포된 애플리케이션입니다. Adobe Experience Manager의 기본 DITA 지원을 활성화하는 강력한 엔터프라이즈급 구성 요소 콘텐츠 관리 솔루션(CCMS)으로, AEM에서 DITA 기반 콘텐츠 생성 및 전달을 처리할 수 있도록 촉진합니다.

추가 정보 [[!DNL Experience Manager Guides]](https://www.adobe.com/kr/products/xml-documentation-for-experience-manager/features.html).

### 추가 리소스

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=ko) - Experience League에 대한 자습서
* [[!DNL Experience Manager Guides] 학습 및 지원](https://helpx.adobe.com/kr/support/xml-documentation-for-experience-manager.html) - 제품 설명서

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source 2.4.x 릴리스 정보](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 릴리스 정보](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 새로운 Adobe Commerce 자습서 및 설명서 {#tutorials-commerce}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 6월 | [MBI 시작하기](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/getting-started.html?lang=en) | 비디오 | 사용 가능한 사전 구성된 대시보드 및 사용자 지정 옵션에 대해 자세히 살펴보면서 상거래 제품 팀에서 직접 MBI의 핵심 기능에 대해 알아보십시오. |
| 2022년 6월 | [MBI의 데이터 세트 관리](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/manage-data-sets.html?lang=en) | 비디오 | Adobe Commerce 제품 팀에서 직접 MBI Data Warehouse 관리자의 몇 가지 강력한 기능에 대해 알아보십시오. 기본 보고서 작성 이외의 작업을 수행하고 데이터를 사용하여 더 많은 작업을 수행하는 방법을 알아보십시오. |
| 2022년 6월 | [MBI Data Warehouse 최적화](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/optimize-data-warehouse.html?lang=en) | 비디오 | 테이블 및 열 동기화 설정을 관리하고 테이블의 스키마로 드릴다운하고 보고서에 사용할 계산된 열을 만드는 방법을 알아봅니다. |
| 2022년 6월 | [MBI를 사용한 휴일 준비](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/holiday-readiness.html?lang=en) | 비디오 | 일반적인 계절별 분석 사용 사례 및 주요 MBI 기능을 사용하여 이를 처리하는 방법을 알아봅니다. |
| 2022년 6월 | [MBI - 전문가에게 문의](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/ask-expert.html?lang=en) | 비디오 | 이 두 부분으로 구성된 웨비나에서는 고객이 Business Intelligence에 대해 말하는 내용을 알아봅니다. 공통 테이블 표현식을 사용하여 Business Intelligence, SQL 최적화 등을 통해 비즈니스 변형을 살펴볼 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/target.png) [!DNL Adobe Target] {#target}

마지막 업데이트 날짜: **2022년 6월 7일**

* 이전 릴리스에 대한 자세한 내용은 [Adobe Target 프리릴리스](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [Adobe Target 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ko)를 참조하십시오.

### 새로운 Adobe Target 교육 과정 및 자습서 {#tutorials-target}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 6월 | [linktext](https://experienceleague.adobe.com/?recommended=Target-D-1-2021.1) | 교육 과정 | 웹 사이트에서 Adobe Target을 구현하는 방법을 알아봅니다. 이 교육 과정에서는 요구 사항 및 사용자 권한을 포함한 관리 항목부터 구현 방법, 고려 사항 및 모범 사례를 다룹니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

* 새로 만들기 [Campaign v8.3 릴리스](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/release-notes.html)
* 새로 만들기 [Campaign Standard 22.2 릴리스](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ko)
* 새로 만들기 [Campaign 컨트롤 패널 5월 릴리스](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en#may-2022)
* 새로 만들기 [튜토리얼 및 교육 과정](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) Experience League 시

### 새로운 [!DNL Campaign] 튜토리얼 및 교육 과정 {#tutorials-campaign}

Adobe Campaign용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 6월 | [게재 템플릿 구성](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/configure-a-delivery-template.html) | 비디오 | 임시 게재용 템플릿을 구성하는 방법을 알아봅니다. | Campaign v8 |
| 2022년 6월 | [반복 및 연속 이메일 게재 만들기](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/recurring-deliveries.html) | 비디오 | 반복 게재 및 스케줄러 활동을 구성하는 방법을 알아봅니다. | Campaign v8 |
| 2022년 6월 | [데이터 보강 활동 구성](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/enrichment-activity.html) | 비디오 | 게재 로그 정보를 기반으로 데이터 보강 활동을 구성하는 방법을 알아봅니다. | Campaign v8 |
| 2022년 6월 | [SMS 소개](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/introduction-to-sms.html) | 비디오 | SMS란 무엇입니까? SMS 서비스 공급자의 역할, Adobe Campaign이 서비스 공급자에 연결되어 있는 방식을 알아봅니다. 서비스 공급자를 통해 전달되는 정보와 사용 가능한 기술 노트를 파악합니다. | Campaign v8, Campaign Standard, Campaign Classic v7 |
| 2022년 6월 | [표준 SMPP 공급자에 대한 SMS 계정 설정](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/set-up-account-for-standard-smpp-provider.html?lang=en) | 비디오 | Adobe Campaign을 사용하여 SMPP 계정을 설정하는 방법, SMS 게재 결과를 분석하고 SMPP 공급자 사양에 따라 SR 처리를 사용자 지정하는 방법을 알아봅니다. | Campaign v8, Campaign Classic v7 |
| 2022년 6월 | [SMPP 공급자에 SMS 커넥터 조정](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/adapt-sms-connector-to-smpp-provider.html) | 비디오 | SMS 커넥터를 SMPP 공급자에게 적용하는 방법을 알아봅니다. SMS 설정을 미세 조정하여 연결 제한을 처리하고, 최대 처리량, 전송 창 및 TLS를 사용한 암호화를 설정합니다. | Campaign v8, Campaign Classic v7, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [설명서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ko)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ko) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ko) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ko)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ko) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ko) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ko)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ko) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ko) 방법 비디오

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer를 사용하면 단일 애플리케이션에서 수백만 고객을 위한 예정된 옴니채널 캠페인과 일대일 순간을 관리할 수 있으며, 지능적인 의사 결정과 통찰력으로 전체 여정을 최적화할 수 있습니다.

### 최신 Journey Optimizer 제품 릴리스

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ko-KR)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ko)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ko)

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 고객 여정을 조율할 수 있습니다.

### 최신 [!DNL Journey Orchestration] 제품 릴리스

[[!DNL Journey Orchestration] 릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ko)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

#### [!DNL Journey Orchestration]를 위한 추가 리소스

* [Journey Orchestration 설명서](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ko) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ko)

## ![아이콘](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 주요 Marketo Engage 업데이트

최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ko)을 참조하십시오.

## ![아이콘](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront]는 아이디어 공유, 콘텐츠 생성, 복잡한 프로세스 관리 및 최상의 작업 수행을 위한 통합 작업 관리 애플리케이션입니다.

모든 제품에 대한 최신 정보를 보려면 [[!DNL Workfront] 릴리스](https://one.workfront.com/s/product-releases) 페이지를 참조하십시오.

## ![아이콘](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP]의 새로운 기능](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search]의 새로운 기능](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### [!DNL Advertising Cloud DSP]의 새로운 기능 {#adcloud-dsp}

마지막 업데이트: **2022년 6월 8일** 5월 31일 릴리스

| 기능 | 설명 |
| ------- | ----------- |
| 맞춤형 보고서 | (베타 기능) 이제 Advertising Cloud DSP에서 고객 데이터 플랫폼(CDP) 내에서 구축된 인증된 신호로 구성된 자사 세그먼트를 수집할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

마지막 업데이트: **** 2022년 6월 8일, 6월 11일 릴리스

| 기능 | 설명 |
| ------- | ----------- |
| [!UICONTROL Insights] | 이제 노출 공유 손실됨 분석을 베타 기능으로 다시 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud용으로 게시된 새로운 튜토리얼 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 6월 | [위임 역할 사용](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | 비디오 | 위임자 역할을 사용하여 문서를 진술자에게 보낸 다음 문서를 서명을 위해 라우팅할 수 있는 방법을 알아봅니다. |
| 2022년 6월 | [이벤트 및 경고에 대한 알림 구성](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/set-up-shared-events-and-alert.html?lang=en) | 비디오 | Acrobat Sign에서 구성할 수 있는 공유 이벤트 및 경고 설정에 대해 알아봅니다. 경고는 특정 시간 프레임에서 발생하지 않은 작업이며 이벤트는 발생한 작업입니다. |
| 2022년 6월 | [고급 계정 공유](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/advanced-account-sharing.html?lang=en) | 비디오 | 고급 계정 공유를 설정하는 방법을 알아봅니다. 관리자 및 사용자는 보내기, 수정 및 보기 권한을 위임할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko)을 참조하십시오.

## ![Icon](/assets/experience-league.png) 고객 데이터 관리 - 음성 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=ko)는 고객 데이터 관리 기술 및 마케팅 실무 리더이자 전문가의 대상입니다. 이 튜토리얼 컬렉션을 통해 동료의 의견을 듣고, 영감을 얻고, MarTech의 개발에 대해 종합적으로 배울 수 있습니다. 등록이 필요하지 않습니다. 클릭하여 시청하십시오.

## ![아이콘](/assets/experience-league.png) Digital Experience 블루프린트 {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=ko)는 전략을 다루고 기존 비즈니스 문제를 빠르게 해결하기 위한 반복 가능한 구현입니다. 각 블루프린트는 고가치 비즈니스 문제, 아키텍처, 구현 단계, 기술 고려 사항 및 관련 문서 링크를 설명하는 일련의 아티팩트를 제공합니다.

[맨 위로](#events)
