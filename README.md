---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Monitor
  platforms: java
---

# Getting Started with Monitor - Query Metrics And Activity Logs - in Java #


  This sample shows examples of retrieving metrics and activity logs for Storage Account.
   - List all metric definitions available for a storage account
   - Retrieve and show metrics for the past 7 days for Transactions where
     - Api name was 'PutBlob' and
     - response type was 'Success' and
     - Geo type was 'Primary'
   -  Retrieve and show all activity logs for the past 7 days for the same Storage account.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/monitor-java-query-metrics-activitylogs.git

    cd monitor-java-query-metrics-activitylogs

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.