---
layout: default
permalink: /week42
---
<div class="hero-week42">
</div>
<section class="section section--description">
    <div class="inner description">
        <h2 class="description_headline">Northern Devs Week</h2>
        <p class="description_text">I en vecka får du som utvecklare chansen att vässa kunskaperna inom en rad olika områden - med frukost, lunch och After Work-föreläsningar på IT-bolag i Östersund och Åre.
Veckan är ett arrangemang av IT-bolagen i regionen för utvecklare och kommer beröra många olika ämnen som Kubernetes, Microservices, UX och&nbsp;mycket&nbsp;mer.</p>
        <p class="description_text">Du kan anmäla dig till ett eller flera event - alla föreläsningar är kostnadsfria. Om du är student - håll utkik efter vilka föreläsningar som är öppna för dig! Anmälan sker här på siten, du kan läsa mer om eventen nedan och på <a class="link" href="https://www.facebook.com/events/2378004445813028">facebook</a>. Ta chansen att hänga med andra&nbsp;kodapor!</p>
    </div>
</section>
<section class="section section--registration">
  <iframe class="registration_iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSdds0R7AGLt_7-EYXRkD2Eyxj9o4d0s09GgU_nXus9MIcMLAQ/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0">Läser in …</iframe>
</section>
<section class="section section--schedule">
    <div class="events">
      <ul class="events_list">
        {% for event in site.events %}
          <li class="event_item">
            <div class="event_metadata">
              <span class="event_date">{{ event.date }}</span>
              <span class="event_time">{{ event.time }}</span>
            </div>
            <div class="event_content">
              <h3 class="event_name">{{ event.name }}</h3>
              <span class="event_description">{{ event.description }}</span>
            </div>
          </li>
        {% endfor %}
      </ul>
      <p class="events_footer">Du hittar <a class="link" href="https://www.facebook.com/events/2378004445813028">alla events</a> och kan läsa mer om <a class="link" href="https://www.facebook.com/northerndevsweek/">Northern Devs Week</a> på facebook</p>
    </div>
</section>
