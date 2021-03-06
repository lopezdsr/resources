---

copyright:
  years: 2015, 2019
lastupdated: "2019-01-28"

keywords: service keys, api keys, using services outside IBM cloud

subcollection: resources

---

{: new_window: target="_blank"}
{:shortdesc: .shortdesc}
{: codeblock: .codeblock}
{: tip: .tip}

# 將服務連接至外部應用程式
{: #externalapp}

您可能有在 {{site.data.keyword.Bluemix}} 之外建立和執行的應用程式，或是您可能使用協力廠商工具。如果 {{site.data.keyword.Bluemix_notm}} 服務提供可從網際網路存取的服務金鑰，您可以使用那些服務來搭配本端應用程式或協力廠商工具。

若要讓外部應用程式或協力廠商工具能夠使用 {{site.data.keyword.Bluemix_notm}} 服務，請完成下列步驟：

大部分服務都不需要額外的參數，對於有需要的服務，每個服務都會定義自己獨特的參數清單。如需所支援配置參數的清單，請參閱特定服務供應項目的文件。
{: tip}

1. 建立服務的實例。
    1. 按一下**型錄**。
    2. 從型錄按一下服務磚以選取您想要的服務。
    3. 依序選取位置，以及組織和空間或資源群組，然後按一下**建立**。
2. 從服務詳細資料頁面，選取**服務認證**以使用 JSON 格式檢視或新增認證。
    * 若要建立新認證，請選取**新建認證**，並選擇性地手動新增配置參數或匯入 JSON 格式的檔案，然後按一下**新增**。選取**檢視認證**，以儲存用來連接至外部應用程式的認證。
    * 選取一組認證，然後按一下「動作」直欄中的**檢視認證**（如果這些認證已存在的話）。
3. 使用顯示為認證的 API 金鑰來連接至服務實例。

在 {{site.data.keyword.Bluemix_notm}} 之外執行的應用程式，現在可以存取 {{site.data.keyword.Bluemix_notm}} 服務。

如果您要刪除服務實例或檢查計費資訊，則必須回到使用者介面中的「資源」清單，才能管理服務實例。
{: tip}

## 具有服務金鑰的服務
{: #service_keys}

下列服務提供您可在外部使用的服務金鑰：

* {{site.data.keyword.alertnotificationshort}} <!--Alert Notification-->
* {{site.data.keyword.sparks}} <!--Analytics for Apache Spark-->
* {{site.data.keyword.blockchain}} <!--Blockchain-->
* {{site.data.keyword.cloudant}} <!--Cloudant&reg; NoSQL DB-->
* {{site.data.keyword.conversationshort}} <!--Conversation-->
* {{site.data.keyword.discoveryshort}} <!--Discovery-->
* {{site.data.keyword.geospatialshort_Geospatial}} <!--Geospatial Analytics-->
* {{site.data.keyword.GlobalizationPipeline_short}} <!--Globalization Pipeline-->
* {{site.data.keyword.appconserviceshort}} <!--IBM&reg; App Connect-->
* {{site.data.keyword.languagetranslatorshort}} <!--Language Translator-->
* {{site.data.keyword.dwl_short}} <!--Lift-->
* {{site.data.keyword.messagehub}} <!--Message Hub-->
* {{site.data.keyword.nlclassifiershort}} <!--Natural Language Classifier-->
* {{site.data.keyword.objectstorageshort}} <!--Object Storage-->
* {{site.data.keyword.personalityinsightsshort}} <!--Personality Insights-->
* {{site.data.keyword.mobilepush}} <!--Push-->
* {{site.data.keyword.speechtotextshort}} <!-- Speech to Text-->
* {{site.data.keyword.streaminganalyticsshort}} <!--Streaming Analytics-->
* {{site.data.keyword.texttospeechshort}} <!--Text to Speech-->
* {{site.data.keyword.toneanalyzershort}} <!--Tone Analyzer-->
* {{site.data.keyword.weather_short}} <!--Weather Company Data-->
* {{site.data.keyword.workloadscheduler}} <!--Workload Scheduler-->
