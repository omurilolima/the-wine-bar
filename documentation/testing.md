# The Wine Bar - Manual Testing

## Functionality

<table>
  <tr>
   <td>
<strong>Test Label</strong>
</li>
</ol>
   </td>
   <td><strong>Test Action</strong>
   </td>
   <td colspan="2" ><strong>Expected Outcome</strong>
   </td>
   <td><strong>Test Outcome </strong>
   </td>
  </tr>
  <tr>
   <td>Site loading
   </td>
   <td>Navigate to the home, contact and menu page
   </td>
   <td colspan="2" >All elements are loaded according to the preview.
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Hero image zoom animation
   </td>
   <td>Access homepage
   </td>
   <td colspan="2" >Hero image load and increases 10%
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Button (See our menu)
   </td>
   <td>Access homepage, then mouseover the button, then click it.
   </td>
   <td colspan="2" >Button load, change colour on mouseover and redirect to menu page when it’s clicked.
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Footer
   </td>
   <td>Access home page and click in each of the icons and links in the Footer.
   </td>
   <td colspan="2" >Every link open in a new window and redirect to the correct url.
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Contact form error
   </td>
   <td>Access contact page and click on submit button.
   </td>
   <td colspan="2" >If the required fields (name, email, subject, message) are not all populated, the browser shows an error
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Contact form valid email
   </td>
   <td>Access contact page, fill in email field with a word that is not a email format and click on submit button.
   </td>
   <td colspan="2" >If the email input is not a valid email address, the browser shows an error
   </td>
   <td>PASS
   </td>
  </tr>
  <tr>
   <td>Contact form submit
   </td>
   <td>Access contact page, fill in all the fields and click on submit button.
   </td>
   <td colspan="2" >All the supplied values are present on the Code Institute formdump page when the form is submitted.
   </td>
   <td>PASS
   </td>
  </tr>
</table>
<ol>

## Browser Compatibility

The website works on different browsers: <strong>Chrome, Firefox and Edge.</strong>

## Code Validator Testing

### HTML 
 
- No errors were returned when passing through the official <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fomurilolima.github.io%2Fthe-wine-bar%2Findex.html">W3C validator</a>.

### CSS 

- No errors were found when passing through the official <a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fomurilolima.github.io%2Fthe-wine-bar%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en">(Jigsaw) validator</a>.<br>

### Responsiveness

- According to <a href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fomurilolima.github.io%2Fthe-wine-bar%2F&form_factor=desktop">Google PageSpeed Insights</a>.

![Google Pagespeed Results](/documentation/pagespeed-results.png)

- Responsiveness was also tested with the site: <a href="https://ui.dev/amiresponsive?url=https://omurilolima.github.io/the-wine-bar/">Am I responsive?</a>

## User Stories 

All user stories were successfully performed.

<strong>New Customer stories:</strong>

1. As a new visitor to the website, I want to <strong>view the main info</strong> about the restaurant.
2. As a new visitor to the website, I want to <strong>view the opening hours</strong> of the restaurant.
3. As a new visitor to the website, I want to <strong>view the location/address</strong> of the restaurant.
4. As a new visitor to the website, I want to<strong> view the menu</strong> of the restaurant.
5. As a new visitor to the website, I want to <strong>contact</strong> the restaurant.

<strong> Returning Customer stories:</strong>

6. As a returning customer to the website, I want to <strong>give feedback</strong> to the restaurant.
7. As a returning customer to the website, I want to <strong>sign up for the mailing list</strong> and <strong>qualify for special offers</strong>.
8. As a returning customer to the website, I want to <strong>view the restaurant's social media</strong>.
