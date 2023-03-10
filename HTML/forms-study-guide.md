To create an HTML file, what file extension should you use? Create one now.

- .html

What element allows you to create a new form?

- <form></form>

How can you write a text input where a user can write their name?

- <input type="text" />

Do so on your page now.

The input element should include a type attribute. What are some options for this attribute's value?

- text, email, radio, checkbox

What is the effect of changing the input's type attribute?

- the ability to type something or choose between options

The input element should also include both an id and a name attribute. What is the purpose of each of these attributes?

- id is unique to the input its being used for and name describes the value

Take a look at the following HTML. Do you see any issue with how the label elements are connected to the form fields?

- the input should be nested in the label element.
  <form>
    <label for="first">Preferred Name</label>
    <input id="preferred" name="first" type="text" />

  <label for="last">Surname</label>
  <input id="surname" name="last" type="text" />
  </form>

Is the following valid HTML?

- it would work but the label name is after the input box which doesnt look right.

<form>
  <label>
    <input id="preferred" name="first" type="text" />
    Preferred Name
  </label>

  <label>
    <input id="surname" name="last" type="text" />
    Surname
  </label>
</form>

Dropdowns require two elements: the select element and the option element.

<form>
  <select>
    <option>-- Choose an Honorific --</option>
    <option value="mr">Mr.</option>
    <option value="mrs">Mrs.</option>
    <option value="ms">Ms.</option>
    <option value="mx">Mx.</option>
    <option value="none">None</option>
  </select>
</form>

Which of the above options will be displayed on the page when it loads, by default?

- the first option (choose ...)

Radio buttons can be created with an input element. In the code below, there are three different radio buttons. However, it is possible to click on all three radio buttons when you should only be able to click on one.

How can you group together radio buttons so that only one option can be selected?

- give each the same value for the name attribute.

<form>
  <label>
    <input type="radio" name="title" />
    Mr.
  </label>
  <label>
    <input type="radio" name="title" />
    Mrs.
  </label>
  <label>
    <input type="radio" name="title" />
    Mx.
  </label>
</form>

How can you create a checkbox in a form?

- <input type="checkbox"/>

How can you create a checkbox that is, by default, checked?

- <input type="checkbox" checked />

What happens when you hit the submit button on a form?

- triggers an action with the data entered

How can you make an input field required?

- <input type="text" id="first-name" name="first-name" required />

How does adding specific requirements to input fields affect the submit functionality?

- when click submit and something is wrong error message will show instead of submitting if correct.
