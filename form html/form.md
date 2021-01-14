# HTML FORM

## An HTML form is used to collect user data/information

    it is vitally important on every website as
    it creates some form of interaction between the user and the web,
    get consumer needs, online surveys, and helps create a great user experience.

### The HTML `form` element defines a form that is used to collect data.

The `input` and `label` element are vitally important in the `form` element
The input attribute includes an input type( includes radio button, checkboxes, submit button,text inputs,numbers, date, time, URL, e-mail etc), value, id, name and placeholder(optional)
The `label` element says what should be filled and usually the on-screen element, also include a `for` attribute with the corresponding value of the input `id` for web accessibility.

### Examples:

```
<form>
 <label for="example">E-mail</label>
 <input type="email" value="email" name="email" id="example">

 <label for="example">
 <input type="email" value="email" id="example" placeholder="E-mail" name="email">
 </label>
</form>
```

## Please Note: Input elements are self-closing element(do not have a closing tag)

### Input Types

- Radio-buttons:
  these are types of input that are usually used when an item needs to be selected among a list of items, and only one button could be selected as all the buttons share only one value.

- Checkboxes: Unlike radio-buttons, multiple boxes can be checked at a time, and also share different values. this input type is usually used when there is more than one selection among various items

### Radio buttons or checkboxes will include a `value` element

### Example:

`<input type="radio button" id="loving" name="personality" value="loving">`

- text: this input type is used when the data is in form of text such as name, username.

- URL: this is used when the input is a website URL or link.

- email: as the input type implies, it is used when the required data is an e-mail

* submit: this input type is usually used when a form is to be submitted
  The submit button defines a button for submitting the form data
  The submit button usually include a value element and it is usually after the labels
  For example

`<input type="submit" value="submit">`

### Other types includes `date`, `phone-no`, `number`,`password` etc.

- select elements:

The select elements are also used as a choice percentage between 2 options with an attribute of range and a “minimum and maximum” set to a value with the step also set to a value

- Text-area input: These are optional and used when there is an extra suggestion. these box placed at the end of a form.

## Form Validation:

These are forms you want to specify some important and instructions to and you want the user to strictly adhere to it using a short message or alert as a clue to what input data is required of the user;

### The required options:

If a particular place in a form is important and needs to be filled you can add required to the input opening tag and it makes that input necessary to fill.
Examples:

`<input type="username" id="username" value="username" required>`

### HTML5 type options:

As said earlier, input types like email, URL, password, number, etc have some slight validation when used. A user can input anything other than an email address in an input type=email box, same goes for URL, number, etc

### Javascript form validation:

this is a type of form validation where inputs are selected using the DOM and a JS line of code is written for validation. These usually come with a prompt or alert as to the basic data input requirement
