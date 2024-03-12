The vh unit stands for viewport height, and is equal to 1% of the height of the viewport. This makes it relative to the viewport height.

You can get rid of the horizontal scroll-bar, by setting the body default margin added by some browsers to 0

The method attribute specifies how to send form-data to the URL specified in the action attribute. The form-data can be sent via a GET request as URL parameters (with method="get") or via a POST request as data in the request body (with method="post").

The rem unit stands for root em, and is relative to the font size of the html element.
As label elements are inline by default, they are all displayed side by side on the same line, making their text hard to read. To make them appear on separate lines, add display: block to the label element, and add a margin of 0.5rem 0, to separate them from each other.

Accessiblity best practices
Following accessibility best practices, link the input elements and the label elements together using the for attribute. The for attributes will link to the respective id attributes.

Specifying the type attribute of a form element is important for the browser to know what kind of data it should expect. If the type is not specified, the browser will default to text.

The email type only allows emails with a @ and a . in the domain. The password type obscures the input, and warns if the site does not use HTTPS.

The first input element with a type of submit is automatically set to submit its nearest parent form element.

To handle the form submission, after the last fieldset element add an input element with the type attribute set to submit and the value attribute set to Submit.

Certain type attribute values come with built-in form validation. For example, type="email" requires that the value be a valid email address.


Passwords: 
With type="password" you can use the pattern attribute to define a regular expression that the password must match to be considered valid.

A[a-z0-5]{8,}

The above is a regular expression which matches eight or more lowercase letters or the digits 0 to 5.

You only want one radio input to be selectable at a time. To do this the form must know the radio buttons are related. This can be accomplished by giving them the same name attribute. 

Follow accessibility best practices by linking the input elements and the label elements