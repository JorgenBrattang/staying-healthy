## Links
- <a href="https://github.com/JorgenBrattang/staying-healthy">Github Repository</a>
- <a href="https://github.com/JorgenBrattang/staying-healthy/blob/main/README.md">README.md</a>
- <a href="https://jorgenbrattang.github.io/staying-healthy/" title="Link to live website" rel="nofollow">View live website here!</a>

## Feature testing
### <u>Video responsive test with free resizing and three screens iPhone SE, iPad Air and Nest Hub.</u>
<details><summary>Home (index.html)</summary>

![Placeholder](Placeholder)

</details>

<details><summary>Stretches (stretches.html)</summary>

![Placeholder](Placeholder)

</details>

<details><summary>Anatomy (anatomy.html)</summary>

![Placeholder](Placeholder)

</details>

<details><summary>Contact (contact.html) - (contact-dump.html uses the same code but without form, no test needed)</summary>

![Placeholder](Placeholder)

</details>

The developer ran into few problems along the way of developing the website, the problems worth mentioning are the responsive side of the website. 

Bug found when resizing the size of the screens height. It made the footer float far above the bottom of the page.
- <strong style="color:#71F57E;">Problem solved</strong>, by changing the footer from the section to its own place within the HTML and adding a display flex and column to the body.



### Slack #peer-code-review
- Carina Stenger
    - "After submitting the form the line ‚have a nice day‘ could use a bit more padding (checked on an iphone SE)"
        - <strong style="color:#71F57E;">Problem solved</strong>, by changing the media queiry for that size of phone.

- Hannah Carey_5p
    - "Issue I found was on the form validation page. The text is hidden by the google maps location on my screen.
        - <strong style="color:#71F57E;">Problem solved</strong>, by changing the div containing the map to auto instead of procent and make the map fixed height.

### <u>Websites on different browsers
<details><summary>Chrome</summary>

![Chrome browser](assets/images/readme-files/Chrome.png)

</details>

<details><summary>Edge</summary>

![Chrome browser](assets/images/readme-files/Edge.png)

</details>

<details><summary>Firefox</summary>

![Chrome browser](assets/images/readme-files/Firefox.png)

</details>

<details><summary>Opera</summary>

![Chrome browser](assets/images/readme-files/Opera.png)

</details>

## <u>Validator Testing</u>
Ran through all the code and no errors were found.

**HTML**
- No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

**CSS**
- No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)