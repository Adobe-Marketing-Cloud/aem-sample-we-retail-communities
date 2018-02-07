# aem-sample-we-retail-communities

These files are used to generate the We.Retail Communities demonstration site for *AEM 6.4*.

### For generating We.Retail Communities demonstration site for AEM 6.3, please checkout 6.3 branch 

Once the package is imported, the following CURL command can be used to generate the site:

	curl -u admin:{yourpassword} http://${yourserver}:${yourauthorport}/bin/CreateCommunities?password=${yourpassword}&port=${yourpublishport}&hostname=${yourpublishhost}&port_author=${yourauthorport}&hostname_author=${yourauthorhost}&contentPath=/etc/community/we-retail&setup-1=on&setup-2=on&setup-3=on&setup-4=on&setup-5=on&setup-6=on&setup-7=on&setup-8=on

