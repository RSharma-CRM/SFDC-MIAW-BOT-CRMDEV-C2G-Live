<html>
  <head>
    <title>
      MIAW Demo: CRMDEV (sandbox)
    </title>
    <style>
      h1{
        display: none;
      }
    </style>
  </head>
  <body>
    <h2> MIAW Demo: CRMDEV-C2G_Live_Chat (sandbox)</h2>
    
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DOz000004sefh',
				'C2G_Live_Chat_Messaging_Channel_Github',
				'https://legrandav--crmdev.sandbox.my.site.com/ESWC2GLiveChatMessagin1731914654902',
				{
					scrt2URL: 'https://legrandav--crmdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://legrandav--crmdev.sandbox.my.site.com/ESWC2GLiveChatMessagin1731914654902/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
