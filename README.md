# UI Basics - Exam 2

- Examine the `index.html` and `style.css` files and the images folder
- These files contain the foundations of a computer store landing page
- The task is to follow the instructions below to complete the landing page
- In the bottom of this README is an reference video showing the completed project
- You are allowed to research online, but write your own code - don't use AI
- You are not allowed to receive help from classmates or teachers to complete the tasks
- You are allowed to ask the teacher or assistant teacher to clarify a task (within reason)
- Good luck!

## Images

- Add the [hero.jpg](./images/hero.jpg) as a background image in the header of the page. The background image should cover the whole header, it should not repeat itself and the image should be at the center of the header.

## Positioning

- Change the position of the header to fixed. The header should be aligned at the top of the page and it should not cover any content of the website.

## Attributes

- Add a `fontawesome` icon to all of the links which contain the attribute `"target="_blank"`. You must select the elements by this attribute in css and add the icon directly in css. You should use the pseudo-element `::after` on the attribute selector, the font should be "FontAwesome" and the content should be `" \f35d"`.

## Responsive Design

- In the "Product Card" section, use flex to make the cards appear as a column for mobile and as a row for tablet/desktop (breakpoint: `768px`). The column and row should appear in the center of the page. The row should not appear on multiple lines.

* In the header section, give a padding of `7rem` on the right side of `h1` on screens larger than or equal to `768px`.

## Tables

- In the "Product Information" section, create a table with the structure below. The table should be placed beneath the  existing`h2` element.

- Add a grey solid border to the table, table header cells and table rows. Make sure all the borders collapse into one border. Every odd row should be white, every even row should be grey. The table should take up `100%` of the width.

### Table Data Structure

|           | Lenovo | Dell      | Macbook |
| --------- | ------ | --------- | ------- |
| **OS**    | Ubuntu | Microsoft | MacOS   |
| **Price** | $350   | $450      | $550    |
| **Color** | Black  | White     | Silver  |
| **RAM**   | 4GB    | 16GB      | 8GB     |

## Forms

In the "Contact Form" section, create a new form. The form should be placed beneath the existing `h2` element. Set the form to use the POST `method` for submitting. Feel free to add `div` elements for formatting, if you would like.

- Include the following:
    - first: a text input field for the user's name
    - second: an email input field for the user's email
    - third: a textarea for a message
    - fourth: a submit button with the class `submit-btn`

- Create `label` elements for the input field and the textarea with the following texts:
    - first: "Tell us who you are"
    - second: "Tell us how to contact you"
    - third: "How can we help you?"

- Add placeholder texts to the input fields and the textarea:
    - first: "Please fill in your full name"
    - second: "Please enter your email"
    - third: "Send us a message!"

- Add client-side HTML validation to the inputs
    - first: a `minimum length` of 1, required
    - second: a `minimum length` of 5
    - third: a `minimum length` of 1, required

On focus, change the outline color of the input fields and textarea to blue.

## Footer Links

- In the "Footer Links" section, add an unordered list beneath the `h3` element. The unordered list should have a class of `icon-list`. Inside the unordered list, add three list items. Each list item should have a class of `icon`. Every list item should have an anchor link nested inside. Only add an "#" symbol to the `href`. Find three social media icons to place inside the anchor links, e.g. instagram, linkedin, twitter.

## Reference video

[Watch Reference Video](simplescreenrecorder-2022-10-21_14.38.54.mp4)
