<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DDw000005Xcu4',
				'ARLY_Customer_Support_UAT',
				'https://arly--uat.sandbox.my.site.com/ESWARLYCustomerSupport1712617937563',
				{
					scrt2URL: 'https://arly--uat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://arly--uat.sandbox.my.site.com/ESWARLYCustomerSupport1712617937563/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
