---
layout: default
title: Bovaer® Producer Database
description: A database of Australian beef and dairy producers using and not using Bovaer®
---

[← Back to home](https://lachlanwintourzg.github.io/bovaer-producer-database/)

# Database Home

## Search the Database

<form action="{{ page.url | relative_url }}">
  <div class="tipue_search_left"><img src="{{ "/assets/tipuesearch/search.png" | relative_url }}" class="tipue_search_icon"></div>
  <div class="tipue_search_right"><input type="text" name="q" id="tipue_search_input" pattern=".{3,}" title="At least 3 characters" required></div>
  <div style="clear: both;"></div>
</form>d

<div id="tipue_search_content"></div>

<script>
$(document).ready(function() {
  $('#tipue_search_input').tipuesearch();
});
</script>