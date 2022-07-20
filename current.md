---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 도움말과 튜토리얼을 찾아보십시오.'
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: bd6e90a7cbb0f07b21c65b6486fb65327fce6003
workflow-type: tm+mt
source-wordcount: '5574'
ht-degree: 49%

---

# Adobe Experience Cloud 릴리스 정보 - 2022년 7월

![배너](assets/experience-cloud-banner-3.png)

[Experience League](https://experienceleague.adobe.com/?lang=en#home)를 통해 성공적인 Experience Maker로서의 길을 시작해 보십시오. 방대한 입문용 문서 라이브러리, 셀프 가이드 튜토리얼, 입문용 비디오, 모든 레벨과 역할을 위한 과정, 동료들의 온라인 커뮤니티, 필요할 경우 전문가 지원을 찾아보십시오.

>[!NOTE]
>
>이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오. Experience League의 최신 상황을 수시로 확인할 수 있습니다.

최신 업데이트: **2022년 7월 19일**

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

Experience League 이벤트는 Adobe의 제품 전문가로부터 배우고, 상호 작용하고, 답변을 얻을 수 있는 유용한 공간입니다. 자세한 내용은 [이벤트](https://experienceleague.adobe.com/events/?lang=en) Experience League 시 2022년 7월에 업데이트됨.

업데이트됨 **2022년 7월 17일**

| 이벤트 | 유형 | 설명 |
| -----------|---------- | ----|
| [전문가에게 문의: 데이터 저장소 및 데이터 준비](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) | Experience League LIVE | Adobe Experience Cloud의 데이터 수집에 대한 이 세 가지 세션의 마지막 단계에서는 데이터 수집을 위한 데이터 준비와 같은 기능을 포함하여 Adobe의 고급 데이터 수집 기능에 대해 자세히 살펴봅니다. 이 세션이 끝날 때 참석자는 디지털 경험에서 데이터를 수집할 수 있는 최신 및 강력한 기능을 확신하고 있습니다&#x200B;<br>**날짜:** 7월 21일 @ 9시 PDT - [세부 사항](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

자세한 내용은 [이벤트](https://experienceleague.adobe.com/events/?lang=en) Experience League에서 예정된 이벤트와 과거 에피소드에 대해 최신 정보를 확인하십시오.

## ![아이콘](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

최신 릴리스 정보는 Adobe 시스템 상태 [릴리스 정보](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ko#status)를 참조하십시오.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud - 중앙 인터페이스 구성 요소 및 관리 {#ecloud}

Experience Cloud [중앙 UI 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko)에는 홈 페이지 및 영구 제품 헤더에서 사용할 수 있는 기능이 포함됩니다. 이러한 기능에는 사용자 프로필 설정, 환경 설정 및 검색이 포함됩니다. 사용자 및 제품 관리, 고객 속성 및 Experience Cloud Audiences에 대한 도움말도 찾을 수 있습니다.

### 프로비저닝 업데이트

업데이트됨: **2022년 7월 19일**

>[!IMPORTANT]
>
>Experience Cloud 프로비저닝에 대한 다음 알림을 검토하십시오.

Adobe은 모든 Experience Cloud 고객이 일부 Experience Cloud 제품 간의 상호 운용성을 지원하는 기본 기능에 액세스할 수 있도록 프로비저닝을 업데이트하고 있습니다. 사용자는 Experience Cloud 조직에 추가된 새 자격 부여 권한으로서 Adobe Experience Platform을 갖게 됩니다. [!UICONTROL 데이터 수집] 를 포함한 서비스로 사용할 수 있습니다.

Adobe Experience Platform [!UICONTROL 데이터 수집] include [태그](https://experienceleague.adobe.com/docs/tags.html?lang=en) 간소화된 범용 태그 관리를 위해 그리고 신뢰할 수 있고 강력하고 완벽한 스트리밍 데이터 인프라를 제공합니다. 태그는 고객 경험 데이터 수집을 단순화하고 경험 전달을 간소화합니다.

이 업데이트 관리자는 Admin Console에 대한 변경 사항이나 추가 사항을 볼 수 있습니다.

1. Admin Console의 Adobe Experience Platform 제품 카드에 포함되는 항목:

   * 장소
   * 보증
   * ID 네임스페이스
   * 샌드박스
   * 경험 데이터 모델
   * 스키마
   * 데이터스트림
   * 방문자 ID

   현재 Experience Platform을 사용하지 않는 조직의 경우 _Adobe Experience Platform_ 위에 나열된 기능을 포함하여 Admin Console의 제품입니다.

   현재 Experience Platform을 사용하는 조직의 경우 _위치_ 이제 Experience Platform 카드에 통합됩니다.

1. Adobe Experience Platform 데이터 수집(이전의 Launch) 및 개인 정보 는 다른 Experience Platform 기능과 별도의 제품 카드로 계속 표시됩니다.

새로운 기능에 대한 자세한 내용은 Experience League의 해당 페이지를 참조하십시오.

* [데이터 수집](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [장소](https://experienceleague.adobe.com/docs/places/using/home.html?lang=en)
* [보증](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html%3Flang%3Dde)
* [ID 네임스페이스](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=ko)
* [샌드박스](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=ko-KR)
* [경험 데이터 모델](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=ko)
* [스키마](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=ko-KR)
* [데이터스트림](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [방문자 ID](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [개인 정보 보호](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=ko)

기능 업데이트: **2022년 7월 11일**

| 기능 | 설명 |
| ------- | ------- |
| 통합 홈 - 빠른 액세스 위젯 | **더 빠른 이동:** 이제 홈 환경을 더욱 개인화하고 원하는 애플리케이션을 결정할 수 있습니다. 새로운 고정 기능을 사용하여 [!UICONTROL 빠른 액세스]의 전면과 중앙에 표시되는 애플리케이션을 선택하십시오. <br>**스마트 고정 기능으로 최신 정보 수신:** 이제 새 애플리케이션을 더 쉽게 찾을 수 있습니다. 새로 할당된 애플리케이션에는 _신규_ 배지가 표시되고 [!UICONTROL 빠른 액세스]에 자동으로 고정됩니다. |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] 및 관리에 대한 추가 도움말 리소스**

* Experience Cloud Central UI 구성 요소에 대한 [릴리스 정보](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=ko)
* Experience Cloud(관리자)의 [사용자 및 제품 관리](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [릴리스 정보](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko)
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ko)에 대한 제품 설명서
* 오브젝트 및 엔티티에 대한 [통합 검색](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=ko)

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 및 [!UICONTROL Mobile SDK]에 대한 최신 릴리스 정보와 새로운 설명서:

릴리스 예정일: **2022년 7월 27일**

* [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko)

### 새로운 [!DNL Experience Platform] 튜토리얼 및 교육 과정 {#tutorials-platform}

[!DNL Experience Platform]용으로 게시된 새로운 비디오 튜토리얼, 문서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 7월 | [이벤트 전달 모니터링](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | 비디오 | 데이터 수집 인터페이스에서 이벤트 전달을 모니터링하는 방법을 알아봅니다. | 데이터 수집 |
| 2022년 7월 | [데이터 수집 모니터링](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | 비디오 | 모니터링 대시보드를 사용하여 Adobe Experience Platform에 수집되는 데이터를 모니터링하고 추적하는 방법을 알아봅니다. | 데이터 수집 |
| 2022년 7월 | [Adobe Experience Platform으로 샘플 데이터 가져오기](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=ko-KR) | 문서 | 샘플 데이터를 사용하여 Experience Platform 샌드박스 환경을 설정하는 방법을 알아봅니다. Postman 컬렉션을 사용하여 필드 그룹, 스키마, 데이터 세트를 만든 다음 샘플 데이터를 Experience Platform으로 가져올 수 있습니다. | Experience Platform |
| 2022년 7월 | [세그먼트 일치 수신 데이터](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html) | 비디오 | 세그먼트 일치 기능을 사용하면 전략적 파트너가 데이터를 공유할 수 있습니다. 이 비디오에서는 데이터를 승인하고 받는 방법, 데이터를 보고 고유한 세그먼트에 추가할 수 있는 위치를 알아봅니다. | Experience Platform - 세그먼트 |
| 2022년 7월 | [전문가에게 문의: Real-Time CDP 연결](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en) | Experience League 라이브 비디오 | 데이터 수집에 대한 세 가지 라이브 스트림 세션 중 두 번째 세션에서 Adobe의 가장 좋아하는 전문가가 Adobe RTCDP를 광범위하게 살펴봅니다 [!UICONTROL 연결]: 고객이 서버측 태그 관리 시스템을 사용하여 Adobe이 아닌 대상에 이벤트를 전달할 수 있습니다. | 데이터 수집 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 정보 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

다음 릴리스: **2022년 7월 20일**

마지막 업데이트: **2022년 7월 13일**

* Adobe Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ko)
* Adobe Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html?lang=ko)

### AppMeasurement {#appm}

릴리스 버전: **2.22.4**

* [JavaScript 릴리스 정보의 AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ko)

### 새로운 [!DNL Analytics] 튜토리얼 및 교육 과정 {#tutorials-analytics}

Adobe Analytics용으로 게시된 새로운 비디오 튜토리얼, 문서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [2022 플로우 개선 사항](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html) | 비디오 | 의 향상된 기능 중 일부에 대해 알아보십시오 [!UICONTROL 흐름] 시각화. 개선 사항으로는 관심 있는 경로의 시작 또는 끝을 구성할 수 있고, 열을 필터링하여 특정 항목을 포함하거나 제외할 수 있으며, 사전 구성 가능한 고급 설정이 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

최신 업데이트: **2022년 7월 12일**

* Customer Journey Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ko)
* Customer Journey Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ko)

### 새로운 Customer Journey Analytics 튜토리얼 및 교육 과정 {#tutorials-cja}

CJA용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [다음 및 이전 항목 패널 구성](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html) | 비디오 | [!DNL Customer Journey Analytics]에서 다음 및 이전 항목 패널을 구성하는 방법에 대해 알아봅니다. 이 패널에서는 특정 차원 값에 대한 다음 또는 이전 항목을 식별하기 위한 표와 시각화가 생성됩니다. |
| 2022년 7월 | [주석 만들기](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en) | 비디오 | 에서 주석을 만드는 방법을 알아봅니다 [!DNL Customer Journey Analytics] 캠페인 시작, 데이터 문제 및 휴일과 같은 이벤트가 발생할 때 프로젝트를 수행합니다. 이 기능은 사용자들에게 이러한 날짜 또는 날짜 범위의 지표 분산에 대해 알려 줍니다. |
| 2022년 7월 | [빠른 필터 만들기](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html) | 비디오 | [!DNL Customer Journey Analytics] 프로젝트에서 바로 빠른 필터를 만들어 전체 필터를 빌드하는 경우의 복잡성을 피할 수 있습니다.  |

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

### 제품 업데이트 비디오

* [2022년 6월 릴리스 개요 비디오](https://video.tv.adobe.com/v/344308/?quality=12) 2022.6 릴리스의 요약입니다.

이전 제품 업데이트 비디오:

* [2022년 5월 릴리스 개요 비디오](https://video.tv.adobe.com/v/343321/?quality=12) 2022.5.0(2022년 5월) 릴리스에 추가된 기능에 대한 요약은 를 참조하십시오.
* [2022년 4월 릴리스 개요 비디오](https://video.tv.adobe.com/v/342612?quality=12)
* [2022년 3월 릴리스 개요 비디오](https://video.tv.adobe.com/v/341465)
* [2022년 1월 릴리스 개요 비디오](https://video.tv.adobe.com/v/340120)
* [2021년 12월 릴리스 개요 비디오](https://video.tv.adobe.com/v/339278)
* [2021년 10월 릴리스 개요 비디오](https://video.tv.adobe.com/v/338253)
* [2021년 9월 릴리스 개요 비디오](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] 로서의 [!DNL Cloud Service]

의 새로운 기능 [!DNL Sites]:

* A [새 사용자 인터페이스](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) 이제 컨텐츠 관리자 및 컨텐츠 작성자가 헤드리스 사용 사례에 대한 컨텐츠 조각을 효율적으로 관리(게시, 게시 취소, 복사 및 이동 등의 작업 수행), 검색/필터 및 만들 수 있습니다.

* 새로운 [목차 구성 요소](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) 은 [!UICONTROL 핵심 구성 요소] 그러나 모든 구성 요소를 사용하여 콘텐츠 페이지에서 목차를 자동으로 렌더링합니다. 또한, 서버 측에서 렌더링되고 디스패처에 의해 완전히 캐시되므로 로드하는 것도 효율적입니다.

### Experience Manager [!DNL Assets] 로서의 [!DNL Cloud Service]

의 새로운 기능 [!DNL Assets]:

* Experience Manager [!DNL Assets] 이제에서 Adobe Sensei AI 기능 사용 [이미지의 색상을 구별하고 수집 시 자동으로 태그로 적용합니다](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=kr). 이러한 태그를 통해 이미지 색상 구성에 따라 향상된 검색 환경을 사용할 수 있습니다. 이미지에 태그가 지정된 색상의 수를 1~40개 범위에서 구성할 수 있으므로 나중에 해당 색상을 기준으로 이미지를 검색할 수 있습니다.

### Experience Manager Forms as a Cloud Service

의 새로운 기능 [!DNL Forms]:

* [통합 [!UICONTROL 응용 Forms] Microsoft® Power Automate 사용](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en): 이제 제출 시 Microsoft® Power Automated Cloud Flow를 실행하도록 적응형 양식을 구성할 수 있습니다. 구성된 적응형 양식은 캡처된 데이터, 첨부 파일 및 기록 문서를 처리를 위해 Power Automate Cloud Flow로 전송합니다. Microsoft® Power Automatic의 강력한 기능을 활용하면서 사용자 정의 데이터 캡처 환경을 구축하여 캡처된 데이터를 중심으로 비즈니스 로직을 구축하고 고객 워크플로를 자동화할 수 있도록 지원합니다.

**적응형 양식을 만드는 마법사:** 비즈니스 사용자에게 친숙한 마법사를 사용하여 신속하게 작성할 수 있습니다 [!UICONTROL 응용 Forms]. 마법사는 미리 구성된 템플릿, 스타일, 필드 및 제출 옵션을 손쉽게 선택하여 적응형 양식을 만들 수 있는 빠른 탭 탐색 기능을 제공합니다.

### Experience Manager as a Cloud Service 기반

새로운 기능:

5월(2022.5.0) 릴리스 노트에서 언급했듯이 복제 에이전트 관리 화면의 분배 탭에 있는 &quot;트리 추가&quot; 옵션이 제거되었습니다. 콘텐츠 트리 계층이 있는 패키지는 대신 게시 관리 또는 콘텐츠 트리 게시 워크플로를 사용하여 복제해야 합니다..

### [!DNL Cloud Manager]

새로운 기능:

* [!DNL Cloud Manager] 이제 사용자는 [!UICONTROL 시작] 언제든지 랜딩 페이지에 카드를 넣을 수 있습니다.

* The popuover on the [컨텐츠 복원](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) 이제 환경 세부 사항 페이지의 탭에 사용자가 변경 사항을 로컬로 볼 수 있도록 해주는 유용한 git 명령 목록이 표시됩니다.

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 7월 | [엔터프라이즈 워크플로우 관리를 최대한 활용](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en) | 비디오 | 자산 관리를 위해 워크플로우를 사용하여 얻을 수 있는 이점 및 워크플로우를 신속하게 만드는 방법을 알아봅니다. | AEM - Experience Workflow Management |
| 2022년 7월 | [Adobe Experience Manager을 통해 헤드리스 경험 제공](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en) | 비디오 | 최신 Experience Manager을 사용한 헤드리스 경험 관리에 대해 알아보기 [!UICONTROL 컨텐츠 조각] 헤드리스 컨텐츠 전달을 위한 새로운 GraphQL API 및 개선 사항. | Experience Manager [!DNL Sites] |
| 2022년 7월 | [Adobe Experience Manager Assets에서 비즈니스에 메타데이터 작동](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en) | 비디오 | 자산에 대한 작업 로드를 줄이고 자산을 보다 검색할 수 있도록 만들어 AEM Assets에서 메타데이터를 최대한 활용하는 방법을 알아봅니다. | Experience Manager [!DNL Assets] |
| 2022년 7월 | [iOS 앱](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html) | 비디오 | 예제 애플리케이션은 Adobe Experience Manager의 헤드리스 기능을 살펴보는 좋은 방법입니다. 이 iOS 애플리케이션은 AEM을 사용하여 컨텐츠를 쿼리하는 방법을 보여줍니다 [!UICONTROL GraphQL API] 지속되는 쿼리 사용. | Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022년 7월 | [Android™ 앱](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html) | 비디오 | 이 Android™ 응용 프로그램은 [!UICONTROL GraphQL API] AEM | Experience Manager [!DNL Assets], [!DNL Sites] |
| 2022년 7월 | [Adobe Experience Manager as a Cloud Service에 대한 OSGi 구성](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en) | 비디오 | AEM CS용 OSGI를 구성하는 방법을 알아봅니다. 예를 들어, AEM 코드 프로젝트의 일부인 구성 파일을 통해 OSGi 번들 관리 및 OSGi 구성 요소에 대한 구성 설정 관리에 대해 알아봅니다. | AEM as a Cloud Service |
| 2022년 7월 | [양식 데이터 모델 속성 재정의](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en) | 비디오 | 다른 종단점에 대해 한 양식 데이터 모델을 쉽게 테스트할 수 있도록 양식 데이터 모델 속성을 재정의하는 방법을 알아봅니다. | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보

모든 Experience Manager 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [Experience Manager as a Cloud Service 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ko)
* [Experience Manager Cloud Manager 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
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
* [Cloud Manager 사용 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Experience Manager 6.5 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ko)
* [Experience Manager 6.4 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ko)
* [Experience Manager 6.3 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko)
* [Experience Manager 6.2 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko#previous-updates)
* [이전 버전의 Experience Manager 설명서](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 도움말 홈](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ko)
* [Experience Manager 설명서: 최신 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ko#aem-as-a-cloud-service)

## ![아이콘](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] 는 AEM에 배포된 애플리케이션입니다. Adobe Experience Manager의 기본 DITA 지원을 활성화하는 강력한 엔터프라이즈급 구성 요소 콘텐츠 관리 솔루션(CCMS)으로, AEM에서 DITA 기반 콘텐츠 생성 및 전달을 처리할 수 있도록 촉진합니다.

[[!DNL Experience Manager Guides]](https://www.adobe.com/kr/products/xml-documentation-for-experience-manager/features.html)에 대해 자세히 알아보십시오.

### 추가 리소스

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - Experience League의 튜토리얼
* [[!DNL Experience Manager Guides] 학습 및 지원](https://helpx.adobe.com/kr/support/xml-documentation-for-experience-manager.html) - 제품 설명서

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source 2.4.x 릴리스 정보](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 릴리스 정보](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 새로운 Adobe Commerce 튜토리얼 및 설명서 {#tutorials-commerce}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [Adobe Commerce 시작 안내서](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | 제품 설명서 | Adobe Commerce 및 Magento Open Source을 처음 사용하는 상인 및 시스템 관리자를 위한 안내서입니다. 해당 전문가의 관점에서 플랫폼에 대한 개요를 보고 기능 저장소를 사용할 수 있는 기본 기능에 대한 자세한 정보를 살펴보십시오. |
| 2022년 7월 | [페이지 빌더 사용 안내서](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | 제품 설명서 | 기본 컨텐츠 구성 요소 작성을 위한 3가지 연습 등 Page Builder 기능에 대해 알아보십시오. 이 안내서는 관리자를 위한 것입니다. 이 섹션에서는 코어 Adobe Commerce 구성 및 기능에 대한 기본적인 이해를 가정합니다. |
| 2022년 7월 | [B2B for Adobe Commerce 안내서](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | 관리 안내서 | 기능 구성 및 관리 등 이 모듈의 설치 및 활성화에 대한 자세한 정보를 얻습니다. |
| 2022년 7월 | [Adobe Commerce용 B2B - 자습서](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en) | 비디오(다중) | 에 대해 알아보기 [!UICONTROL 회사] 페이지를 Adobe Commerce에 추가합니다. 회사 계정을 관리할 수 있으며 승인 대기 중인 요청이 목록 맨 위에 나타납니다. |
| 2022년 7월 | [품질 패치 도구 사용](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html) | 비디오 | 에 대해 알아보기 [!UICONTROL 품질 패치 도구]- Adobe Commerce 및 Magento Open Source에 대한 품질 패치를 제공하는 명령줄 툴입니다. |
| 2022년 7월 | [사이트 전체 분석 도구 대시보드](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html) | 비디오 | 사이트 전체 분석 도구에 대해 알아봅니다. 이 기능은 Adobe Commerce 설치의 보안 및 운영을 보장하기 위한 자세한 시스템 통찰력과 권장 사항이 포함된 사전 예방적, 셀프 서비스 도구 및 중앙 저장소입니다. |
| 2022년 7월 | [결제 서비스 사용](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html) | 비디오 | 사용 방법 알아보기 [!UICONTROL 결제 서비스] 운영 오버헤드를 줄이려면 매출 증대 |
| 2022년 7월 | [주문 상태 관리](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html) | 비디오 | 주문 상태 및 주문 세부 사항을 확인하는 방법과 필요한 경우 주문 상태를 변경하는 방법을 알아봅니다. |
| 2022년 7월 | [마케팅 도구](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en) | 비디오(다중) | 카탈로그 가격 규칙 만들기, 장바구니 가격 규칙, 관련 제품 규칙 관리, 라이브 검색 등에 대해 알아봅니다. |
| 2022년 7월 | [비즈니스 가치를 제공하는 컨텐츠 개인화의 혁신](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en) | 비디오 | Skill Builder 프레젠테이션을 보고 컨텐츠 작성을 대중화하고, 옴니채널 게재를 간소화하고, 개인화를 규모에 맞게 개인화할 수 있는 Adobe의 컨텐츠 솔루션의 최근 혁신적인 기능에 대해 알아보십시오. |
| 2022년 7월 | [카탈로그 관리](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html) | 비디오 | Adobe Commerce의 카탈로그 관리에 대해 알아봅니다. 카테고리를 만들고, 카테고리의 제품을 관리하고, 인벤토리를 관리하는 등의 작업을 수행합니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/target.png) [!DNL Adobe Target] {#target}

마지막 업데이트: **2022년 6월 30일**

* 이전 릴리스에 대한 자세한 내용은 [Adobe Target 프리릴리스](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [Adobe Target 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ko)를 참조하십시오.

### 새로운 Adobe Target 교육 과정 및 튜토리얼 {#tutorials-target}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [대상자 만들기](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html) | 비디오 | 에서 사용자 지정 대상을 만들고 저장하는 방법을 알아봅니다. [!DNL Target] 활동에 사용. |
| 2022년 7월 | [Adobe Target을 사용하여 개인화 및 자동화](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en) | 비디오 | 다음을 사용하여 Adobe Target 기능의 자동화 및 최적화에 대한 핵심 개념을 알아봅니다 [!UICONTROL 자동 Target] 및 [!UICONTROL 자동 개인화]. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

* [Campaign v7.3 릴리스](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)
* [Campaign 컨트롤 패널 6월 릴리스](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [튜토리얼 및 교육 과정](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) Experience League 시

### 새로운 [!DNL Campaign] 튜토리얼 및 교육 과정 {#tutorials-campaign}

Adobe Campaign용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 7월 | [하이브리드 호스팅 모델에 컨트롤 패널 사용](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html) | 비디오 | 컨트롤 패널을 Adobe Campaign 하이브리드 호스팅 모델에 사용할 수 있도록 설정하고 컨트롤 패널에 액세스하며 주요 기능을 잠금 해제하는 방법을 알아봅니다. | 제어판 |
| 2022년 7월 | [스루 넣기 및 지연 모니터링](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=ko) | 비디오 | 캠페인 인스턴스의 고객을 통해 게재를 모니터링하고 트랜잭션 메시지 지연을 모니터링하는 방법을 알아봅니다. | 제어판 |
| 2022년 7월 | [워크플로우를 모니터링하여 리소스 사용 최적화](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=ko) | 비디오 | 워크플로우의 임시 저장소 사용을 모니터링하는 방법 및 인스턴스의 데이터베이스 또는 워크플로우 문제를 방지하기 위해 워크플로우 설정을 구성하는 위치를 알아봅니다. | 제어판 |
| 2022년 7월 | [Adobe Campaign Classic에서 데이터 모델 개발 및 사용자 지정](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en) | 비디오(Skill Builder 이벤트) | 이 세션에 참여하여 Campaign Classic 내의 데이터 모델 내에서 데이터 스키마를 개발하는 방법을 Campaign 트레이너와 함께 알아보십시오. | Campaign Classic v7 |
| 2022년 7월 | [결과를 도출하는 게재 가능성 모범 사례 및 전략](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | 비디오 | 이메일 캠페인 계획 및 프로덕션에 들어가는 수많은 시간을 최소화하는 방법을 알아봅니다. | Campaign Classic v7 |
| 2022년 7월 | [Adobe Campaign Classic을 통해 크로스 채널 마케팅 강화](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en) | 비디오 | Adobe Campaign Classic 고객을 위한 워크플로우, 자동화, 개인화 및 측정에 중점을 둔 이 심층적인 웨비나를 시청하십시오. | Campaign Classic v7 |
| 2022년 7월 | [프로에서 팁을 절약하는 시간!](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en) | 비디오 | Adobe Campaign 프로의 팁과 트릭으로 새해를 시작하십시오! 캠페인을 제작 및 시작하고 보다 의미 있고 맞춤 설정된 크로스채널 경험을 제공하는 방법을 통해 보다 효율적으로 캠페인을 수행할 수 있습니다. | Campaign Classic v7 |
| 2022년 7월 | [마케팅 에코시스템과 Adobe Campaign 통합](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en) | 비디오 | 마케팅 에코시스템과 Adobe Campaign 통합에 대해 알아봅니다. Adobe Campaign과 같은 크로스 채널 마케팅 솔루션은 다른 기술 또는 팀과 분리되지 않아야 합니다. 서로 다른 시스템이 고객을 완전히 이해하고 크로스채널 전략을 방해하지 않도록 하십시오. | Campaign Classic v7 |
| 2022년 7월 | [Adobe Campaign Standard 고객 Spotlight - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en) | 비디오 | Microsoft®의 마케팅 팀에서 Adobe Campaign Standard 사용 방법, 아키텍처 및 안내 원칙, 모범 사례를 공유할 수 있습니다. | Campaign Standard |
| 2022년 7월 | [Adobe Campaign Customer Spotlight - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en) | 비디오 | Adobe Campaign 고객이 Adobe Campaign을 통해 도전을 극복하고, 새로운 표준에 적응하며, 캠페인 관리를 통해 보다 효율적으로 대처하고, 의미 있는 가치를 창출하는 방법을 공유하고 있다는 것을 알아보십시오. | Campaign Classic v7 |
| 2022년 7월 | [Adobe Campaign Classic V7와 V8 비교](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en) | 비디오 | 최신 제품 업데이트에 대해 듣고 제품 관리자의 V7와 V8 간의 차이점을 파악합니다. | Campaign Classic v7, Campaign v8 |
| 2022년 7월 | [Keynote - B2B 및 B2C에서 고객 여정 트렌드와 혁신](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en) | 비디오 | B2B 및 B2C에서 고객 여정 관리의 최신 트렌드에 대해 알아봅니다. 주요 여정 애플리케이션과 광범위한 Adobe Experience Cloud 및 플랫폼의 최신 혁신 사항을 확인할 수 있습니다. | Marketo, Campaign Classic v7, Campaign v8 |
| 2022년 7월 | [Adobe Campaign Standard을 위한 주요 팁과 트릭](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en) | 비디오 | Adobe Campaign Standard 인스턴스에 로그인하고 ACS를 보다 효율적으로 사용할 수 있도록 타깃팅, 개인화 및 마케팅 피로에 대한 우수 사례를 알아봅니다. | Campaign Standard |
| 2022년 7월 | [크로스 채널 마케팅을 지원하는 데 필요한 팀, 기술 및 조직 디자인](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | 비디오 | 언제 어디서나 원하는 방식으로 참여할 수 있는 권한을 부여하는 방법을 알아보십시오. 계획, 실행 및 측정을 지원하는 마케팅 조직이 있어야 하는 중요성에 대해 알아봅니다. | Campaign Classic v7, Campaign v8, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [설명서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=ko) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ko)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ko) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ko) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ko)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ko) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ko) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ko)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ko) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ko) 방법 비디오

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer를 사용하면 단일 애플리케이션에서 수백만 고객을 위한 예정된 옴니채널 캠페인과 일대일 순간을 관리할 수 있으며, 지능적인 의사 결정과 통찰력으로 전체 여정을 최적화할 수 있습니다.

### 최신 Journey Optimizer 제품 릴리스

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ko?lang=ko-KR)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

### 새로운 Journey Optimizer 튜토리얼 및 교육 과정 {#tutorials-ajo}

Adobe Journey Optimizer에 대해 게시된 새로운 비디오, 자습서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [메시지 빈도 규칙 구성](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html) | 비디오 | 빈도 규칙을 만들고, 활성화하고, 테스트하고, 보고하는 방법을 알아봅니다. 메시지에 대해 상속될 빈도 규칙을 결정하는 방법을 알아봅니다. |
| 2022년 7월 | [SMS 메시지 구성, 작성, 전달](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html) | 비디오 | 고객 여정에 SMS 메시지를 구성하고, 작성하고, 포함하는 방법을 알아봅니다. |
| 2022년 7월 | [SMS에 대한 인바운드 키워드 지원](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html) | 비디오 | SMS에 대한 기본 인바운드 키워드 지원(시작, 중지, 중지 해지)이 작동하는 방식을 이해합니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ko)
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

### 새로운 Marketo 튜토리얼 및 교육 과정 {#tutorials-marketo}

Adobe Marketo에 대해 게시된 새로운 비디오, 자습서 또는 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 7월 | [Marketo Engage 및 Adobe Experience Cloud을 사용한 B2B 경험](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en) | 비디오 | Marketo Engage과 Adobe Experience Cloud 애플리케이션 간의 통합 및 해결할 문제점 대해 연습하십시오. | Marketo Engage |
| 2022년 7월 | [함께 개선 - Adobe Marketo Engage과 Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en) | 비디오 | Marketo Engage 및 RT-CDP(B2B 버전)를 사용하여 B2B 캠페인을 오케스트레이션하는 방법과 주요 사용 사례 및 이점이 무엇입니까? | Marketo, Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

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

마지막 업데이트: **2022년 7월 14일**

| 기능 | 설명 |
| ------- | ----------- |
| 맞춤형 보고서 | (31) 5월 5일 베타 기능) 이제 Advertising Cloud DSP에서 고객 데이터 플랫폼(CDP) 내에서 구축된 인증된 신호로 구성된 자사 세그먼트를 수집할 수 있습니다. |
| [!UICONTROL 인벤토리] | (6월 29일 릴리스) 새로운 기능 [!UICONTROL 인벤토리] > [!UICONTROL 딜] 보기에는 와 동일한 데이터 사용자 지정 기능이 포함되어 있습니다. [!UICONTROL 캠페인] 추가 필터, 열 사용자 지정 및 사용자 지정 보기, 열 정렬 및 데이터 시각화(차트) 보기를 저장하는 옵션을 포함한 보기. 거래 이름 뒤에 있는 줄임표(..)를 클릭하여 각 행에서 명령 메뉴를 열 수 있습니다. |
| [!UICONTROL Inventory Inspector] | (6월 29일 릴리스) [!UICONTROL 인벤토리] 배치 탭 [!UICONTROL 검사자] 이제 사용자 정의 가능한 데이터 시각화 차트와 다음과 같은 확장된 성능 지표를 포함합니다 [!UICONTROL 뷰가능 비율], [!UICONTROL 클릭 수], 및 [!UICONTROL 어제의 CPM]. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

마지막 업데이트: **2022년 7월 14일**

| 기능 | 설명 |
| ------- | ----------- |
| [!UICONTROL Insights] | (6월 11일 릴리스) 이제 노출 공유 손실된 분석을 베타 기능으로 다시 사용할 수 있습니다. |
| [!DNL Advanced Campaign Management] | (6월 20일) ([!DNL Google Ads] 및 [!DNL Microsoft Advertising] 캠페인) 이제 인벤토리의 내용을 기반으로 검색 엔진별 광고 템플릿을 사용하여 동적 응답형 검색 광고 변형을 만들 수 있습니다. [!UICONTROL 캠페인] > [!UICONTROL 고급(ACM)]. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud용으로 게시된 새로운 튜토리얼 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 7월 | [승인자 역할 사용](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en) | 비디오(업데이트됨) | 승인 프로세스를 통해 문서를 보내는 방법을 알아봅니다. | Adobe Sign |
| 2022년 7월 | [웹 양식 설정](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html) | 비디오(업데이트됨) | 웹 사이트에서 직접 전자 방식으로 서명할 수 있는 문서를 만드는 방법을 알아봅니다. | Adobe Sign |
| 2022년 7월 | [위임자 역할 사용](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | 비디오 (업데이트됨) | 설명 | Adobe Sign |
| 2022년 7월 | [전자 서명 문서](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en) | 비디오(업데이트됨) | Acrobat Sign으로 보낼 문서에 서명하는 것이 얼마나 쉬운지 알아보십시오. | Adobe Sign |
| 2022년 7월 | [Acrobat Sign 관리자를 위한 설정 및 실행](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en) | 비디오(업데이트됨) | Acrobat Sign에서 신속하게 시작하고 실행하기 위해 관리자가 중점을 두어야 하는 7가지 주요 영역을 알아봅니다. | Adobe Sign |
| 2022년 7월 | [Outlook의 Send for Signature](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#) | 비디오(업데이트됨) | Microsoft® Outlook에서 직접 서명용 문서를 전송하여 문서 워크플로우를 간소화하는 방법을 알아봅니다. | Adobe Sign |
| 2022년 7월 | [Outlook 채우기 및 로그인](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en) | 비디오(업데이트됨) | Microsoft Outlook에서 직접 양식을 작성하고 서명하여 문서 워크플로우를 간소화하는 방법을 살펴볼 수 있습니다. | Adobe Sign |
| 2022년 7월 | [그룹 만들기 및 관리](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en) | 비디오(업데이트됨) | 그룹을 만들고, 사용자를 그룹에 추가하고, 그룹 설정을 편집하는 방법을 알아봅니다. | Adobe Sign |
| 2022년 7월 | [다른 사람에게 서명 위임](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en) | 비디오(업데이트됨) | 문서 서명을 다른 사람에게 위임하는 방법을 알아봅니다. | Adobe Sign |

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
