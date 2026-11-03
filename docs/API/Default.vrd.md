<?xml version="1.0" encoding="UTF-8"?>
<point xmlns="http://v8.1c.ru/8.2/virtual-resource-system"
		xmlns:xs="http://www.w3.org/2001/XMLSchema"
		xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
		base="/Test_Market"
		ib="Srvr=&quot;localhost:1541&quot;;Ref=&quot;Test_Market&quot;;Usr=&quot;api_client&quot;;Pwd=&quot;LhbJnw8m26Ybqh8&quot;;">
	<debug enable="true"
			protocol="tcp"
			url="tcp://localhost"/>
	<ws enable="false"
			pointEnableCommon="true"/>
	<standardOdata enable="false"
			reuseSessions="autouse"
			sessionMaxAge="20"
			poolSize="10"
			poolTimeout="5"/>
	<analytics enable="false"/>
	<httpServices>
	    <service name="StockAPI"
                rootUrl="stock"
                enable="true"
                reuseSessions="autouse"
                sessionMaxAge="20"
                poolSize="10"
                poolTimeout="5">
        </service>
	</httpServices>
</point>