---
title: Contact Us
layout: layouts/base.njk
subtitle: Give us feedback and / or validate us.
---

<form name="contact" method="POST" data-netlify="true">
<ul class="form-style-1">
    <li><label>Full Name <span class="required">*</span></label><input type="text" name="first-name" class="field-divided" placeholder="First" /> <input type="text" name="last-name" class="field-divided" placeholder="Last" /></li>
    <li>
        <label>Email <span class="required">*</span></label>
        <input type="email" name="email" class="field-long" />
    </li>
	<li>
        <label>Your Message <span class="required">*</span></label>
        <textarea name="message" class="field-long field-textarea"></textarea>
    </li>
	<button type="submit">Send Message</button>
</ul>
</form>
