---
layout: page
permalink: /search/
title: Blog Search
---

<!-- Search input field -->
  <div class="main-search form-group mb-0 border-bottom">
  <div class="input-group">
    <input id="search" name="main_input" class="form-control border-0" placeholder="press / to search" type="text">
    <div class="input-group-append">
      <span class="input-group-text border-0"><i class="fa fa-search" aria-hidden="true"></i></span>
    </div>
  </div>
</div>

<!-- Search result container -->
<div class="search-results position-absolute">
      <ul id="results" class="search-results-ul card shadow border border-top-0">
      </ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="/path/to/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json'
})
</script>
