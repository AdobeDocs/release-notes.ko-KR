---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 도움말과 튜토리얼을 찾아보십시오.'
doc-type: release notes
last-update: August 2022
author: mfrei
mini-toc-levels: 2
source-git-commit: 02987b7f5f4fd84837e4d774ff8f96cea6b4debd
workflow-type: tm+mt
source-wordcount: '4134'
ht-degree: 52%

---

# Adobe Experience Cloud 릴리스 정보 - 2022년 8월

![배너](assets/experience-cloud-banner-3.png)

[Experience League](https://experienceleague.adobe.com/?lang=en#home)를 통해 성공적인 Experience Maker로서의 길을 시작해 보십시오. 방대한 입문용 문서 라이브러리, 셀프 가이드 튜토리얼, 입문용 비디오, 모든 레벨과 역할을 위한 과정, 동료들의 온라인 커뮤니티, 필요할 경우 전문가 지원을 찾아보십시오.

>[!NOTE]
>
>이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오. Experience League의 최신 상황을 수시로 확인할 수 있습니다.

최신 업데이트: **2022년 8월 12일**

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

Experience League 이벤트는 Adobe의 제품 전문가로부터 배우고, 상호 작용하고, 답변을 얻을 수 있는 유용한 공간입니다. 2022년 7월의 최신 정보를 확인하려면 Experience League의 [이벤트](https://experienceleague.adobe.com/events/?lang=en)를 참조하십시오.

**2022년 8월 10일** 업데이트됨

| 이벤트 | 유형 | 설명 |
| -----------|---------- | ----|
| [Adobe Analytics](https://engage.adobe.com/NA_FY22_Q3_WBR_Adobe_Analytics_Data_Validation.html) | 웨비나 | _내일의 성공을 더욱 부채질하다: 데이터 품질 및 채택_ - 이 라이브 웨비나에서 Adobe Analytics Champions Frederk Werner와 Sarah Owen과 함께 분석의 모든 측면에 데이터 품질을 빌드하고 이를 둘러싼 공유 문화를 만드는 방법을 알아봅니다.<p>**날짜:** 8월 25일 @ 동부시간 오전 11:00 - [세부 사항 및 등록](https://engage.adobe.com/NA_FY22_Q3_WBR_Adobe_Analytics_Data_Validation.html) |
| [Experience Makers 라이브](https://business.adobe.com/events/experience-makers-live.html) | 웨비나 | Sara Blakely, Peyton Manning 및 Eli Manning의 주요 노트가 포함된 Experience Makers를 위한 무료 이벤트입니다.<p>**날짜:** 9월 13일 - 14일 - [세부 사항 및 등록](https://business.adobe.com/events/experience-makers-live.html) |

{style=&quot;table-layout:auto&quot;}

예정된 이벤트 및 이전 에피소드에 대한 최신 정보는 Experience League의 [이벤트](https://experienceleague.adobe.com/events/?lang=en)를 참조하십시오.

## ![아이콘](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

최신 릴리스 정보는 Adobe 시스템 상태 [릴리스 정보](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=ko-KR#status)를 참조하십시오.

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud - 중앙 인터페이스 구성 요소 및 관리 {#ecloud}

Experience Cloud [중앙 UI 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko)에는 홈 페이지 및 영구 제품 헤더에서 사용할 수 있는 기능이 포함됩니다. 이러한 기능에는 사용자 프로필 설정, 환경 설정 및 검색이 포함됩니다. 사용자 및 제품 관리, 고객 속성 및 Experience Cloud Audiences에 대한 도움말도 찾을 수 있습니다.

### 프로비저닝 업데이트

>[!IMPORTANT]
>
>관리자, 놓치지 마십시오 [중요 공지](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=ko#july—2022) Experience Cloud 프로비저닝 기본 정보(2022년 7월 발표).

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 및 [!UICONTROL Mobile SDK]에 대한 최신 릴리스 정보와 새로운 설명서:

예정된 릴리스: **2022년 8월 24일**

* [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko-KR)

### [!DNL Adobe Mobile] SDK

업데이트됨: **2022년 8월 2일** - 다음을 참조하십시오. [릴리스 노트 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes) Adobe Experience Platform Mobile SDK용.

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

다음 릴리스: **2022년 8월 17일**

마지막 업데이트: **2022년 7월 13일**

* Adobe Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ko-KR)
* Adobe Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html?lang=ko-KR)

### AppMeasurement {#appm}

릴리스 버전: **2.22.4**

* [JavaScript 릴리스 정보의 AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ko-KR)

### 새로운 [!DNL Analytics] 튜토리얼 및 교육 과정 {#tutorials-analytics}

Adobe Analytics용으로 게시된 새로운 비디오 튜토리얼, 문서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 8월 | [폴아웃 시각화 보고서 만들기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/fallout-visualization.html) | 비디오 | 폴아웃 보고서 사용 사례와 Analysis Workspace에서 이 보고서를 구성하는 방법에 대해 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

최신 업데이트: **2022년 8월 5일**

* Customer Journey Analytics [릴리스 정보](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ko-KR)
* Customer Journey Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ko)

## ![아이콘](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

마지막 업데이트: **2022년 3월 23일**

* [!DNL Streaming Media Analytics] [릴리스 정보](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=ko)
* [!DNL Streaming Media Analytics] [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=ko-KR)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 수정 및 개선 사항:

| 개선 사항 | 설명 |
| -----------| ---------- |  
| 다른 회사에 속한 대상 데이터 소스의 유효성 검사기 | Audience Manager는 [배치 데이터 온보딩 프로세스](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=ko-KR)에 대한 개선 사항을 발표했습니다. 파일 및 데이터가 실수로 다른 파트너가 소유한 대상 데이터 소스에 온보딩되는 것을 방지하기 위해, Audience Manager는 파트너 ID(PID)와 다른 파트너가 소유한 데이터 소스(DPID) 간의 매핑 요구 사항을 추가했습니다. <ul><li>[인바운드 데이터 파일에 대한 Amazon S3 이름 및 파일 크기 요구 사항](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=ko-KR#name-elements)의 __DPID_TARGET_DATA_OWNER_ 필드도 참조하십시오.</li><li>Adobe 내부 컨설턴트 및 고객 지원 팀에서 새 매핑 요청 방법 및 개선이 필요한 새 매핑에 대한 정보를 보려면 [타사 데이터에 대한 온보딩 액세스 관리](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=ko-KR)를 참조하십시오.</li><li>기존 데이터 공유 관계에 대한 매핑을 요청할 필요는 _없습니다_. PID에 속하는 대상 데이터 소스에 데이터를 온보딩할 때도 매핑이 필요하지 _않습니다_.</li></ul> |

{style=&quot;table-layout:auto&quot;}

자가 진단 리소스에 대한 자세한 내용은 Experience League에서 [Audience Manager 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/audience-manager.html?lang=ko-KR)을 참조하십시오.

## ![아이콘](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온프레미스 배포를 사용하는 것이 좋습니다.

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ko-KR) 페이지를 방문할 것을 권장합니다.

### 제품 업데이트 비디오

보기 [2022년 7월 릴리스 개요 비디오](https://video.tv.adobe.com/v/345409/?quality=12) 2022.7.0(2022년 7월) 릴리스에 추가된 기능에 대한 요약은 를 참조하십시오. <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

* [2022년 6월 릴리스 개요 비디오](https://video.tv.adobe.com/v/344308/?quality=12)
* [2022년 5월 릴리스 개요 비디오](https://video.tv.adobe.com/v/343321/?quality=12)
* [2022년 4월 릴리스 개요 비디오](https://video.tv.adobe.com/v/342612?quality=12)
* [2022년 3월 릴리스 개요 비디오](https://video.tv.adobe.com/v/341465)
* [2022년 1월 릴리스 개요 비디오](https://video.tv.adobe.com/v/340120)
* [2021년 12월 릴리스 개요 비디오](https://video.tv.adobe.com/v/339278)
* [2021년 10월 릴리스 개요 비디오](https://video.tv.adobe.com/v/338253)
* [2021년 9월 릴리스 개요 비디오](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

_새로운 기능_

* 다음 [컨텐츠 조각 콘솔](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=ko-KR) 이제에서 지원 [키보드 단축키](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console-keyboard-shortcuts.html?lang=en).
* as a Cloud Service Experience Manager [웹에 최적화된 이미지 제공](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/web-optimized-image-delivery.html?lang=en) WebP와 같은 형식을 제공하여 페이지 속도를 크게 향상시킵니다. 또한 이 새로운 서비스는 보다 유연한 이미지 크기 조정 및 변환 옵션을 제공합니다. 모든 버전의 [코어 이미지 구성 요소](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/image.html?lang=en) 이 서비스를 사용하고 이미지 구성 요소의 정책에서 옵션을 선택하여 WebP에서 이미지를 제공할 수 있습니다.
* 이제 Experience Manager 개인화 활동은 이전 오퍼 대신 경험 조각을 사용할 수 있습니다. 이 기능은 다음을 수행하는 데 도움이 됩니다.
   * Experience Manager 컨텐츠가 이전 라이브러리 오퍼보다 경험 조각 오퍼를 홍보하는 마이그레이션 경로를 활성화하여 향후 개인화에 맞게 적절히 스타일이 지정된 콘텐츠를 제공할 수 있습니다.
   * 콘텐츠 작성자가 실수로 스타일이 지정되지 않은 콘텐츠를 사이트에 제공하지 않도록 합니다.
   * 모든 구성 요소의 타깃팅 모드를 편집 가능한 템플릿을 사용하는 경험 조각(JSON 및 HTML 유형 모두)으로 변환할 수 있습니다.

### Experience Manager [!DNL Assets] 로서의 [!DNL Cloud Service]

_사전 릴리스 채널에서 사용할 수 있는 새로운 기능_

* 이제 Adobe Experience Manager Assets을에 구성할 수 있습니다. [MIME 유형에 따라 사용자가 업로드할 수 있는 자산 유형을 제한합니다](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/configure-asset-upload-restrictions.html?lang=en).

### Experience Manager [!DNL Forms] 로서의 [!DNL Cloud Service]

_새로운 기능_

* **스크리블 서명에 대한 키보드 입력 지원** - 적응형 Forms이 터치 장치에서 점점 더 많이 사용되고 있으며, 한 가지 일반적인 요구 사항은 서명을 지원하는 것입니다. 터치 장치에서 문서에 서명하는 것은 허용되는 양식 서명 방법이 되었다. 적응형 Forms에는 스크리블 서명 및 Adobe Sign에 대한 기본 지원 기능이 있습니다. 이제 이미 지원되는 다른 옵션과 함께 키보드를 사용하여 적응형 양식에서 스크리블 서명을 사용할 수도 있습니다. 또한 접근성 준수를 강화하는 데에도 도움이 됩니다.

* **로컬 언어로 적응형 Forms 마법사 사용** - 원하는 언어로 마법사를 사용할 수 있습니다. 이제 Experience Manager에서 지원하는 모든 언어를 지원합니다.

_프리릴리스 채널에서 사용할 수 있는 새로운 기능_

* **호출 - Experience Manager 워크플로우 단계** - DDX(Document Description XML)는 요소가 문서 빌딩 블록을 나타내는 선언적 마크업 언어입니다. 이러한 빌딩 블록에는 PDF 및 XDP 문서와 주석, 책갈피 및 스타일이 지정된 텍스트와 같은 기타 요소가 포함됩니다. DDX 문서는 문서의 템플릿이며 결과 문서에 표시되어야 하는 소스 문서의 원하는 특성을 설명합니다. 하나의 DDX를 다양한 소스 문서와 함께 사용할 수 있습니다. 호출 단계 및 Experience Manager 워크플로우를 사용하여 문서 분해, Acrobat 및 XFA Forms 작성 및 수정, 그리고 에 설명된 기타 작업과 같은 다양한 작업을 수행할 수 있습니다. [DDX 참조](https://helpx.adobe.com/content/dam/help/en/experience-manager/forms-cloud-service/ddxRef.pdf) 설명서.

* **PDF/A로 변환 - Experience Manager 워크플로우 단계** - PDF/A는 문서의 컨텐츠를 장기 보존하기 위한 보관 형식이며 모든 글꼴이 포함되고 파일의 압축이 해제됩니다. 이제 AEM Workflow에서 PDF/A로 변환 단계를 사용하여 문서 또는 파일을 어떤 형식의 형식으로든 PDF/A 형식으로 변환할 수 있습니다.

### Experience Manager as a Cloud Service 기반

_새로운 기능_

* 다음 [저장소 브라우저](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developer-tools/repository-browser.html?lang=ko) 이제 경로 입력 필드가 있으므로 저장소 계층 구조의 특정 폴더로 바로 이동할 수 있습니다
* 이제 SCD(Sling Content Distribution)에서 게시되는 컨텐츠를 사용하지 않고 콘텐츠를 무효화하기 위해 명시적 &quot;무효화&quot; 작업을 지원합니다. 자세한 내용은 [Experience Manager as a Cloud Service 캐싱](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/caching.html?lang=en#explicit-invalidation) 페이지를 참조하십시오.
* `mod_macro` 이제 Experience Manager as a Cloud Service에서 사용할 수 있습니다. [이 표 보기](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/disp-overview.html?lang=ko) 지원되는 Apache 모듈 목록입니다.

_as a Cloud Service SDK Dispatcher 도구 Experience Manager 개선 사항_

* Apache는 `update_sdk.sh` Apache 및 Dispatcher 구성에 대한 후속 변경 사항을 자동으로 로드 및 확인하여 개발자 속도를 향상시킵니다. Dispatcher 도구 유연한 모드에서만 지원됩니다. 또한, [Apache 및 Dispatcher 구성 디버깅](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/validation-debug.html?lang=en#automatic-loading) 자동 로드 및 유효성 검사에 대한 자세한 내용은 를 참조하십시오.
* 로컬 Apache/Dispatcher 구성은 클라우드 환경의 변경 사항을 더 밀접하게 추적하여 두 환경 간의 패리티를 증가시킵니다.

_사전 릴리스 채널에서 사용할 수 있는 새로운 기능_

* 이제 Experience Manager as a Cloud Service가 통합 쉘과 통합되어 사용자 경험을 개선하고 다른 모든 Experience Cloud 애플리케이션과 통합합니다. 자세한 내용은 [통합 셸의 as a Cloud Service Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/overview/aem-cloud-service-on-unified-shell.html?lang=kr).

### [!DNL Cloud Manager]

_새로운 기능_

* 이제 Cloud Manager 사용자는 **[!UICONTROL 시작]** 랜딩 페이지의 카드입니다.
* 팝업 [컨텐츠 복원](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=ko-KR) 이제 환경 세부 사항 페이지의 탭에 사용자가 변경 사항을 로컬로 볼 수 있도록 해주는 유용한 git 명령 목록이 표시됩니다.

### Adobe Learning Manager 커넥터

_새로운 기능_

* 새로운 Adobe Learning Manager에는 Adobe Experience Manager Sites, Marketo Engage 및 Adobe Commerce에 대한 커넥터가 있습니다. 자세한 내용은 [Adobe Learning Manager 사용 안내서](https://helpx.adobe.com/learning-manager/user-guide.html).

### 커뮤니티

* Experience Manager as a Cloud Service [2022.7.0 릴리스 업데이트](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager-blogs/aem-as-a-cloud-service-2022-7-0-release-update/ba-p/540062#M546).
* 드디어! 필요한 모든 Experience Manager 컨텐츠를 한 곳에서 관리 [Experience Manager 커뮤니티](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager-blogs/finally-all-the-aem-content-you-need-all-in-one-place-on-aem/ba-p/460583)!
* Adobe Experience Manager [Community Lens 1st Edition](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager-blogs/adobe-experience-manager-community-lens-1st-edition-august-2022/ba-p/538960)2022년 8월

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022년 8월 | [AEM as a Cloud Service 2022.7.0 릴리스 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2022/2022-7-0.html) | 비디오 | Adobe Experience Manager Assets, Assets Essentials, Sites, Commerce Integration Framework, Forms 및 Cloud Manager의 최신 릴리스에 대한 기능 및 혁신에 대해 AEM 제품 팀의 의견을 들어 알아보십시오. | AEM as a Cloud Service |
| 2022년 8월 | [AEM Headless 자습서](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/overview.html?lang=en) | 업데이트된 문서 | AEM Headless SDK 자습서가 지속형 쿼리 및 WKND 2.0을 사용하도록 업데이트되었습니다. 실습 자습서를 사용하여 다양한 옵션을 사용하는 방법을 탐색하고 자신에게 적합한 옵션을 선택하십시오. | AEM as a Cloud Service |
| 2022년 8월 | [Adobe Experience Cloud와의 AEM as a Cloud Service 통합](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/integrations.html) | 비디오 | AEM as a Cloud Service이 다른 Adobe Experience Cloud 제품과의 지원되는 통합에 대해 알아봅니다. | AEM CS, Experience Cloud |
| 2022년 8월 | [Forms CS 및 Microsoft® Power 자동화](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-and-power-automate/integrate-formscs-power-automate.html) | 비디오 | 적응형 양식 제출에서 자동 흐름을 신속하게 실행할 수 있습니다. | AEM Forms |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보

모든 Experience Manager 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [Experience Manager as a Cloud Service 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ko-KR)
* [Experience Manager Cloud Manager 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=ko-KR)
* [Automated Forms Conversion Service 릴리스 정보](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ko-KR)
* [Experience Manager 6.5 Service Pack 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=ko-KR)
* [Experience Manager 6.4 Cumulative Fix Pack 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ko-KR)
* [Experience Manager Assets Dynamic Media 릴리스 정보](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ko-KR)
* [Experience Manager Brand Portal 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ko-KR)
* [Experience Manager 데스크탑 앱 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ko-KR)
* [Experience Manager Dispatcher 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ko-KR)
* [Adobe Primetime 릴리스 정보](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ko-KR)
* [Livefyre 릴리스 정보](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ko-KR)

### Experience Manager용 기타 도움말 리소스

* [Experience Manager as a Cloud Service 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=ko-KR)
* [Cloud Manager 사용 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=ko-KR)
* [Experience Manager 6.5 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ko-KR)
* [Experience Manager 6.4 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ko-KR)
* [Experience Manager 6.3 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR)
* [Experience Manager 6.2 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR#previous-updates)
* [이전 버전의 Experience Manager 설명서](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 도움말 홈](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ko-KR)
* [Experience Manager 설명서: 최신 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ko-KR#aem-as-a-cloud-service)

## ![아이콘](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides]는 AEM에 배포되는 애플리케이션입니다. Adobe Experience Manager의 기본 DITA 지원을 활성화하는 강력한 엔터프라이즈급 구성 요소 콘텐츠 관리 솔루션(CCMS)으로, AEM에서 DITA 기반 콘텐츠 생성 및 전달을 처리할 수 있도록 촉진합니다.

[[!DNL Experience Manager Guides]](https://www.adobe.com/kr/products/xml-documentation-for-experience-manager/features.html)에 대해 자세히 알아보십시오.

### 추가 리소스

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=ko-KR) - Experience League의 튜토리얼
* [[!DNL Experience Manager Guides] 학습 및 지원](https://helpx.adobe.com/kr/support/xml-documentation-for-experience-manager.html) - 제품 설명서

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source 2.4.x 릴리스 정보](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 릴리스 정보](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 새로운 Adobe Commerce 튜토리얼 및 설명서 {#tutorials-commerce}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 8월 | [Adobe Commerce 컨텐츠 및 디자인 안내서](https://experienceleague.adobe.com/docs/commerce-admin/content-design/guide-overview.html) | 제품 설명서 | Adobe Commerce 컨텐츠 및 디자인을 위한 새 제품 설명서 홈 을 참조하십시오. |
| 2022년 8월 | [카탈로그 서비스 안내서 개요](https://experienceleague.adobe.com/docs/commerce-merchant-services/catalog-service/guide-overview.html) | 제품 설명서 | 소개 [!UICONTROL 카탈로그 서비스]. 온보딩 및 설치에 대해 알아봅니다. |
| 2022년 8월 | [Adobe Commerce에 대한 빠른 체크아웃](https://experienceleague.adobe.com/docs/commerce-merchant-services/quick-checkout/overview.html) | 제품 설명서 | Adobe Commerce을 위한 일반적인 체크아웃 경험과 빠른 체크아웃 이점 및 해당 여정을 따르는 모범 사례에 대한 개요를 살펴보십시오. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/target.png) [!DNL Adobe Target] {#target}

마지막 업데이트 날짜: **2022년 7월 20일**

* 이전 릴리스에 대한 자세한 내용은 [Adobe Target 프리릴리스](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko-KR)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [Adobe Target 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ko-KR)를 참조하십시오.

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

* [Campaign v8 릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/release-notes.html?lang=en)
* [Campaign v7.3 릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ko-KR)
* [Campaign 컨트롤 패널 7월 릴리스](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=ko-KR)

<!--* [Tutorials and courses](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) on Experience League-->

<!-- ### New [!DNL Campaign] tutorials and courses {#tutorials-campaign}

New videos, tutorials, or courses published for Adobe Campaign.

|Published|Name|Type|Description |Applications|
| -----------| ---------- | ---------- | ---------- |---------- |
|July 2022|[Control Panel for hybrid hosting models](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html)|Video |Learn how to enable Control Panel for Adobe Campaign hybrid hosting models, access Control Panel, and unlock key features.|Control Panel|
|July 2022|[Monitor through-puts and latency](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html)|Video |Learn how to monitor delivery through-puts and transactional message latencies of your campaign instance.|Control Panel|
|July 2022|[Monitor workflows to optimize resource usage](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html)|Video |Learn how to monitor your workflows' temporary storage usage and where to configure workflow settings to avoid database or workflow issues on your instance.|Control Panel|
|July 2022|[Develop and customize data models in Adobe Campaign Classic](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en)|Video (Skill Builder events) |Join this session with our Campaign trainer to learn how to develop a data schema inside a data model within Campaign Classic.|Campaign Classic v7|
|July 2022|[Deliverability best practices and strategies that drive results](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html)|Video |Learn how to minimize the countless hours that go into the planning and production of your email campaigns.|Campaign Classic v7|
|July 2022|[Level up Your Cross-channel Marketing with Adobe Campaign Classic](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en)|Video |Watch this deep-dive webinar focusing on workflows, automation, personalization, and measurement for Adobe Campaign Classic customers.|Campaign Classic v7|
|July 2022|[Time saving tips from a pro!](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en)|Video |Start your new year with tips and tricks from an Adobe Campaign pro! Learn to be more efficient with creating and launching campaigns and how to deliver more meaningful and tailored cross-channel experiences.|Campaign Classic v7|
|July 2022|[Adobe Campaign integrations with a marketing ecosystem](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en)|Video |Learn about Adobe Campaign integrations with a marketing ecosystem. Cross-channel marketing solutions like Adobe Campaign should not sit in isolation from other technologies or teams. Don't let disparate systems impede a complete understanding of a customer and disrupt cross-channel strategies.|Campaign Classic v7|
|July 2022|[Adobe Campaign Standard Customer Spotlight - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en)|Video |Hear from the marketing team at Microsoft&reg; to share how they use Adobe Campaign Standard, their architecture and guiding principles, and best practices. |Campaign Standard|
|July 2022|[Adobe Campaign Customer Spotlight - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en)|Video |Hear Adobe Campaign customers share how they overcome challenges, adjust to the new normal, become more efficient with managing campaigns, and drive meaningful value through Adobe Campaign.|Campaign Classic v7|
|July 2022|[Adobe Campaign Classic V7 vs V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en)|Video |Hear about the latest Product updates and understand differences between V7 and V8 from our Product Managers.|Campaign Classic v7, Campaign v8|
|July 2022|[Keynote - Customer Journey trends and innovation across B2B & B2C](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en)|Video |Learn about the latest trends in Customer Journey Management across B2B and B2C. See the most recent innovations in key journey applications and the broader Adobe Experience Cloud and Platform.|Marketo, Campaign Classic v7, Campaign v8|
|July 2022|[Top Tips and Tricks for Adobe Campaign Standard](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en)|Video |Plug in to your Adobe Campaign Standard instance and discover best practices around targeting, personalization, and marketing fatigue to have a better usage of ACS.|Campaign Standard|
|July 2022|[Team, skills, and organizational design required to support cross-channel marketing](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html)|Video |Learn how to be empowered to engage wherever, whenever, and however you want. Learn the importance of having a marketing organization that supports planning, execution, and measurement.|Campaign Classic v7, Campaign v8, Campaign Standard|

{style="table-layout:auto"} -->

### Campaign 도움말 리소스

* Adobe Campaign v8: [설명서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=ko-KR) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ko-KR)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ko-KR) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ko-KR) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign Campaign 컨트롤 패널: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko-KR) - [릴리스 노트](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - 방법 비디오 [방법 비디오](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-overview.html?lang=en)

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer를 사용하면 단일 애플리케이션에서 수백만 고객을 위한 예정된 옴니채널 캠페인과 일대일 순간을 관리할 수 있으며, 지능적인 의사 결정과 통찰력으로 전체 여정을 최적화할 수 있습니다.

### 최신 Journey Optimizer 제품 릴리스

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=en)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

<!-- ### New Journey Optimizer tutorials and courses {#tutorials-ajo}

New videos, tutorials, or courses published for Adobe Journey Optimizer.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|July 2022|[Configure message frequency rules](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html)|Video |Learn how to create, activate, test, and report on frequency rules. Understand how to determine which frequency rules will be inherited for a message.|
|July 2022|[Configure, author, and deliver SMS messages](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html)|Video |Learn how to configure, author, and include SMS messaging into your customer journeys.|
|July 2022|[Inbound keyword support for SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html)|Video |Understand how native inbound keyword support (start, stop, unstop) for SMS works.|

{style="table-layout:auto"} -->

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ko-KR) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ko-KR)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ko-KR)

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간 지능적으로 예측하여 경험 채널에서 규모에 맞게 고객 여정을 오케스트레이션할 수 있습니다.

### 최신 [!DNL Journey Orchestration] 제품 릴리스

[[!DNL Journey Orchestration] 릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ko-KR)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

#### [!DNL Journey Orchestration]를 위한 추가 리소스

* [Journey Orchestration 설명서](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ko-KR)

## ![아이콘](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 주요 Marketo Engage 업데이트

최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ko-KR)을 참조하십시오.

### 새로운 Marketo 튜토리얼 및 교육 과정 {#tutorials-marketo}

Adobe Marketo에 게시된 새로운 비디오, 튜토리얼 또는 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 8월 | [Marketo Engage 자습서](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) | 비디오 | 다음 방문 [Marketo Engage 자습서 홈](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) Marketo Engage을 위한 모든 과거 및 새로운 자습서에 대한 Experience League 설정. |

{style=&quot;table-layout:auto&quot;}

최신 제품 설명서는 [Marketo 제품 설명서](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=en) 홈

## ![아이콘](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront]는 아이디어 공유, 콘텐츠 생성, 복잡한 프로세스 관리 및 최상의 작업 수행을 위한 통합 작업 관리 애플리케이션입니다.

### 새로운 Adobe Workfront 교육 과정 및 자습서 {#tutorials-workfront}

Experience League에 대한 새로운 Workfront 교육 과정 및 자습서

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 8월 | [Workfront 튜토리얼](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/home.html?lang=en) | 튜토리얼 홈 | Experience League에서 Workfront 자습서를 위한 새 홈 을 참조하십시오. |
| 2022년 8월 | [시스템 관리자를 위한 Workfront 시작하기](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.1.admin) | 교육 과정 | 시스템 설정을 사용하여 사용자를 설정하고 사용자의 경험을 최적화하는 방법에 대한 첫 번째 단계를 알아봅니다. |
| 2022년 8월 | [Workfront 관리자에 대한 시스템 설정 추가 정보](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.2.admin) | 교육 과정 | 사용자 조직, 사용자 지정 양식, 승인 프로세스 및 이정표, 레이아웃 템플릿 등 사용자의 경험을 향상시키기 위한 시스템 설정에 대해 자세히 알아보십시오. |
| 2022년 8월 | [계획자용 Workfront 시작하기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.1.planners) | 교육 과정 | 프로젝트를 만들고 계획하는 방법을 배워서 Workfront 여정을 시작합니다. Workfront에서는 단순하게 유지하는 것이 좋습니다. |
| 2022년 8월 | [프로젝트 관리 및 닫기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.2.planners) | 교육 과정 | 이제 프로젝트를 만들고 계획하는 방법을 배웠으므로 프로젝트를 관리하고 닫을 수 있습니다. |
| 2022년 8월 | [계획자로서 작업 관리에 대한 추가 이해 ](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.3.planners) | 교육 과정 | 프로젝트 만들기, 계획 및 관리의 기본 사항을 알게 되면 Workfront을 최대한 활용하기 위해 알고 있어야 하는 몇 가지 사항이 있습니다. |
| 2022년 8월 | [근로자를 위한 Workfront 시작하기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.1.workers) | 교육 과정 | 이 교육 과정은 작업 또는 요청을 받고 프로젝트 및 문서에서 팀과 공동 작업하는 Adobe Workfront의 작업 라이선스 사용자를 위한 것입니다. |
| 2022년 8월 | [Adobe Workfront for 공동 작업자](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.1.collaborators) | 교육 과정 | 새로운 Workfront 환경에서 검토 또는 요청 라이센스를 사용하여 작업, 문서 및 증명을 쉽게 요청, 검토 및 공동 작업하는 방법을 알아봅니다. |
| 2022년 8월 | [사용자 지정 양식 만들기 및 관리](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.1.customforms) | 교육 과정 | 시스템에서 사용자 지정 필드를 만들어 조직의 고유한 정보를 캡처합니다. Workfront 내에서 사용자 지정 양식을 만들고, 공유하고, 첨부하는 방법을 알아봅니다. |
| 2022년 8월 | [Workfront 증명 - 관리 및 설정](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.3.proof) | 교육 과정 | 증명 설정을 조정하고, 작업 및 보고서를 사용자 지정하고, 증명 워크플로우를 설정하는 방법을 알아봅니다. |
| 2022년 8월 | [Workfront 증명 - 증명 업로드](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.2.proof) | 교육 과정 | 검토 및 승인을 위해 증명을 업로드하는 방법을 알아봅니다. |
| 2022년 8월 | [Workfront 증명 - 작업 검토 및 승인](https://experienceleague.adobe.com/?recommended=Workfront-L-1-2022.1.proof) | 교육 과정 | Workfront 증명을 검토자 또는 승인자로 사용하는 방법을 알아봅니다. |
| 2022년 8월 | [기본 보고 요소](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.1.reporting) | 교육 과정 | 보고 요소는 Workfront의 모든 목록 보고서에 있는 필터, 보기 및 그룹화입니다. 이에 대해 학습하면 사용자 지정 보고서 및 달력을 만드는 데 도움이 됩니다. |
| 2022년 8월 | [사용자 지정 달력 만들기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.4.reporting) | 교육 과정 | 사용자 지정 달력을 사용하면 프로젝트, 작업 및 문제의 날짜 및 정보를 달력 형식으로 직접 표시할 수 있습니다. |
| 2022년 8월 | [사용자 지정 보고서 및 대시보드 만들기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.3.reporting) | 교육 과정 | 보고서는 데이터의 창입니다. Workfront에서 세 가지 유형의 보고서를 만들어 대시보드에서 사용하는 방법을 알아봅니다. |
| 2022년 8월 | [중간 필터 만들기](https://experienceleague.adobe.com/?recommended=Workfront-U-1-2022.2.reporting) | 교육 과정 | 와일드카드, OR 필터 및 텍스트 모드를 보다 잘 이해할 수 있습니다. 내장된 프로젝트, 작업 및 문제 필터를 열고 진행 중인 작업의 세부 사항을 살펴보십시오. |

{style=&quot;table-layout:auto&quot;}

자세한 내용은 [[!DNL Workfront] 제품 릴리스](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html) 페이지를 참조하십시오.

## ![아이콘](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

* [ [!DNL Advertising Cloud]의 새로운 기능](#adcloud-all)

<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
<!-- * [New features in [!DNL Advertising Cloud Search]](#adcloud-search) -->
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

### [!DNL Advertising Cloud]의 새로운 기능 {#adcloud-all}

마지막 업데이트: **2022년 8월 9일**

| 기능 | 설명 |
| ------- | ----------- |
| Adobe Analytics와의 통합 | (8월 6일 릴리스) Advertising Cloud이 보내는 데이터 피드 개선 사항 [!DNL Analytics] 검색 엔진의 클릭/비용/노출 데이터와 의 관련 전환 데이터 간에 불일치가 줄어듭니다. [!DNL Analytics]. |

{style=&quot;table-layout:auto&quot;}

<!--

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **July 27, 2022**

| Feature | Description |
| ------- | ----------- |
| [!UICONTROL Inventory] | (July 27 release) [!UICONTROL Auction Insights] is a new troubleshooting tool that allows you to analyze the deal composition of both guaranteed and non-guaranteed private deals. Using data visualizations, this tool shows the trend and relative proportions of values received for key auction attributes within a specific time period. |

{style="table-layout:auto"}

-->

<!--

### New features in [!DNL Advertising Cloud Search] {#adcloud-search}

Last updated: **, 2022**

| Feature | Description |
| ------- | ----------- |
|  |  |

-->

## ![아이콘](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud용으로 게시된 새로운 튜토리얼 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022년 8월 | [새로운 작업 공간 경험](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/new-workspace.html) | 비디오 | 도구 및 파일 간에 원활하게 이동할 수 있도록 Acrobat에서 활성화할 수 있는 새로운 작업 공간 경험에 대해 알아보십시오. | Adobe Acrobat |
| 2022년 8월 | [온라인 결제 설정](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/set-up-online-payments.html?lang=en) | 비디오 | 문서에서 온라인 결제를 설정하고 수락하는 방법을 알아봅니다. | Acrobat Sign |
| 2022년 8월 | [스탬프로 서명](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-stamp.html) | 비디오 | 서명 워크플로우에서 스탬프를 사용하여 승인되었거나 완료된 문서를 표시하는 방법을 알아봅니다. | Acrobat Sign |
| 2022년 8월 | [직접 서명 받기](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-in-person.html?lang=en) | 비디오 | 를 사용하여 다른 사람의 서명을 직접 가져오는 방법을 알아봅니다. [Acrobat Sign 모바일 앱](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/mobile/mobile-overview.html?lang=en). | Acrobat Sign |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko-KR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko-KR)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko-KR)을 참조하십시오.

## ![Icon](/assets/experience-league.png) 고객 데이터 관리 - 음성 {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=ko-KR)는 고객 데이터 관리 기술 및 마케팅 실무 리더이자 전문가의 대상입니다. 이 튜토리얼 컬렉션을 통해 동료의 의견을 듣고, 영감을 얻고, MarTech의 개발에 대해 종합적으로 배울 수 있습니다. 등록이 필요하지 않습니다. 클릭하여 시청하십시오.

## ![아이콘](/assets/experience-league.png) Digital Experience 블루프린트 {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=ko-KR)는 전략을 다루고 기존 비즈니스 문제를 빠르게 해결하기 위한 반복 가능한 구현입니다. 각 블루프린트는 고가치 비즈니스 문제, 아키텍처, 구현 단계, 기술 고려 사항 및 관련 문서 링크를 설명하는 일련의 아티팩트를 제공합니다.

[맨 위로](#events)
