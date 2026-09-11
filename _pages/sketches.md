---
layout: archive
title: "Sketches"
permalink: /sketches/
author_profile: true
---

Some drawings I've made when I should have been writing.
<div class="sketch-grid" style="display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px;align-items:start;">
<figure style="margin:0;">
<img src="/images/palace_fine_arts.jpg" alt="Palace of Fine Arts, San Francisco" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Palace of Fine Arts, San Francisco</figcaption>
</figure>
  
<figure style="margin:0;">
<img src="/images/sarlat.jpg" alt="Sarlat-la-Caneda, France" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Sarlat-la-Caneda, France</figcaption>
</figure>
  
<figure style="margin:0;">
<img src="/images/flr_gas_station.jpg" alt="Frank Lloyd Wright Gas Station, Cloquet, MN" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Frank Lloyd Wright Gas Station, Cloquet, MN</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/ascoli.jpg" alt="Ascoli Piceno" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Ascoli Piceno, Itlay</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/bauhaus.jpg" alt="Frank Lloyd Wright Gas Station, Cloquet, MN" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Bauhaus Building</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/town_topic.jpg" alt="Frank Lloyd Wright Gas Station, Cloquet, MN" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Town Topic Hamburgers, Kansas City, MO</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/courthouse.jpg" alt="Santa Barbara Courthouse" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Santa Barbara Courthouse</figcaption>
</figure>


<figure style="margin:0;">
<img src="/images/ascoli2.jpg" alt="Ascoli Piceno town square" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Ascoli Piceno, Italy</figcaption>
</figure>


<figure style="margin:0;">
<img src="/images/duluth.jpg" alt="Duluth, MN" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Lift Bridge, Duluth, MN</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/ferry.jpg" alt="Ferry Building" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">San Francisco Ferry Building</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/harkness.jpg" alt="Harkness" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">Harkness Tower, Yale</figcaption>
</figure>

<figure style="margin:0;">
<img src="/images/ghriba.jpg" alt="Duluth, MN" style="width:100%;height:200px;object-fit:cover;">
<figcaption style="font-size:0.85em;color:#666;margin-top:4px;">El Ghriba Synagogue</figcaption>
</figure>
</div>

<div id="lb" onclick="this.style.display='none'" style="display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.85);z-index:9999;cursor:zoom-out;align-items:center;justify-content:center;">
<img id="lb-img" alt="" style="max-width:90%;max-height:90%;">
</div>

<script>
document.querySelectorAll('.sketch-grid img').forEach(function(img){
  img.style.cursor = 'zoom-in';
  img.addEventListener('click', function(){
    document.getElementById('lb-img').src = this.src;
    document.getElementById('lb-img').alt = this.alt;
    document.getElementById('lb').style.display = 'flex';
  });
});
document.addEventListener('keydown', function(e){
  if (e.key === 'Escape') document.getElementById('lb').style.display = 'none';
});
</script>
