---
layout: page
title:  "Register for an API Key"
permalink: /api-keys/
---


{% raw %}
<div id="apidatagov_signup">Loading signup form...</div>
<script type="text/javascript">
  /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
  var apiUmbrellaSignupOptions = {
    registrationSource: 'ed-developer-hub',
    apiKey: '8zAyBbZEQ9oV9TW5PI7d6Tt17z6aVnUKxwrMG8hN',
   exampleApiUrl: 'https://api.ed.gov/data/less-than-highschool_2015?api_key={{api_key}}',
  contactUrl: 'https://pages.18f.gov/ED-Developer-Hub/contact/', 
  siteName: 'Department of Education - Developers',
  emailFromName: 'Department of Education - Developers'
  };

  /* * * DON'T EDIT BELOW THIS LINE * * */
  (function() {
    var apiUmbrella = document.createElement('script'); apiUmbrella.type = 'text/javascript'; apiUmbrella.async = true;
    apiUmbrella.src = 'https://api.data.gov/static/javascripts/signup_embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(apiUmbrella);
  })();
</script>
<noscript>Please enable JavaScript to signup for an <a href="http://api.data.gov/">api.data.gov</a> API key.</noscript>
{% endraw %}
