---

copyright:
  years: 2017, 2018
lastupdated: "2018-03-16"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 앱 마이그레이션 및 호스팅
{: #hosting}

기존 앱이 있는 경우 필요한 모든 인프라 또는 플랫폼 서비스를 사용하여 {{site.data.keyword.Bluemix}}에 기존 앱을 호스팅할 수 있습니다. 앱을 클라우드 환경으로 한 번에 전환하는 대신 {{site.data.keyword.Bluemix_notm}}에 증분식으로 마이그레이션할 수도 있습니다.

## 앱 마이그레이션
{: #migrating}

앱에서 온프레미스 데이터 또는 서비스에 액세스해야 하는 경우에는 [{{site.data.keyword.SecureGatewayfull}}](../services/SecureGateway/secure_gateway.html)를 사용하여 {{site.data.keyword.Bluemix_notm}} 조직과 엔터프라이즈 백엔드 네트워크 간에 보안 터널을 설정할 수 있습니다. 세부사항은 [Reaching enterprise backend with {{site.data.keyword.Bluemix_notm}} Secure Gateway via console ](https://developer.ibm.com/bluemix/2015/04/01/reaching-enterprise-backend-bluemix-secure-gateway/){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg)을 참조하십시오.

마이그레이션에 대해 도움이 필요한 경우에는 [IBM Cloud Migration Services](https://www.ibm.com/cloud/migration-services){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")를 사용할 수 있습니다.

## 앱 호스팅
{: #ht_hostapp}

{{site.data.keyword.Bluemix_notm}} [카탈로그](https://console.bluemix.net/catalog/?taxonomyNavigation=apps){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")에서는 Kubernetes 또는 Cloud Foundry와 같은 관리 환경을 선택하거나, 베어메탈 또는 가상 서버에서 직접 앱을 호스팅할 수 있습니다.

가상 배치에서는 앱의 오퍼레이션 대부분이 {{site.data.keyword.Bluemix_notm}}에 의해 관리됩니다. 지리적 지역 간에 워크로드가 분산되어 있으며 {{site.data.keyword.Bluemix_notm}} 하이퍼바이저를 사용하여 배치를 관리하려는 경우에는 [가상](../vsi/vsi_about.html) 배치가 최상입니다. 고성능을 위해 전용 실제 서버에 대한 직접 액세스가 필요한 경우에는 [베어메탈](../bare-metal/index.html) 배치가 가장 좋습니다.

다음과 같이 다양한 옵션이 제공됩니다.
* 블록 스토리지, 파일 스토리지 또는 오브젝트 스토리지 중 필요한 [스토리지](https://console.bluemix.net/catalog/?taxonomyNavigation=apps&category=slstorage){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘") 유형을 선택합니다.
* 필요한 [네트워크](https://console.bluemix.net/catalog/?taxonomyNavigation=apps&category=slnetwork){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘") 유형을 선택합니다.
* {{site.data.keyword.Bluemix_notm}} Kubernetes 기술을 활용하는 데 필요한 [컨테이너화](https://console.bluemix.net/catalog/?taxonomyNavigation=apps&category=containers){: new_window} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘") 서비스를 선택합니다.
