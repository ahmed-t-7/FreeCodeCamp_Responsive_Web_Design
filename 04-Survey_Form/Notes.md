-> At lesson 21
---->   

Certain type attribute values come with built-in form validation. For example, type="email" requires that the value be a valid email address.

Add custom validation to the password input element, by adding a minlength attribute with a value of 8. Doing so prevents inputs of less than 8 characters being submitted.

-> At lesosn 27
---->   

You only want one radio input to be selectable at a time. However, the form does not know the radio inputs are related.

To relate the radio inputs, give them the same name attribute with a value of account-type. Now, it is not possible to select both radio inputs at the same time.

-> At lesson 32
---->   Adding a dropdown to the form is easy with the select element. The select element is a container for a group of option elements, and the option element acts as a label for each dropdown option. Both elements require closing tags.

-> At lesson 35
---->   Submitting the form with an option selected would not send a useful value to the server. As such, each option needs to be given a value attribute. Without which, the text content of the option will be submitted to the server.

-> At lesson 43
---> min-width Property sets the minumun value of an element. It pervents the used value of the width property from becoming smaller than the value specified for min-width

max-width Property sets the maximum value of an element. It prevents the used value of the width property from becoming larger than the value specifeid by max-width

Some Units in css 
    vw (view width) --> 1% of the viewport width.
    vh (view height) --> 1% of the viewport heiht.
    em --> Font size of the parent, in the case of typographical properties like font-size, and font size itself, in the case of other properties like width.
    rem --> font size of the root element;

-> at lesson 46
---->   The border of the last fieldset element looks a little out of place. You can select the last element of a specific type using the last-of-type CSS pseudo-class, like this:

p:last-of-type { }

-> At lesson 49
----> Select only the .inline elements, and give them width of unset. This will remove the earlier rule which set all the input elements to width: 100%.

-> At lesson 51
---->   The vertical-align CSS Property sets vertical alignment of an inline, inline-block or table-cell box

   If you look close enough, you will notice the .inline elements are too high on the line.
   To combat this, set the vertical-align property to middle.

-> At lesson 55
---->   attribut selector, which selects na element based on the given attribute value Here is an example:
input[name="password"]


