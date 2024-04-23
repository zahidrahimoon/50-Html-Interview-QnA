1. **What is HTML5?**
   - HTML5 is the latest version of the Hypertext Markup Language used for structuring and presenting content on the World Wide Web.

2. **What are the new features in HTML5 compared to HTML4?**
   - Some of the new features in HTML5 include new semantic elements, native support for video and audio, new form input types, local storage, canvas for drawing, and improved accessibility.

3. **What is the purpose of the `<!DOCTYPE html>` declaration in HTML5?**
   - It specifies to the web browser that the document is an HTML5 document, ensuring that the browser renders the document correctly.

4. **What are semantic elements in HTML5?**
   - Semantic elements are tags that provide meaning to the content they enclose, making it easier for search engines and developers to understand the structure of a web page.

5. **How do you create a hyperlink in HTML5?**
   - You can create a hyperlink using the `<a>` tag and specifying the URL in the `href` attribute. For example, `<a href="https://example.com">Visit Example</a>`.

6. **What is the `<canvas>` element in HTML5 used for?**
   - The `<canvas>` element is used for drawing graphics, animations, or other visual images on the fly using JavaScript.

7. **What is the difference between the `<canvas>` and `<svg>` elements in HTML5?**
   - `<canvas>` is used for drawing raster graphics using JavaScript, while `<svg>` is used for creating vector graphics that can be scaled without losing quality.

8. **How do you embed a video in HTML5?**
   - You can embed a video using the `<video>` element and specifying the video file URL in the `src` attribute. For example, `<video src="video.mp4" controls></video>`.

9. **What is the purpose of the `controls` attribute in the `<video>` element?**
   - The `controls` attribute adds playback controls (play, pause, volume, etc.) to the video player, allowing users to interact with the video.

10. **How do you create a form in HTML5?**
    - You can create a form using the `<form>` element and adding input fields, buttons, and other form elements inside the form tag.

11. **What are the new input types in HTML5?**
    - HTML5 introduced new input types such as `email`, `url`, `tel`, `date`, `time`, `number`, `color`, etc., which provide better user experience and validation.

12. **How do you create a placeholder text in an input field in HTML5?**
    - You can create a placeholder text using the `placeholder` attribute in an input field. For example, `<input type="text" placeholder="Enter your name">`.

13. **What is the purpose of the `required` attribute in HTML5 form elements?**
    - The `required` attribute specifies that an input field must be filled out before submitting the form, helping to ensure that the user provides necessary information.

14. **How do you create a dropdown list in HTML5?**
    - You can create a dropdown list using the `<select>` element and adding `<option>` elements inside it. For example,
      ```html
      <select>
        <option value="1">Option 1</option>
        <option value="2">Option 2</option>
      </select>
      ```

15. **What is the purpose of the `autofocus` attribute in HTML5 form elements?**
    - The `autofocus` attribute specifies that an input field should automatically get focus when the page loads, allowing the user to start typing without clicking.

16. **What is the purpose of the `autocomplete` attribute in HTML5 form elements?**
    - The `autocomplete` attribute specifies whether a form field should have autocomplete enabled or disabled, helping users fill out forms more quickly.

17. **How do you create a radio button in HTML5?**
    - You can create a radio button using the `<input>` element with `type="radio"` and specifying the `name` attribute to group related radio buttons. For example,
      ```html
      <input type="radio" name="gender" value="male"> Male
      <input type="radio" name="gender" value="female"> Female
      ```

18. **What is the purpose of the `<article>` element in HTML5?**
    - The `<article>` element is used to define a self-contained piece of content that can be independently distributed or reused, such as a blog post or news article.

19. **How do you create a table in HTML5?**
    - You can create a table using the `<table>` element and adding `<tr>` for rows, `<td>` for data cells, and `<th>` for header cells. For example,
      ```html
      <table>
        <tr>
          <th>Name</th>
          <th>Age</th>
        </tr>
        <tr>
          <td>John</td>
          <td>30</td>
        </tr>
      </table>
      ```

20. **What is the purpose of the `localStorage` object in HTML5?**
    - The `localStorage` object is used to store key-value pairs locally in the user's browser, allowing data to persist even after the browser is closed.

21. **How do you create a new section in HTML5?**
    - You can create a new section using the `<section>` element, which is used to group related content together. For example,
      ```html
      <section>
        <h2>Section Title</h2>
        <p>Section content goes here...</p>
      </section>
      ```

22. **What is the purpose of the `download` attribute in HTML5?**
    - The `download` attribute is used in `<a>` and `<area>` elements to specify that the target will be downloaded when a user clicks on the link.

23. **How do you create a responsive image in HTML5?**
    - You can create a responsive image using the `<img>` element with the `width` set to `100%` in CSS. For example,
      ```html
      <style>
        img {
          width: 100%;
          height: auto;
        }
      </style>
      <img src="image.jpg" alt="Responsive Image">
      ```

24. **What is the purpose of the `async` attribute in the `<script>` tag in HTML5?**
    - The `async` attribute is used to indicate that the script should be executed asynchronously, allowing the rest of the page to load without waiting for the script to finish.

25. **How do you create a tooltip in HTML5?**
    - You can create a tooltip using the `title` attribute in HTML elements. For example, `<span title="Tooltip text">Hover over me</span>`.

