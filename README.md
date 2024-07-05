# HTML-Placeholder-and-Required

There's quite a neat new attribute you can add to your text boxes called PLACEHOLDER. This is default text that disappears when you click inside a text box. Try the following:

<FORM>

<INPUT TYPE="Text" PLACEHOLDER="Enter your first name">

<P>
<INPUT TYPE="Submit" VALUE="Contact Us">

</FORM>

The word PLACEHOLDER does not have to be in capitals, as like just about every HTML element it is not case sensitive. After an equal sign, you type the text you want to appear in your text box, surrounded by quotation marks.

The REQUIRED attribute
If you want a text box to be filled in, you can use the REQUIRED attribute:

<FORM>

<INPUT TYPE="Text" PLACEHOLDER="Enter your first name" REQUIRED>

<P>
<INPUT TYPE="Submit" VALUE="Contact Us">

</FORM>

You just type the word REQUIRED, with no equal sign or text after it.So the browser has not submitted the form, but displayed a popup box asking the user to fill out the text box. Opera, Internet Explorer and Safari don't recognize the REQUIRED attribute, however, and just submit the form. So you shouldn't rely on it. Internet Explorer versions 9 and lower don't even recognise the PLACEHOLDER attribute, the only one of the big five browsers not to do so!

In the next lesson, you'll learn about Email, URL and Search boxes.
