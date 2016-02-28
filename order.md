---
layout: page
title: Order
permalink: /order/
---

<script>
function process()
{
var url="{{ site.baseurl }}/" + document.getElementById("roastID").value;
location.href=url;
return false;
}
</script>

<p class="roast-lookup">
<form action="{{ site.baseurl }}/" onSubmit="return process();">
  <span>Roast#</span>
  <input type="text" name="Roast #" id="roastID" placeholder="42" maxlength="2" size="4" />
  <input type="submit" value="Learn about roast" />
</form>
</p>

> All roast are numbered and have a dedicated page with details about the applied process and roast parameters. The idea is to empower you to learn more about your coffee and connect the dots between roast process yourself.

Limited sample batches are available from time to time.  

If you do your own home roasting, I would to love exchange samples and experiences with you.

I can't guarantee availability. But if you'd like to reserve a roast or do a sample exchange please get in touch via <a href="mailto:hello@plontsch.de">mail</a> or <a href="https://twitter.com/berndplontsch">twitter</a>.

Thank you.
