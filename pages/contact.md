---
layout: default
title: Contact
---
<form name="contact" method="POST" data-netflify="true">
    <p>
        <label> Your Name: <input type="text" name="name"/> </label>
    </p>
    <p>
        <label> Your Email: <input type="email" name="email"/> </label>
    </p>
        Message: <br>
   <input type="text" class="scrollabletextbox" name="note" value="<?php echo $note; ?>">
        <button type="submit"> Send</button>
        <button type="reset"> Reset</button>
</form>
