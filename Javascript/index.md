---
layout: layouts/post.njk
title: Javascript
templateClass: row
eleventyNavigation:
  key: Javascript
  order: 6
---
<script type='text/javascript'>

// JavaScript Tip Calculator

var total = 40;

var tipPercent = 15;

var tip = (total / 100) * tipPercent;

document.write('Your total bill before tips is £', ${total} + '.');

break;

document.write('You have paid a 15% tip, thank you!');

break;

document.write('Your new bill total is' + ${total} + ${tip} + '.');

break;

document.write('Thank you for your tip of £' + ${tip} + '.');

</script>