---
layout: page
title: Research Activities
css: "/assets/css/index.css"
---

<!-- <div class="list-filters">
  <a href="/" class="list-filter ">Home</a>
  <a href="/publications" class="list-filter filter-selected">Publications</a>
  <a href="/contact" class="list-filter">Contact</a>
  <a href="/about" class="list-filter">About</a>
</div> -->


<div class="tab-wrapper">
	<div class="tab">
	<button class="tablinks" onclick="openSection(event, 'Rsearch Projects')"id="defaultOpen"><strong>Research Projects</strong></button>
	<button class="tablinks" onclick="openSection(event, 'Scientific Activities')"><strong>Scientific Activities</strong></button>
	</div>
</div>



<script>
// JavaScript for Tabs
function openSection(evt, sectionName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(sectionName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Open the first tab by default
document.addEventListener("DOMContentLoaded", function() {
  document.getElementById("defaultOpen").click();
});
</script>