26. **What is the purpose of the `<details>` and `<summary>` elements in HTML5?**
    - The `<details>` element is used to create a disclosure widget that can be toggled open and closed, and the `<summary>` element provides

 a summary or label for the details. Example:
      ```html
      <details>
        <summary>Click me</summary>
        <p>Hidden details</p>
      </details>
      ```

27. **How do you create a progress bar in HTML5?**
    - You can create a progress bar using the `<progress>` element and specifying the `value` and `max` attributes. For example, `<progress value="50" max="100"></progress>`.

28. **What is the purpose of the `<time>` element in HTML5?**
    - The `<time>` element is used to represent a specific time or date, and it can help search engines and browsers understand the date and time content of a web page.

29. **How do you create a section of text that is not displayed by the browser in HTML5?**
    - You can create a section of text that is not displayed using the `<!-- -->` comment syntax. For example, `<!-- This is a comment -->`.

30. **What is the purpose of the `sandbox` attribute in the `<iframe>` element in HTML5?**
    - The `sandbox` attribute is used to restrict what can be done with the content inside the `<iframe>`, such as preventing it from executing JavaScript or submitting forms.

31. **How do you create a responsive YouTube video in HTML5?**
    - You can create a responsive YouTube video using the `<iframe>` element with a specific aspect ratio and setting the `width` and `height` to `100%`. For example,
      ```html
      <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe src="https://www.youtube.com/embed/VIDEO_ID" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allowfullscreen></iframe>
      </div>
      ```

32. **What is the purpose of the `defer` attribute in the `<script>` tag in HTML5?**
    - The `defer` attribute is used to indicate that the script should be executed after the document has been parsed, ensuring that it does not block the rendering of the page.

33. **How do you create a line break in HTML5?**
    - You can create a line break using the `<br>` element. For example, `<p>Line 1<br>Line 2</p>`.

34. **What is the purpose of the `hidden` attribute in HTML5?**
    - The `hidden` attribute is used to hide an element from being displayed on the page, similar to setting `display: none` in CSS.

35. **How do you create a responsive table in HTML5?**
    - You can create a responsive table by wrapping the table in a `<div>` element with `overflow-x: auto;` in CSS. For example,
      ```html
      <div style="overflow-x: auto;">
        <table>
          <!-- table content -->
        </table>
      </div>
      ```

36. **What is the purpose of the `min` and `max` attributes in HTML5 form elements?**
    - The `min` and `max` attributes are used to set the minimum and maximum values for input fields such as `number` and `date`.

37. **How do you create a section of text with a specific background color in HTML5?**
    - You can create a section of text with a specific background color using the `<span>` element and setting the `background-color` property in CSS. For example,
      ```html
      <span style="background-color: yellow;">Highlighted text</span>
      ```

38. **What is the purpose of the `placeholder` attribute in HTML5 form elements?**
    - The `placeholder` attribute is used to provide a hint or example text for the user about what to enter in an input field.

39. **How do you create a responsive image gallery in HTML5?**
    - You can create a responsive image gallery using a combination of `<div>` for the gallery container, `<img>` for each image, and CSS for styling and layout.

40. **What is the purpose of the `required` attribute in HTML5 form elements?**
    - The `required` attribute is used to specify that an input field must be filled out before submitting the form, helping to ensure that the user provides necessary information.

41. **How do you create a responsive navigation menu in HTML5?**
    - You can create a responsive navigation menu using the `<nav>` element for the menu container, `<ul>` for the list of menu items, and CSS for styling and layout.

42. **What is the purpose of the `autocomplete` attribute in HTML5 form elements?**
    - The `autocomplete` attribute is used to specify whether a form field should have autocomplete enabled or disabled, helping users fill out forms more quickly.

43. **How do you create a tooltip in HTML5?**
    - You can create a tooltip using the `title` attribute in HTML elements. For example, `<span title="Tooltip text">Hover over me</span>`.

44. **What is the purpose of the `hidden` attribute in HTML5?**
    - The `hidden` attribute is used to hide an element from being displayed on the page, similar to setting `display: none` in CSS.

45. **How do you create a responsive table in HTML5?**
    - You can create a responsive table by wrapping the table in a `<div>` element with `overflow-x: auto;` in CSS. For example,
      ```html
      <div style="overflow-x: auto;">
        <table>
          <!-- table content -->
        </table>
      </div>
      ```

46. **What is the purpose of the `min` and `max` attributes in HTML5 form elements?**
    - The `min` and `max` attributes are used to set the minimum and maximum values for input fields such as `number` and `date`.

47. **How do you create a section of text with a specific background color in HTML5?**
    - You can create a section of text with a specific background color using the `<span>` element and setting the `background-color` property in CSS. For example,
      ```html
      <span style="background-color: yellow;">Highlighted text</span>
      ```

48. **What is the purpose of the `placeholder` attribute in HTML5 form elements?**
    - The `placeholder` attribute is used to provide a hint or example text for the user about what to enter in an input field.

49. **How do you create a responsive image gallery in HTML5?**
    - You can create a responsive image gallery using a combination of `<div>` for the gallery container, `<img>` for each image, and CSS for styling and layout.

50. **What is the purpose of the `defer` attribute in the `<script>` tag in HTML5?**
    - The `defer` attribute is used to indicate that the script should be executed after the document has been parsed, ensuring that it does not block the rendering of the page.
