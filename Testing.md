# Links
- <a href="https://github.com/JorgenBrattang/staying-healthy">Github Repository</a>
- <a href="https://github.com/JorgenBrattang/staying-healthy/blob/main/README.md">README.md</a>
- <a href="https://jorgenbrattang.github.io/staying-healthy/" title="Link to live website" rel="nofollow">View live website here!</a>

# Feature testing
## <u>Video responsive test with free resizing and three screens iPhone SE, iPad Air and Nest Hub.</u>
<details><summary>Home (index.html)</summary>

https://user-images.githubusercontent.com/104900271/174786448-4b5b03c0-6743-49e1-88cc-a2d304b38534.mov

</details>

<details><summary>Stretches (stretches.html)</summary>

https://user-images.githubusercontent.com/104900271/174786503-018c83d8-b76e-4bc3-88c1-8f4811ccaac8.mov

</details>

<details><summary>Anatomy (anatomy.html)</summary>

https://user-images.githubusercontent.com/104900271/174786551-e667df2f-7219-475b-8950-24143a256f26.mov
    
</details>

<details><summary>Contact (contact.html) - (contact-dump.html uses the same code but without form, no test needed)</summary>

https://user-images.githubusercontent.com/104900271/174786587-9e944184-eb41-4a03-8c7b-8ae558fdd60b.mov

</details>

<br>

## Features within the website
- Favicon feature, works as intended. It shows a heart next to the title of the website
<details><summary>Favicon feature video</summary>

https://user-images.githubusercontent.com/104900271/174786633-c2e63549-ad01-4e57-bcd1-68e2d1200662.mov

</details>

- Navigation bar feature, works as intended. When you press on each navigation link they move you to different site within the website, and gives you an hover effect plus an active feature when you are in "Anatomy" for example the name is highlighted.
<details><summary>Images fading and hover feature video</summary>

https://user-images.githubusercontent.com/104900271/174786863-d86d2c2c-3079-4be5-98c7-5eeb05071675.mov

</details>

- Back to top button feature, works as intended. It gets you back to the top of the page, and when you hover over it it changes color.
<details><summary>Back to top feature video</summary>

https://user-images.githubusercontent.com/104900271/174760759-38c74a64-377f-4cf0-bd9e-6e6d46469bce.mov

</details>

- Images fading and hover feature, works as intended. When entering the site the border of the images fade in and when hovering them they give a more clear color.
<details><summary>Images fading and hover feature video</summary>

https://user-images.githubusercontent.com/104900271/174786801-e9dacb2e-4c02-4337-b79c-cbf83c38c9a1.mov

</details>

- Read more feature, works as intended. When hovering it will change color and once you press on it will open a new tab where the full article is found.
<details><summary>Read more feature video/summary>

https://user-images.githubusercontent.com/104900271/174786903-f613cccf-eb54-41ee-98b7-f0d172ee2fdf.mov

</details>

- Video feature, works as intended. When entering the page the video will fade in and load, it will not play by it self nor with any audio. User has full control of the video.
<details><summary>Video feature video</summary>

https://user-images.githubusercontent.com/104900271/174786928-3fb3161a-4af0-4a95-b1d4-69c0f49d90c5.mov

</details>

- Google Map feature, works as intended. It shows you the location and its fully functional.
<details><summary>Google map feature video</summary>

https://user-images.githubusercontent.com/104900271/174786760-d96c1bd5-63eb-4af5-9c4e-3862f70aa795.mov
    
</details>

- Contact form feature, works as intended. It gives you clear instructions on what's needed to fill out the form, and when submitted it gives you an confirmation that the form has been submited.
<details><summary>Contact form feature video</summary>

https://user-images.githubusercontent.com/104900271/174786740-c355a2fe-7ba9-4283-a0f4-2915dc02bc8c.mov

</details>
    
 - Footer links feature, works as intended. When hovering the the links, they change color to give feedback that they are links and will open up a new tab when pressed upon.
<details><summary>Footer links video</summary>

https://user-images.githubusercontent.com/104900271/174786656-13ea9281-9f24-4a05-9186-f7b5881e805a.mov

</details>

<br>

## Bug reports

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
