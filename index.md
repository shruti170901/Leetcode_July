---
layout: default
---


{% include 01-name.md %}

<br>

{% include 03-links.md %}

<br>

{% include 04-lists.md %}

<br>

{% include 05-emphasis.md %}


<form method="get" action="http://www.google.com/search" target="_blank">
<input type="hidden" name="sitesearch" value="shruti170901.github.io/Leetcode_July/" />
<input type="text" name="q" maxlength="255" placeholder="Search with Google" />
</form>




<script src="https://raw.githubusercontent.com/DataMcFly/jquery.camelhunter/master/jquery.camelhunter.min.js"></script>
<script type="text/javascript">
	$("#search-field").camelHunter({
		onKeyUp 			: true,
		rss: "/search.xml",
		results   : "#results"
	});
</script>
