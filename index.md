
<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DE1000001p6MG',
				'Web_Chat_POC',
				'https://geisingerhealthsys--hcrmdev.sandbox.my.site.com/ESWWebChatPOC1715676706316',
				{
					scrt2URL: 'https://geisingerhealthsys--hcrmdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://geisingerhealthsys--hcrmdev.sandbox.my.site.com/ESWWebChatPOC1715676706316/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
