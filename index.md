<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DUC000003jYGj',
				'MIAW_K_Living',
				'https://kaplaninternational--livechat.sandbox.my.site.com/ESWMIAWKLiving1752562057162',
				{
					scrt2URL: 'https://kaplaninternational--livechat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://kaplaninternational--livechat.sandbox.my.site.com/ESWMIAWKLiving1752562057162/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


  
</body>
  
</html>
