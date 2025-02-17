<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'es'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dba0000014cKf',
				'MiAW_OmniFlowDeployment',
				'https://telefonica-d--devmiaw.sandbox.my.site.com/ESWMiAWOmniFlowDeploymen1739522579948',
				{
					scrt2URL: 'https://telefonica-d--devmiaw.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://telefonica-d--devmiaw.sandbox.my.site.com/ESWMiAWOmniFlowDeploymen1739522579948/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>

