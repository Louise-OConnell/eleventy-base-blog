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
function totalWithTip(Number){
let total = Number;
let tipPercent = 15;
let tip = (Number / 100) * 15;
let totalWithTip = total + tip;
}

//document.write('Your total bill before tips is £', + total + '.');

//document.write('You have paid a 15% tip, thank you!');
//document.getElementById("bill").innerHTML = totalWithTip

//document.write('Your new bill total with a tip is £' + totalWithTip + '.');

//document.write('Thank you for your tip of £' + tip + '.');

</script>
<h2>Tip Calculator</h2>
<h4>What is my total bill?</h4>
<p>Here is your bill total with 15% tip</p>
<input type="text" id="Number" placeholder="enter a number" oninput="totalWithTip(this.value)">
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