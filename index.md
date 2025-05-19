<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DRR00000D8tgL',
				'Web_Messaging',
				'https://tti-fc--crederap2.sandbox.my.site.com/ESWVaxMIAWChat1740480596690',
				{
					scrt2URL: 'https://tti-fc--crederap2.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://tti-fc--crederap2.sandbox.my.site.com/ESWVaxMIAWChat1740480596690/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
