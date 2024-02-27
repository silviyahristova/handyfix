# HandyFix Testing

## Table of content
* [**Manual Testing User stories**](#manual-testing-user-stories)
* [**Browser Compatibility**](#browser-compatibility)
* [**Responsiveness**](#responsiveness)
* [**Performance**](#performance)
* [**Code Validation**](#code-validation)
* [**Bugs**](#bugs)
* [**Accessibility**](#accessibility)

## Manual Testing User stories

### As a first-time visitor, I want to easily understand the main purpose of the site and learn more about the company.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
| Why choose our company for your home repair?(About)|Scroll down on home page and read information about the company.|user is brought to the information section about the company.|

### As a first-time visitor, I want to be able to easily navigate through the site to find content.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Navigation bar| On top of each page there is a navigation bar; click on any link.| User is exploring the website.|
|Footer| Scroll down to the bottom on any page; find quick links; click on any link.| User is exploring the website.|

### As a first-time visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
| Testimonials| Click on the logo; scroll down; read testimonials.| User can read feedback about the company.|

### As a first-time visitor, I want to locate their social media links to determine how trusted and known they are.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
| Footer| Scroll down to the bottom on any page;click social media icon.| User is brought to social media links.|

### As a first-time visitor, I want to have an insight into the company and where they operate.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Home page| Click Home on navbar;scroll down to read information about the company.| User knows where the company is operating.|
|Footer| Scroll down to the bottom on any page;see contact information.| User can see where the company is operating.|

### As a first-time visitor, I want to be able to see what services they offer.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Navigation bar|Click Services on navbar;click on any service.|User can see what services are provided.|
|Our services|Click Home on navbar;scroll down to our services;see what services are provided;click on the service.|User can see what services the company is offering|
|Service page|Click Home; click our services button;scroll to read about the services.| User can see what services are provided.|

### As a first-time visitor, I want to be able to see what the pricing is for each service or hourly.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Price|Click Price on navbar;read about the prices.| User is brought to price section.|

### As a first-time visitor I want to see what is included in the price.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
||Price|Click Price on navbar;read about the prices,read the note under price cards.| User can read what is included in the price.|

### As a first-time visitor I want to know how to get in touch with the company.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Contact page|Click Contact on navbar;scroll down; see the company contact information.| User can see contact details.|
|Get in touch|Click Contact on navbar;scroll to form;fill and submit the form.| User can get in touch with the company by filling the form.|
|Footer| Scroll down to the bottom on any page;see contact information.| User can see contact details.|

### As a first-time visitor I want to see pictures of their previous project/work.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Gallery|Click Price on navbar;scroll down; see the gallery| User is brought to gallery section|

### As a first-time visitor I want to see what hours the company operates at.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
||Contact page|Click Contact on navbar;scroll down; see the company`s operating hours.| User can see the company`s operating hours.|

### As a first-time visitor I want to be able to see and click on the links to their social media pages.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Footer| Scroll down to the bottom on any page;click social media icon.| User is brought to social media links.|

### As a first-time visitor I want to easily navigate through the site without becoming overwhelmed with too much information.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Navigation bar| On top of each page there is a navigation bar; click on any link.| User is exploring the website.|

### As a first-time visitor I want to see where the company is located.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Get in touch|Click Contact on navbar;scroll to map;see adress on the map.| User can see where the company is located.|

### As an owner, I want to generate new business by getting users to contact the company.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Get in touch|Click Contact on navbar;scroll to form;fill and submit the form.| User can get in touch with the company by filling the form.|

### As an owner, I want users to easily navigate through the site and at the end be confident enough to contact the company.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Navigation bar| On top of each page there is a navigation bar; click on any link.| User is exploring the website.|

### As owner, I want the site to show the motto of "quality over quantity" in terms of the information that is on display.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Gallery|Click Price on navbar;scroll down; see the gallery| User is brought to gallery section|

### As owner, I want to encourage users to go to our social media pages which will help boost the profile of the company.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Footer| Scroll down to the bottom on any page;click social media icon.| User is brought to social media links.|

### As owner, I want the site to be responsive so users on any platform can successfully navigate the site.

| **Feature** | **Test case** | **Outcome** |
|-------------|---------------|-------------|
|Website| Website is tested on different devices and browsers.|User can explore the website on any device.|

[Back to top](#table-of-content)

## Browser Compatibility

| **Browser tested** | **Intended appearance** | **Intended responsiveness** | 
|--------------------|-------------------------|-----------------------------|
| Google Chrome      |<center>Very Good<center>|<center>Very Good<center>    |
| Mozzila            |<center>Very Good<center>|<center>Very Good<center>    |
| Firefox            |<center>Very Good<center>|<center>Very Good<center>    |
| Microsoft edge     |<center>Good<center>     |<center>Good<center>         |
| Safari*            |<center>Good<center>     |<center>Good<center>         |

* On Microsoft edge hero section taking large amount of space. Does not affect the website.
* There was issue regarding Safari browser. More details can be found [here](#resolved-bugs).
* There was no issues found regarding the appearance and responsiveness.

[Back to top](#table-of-content)

## Responsiveness

| **Device Tested** | **Site responsive** | **Renders as expected** | 
|-------------------|---------------------|-------------------------|
| Samsung Galaxy S21 Ultra|<center>Very Good<center>|<center>Yes<center>|
| Iphone 5s/6s      |<center>Very Good<center>|<center>Yes<center>|
| Ipad              |<center>Very Good<center>|<center>Yes<center>|
| Samsung Galaxy Tab 3|<center>Very Good<center>|<center>Yes<center>|
| Desktop           |<center>Very Good<center>|<center>Yes<center>|
| Laptop            |<center>Very Good<center>|<center>Yes<center>|
| Google Dev Tools  |<center>Very Good<center>|<center>Yes<center>|

* There was no issues found regarding the responsiveness.

[Back to top](#table-of-content)

## Performance

<details><summary>Index.html</summary>

<img src="assets/images/testing/home-desktop-lighthouse.png">, <img src="assets/images/testing/home-mobile-lighthouse.png">
</details>

<details><summary>Service.html</summary>

<img src="assets/images/testing/service-desktop-lighthouse.png">, <img src="assets/images/testing/service-mobile-lighthouse.png">
</details>

<details><summary>Contact.html</summary>

<img src="assets/images/testing/contact-desktop-lighthouse.png">, <img src="assets/images/testing/contact-mobile-lighthouse.png">

* There is a warning regarding Google Map and JavaScript. No further action is taken.

<img src="assets/images/testing/lighthouse-contact-issue.png">

</details>

<details><summary>Success.html</summary>

<img src="assets/images/testing/success-desktop-lighthouse.png">, <img src="assets/images/testing/success-mobile-lighthouse.png">
</details>

*  The site was tested through Google Chrome Dev Tools - Lighthouse to check each of the pages for performance, accessibility, best practices and SEO.
* On mobile devices the site is loading a bit slower than on large screen devices. This is due to image sizes, longer pages and large layout shifts. At the moment no further action is taken, but improvements will be made in future.

[Back to top](#table-of-content)

## Code Validation

### HTML Validation

<details><summary>Index.html</summary>

<img src="assets/images/testing/home-page-code-validation.png">
</details>

<details><summary>Service.html</summary>

<img src="assets/images/testing/service-html-validation.png">

* Solution 

<img src="assets/images/testing/service-edit-video.png">

* Final Validation

<img src="assets/images/testing/service-final-validation.png">
</details>

<details><summary>Contact.html</summary>

<img src="assets/images/testing/contact-page-code-validation.png">

* Solution 

<img src="assets/images/testing/contact-page-resolve-code.png">

* Final Validation

<img src="assets/images/testing/contact-page-final-validation.png">
</details>

<details><summary>Success.html</summary>

<img src="assets/images/testing/success-page-code-validation.png">

</details>

* The validation site [W3C HTML Validator](https://validator.w3.org/nu/) was used to validate the HTML. Some errors were found and resolved.

### CSS Validation

<details><summary>CSS Test</summary>

<img src="assets/images/testing/css-validation.png">

<img src="assets/images/testing/css-warning.png">

</details>

* The validation site [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to validate the CSS. No errors were found. There were 3 warnings regarding vendor extensions, but doesn`t affect the website.

### Link Checker

<details><summary>Link Test</summary>

<img src="assets/images/testing/check-broken-links.png">

</details>

* The validation site [W3C Link Checker](https://validator.w3.org/checklink) was used to check the website for broken links. There were no broken links found, but three links were manually checked and worked as expected. They were not checked due to robots exclusion rules.

[Back to top](#table-of-content)

## Bugs

### Resolved bugs

<details><summary>Autocomplete attribute in form</summary>

<img src="assets/images/testing/missing-autocomplete.png">

* Solution

<img src="assets/images/testing/resolve-autocomplete.png">

</details>

* After testing the form two issues came up. There were not found autocomplete attribute. After research autocomplete atribute were added for better accessibility and better user experience. 

<details><summary>Link missing discernible name</summary>

<img src="assets/images/testing/link-name.png">

* Solution

<img src="assets/images/testing/link-add-title.png">

</details>

* When submiting the form, the user is forwarded to success page. On the code were missing title for the link and it was empty. After adding title the problem was solved.

<details><summary>Responsive images- Test with Lint</summary>

<img src="assets/images/testing/responsive-images-srcset.png">

<img src="assets/images/testing/responsive-images-sizes.png">

* Solution

<img src="assets/images/testing/lint-solution.png">

* Final test

<img src="assets/images/testing/report-index.png">

<img src="assets/images/testing/report-service.png">

<img src="assets/images/testing/contact-report.png">

<img src="assets/images/testing/success-report.png">

</details>

* All pages were tested during coding with [Responsive Image Linter](https://chromewebstore.google.com/detail/responsive-image-linter/mnddginionlghpblkimpdalcecpnbjln?pli=1). The extension provided srcset and sizes to make the images responsive. The solution is used for all images on the website. All images are responsive.

<details><summary>Map was translated</summary>

<img src="assets/images/testing/map-first-code.png">

* Solution

<img src="assets/images/testing/map-resolved.png">
</details>

* When copied the code for the map, the page were automatically translated in Bulgarian language. It was noticed at some point and then were added the new code.

<details><summary>Safari is not displaying images</summary>

<img src="assets/images/testing/iphone-check.jpg">

* Solution

<img src="assets/images/testing/fallback-code.png">

</details>

* When checked on the real devices Iphone 5, Iphone 6 and Ipad, all the images did not display. After research about the WEbP format images compatibility, was found that only from IOS 14 and up support this format. The solution were found in [Stack Overflow](https://stackoverflow.com/) and was to add fallback images in different format from WEbp. Fallback images were added for all images on the website. Google Dev Tools didn`t show up this problem-there all images were working on the Iphone 5, Iphone 6 plus and Ipad.

<details><summary>Contact page title</summary>

<img src="assets/images/testing/heading-change-position.png">

* Solution

<img src="assets/images/testing/contact-position-solved.png">

* Final result

<img src="assets/images/testing/contact-position-final.png">

</details>

* After html validation on the contact page, the bug with open tags was fixed. After that the title position changed. It was fixed by changing top property in a class cover-text-contact. It was changed or remove from media queries as appropriate.

[Back to top](#table-of-content)

## Accessibility

### Color contrast

* The main colors, used for the website, have very good contrast. They were tested with [WebAIM contrast checker](https://webaim.org/resources/contrastchecker/).

<img src="assets/images/testing/contrast1.png" width=250px>, <img src="assets/images/testing/contrast2.png" width=250px>, <img src="assets/images/testing/contrast3.png" width=250px>

### WAVE Web Accessibility Evaluation Tools

* On all pages same alert came up - that there is more than 1 redundant link. This is, because some links are navigating users to the same page, but was made to be user friendly and intuitive as possible for the user. No further action was taken.

* On service page alert came up about the video. The video does not have audio and does not need synchronized captioning and a transcript. No further action was taken.

<details><summary>Home page</summary>

* First test

<img src="assets/images/testing/wave-home.png">

* Alerts

<img src="assets/images/testing/wave-home-alerts.png">

* Solution

First solution was to change p to h4 to the four images of the section. Second solution was to change alt text to images in the testimonial section.

<img src="assets/images/testing/wave-home-solution.png">

<img src="assets/images/testing/wave-home-solution-2.png">

<img src="assets/images/testing/wave-home-solution-3.png">

<img src="assets/images/testing/wave-home-solution-4.png">

* Final result

<img src="assets/images/testing/wave-home-resolve.png">

</details>

<details><summary>Service page</summary>

* First test

<img src="assets/images/testing/wave-service.png">

* Alerts

<img src="assets/images/testing/wave-service-alerts.png">

* Solution

Solution was to change alt text to one image on the page.

<img src="assets/images/testing/wave-service-solution1.png">

* Final result

<img src="assets/images/testing/wave-service-solve.png">

</details>

<details><summary>Contact page</summary>

* First test

<img src="assets/images/testing/wave-contact.png">

* Alerts

<img src="assets/images/testing/wave-contact-errors.png">

* Solution

Solution for the contrast was to change the background-color of the hero image. In case if the hero image does not load background-color will show up and it will be in very good contrast with the title color. In the form labels were empty and was missing aria-label to the input attributes. The code was fixed.

<img src="assets/images/testing/wave-contact-contrast.png">

<img src="assets/images/testing/contact-wave-form-solved.png">

* Final result

<img src="assets/images/testing/contact-wave-solved.png">

</details>

<details><summary>Success page</summary>

* First test

<img src="assets/images/testing/wave-success.png">

* Solution

First solution was to change p to h2 to the heading under the h1. Second solution was to change alt text for the hero image.

<img src="assets/images/testing/wave-success-alerts.png">

* Final result

<img src="assets/images/testing/success-wave-final.png">

</details>

[Back to top](#table-of-content)