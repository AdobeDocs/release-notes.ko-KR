---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 도움말과 튜토리얼을 찾아보십시오.'
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 3f75b897e739d296d4b69d0f85d50ef4fa661ff0
workflow-type: tm+mt
source-wordcount: '5702'
ht-degree: 49%

---

# Adobe Experience Cloud 릴리스 정보 - 2022년 3월

![배너](assets/experience-cloud-banner-3.png)

[Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)를 통해 성공적인 Experience Maker로서의 길을 시작해 보십시오. 방대한 입문용 문서 라이브러리, 셀프 가이드 튜토리얼, 입문용 비디오, 모든 레벨과 역할을 위한 과정, 동료들의 온라인 커뮤니티, 필요할 경우 전문가 지원을 찾아보십시오.

시작할 준비가 되셨습니까? [5분짜리 퀴즈를 풀고 당첨되어 보십시오.](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)

>[!NOTE]
>
>이 페이지의 업데이트에 대한 월별 이메일 알림을 받아 보려면 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)를 구독하십시오. Experience League의 최신 상황을 수시로 확인할 수 있습니다.

최신 업데이트: **2022년 3월 18일**

* [[!DNL Experience League] 이벤트](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 중앙 인터페이스 구성 요소 및 관리](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
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

도움이 필요하십니까? [Adobe Experience League](https://experienceleague.adobe.com/?lang=ko-KR/#home)에서 제품 및 기술 문서, Adobe에서 제공하는 교육 과정, 비디오 튜토리얼, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 교육을 확인할 수 있습니다.

## ![아이콘](/assets/experience-league.png) [!DNL Experience League] events {#events}

Experience League 이벤트는 Adobe의 제품 전문가로부터 학습, 상호 작용 및 답변을 얻을 수 있는 좋은 장소입니다.

| 이벤트 | 유형 | 설명 |
| -----------|---------- | ----|
| [Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | 라이브 및 온디맨드 비디오 | Experience League 팀이 만든 라이브 스트리밍 쇼입니다. Adobe 제품 전문가를 만나 볼 수 있는 기회입니다. Adobe Experience Cloud 애플리케이션에 적용할 수 있는 유용한 팁, 요령 및 전략을 배워 보십시오.<br> [세부 사항 및 과거 이벤트](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [AEM Gems](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) | Adobe Live 웨비나 | Adobe을 사용하여 SPA(단일 페이지 앱)을 신속하게 Bootstrap 및 배포 [!UICONTROL App Builder] Java™ 및 Sling과 같은 기존 Experience Manager 기술을 사용하지 않는 워크플로우 및 도구입니다. 마케터와 개발자는 Experience Manager 헤드리스를 사용하여 각각 고유한 도메인에 대한 전문 지식을 가질 수 있습니다. 개발자는 전체 애플리케이션 프레임워크, 스타일 지정 및 라우팅을 제어하고 마케터는 콘텐츠와 표시되는 방식을 결정할 수 있습니다.<br>**날짜:** 3월 23일 수요일 - [세부 사항 및 등록](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) |
| [Adobe Analytics: 데이터를 사용하여 효과적인 스토리 전달](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Adobe Live 웨비나 | 데이터 스토리텔링은 예술과 과학의 균형에서 잘 이루어진다. 그럼, 왜 과장을 하는 거죠? Adobe Analytics 챔피언 에이미 아드가 창의력을 잃지 않고 데이터 스토리텔링을 안내하기 위한 세 가지 부분에 대해 이야기합니다.<ul><li>영업 기회 또는 문제 확인</li><li>데이터 설명</li><li>솔루션 제공</li></ul>**날짜:** 3월 31일 목요일 - [세부 사항 및 등록](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b...%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [경험 작성자 - Adobe Workfront의 기술 교환](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Adobe Live 웨비나 | Experience Makers의 첫 번째 판을 발표하게 되어 매우 기쁘게 생각합니다. Adobe Workfront의 기술 교환이 4월 13일에 시작됩니다. 무료 3시간 디지털 학습 이벤트는 전적으로 Workfront에 중점을 두고 있으며, 고객은 작업 관리를 가장 잘 알고 있는 전문가 및 동료에게 실시간으로 질문을 할 수 있습니다. 여러분이 Workfront에 더 신참이거나 노련한 전문가라면, 우리는 모든 사람들을 위한 무언가를 가지고 있습니다. <br>**날짜:** 4월 13일 수요일 - [세부 사항 및 등록](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=ko-KR) | 비디오 | [!DNL Developers Live] 업계 전반에 걸쳐 디자인, 콘텐츠 제작 워크플로, 문서 서비스 및 고객 경험 관리를 지원하는 최신 기술 발전 및 개발자 도구를 소개합니다. 기조 연설을 보고 Analytics API, 클라이언트 데이터 레이어, Adobe I/O 오픈 소스 프로젝트 등에 대해 알아보십시오. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

최신 릴리스 정보는 Adobe 시스템 상태 를 참조하십시오. [릴리스 노트](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![아이콘](/assets/ec_appicon_24.png) Experience Cloud - 중앙 인터페이스 구성 요소 및 관리 {#ecloud}

Experience Cloud [중앙 UI 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) 홈 페이지와 영구 제품 헤더에서 사용할 수 있는 기능을 포함합니다. 이러한 기능에는 사용자 프로필 설정, 환경 설정 및 검색이 포함됩니다. 사용자 및 제품 관리, 고객 속성 및 Experience Cloud 대상에 대한 도움말도 찾을 수 있습니다.

| 기능 | 설명 |
| ------- |-------|
| 액세스 _[!UICONTROL 최근 항목]_ 를 사용하여 Experience Platform 및 Journey Optimizer 간 [!UICONTROL 통합 검색] | 를 통해 Experience Platform 및 Journey Optimizer의 모든 페이지에서 최근에 액세스한 객체에 액세스할 수 있습니다 [!UICONTROL 통합 검색] 필드.<br>자세한 내용은 [개체 및 엔터티 통합 검색](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en) 추가 정보. |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] 및 관리에 대한 추가 도움말 리소스**

* Experience Cloud Central UI 구성 요소에 대한 [릴리스 정보](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en)
* Experience Cloud(관리자)의 [사용자 및 제품 관리](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [릴리스 정보](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko-KR)
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)에 대한 제품 설명서
* 오브젝트 및 엔티티에 대한 [통합 검색](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform 및 [!UICONTROL 모바일 SDK]에 대한 최신 릴리스 정보와 새로운 설명서:

릴리스 날짜: **2022년 3월 7일**

* [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko-KR)

### 새로운 Experience Platform 튜토리얼 및 교육 과정 {#tutorials-platform}

Experience Platform을 위해 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [모바일 앱에서 Adobe Experience Cloud 구현 자습서](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html) | 교육 과정 | Adobe Experience Platform Mobile SDK를 사용하여 모바일 앱에서 Adobe Experience Cloud 애플리케이션을 구현하는 방법을 알아봅니다. |
| 2022년 3월 | [자사 장치 ID 생성](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html) | 비디오 | 자사 장치 ID 생성 및 장치 작동 방식에 대해 알아봅니다. |
| 2022년 3월 | [데이터스트림 구성](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html) | 비디오 | 웹 및 Mobile SDK 구현을 위한 데이터 세트를 만들고 구성하는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Adobe 모바일 SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 정보 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

릴리스 날짜: **2022년 3월 23일**

* Adobe Analytics [릴리스 노트](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=ko-KR) (**새 위치**)(검토자, 다음 위치로 이동 `https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en`)
* Adobe Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html?lang=ko-KR)

### AppMeasurement {#appm}

릴리스 버전: **2.22.4**

* [JavaScript 릴리스 정보의 AppMeasurement](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ko-KR)

### 새로운 Analytics 튜토리얼 및 교육 과정 {#tutorials-analytics}

Adobe Analytics용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [사용자를 단순화하고 교육하는 시간을 줄이는 방법에 대한 팁과 트릭](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=en) | 비디오 및 문서 | 잘 훈련된 Adobe Analytics 조직이 비즈니스에 얼마나 중요한지 알아봅니다. |
| 2022년 3월 | [자율 커뮤니티를 만들기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html) | 비디오 및 문서 | 권한이 부여된 Analytics 커뮤니티의 값과 이를 만들고 지원하는 방법을 알아봅니다. |
| 2022년 3월 | [마케팅 채널 처리 규칙 만들기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=en) | 비디오 | 구성 방법 알아보기 [!UICONTROL 처리 규칙] 대상 [!UICONTROL 마케팅 채널]. |
| 2022년 3월 | [보고서 세트에서 마케팅 채널 설정](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html) | 비디오 | 이 비디오에서는 Analytics 보고서 세트에서 마케팅 채널 보고를 구성하는 방법을 알아봅니다. |
| 2022년 3월 | [Google Analytics에서 Adobe Analytics으로 전환](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=en) | 비디오 | 로 전환을 위한 포괄적인 안내서 [!DNL Adobe Analytics] 변환 전: [!DNL Google Analytics]. |
| 2022년 3월 | [계층 변수 구성](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=en) | 비디오 | 사이트에 대한 계층 변수를 설정하고 구성하는 방법 및 시기를 알아봅니다. 이 기능을 사용하여 사이트의 페이지에 대한 계층적 보기와 각 노드에 전달되는 트래픽의 양을 표시할 수 있습니다. |
| 2022년 3월 | [Analysis Workspace에서 조정 및 공유](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=en) | 비디오 | Analysis Workspace에서 프로젝트 조정 및 공유 작업을 하는 방법을 알아봅니다. |
| 2022년 3월 | [Analysis Workspace의 프로젝트에 대한 직접 링크](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=en) | 비디오 | 동료에게 Analysis Workspace 프로젝트로 바로 안내하는 단축된 링크를 만들어 Analytics를 더 잘 민주화할 수 있는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

릴리스 날짜: **2022년 3월 23일**

* Customer Journey Analytics [릴리스 노트](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=ko-KR)  (**새 위치**)(검토자, 다음 위치로 이동 `https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en`)
* Customer Journey Analytics [제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=ko-KR)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 수정 및 개선 사항:

| 개선 사항 | 설명 |
| -----------| ---------- |  
| 다른 회사에 속하는 target 데이터 소스에 대한 유효성 검사기 | Audience Manager은 다음과 같은 개선 사항을 발표했습니다 [배치 데이터 온보딩 프로세스](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). 다른 파트너가 소유한 대상 데이터 소스에 파일 및 데이터 온보딩을 우발적으로 방지하기 위해 Audience Manager은 파트너 ID(PID)와 다른 파트너가 소유한 DPID(데이터 소스) 간에 매핑 요구 사항을 추가했습니다. <ul><li>참조 -_DPID_TARGET_DATA_OWNER_ 필드 [인바운드 데이터 파일에 대한 Amazon S3 이름 및 파일 크기 요구 사항](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Adobe 내부 컨설턴트와 고객 지원 센터에서 [제2자 데이터에 대한 온보딩 액세스 관리](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) 새 매핑에 대한 자세한 내용은 개선된 기능을 사용하고 새 매핑을 요청하는 방법을 참조하십시오</li><li>그렇습니다 _not_ 기존 데이터 공유 관계에 대한 매핑을 요청하는 데 필요합니다. 매핑도 _not_ PID에 속하는 target 데이터 소스에 데이터를 온보딩할 때 필요합니다.</li></ul> |

{style=&quot;table-layout:auto&quot;}

자습 리소스는 [Audience Manager 설명서 및 자습서](https://experienceleague.adobe.com/docs/audience-manager.html?lang=ko-KR) Experience League에서 확인하십시오.

## ![아이콘](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=ko-KR) 페이지를 방문할 것을 권장합니다.

### Experience Manager 제품 업데이트

* **Experience Manager 6.5, 서비스 팩 12(6.5.12.0)**

   Adobe Experience Manager 6.5.12.0에는 2019년 4월 6.5 릴리스의 가용성 이후 릴리스된 새로운 기능, 주요 고객이 요청한 향상된 기능 및 성능, 안정성, 보안 개선 사항이 포함되어 있습니다. 서비스 팩은 Adobe Experience Manager 6.5에 설치됩니다.

   자세한 내용은 [릴리스 노트](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=ko-KR).

### Experience Manager 제품 릴리스

* **Experience Manager as a Cloud Service**

   * [2022년 1월 릴리스 개요 비디오](https://video.tv.adobe.com/v/340120) 새로운 기능.
   * 새로운 기능에 대한 [2021년 12월 릴리스 개요 비디오](https://video.tv.adobe.com/v/339278)
   * 새로운 기능에 대한 [2021년 10월 릴리스 개요 비디오](https://video.tv.adobe.com/v/338253).
   * 새로운 기능에 대한 [2021년 9월 릴리스 개요 비디오](https://video.tv.adobe.com/v/337381).

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets의 새로운 기능_

      * Dynamic Media - 이제 Dynamic Media Classic 데스크탑 애플리케이션을 사용하지 않고도 Experience Manager - Dynamic Media 인터페이스를 사용하여 [일반 설정](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=ko-KR) 및 [게시 설정](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=ko-KR)을 구성할 수 있습니다.
      * Dynamic Media는 이제 MXF 비디오에 대해 수집, 미리보기, 재생 및 게시 기능을 지원합니다. MXF에 대한 주석 및 구매 가능한 비디오는 아직 지원되지 않습니다.
      * 원격 DAM 및 Sites 배포 간의 연결을 구성한 후에는 Sites 배포에서 원격 DAM의 에셋을 사용할 수 있습니다. 이제 원격 DAM 에셋 또는 폴더에서의 [작업을 업데이트하고, 삭제하고, 이름을 바꾸고, 이동](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=ko-KR)할 수 있습니다. 업데이트는 약간의 지연과 함께 Sites 배포에서 자동으로 사용할 수 있습니다.

      _Experience Manager Assets 프리릴리스 채널의 새로운 기능_

      * 이제 Dynamic Media는 사용자 인터페이스에서 [하나의 회사 별칭 계정을 구성](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=ko-KR)할 수 있는 유연성을 제공하므로 즉시 사용 가능한 Dynamic Media URL 및 Viewer Embed 코드가 업데이트됩니다. 이는 리브랜딩과 같은 비즈니스 컨텍스트에 대한 업데이트를 반영하여 SEO에 긍정적인 영향을 미칩니다.
      * 이제 Experience Manager Assets 사용자 인터페이스를 사용하여 다음을 수행할 수 있습니다.

         * 저장소에서 중복 에셋 감지를 구성합니다.
         * 이미지에 디지털 워터마크 추가를 구성합니다.
      * 이제 관리자는 대량 다운로드를 위한 이메일 서비스를 구성할 수 있습니다. 이를 통해 사용자는 Experience Manager Assets 인터페이스에서 [대량 다운로드에 대한 이메일 알림을 활성화](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=ko-KR#enable-email-notifications-for-large-downloads)할 수 있습니다. 사용자는 다운로드 프로세스가 완료되면 아카이브된 zip 폴더의 다운로드 링크가 포함된 이메일 알림을 수신하게 됩니다.
      * [게시 관리](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=ko-KR) 기능은 개선된 사용자 인터페이스로 향상되었습니다. 사용자는 선택한 대상에서 콘텐츠를 게시하거나 게시를 취소할 수 있으며 DAM 저장소의 게시 목록에 [콘텐츠를 추가](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=ko-KR#add-content)할 수 있습니다. 또한 [폴더 설정을 포함하여](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=ko-KR#include-folder-settings) 선택한 폴더의 콘텐츠를 게시하고 필터를 적용하고, 나중에 게시할 날짜 또는 시간에 [게시 일정](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=ko-KR#publish-assets-later)을 지정할 수 있습니다.

      _버그 수정_

      * 원본 렌디션이 없는 처리되지 않은 에셋은 Experience Manager 온프레미스에서 클라우드 서비스로 에셋을 마이그레이션하는 동안 처리를 위해 Asset Compute로 전송됩니다.
   * **Experience Manager Forms as a Cloud Service**

      _Forms의 새로운 기능_

      * **Experience Manager Forms as a Cloud Service - 통신** - [통신 API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=ko-KR)를 통해 템플릿과 XML 데이터를 결합하여 다양한 형식의 인쇄 문서를 생성할 수 있습니다. 이 서비스를 통해 동기화 모드와 배치 모드에서 문서를 생성할 수 있습니다. API를 사용하면 다음 작업을 수행하는 데 도움이 되는 애플리케이션을 만들 수 있습니다.

         * XML 데이터로 템플릿 파일을 채워 문서를 생성합니다.
         * 비대화형 PDF 인쇄 스트림을 포함하여 다양한 형식의 양식을 생성합니다.
         * XFA 양식 PDF에서 인쇄 PDF를 생성합니다.
         * 여러 데이터 세트를 소스 템플릿과 병합하여 PDF, PostScript, PCL 및 ZPL 문서를 대량으로 생성합니다.
      * **커뮤니케이션 API로 생성된 기록 문서 및 PDF 문서에 대한 맞춤형 글꼴** - 이제 커뮤니케이션 API를 사용하여 생성된 PDF 문서의 브랜드 승인 글꼴을 사용하여 조직 요구 사항을 맞출 수 있습니다.

      _Forms 프리릴리스 채널의 새로운 기능_

      * [어셈블러 API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) - PDF 문서에 대한 정보를 결합, 재배열, 보강 및 얻을 수 있는 어셈블러 API입니다.
   * **Cloud Manager**

      _릴리스 날짜_

      Experience Manager as a Cloud Service 2022.01.0의 Cloud Manager 릴리스 날짜는 2022년 1월 20일입니다.
다음 릴리스는 2022년 3월 31일에 예정되어 있습니다.

      _새로운 기능_

      * Cloud Manager는 [동일한 Git Commit이 여러 전체 스택 파이프라인 실행에 사용되는 것을 감지하면 코드 베이스를 다시 빌드하지 않습니다](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=ko-KR#build-artifact-reuse).
      * 이제 Experience Manager 환경 로그에 액세스하려면 **[!UICONTROL Deployment Manager]** 제품 프로필이 필요합니다. 이 프로필이 없는 사용자에게는 사용자 인터페이스에서 비활성화된 버튼이 표시됩니다.
      * 사용자 인터페이스는 Sites를 솔루션으로 사용할 수 없는 프로그램에 대한 프런트 엔드 파이프라인 구성을 허용하지 않습니다.
      * Git 비밀번호 생성 시 만료 날짜가 표시됩니다.








### 커뮤니티

* **Experience Manager GEM Webinar: _Experience Manager Headless 및 App Builder를 사용하여 보다 빠르게 사이트 구축_**

   * 2022년 Adobe Summit 개회사 기조 연설을 놓치셨나요? 보기 [개인 디지털 경제 구축](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612).
   * Adobe Summit 2022 | [전체 Experience Manager 세션 목록](https://adobe.ly/3rti6gF).
   * Experience Manager GEM | 웨비나 | 2022년 3월 23일 수요일
      * 항목: *Experience Manager 헤드리스 및 App Builder를 사용하여 보다 신속하게 사이트 구축*
      * [여기에서 등록](https://adobe.ly/3oCkEsh)
      * [Q&amp;A용](https://adobe.ly/3LkSWdm)

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022년 3월 | [AEM Headless를 사용하여 개발 시작](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=ko-KR) | 교육 과정 | ExL에서 AEM 헤드리스의 모든 컨텐츠를 함께 가져오는 AEM 헤드리스 랜딩 페이지를 만듭니다. | AEM Headless |
| 2022년 3월 | [Adobe Experience Manager as a Cloud Service에서 첫 번째 웹 사이트 만들기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.1.aemcs.website) | 교육 과정 | 사전 정의된 사이트 템플릿을 사용하여 Experience Manager에서 새 웹 사이트를 신속하게 생성합니다. | AEM Sites |
| 2022년 3월 | [제출된 데이터 xml에서 노드 추출](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=en) | 비디오 | 다른 XML 문서에서 노드를 추출하여 XML 문서를 만드는 이 사용자 지정 프로세스 단계를 알아봅니다. 제출된 데이터를 XDP 템플릿과 병합하여 PDF을 생성하려는 경우 이 프로세스를 사용합니다. | AEM Forms |
| 2022년 3월 | [파일 시스템에 문서를 작성합니다](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=en) | 비디오 | 워크플로우에서 생성된 문서를 파일 시스템에 쓰는 방법을 알아봅니다. | AEM Forms |
| 2022년 3월 | [사용자 지정 함수](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=en) | 비디오 | AEM Forms 6.5에서는 규칙 편집기를 사용하여 복잡한 비즈니스 규칙을 정의하는 데 사용할 수 있는 JavaScript 함수를 정의하는 기능을 도입했습니다. | AEM Forms |
| 2022년 3월 | [Workfront for Experience Manager enhanced connector Expert Series](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=en) | 비디오 | 이 4가지 부분 비디오 시리즈에서는 Adobe의 Workfront 및 Experience Manager Assets 전문가에게 Workfront for Experience Manager enhanced connector의 내부 및 외부 설명을 제공하고 설명합니다. | AEM Assets, Workfront |
| 2022년 3월 | [계단식 드롭다운 목록](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=en) | 비디오 | 계단식 드롭다운 목록이 있는 양식을 만드는 샘플 자산이 있는 자습서입니다. | AEM Forms |
| 2022년 3월 | [초기 설정 및 구성](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=en) | 비디오 | AEM Assets과 Workfront의 통합 기능을 잠금 해제하여 Experience Manager 향상 커넥터를 위한 Workfront을 설정 및 구성하는 방법을 알아봅니다. | AEM Assets, Workfront |
| 2022년 3월 | [Workfront 사용자 지정 양식 및 메타데이터 매핑](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=en) | 비디오 | Workfront 사용자 지정 양식 및 AEM 메타데이터 스키마를 사용하여 자산 메타데이터를 관리하고 동기화하도록 Workfront 및 AEM Assets을 구성하는 방법을 알아봅니다. | AEM Assets, Workfront |
| 2022년 3월 | [AEM 태그, 프로젝트 연결 폴더 및 폴더 메타데이터](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=en) | 비디오 | Workfront 데이터를 통해 자산에서 AEM 태그를 사용하도록 유도하고, 프로젝트 연결 폴더를 설정 및 사용하고, Workfront 데이터를 AEM 자산 폴더 메타데이터 스키마에 사용하는 방법을 알아봅니다. | AEM Assets, Workfront |
| 2022년 3월 | [고급 설정 및 워크플로우](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=en) | 비디오 | Workfront for AEM enhanced connector의 고급 설정에 대해 알아보고, AEM에서 고급 워크플로우 및 런처를 구성하여 AEM과 Workfront 간의 데이터 동기화를 관리하는 방법을 알아봅니다. | AEM Assets, Workfront |
| 2022년 3월 | [Dynamics 계정 만들기 및 구성](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=en) | 비디오 | Microsoft® Dynamics를 Azure Active Directory에 등록하는 단계를 알아봅니다. | AEM CS |
| 2022년 3월 | [공개 링크 공유](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html) | 비디오 | Assets Essentials 공유 링크를 통해 사용자가 잘못된 자산 또는 정보를 공유하는 위험을 최소화하면서 내부 및 외부 이해 관계자와 자산을 공유할 수 있는 방법을 알아봅니다. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보

모든 Experience Manager 릴리스 정보는 다음 페이지에서 유지 관리됩니다.

* [Experience Manager as a Cloud Service 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=ko-KR)
* [Experience Manager Cloud Manager 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=ko-KR)
* [자동 양식 전환 서비스 릴리스 정보](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ko-KR)
* [Experience Manager 6.5 서비스 팩 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ko-KR)
* [Experience Manager Assets Dynamic Media 릴리스 정보](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ko-KR)
* [Experience Manager Brand Portal 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ko-KR)
* [Experience Manager 데스크탑 앱 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ko-KR)
* [Experience Manager Dispatcher 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ko-KR)
* [Adobe Primetime 릴리스 정보](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ko-KR)
* [Livefyre 릴리스 정보](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ko-KR)

### Experience Manager용 기타 도움말 리소스

* [Experience Manager as a Cloud Service 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=ko-KR)
* [Cloud Manager 사용 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ko-KR)
* [Experience Manager 6.5 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ko-KR)
* [Experience Manager 6.4 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ko-KR)
* [Experience Manager 6.3 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR)
* [Experience Manager 6.2 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR#previous-updates)
* [이전 버전의 Experience Manager 설명서](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 도움말 홈](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ko-KR)
* [Experience Manager 설명서: 최신 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ko-KR#aem-as-a-cloud-service)

## Adobe Experience Manager를 위한 ![아이콘](/assets/ec_appicon_24.png) XML 설명서 {#xml-doc}

Adobe Experience Manager를 위한 XML 설명서는 AEM에 배포된 애플리케이션입니다. Adobe Experience Manager의 기본 DITA 지원을 활성화하는 강력한 엔터프라이즈급 구성 요소 콘텐츠 관리 솔루션(CCMS)으로, AEM에서 DITA 기반 콘텐츠 생성 및 전달을 처리할 수 있도록 촉진합니다.

[AEM을 위한 XML 설명서](https://www.adobe.com/kr/products/xml-documentation-for-experience-manager/features.html)에 대해 자세히 알아보십시오.

### 에 대한 새로운 자습서 [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

에 게시된 새로운 비디오, 자습서 또는 교육 과정 [!DNL XML Documentation for Adobe Experience Manager].

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [XML을 사용한 출력 생성 설명서](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs) | 교육 과정 | 을 사용하여 출력을 생성하는 방법을 알아봅니다. [!DNL XML Documentation for Adobe Experience Manager]. 보고서, 기준선, 조건, 문제 해결, 일괄 게시 및 활성화 등 출력 생성에 사용할 수 있는 다양한 기능에 대해 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### 추가 리소스

* [Adobe Experience Manager를 위한 XML 설명서](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=ko-KR) - Experience League 튜토리얼
* [Adobe Experience Manager 학습 및 지원을 위한 XML 문서](https://helpx.adobe.com/kr/support/xml-documentation-for-experience-manager.html) - 제품 문서

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Adobe Commerce용 클라우드 제품군](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 새로운 Adobe Commerce 리소스 {#new-commerce}

Experience League에 대한 Adobe Commerce에 대한 새로운 설명서 및 자습서.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [결제 서비스 안내서](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html) | 안내서 | Adobe Commerce 및 Magento Open Source 관리자를 위한 안내서입니다. 여기에는 결제 서비스의 설치 및 온보딩과 서비스 구성 및 관리에 대한 자세한 정보가 포함되어 있습니다. 이 섹션에서는 코어 상거래 구성 및 기능에 대한 기본적인 이해를 가정합니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/target.png) [!DNL Adobe Target] {#target}

마지막 업데이트 날짜: **2022년 2월 1일**

* 이전 릴리스에 대한 자세한 내용은 [Adobe Target 프리릴리스](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko-KR)를 참조하십시오.
* 최신 릴리스에 대한 자세한 내용은 [Adobe Target 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=ko-KR)를 참조하십시오.

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

릴리스된 최신 기능, 개선 사항 및 수정 사항에 대해 자세히 알아보십시오.

* [Campaign Classic v7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ko-KR)

### 새로운 [!DNL Campaign] 튜토리얼 및 교육 과정 {#tutorials-campaign}

Adobe Campaign에 대해 게시된 새로운 자습서 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 | 애플리케이션 |
| ------| ----- | -----| ------ | --- |
| 2022년 3월 | [Experience Manager와 통합 - 개요](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/overview.html?lang=ko) | 비디오 | Adobe Campaign과 Adobe Experience Manager를 연결하면 Experience Manager에서 이메일 게재 템플릿, 자산, 양식을 관리할 수 있습니다. | AEM, Campaign v8 |
| 2022년 3월 | [Experience Manager 통합을 위한 Campaign 구성](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=en) | 비디오 | 찾아야 할 중요한 설정과 피해야 할 잠재적 &#39;과제&#39;를 포함하여 Experience Manager과 Campaign 간의 통합을 설정하는 방법을 알아봅니다. | AEM, Campaign v8 |
| 2022년 3월 | [Campaign에서 Experience Manager 페이지 승인 및 게시](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=en) | 비디오 | Experience Manager에서 뉴스레터를 만드는 방법과 Campaign에서 이 뉴스레터를 승인하고 게시하는 방법을 알아봅니다. | AEM, Campaign v8 |
| 2022년 3월 | [Campaign에서 Experience Manager 이메일 게재 동기화 및 보내기](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=en) | 비디오 | Experience Manager에서 만들어진 뉴스레터를 사용하여 Adobe Campaign에서 이메일을 테스트하고 보내는 방법을 알아봅니다. | AEM, Campaign v8 |
| 2022년 3월 | [Adobe Target과 통합](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html) | 비디오 | Adobe Target에서 제공하는 동적 콘텐츠를 사용하여 게재를 개인화하는 방법을 알아봅니다. | Adobe Target, Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [설명서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ko-KR)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ko-KR) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ko-KR) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ko-KR) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ko-KR) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ko-KR) 방법 비디오

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer를 사용하면 단일 애플리케이션에서 수백만 고객을 위한 예정된 옴니채널 캠페인과 일대일 순간을 관리할 수 있으며, 지능적인 의사 결정과 통찰력으로 전체 여정을 최적화할 수 있습니다.

### 최신 Journey Optimizer 제품 릴리스

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=ko-KR)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

### Journey Optimizer 튜토리얼 및 교육 과정 {#tutorials-ajo}

최신 Journey Optimizer 튜토리얼:

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [개인화 라이브러리에서 저장된 표현식 사용 및 관리](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=en) | 비디오 | 메시지에 저장된 개인화 라이브러리 항목을 사용하는 방법과 개인화 라이브러리 항목을 만들고 관리하는 방법을 알아봅니다. |

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ko-KR)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=ko-KR)

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 고객 여정을 조율할 수 있습니다.

### 최신 [!DNL Journey Orchestration] 제품 릴리스

[[!DNL Journey Orchestration] 릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ko-KR)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

#### [!DNL Journey Orchestration]를 위한 추가 리소스

* [Journey Orchestration 설명서](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ko-KR)

## ![아이콘](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 주요 Marketo Engage 업데이트

최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ko-KR)을 참조하십시오.

### 새로운 Marketo 자습서 및 강좌 {#tutorials-marketo}

Adobe Marketo에 대해 게시된 새로운 자습서 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [개인화된 대화 상자 만들기 및 관리](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=en) | 비디오 | 을(를) 만들고 관리하는 방법을 알아봅니다. _[!UICONTROL 대화 상자]_. 타겟팅되고 개인화된 대화를 디자인하는 것은 모든 웹 방문자를 위한 훌륭한 대화형 경험을 만드는 열쇠입니다. |
| 2022년 3월 | [차트 보트 설정 및 설치](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=en) | 비디오 | 웹 사이트나 랜딩 페이지에 chatbot JavaScript를 설치하고 브랜드와 일치하도록 모양을 사용자 지정하는 데 도움이 되는 안내서입니다. |
| 2022년 3월 | [영업 팀과 회의를 예약할 수 있도록 합니다.](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=en) | 비디오 | 사용 [!UICONTROL 다이내믹 채팅] target 계정 리드에 대한 매출과의 연결을 가속화하기 위해 |
| 2022년 3월 | [Marketo 통합 활성화 [!UICONTROL 다이내믹 채팅]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=en) | 비디오 | [!UICONTROL 다이내믹 채팅] 는 기본적으로 Marketo Engage에 통합되어 있으므로 chatbot 대화의 컨텍스트를 사용하여 잠재 고객을 재타겟팅하거나 점수를 받을 수 있습니다. |
| 2022년 3월 | [사용자 관리 [!UICONTROL 다이내믹 채팅]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=en) | 비디오 | 관리 [!UICONTROL 다이내믹 채팅] Adobe Admin Console을 통해 사용자를 검색합니다. |
| 2022년 3월 | [제품 둘러보기 [!UICONTROL 다이내믹 채팅]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=en) | 비디오 | [!UICONTROL 다이내믹 채팅] 는 마케팅 및 영업을 위해 만들어진 새로운 차트 보트 솔루션입니다. 기본적으로 Marketo Engage과 통합되어 있으므로 채널 간 마케팅에서 새로운 채널로 동적 채팅을 사용할 수 있습니다. 사용이 간단하고 설정이 쉽습니다. |

## ![아이콘](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront]는 아이디어 공유, 콘텐츠 생성, 복잡한 프로세스 관리 및 최상의 작업 수행을 위한 통합 작업 관리 애플리케이션입니다.

모든 제품에 대한 최신 정보를 보려면 [[!DNL Workfront] 릴리스](https://one.workfront.com/s/product-releases) 페이지를 참조하십시오.

## ![아이콘](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [ [!DNL Advertising Cloud Search]의 새로운 기능](#adcloud-search)
* [새로운 [!DNL Advertising Cloud] 튜토리얼](#tutorials-ad-cloud)

<!-- 
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
-->

<!-- 
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

<!--
{style="table-layout:auto"}
-->

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

마지막 업데이트: **2022년 3월 14일** 3월 12일 릴리스

| 기능 | 설명 |
| ------- | ----------- |
| [!UICONTROL 포트폴리오] | 기본적으로 하이브리드 최적화는 캠페인 수준에서 사용할 수 있습니다. 이제 최적화 기능이 설정된 광고 그룹 수준에서 하이브리드 최적화를 선택적으로 활성화할 수 있습니다 [!DNL Google] CPA 또는 ROAS는 광고 그룹 수준에서 타겟을 지정하므로 성능을 보다 정확하게 제어할 수 있습니다.<br>모든 포트폴리오에서 학습 기간을 허용하여 포트폴리오 시작 전에 충분한 모델 적용 범위를 확보할 수 있어야 합니다. 마찬가지로, 하이브리드 포트폴리오를 캠페인 수준에서 광고 그룹 수준 최적화로 변경한 다음 포트폴리오를 약 2주 동안 활성 상태로 설정하십시오. 따라서 최적화 기능에서 포함된 광고 그룹에 대해 알아보고 타겟을 생성할 시간이 있습니다.<br>이제 광고 그룹 수준 최적화를 지원하기 위해 사용자 지정 시뮬레이션에 광고 그룹별 결과가 포함될 수 있습니다. 광고 그룹 수준 최적화를 사용하여 하이브리드 포트폴리오를 시작하기 전에 광고 그룹 수준 결과를 사용하여 사용자 지정 시뮬레이션을 실행합니다. |
| [!UICONTROL 포트폴리오] <br> [!UICONTROL 캠페인] | (베타 기능, [!DNL Microsoft® Advertising] campaigns) - 이제 검색 캠페인을 구성하여 [!UICONTROL 전환 최대화] 입찰 전략이며 선택적으로 클릭당 최대 비용을 설정합니다.<br>다른 자동 입찰 전략을 위해 이미 하이브리드 최적화 베타에 참여하는 경우 자동으로 [!UICONTROL 전환 최대화] 전략과 함께 캠페인을 포함할 수 있습니다. [!UICONTROL 전환 최대화] 하이브리드 포트폴리오의 전략 하이브리드 포트폴리오에서 이 전략을 사용하려면 Advertising Cloud Search 목표를에 업로드하도록 설정해야 합니다 [!DNL Microsoft® Ads]. 베타에 아직 참가하지 않고 참가하려면 [!DNL Adobe] 계정 관리자. |
| 캠페인 [!UICONTROL 대상]<br><br>캠페인 [!UICONTROL 일괄 시트] | ([!DNL Microsoft® Advertising] campaigns) - 이제 [!DNL Microsoft® Advertising] 시장 내 대상을 캠페인 수준 타겟 또는 캠페인으로 제외한 대상 [!UICONTROL adgroup]-수준 타겟입니다. 이전에는 이 변수들을 [!UICONTROL adgroup]-수준 타겟입니다. |
| 캠페인 [!UICONTROL 대상] | (베타 기능, [!DNL Microsoft® Advertising] 다음에 적합한 계정 [!UICONTROL 고객 일치]) 이제 이메일 주소를 사용하여 CSV 파일을 업로드하여 고객 일치 대상을 만들고 관리할 수 있습니다. SHA-256 알고리즘을 사용하여 데이터를 해시해야 합니다. |

{style=&quot;table-layout:auto&quot;}

### 새로운 Advertising Cloud 튜토리얼 {#tutorials-ad-cloud}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [표준 디스플레이 배치를 만드는 방법](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html) | 비디오 | Advertising Cloud DSP 캠페인에 대한 표준 표시 배치를 만드는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Adobe Document Cloud에 대해 게시된 새로운 자습서 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 3월 | [사용자 정의 명령 및 도구](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=en) | 비디오 | 사용자 정의 명령과 도구를 사용하여 문서 워크플로우 생산성을 향상시키는 방법을 알아봅니다. 그런 다음 새 명령과 도구를 동료와 공유하여 조직의 효율성을 높입니다. |
| 2022년 3월 | [책갈피 및 하이퍼링크 추가](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=en) | 비디오 | PDF 파일과의 탐색 및 상호 작용을 향상하기 위해 책갈피와 하이퍼링크를 추가하는 방법을 알아봅니다. |
| 2022년 3월 | [스캔한 문서 최적화](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html) | 비디오 | 문서를 카메라나 스캐너에서 가져오는지 여부에 관계없이 Acrobat에서 더 나은 PDF 보기 및 검색 환경을 위해 결과를 향상시키는 방법을 배웁니다. |
| 2022년 3월 | [양식 필드를 포함하는 Word를 PDF으로 변환](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 Word 파일 및 양식을 PDF으로 변환하고 양식 필드를 자동으로 작성하는 방법을 알아봅니다. |
| 2022년 3월 | [고급 양식 필드](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=en) | 비디오 | 이 실습 자습서에서는 기존 양식 필드를 모두 다시 빌드하지 않고 계산을 설정하고, 전자 메일 제출 단추를 만들고, 양식 페이지를 빠르게 업데이트하는 방법을 알아봅니다. |
| 2022년 3월 | [스냅에서 보다 효율적인 PDF 파일 생성](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 Optimize PDF 도구를 사용하여 PDF 파일의 크기를 크게 줄이는 방법을 알아봅니다. |
| 2022년 3월 | [스캔한 PDF 파일에서 텍스트 인식](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 PDF에서 텍스트를 검색할 수 있도록 스캔한 PDF을 변환하는 방법을 알아봅니다. |
| 2022년 3월 | [Acrobat을 통해 액세스 가능한 PDF 만들기](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 PDF이 액세스 가능한지 확인하는 방법을 알아봅니다. |
| 2022년 3월 | [휴대폰에서 Word로 Export PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 Acrobat 모바일 앱을 사용하여 PDF 파일을 편집 가능한 Microsoft® Word 문서로 변환하는 방법을 알아봅니다. |
| 2022년 3월 | [암호를 사용하여 PDF 파일 Protect](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=en) | 비디오 | 이 60초 비디오 자습서에서는 PDF을 열거나 편집하기 위해 암호가 필요하도록 PDF을 보호하는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko-KR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko-KR)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko-KR)을 참조하십시오.

## ![아이콘](/assets/experience-league.png) 고객 데이터 관리 - 음성 {#voices}

[고객 데이터 관리 음성](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) 는 고객 데이터 관리 기술 및 마케팅 실무 담당자 및 전문가로서의 대상입니다. 이 자습서 컬렉션은 동료로부터 의견을 듣고, 영감을 받고, MarTech의 개발에 대해 배울 수 있는 원스톱 샵입니다. 등록할 필요가 없습니다. 를 클릭하고 확인하십시오.

## ![아이콘](/assets/experience-league.png) Digital Experience 블루프린트 {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=ko-KR)는 전략을 다루고 기존 비즈니스 문제를 빠르게 해결하기 위한 반복 가능한 구현입니다. 각 블루프린트는 고가치 비즈니스 문제, 아키텍처, 구현 단계, 기술 고려 사항 및 관련 문서 링크를 설명하는 일련의 아티팩트를 제공합니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2022년 2월 | [고객 여정](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=ko-KR) | 비디오 | 고객 여정은 브랜드가 이메일, SMS 및 모바일 알림과 같은 채널을 통해 주도적으로 고객과 관계를 맺고 소통할 수 있는 기능을 제공합니다. |
| 2022년 2월 | [Campaign v7 블루프린트](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=ko-KR) | 비디오 | Adobe Campaign v7은 이메일 및 DM(Direct Mail)과 같은 기존 마케팅 채널을 위해 구축된 캠페인 도구입니다. 완벽한 캠페인을 만들고 선별하는 데 도움이 되는 강력한 ETL 및 데이터 관리 기능을 제공합니다. |

{style=&quot;table-layout:auto&quot;}
