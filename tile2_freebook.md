---
layout: page
title: Book Free Half-Hour Consultation
# description: Book half-hour free consultation.
permalink: booking
image: assets/images/consult.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>{{page.title}}</h1>
		</header>

    <form action="https://formspree.io/f/mqaebpog" method="POST">
      <div class="field half first">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" />
      </div>
      <div class="field half">
        <label for="email">Email</label>
        <input type="text" name="_replyto" id="email" />
      </div>
      <div class="field half first">
        <label for="prefday">Preferred Day(s)</label>
        <input type="text" name="prefday" id="prefday" />
      </div>
      <div class="field half">
        <label for="preftime">Preferred Time(s) (EST)</label>
        <input type="text" name="preftime" id="preftime" />
      </div>
      <div class="field">
        <label for="message">Project/Topic</label>
        <textarea name="message" id="message" rows="6"></textarea>
      </div>
      <ul class="actions">
        <li><input type="submit" value="Request Booking" class="special" /></li>
        <li><input type="reset" value="Clear" /></li>
      </ul>
    </form>

  </div>
</section>
</div>