---
layout: layouts/post.njk
title: Javascript
templateClass: row
eleventyNavigation:
  key: Javascript
  order: 6
---
<script>

// JavaScript Tip Calculator
function bill(whatIsMyBill) {
    let totalBill = 50;
    let tipPercent = 15;
    let tip = (totalBill / 100) * tipPercent;
    let totalBillWithTip = totalBill + tip; 
 document.getElementById("myBill").innerHTML = totalBillWithTip;
}
document.write(totalBillWithTip);

</script>
<h2>Tip Calculator</h2>
<h4>Your bill is £50</h4>
<p>Your bill total with 15% tip is?</p>
<input type="text" id="Number" placeholder="enter your bill" oninput="bill(this.value)">
<p id="myBill"></p>

<script> 