---
layout: page
permalink: /search/
title: Search
---

To search your blog, enter the search terms in the textbox below:
<!-- Html Elements for Search -->
<div id="search-container">
  <input type="text" id="search-input" placeholder="search...">
  <p>  
    Results:
    <ul id="results-container"></ul>
  </p>
</div>

<!-- Script pointing to search-script.js -->
<script src="\search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json'
})
</script>
