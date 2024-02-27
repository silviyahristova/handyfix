# HandyFix Testing

## Manual Testing User stories

## Browser Compatibility

## Responsiveness

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

<details><summary>Safari displaying images</summary>

<img src="assets/images/testing/iphone-check.jpg">

* Solution

<img src="assets/images/testing/fallback-code.png">

</details>

* When checked on the real devices Iphone 5, Iphone 6 and Ipad, all the images did not display. After research about the WEbP format images compatibility, was found that only from IOS 14 and up support this format. The solution were found in [Stack Overflow](https://stackoverflow.com/) and was to add fallback images in different format from WEbp. Fallback images were added for all images on the website. Google Dev Tools didn`t show up this problem-there all images were working on the Iphone 5, Iphone 6 plus and Ipad.

## Performance

## Accessibility

###
