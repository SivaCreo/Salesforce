<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHp000003WErm',
				'ARLY_Customer_Support',
				'https://arly.my.site.com/ESWARLYCustomerSupport1709967206643',
				{
					scrt2URL: 'https://arly.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://arly.my.site.com/ESWARLYCustomerSupport1709967206643/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
  </html>
