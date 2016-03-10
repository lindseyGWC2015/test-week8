# test-week8

What do jQuery selectors start with?

similar to CSS selectors, except wrapped in  $(‘ ’);

What's the problem with this code
in your html:
<div class="my-element">Hide me</div>
in your javascript:
$(".another-element").hide();

another-element and my-element need to be the same name.

What's wrong with this code:
in your html:
<div class="my-element">Hide me</div>
in your javascript:
$("#hideMe").hide();

hideMe should be my-element.

If you have a FOLDER named lib and a FILE named app.js, why won't this link to your javascript work?
<script src="app.js"></script>

It also needs to link to the folder "app.js" is in.

What can you tell me about this: <input type="text"/> what is it? what will we be using them for?

It allows the user to type their name and be counted in the counter. It is what is plugged in to the variable.
