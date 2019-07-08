## Phishing Site Detection

In the Pre processing of the Data the attributes are coded into following format for application of KNN Classifier 

 	SFH's type is nominal, range is ('1', '-1', '0')
 	popUpWidnow's type is nominal, range is ('-1', '0', '1')
 	SSLfinal_State's type is nominal, range is ('1', '-1', '0')
 	Request_URL's type is nominal, range is ('-1', '0', '1')
 	URL_of_Anchor's type is nominal, range is ('-1', '0', '1')
 	web_traffic's type is nominal, range is ('1', '0', '-1')
 	URL_Length's type is nominal, range is ('1', '-1', '0')
 	age_of_domain's type is nominal, range is ('1', '-1')
 	having_IP_Address's type is nominal, range is ('0', '1')
 	Result's type is nominal, range is ('0', '1', '-1'))
    
    The  data coding is as follows:
    "1"  - Legitimate Website
    "0"  - Suspisious
    "-1" - Malicious Website
