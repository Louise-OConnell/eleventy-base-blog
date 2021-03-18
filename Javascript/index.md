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

var total = Number;

var tipPercent = 15;

var tip = (Number / 100) * 15;

var totalWithTip = total + tip;

//document.write('Your total bill before tips is £', + total + '.');

//document.write('You have paid a 15% tip, thank you!');
document.getElementById("bill").innerHTML = totalWithTip

document.write('Your new bill total with a tip is £' + totalWithTip + '.');

document.write('Thank you for your tip of £' + tip + '.');

</script>
<h1>Tip Calculator</h1>
<h2>What is my total bill?</h2>
<p>Total with 15% tip</p>
<input type="text" id="Number" placeholder="enter a number" oninput="Number(this.value)">
<p id="bill"></p>

<script> 
function putOnCoat(temperature){
    let sentence = '';
    if (temperature < 50) {
        sentence += 'Put on a coat '
    } else {
        'Pants and vest are fine'
    }
    if (temperature < 30) {
        sentence += 'and a hat'
    }
    if (temperature < 0) {
        sentence = 'Stay inside'
    }
    if (sentence == '') {
        sentence = 'Pants and vest are fine'
    }
  document.getElementById("demo").innerHTML = sentence
}
</script>
<h1>Javascript Exercises</h1>
<h2>Shall I put on a coat?</h2>
<p>What is the temperature?</p>
<input type="text" id="temperature" placeholder="enter a temperature" oninput="putOnCoat(this.value)">
<p id="demo"></p>