# Technical skills test

This front end development test is intended to cover a broad range of skills required to deliver high quality government digital services. This includes:

* Accessibility
* HTML
* CSS
* jQuery and JavaScript
* Other best practices

Candidates are asked to perform this test remotely and submit their responses to the sender. 

## Accessibility

1. Describe how you would implement the ***'I am looking for...'*** tab panel that appears on [justice.gov.uk](https://www.justice.gov.uk).

  Focus specifically on not disadvantaging users of:

  * Assistive technology
  * Older/less featured browsers

  Your answer should describe both ***how*** you would do this and describe ***what*** specific features of HTML, ARIA, CSS and JavaScript you would use to achieve this.

2. How would you implement a version of [GOV.UK browse](https://www.gov.uk/browse/) for a new digital service.

  Your answer should:

  * identify, so far as possible, what GOV.UK have done to ensure accessibility and progressive enhancement
  * assume you're approaching this from scratch

## JavaScript and jQuery

1. An exercise using jQuery is provided in test-jquery.html.

2. If you saw this in a Pull Request, what would your advice be:

  ```javascript
  Array.prototype.split = function(i) { // Adds split to all arrays
      return [this.slice(0, i), this.slice(i)];
  };
  ```

## CSS

1. What colour would each of the following elements be (Assume each pair of rules are targeting the same element)
  ```css
  h1 {color: red;}
  body h1 {color: green;}

  h2.grape {color: purple;}
  h2 {color: silver;}

  html > body table tr[id="totals"] td ul > li {color: maroon;} // li has an id of answer
  li#answer {color: navy;}
  ```

2. Given the HTML below, write a CSS3 rule that will give prepend the text ‘Tel:’ to the third list item. You are not able to amend the HTML to achieve this.
  ```html
  <body>
    <ul>
      <li>JavaScript</li>
      <li>HTML</li>
      <li>Ruby</li>
      <li>Python</li>
    </ul>
  </body>
  ```

3. What changes would you suggest to make these CSS rules ready for a production environment?
  ```html
  <!DOCTYPE html>
  <html>
      <head>
      <meta charset=utf‐8 />
      <title>Test</title>
        <style type="text/css">
          #one { background‐color: #000; }
          .three { color: rgba(255,255,255,1); }
          div > span { border: 3px solid green; }
        </style>
      </head>
      <body>
        <div id="one">
          <div class="three">
            Hello <span>World!</span>
          </div>
        </div>
      </body>
  </html>
  ```

4. How would you style all links to 'gov.uk' domains differently to other links in an application?

## HTML

1. A test using HTML5 is provided in test-html.html within this repository.
Please amend the code and submit your changes as a pull request.

## Testing

1. What are **the key things you need to test for** on the front-end of digital services?

2. How do you ***how*** approach testing the front end of applications?

## Best practices

1. Is this good quality code? Provide a brief justification of your answer.

  ```css
    <button
      type="button"
      onclick="document.getElementById('xyz').style.color='red';">
        Click Me
    </button>
  ```

2. Describe three ways to decrease page load time (answers may include perceived or actual load times)

3. Why is it generally a good idea to position CSS ```<link>```s between ```<head></head>``` and JS ```<script>```s just before ```</body>```? Do you know any exceptions?
