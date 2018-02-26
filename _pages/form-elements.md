---
ID: 42
post_title: Form Elements
author: ahadavand
post_excerpt: ""
layout: page
permalink: http://ahadavand.com/form-elements/
published: true
post_date: 2014-08-08 21:33:41
---
Here are all forms elements cross browser styled.

<form class="validate-form" action="#" method="post">
<label for="your-name">Your Name *</label><input id="your-name" class="required" name="your-name" type="text">

<label for="your-email">Your Email *</label><input id="your-email" class="required email" name="your-email" type="text">

<label for="subject">Subject</label><input id="subject" name="subject" type="text">

<label for="budget">Budget</label><select name="budget"><option value="1000$">1000$</option>
<option value="2000$">2000$</option>
<option value="3000$">3000$</option>
<option value="5000$+">5000$+</option></select>

<label for="attach-file">Attach a file</label><input id="attach-file" name="attach-file" type="file">

<label for="your-message">Your Message</label><textarea id="your-message" name="your-message"></textarea>

<label>Tech</label><label class="inline-label"><input name="gender[]" type="checkbox" value="male">HTML5</label><label class="inline-label"><input name="gender[]" type="checkbox" value="female">jQuery</label><label class="inline-label"><input name="gender[]" type="checkbox" value="female">Wordpress</label>

<label>Gender</label><label class="inline-label"><input class="required" name="radio" type="radio" value="radio-1">Male</label><label class="inline-label"><input class="required" name="radio" type="radio" value="radio-2">Female</label>

<input type="submit" value="Send it">
</form>