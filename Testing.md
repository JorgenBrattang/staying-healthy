# Links
- <a href="https://github.com/JorgenBrattang/staying-healthy">Github Repository</a>
- <a href="https://github.com/JorgenBrattang/staying-healthy/blob/main/README.md">README.md</a>
- <a href="https://jorgenbrattang.github.io/staying-healthy/" title="Link to live website" rel="nofollow">View live website here!</a>

# Feature testing
## <u>Responsive test</u>
Video shows free resizing and three screens iPhone SE, iPad Air and Nest Hub.
- (It works with all other examples that the inspect feature displays, but would be a longer video for that).

<strong>Home (index.html)</strong>

https://user-images.githubusercontent.com/104900271/174786448-4b5b03c0-6743-49e1-88cc-a2d304b38534.mov

<strong>Stretches (stretches.html)</strong>

https://user-images.githubusercontent.com/104900271/174786503-018c83d8-b76e-4bc3-88c1-8f4811ccaac8.mov

<strong>Anatomy (anatomy.html)</strong>

https://user-images.githubusercontent.com/104900271/174786551-e667df2f-7219-475b-8950-24143a256f26.mov
    
<strong>Contact (contact.html) - (contact-dump.html uses the same code but without form, no test needed)</strong>

https://user-images.githubusercontent.com/104900271/174786587-9e944184-eb41-4a03-8c7b-8ae558fdd60b.mov

<br>

## Features within the website
<strong>Favicon feature</strong>, works as intended. It shows a heart next to the title of the website

https://user-images.githubusercontent.com/104900271/174786633-c2e63549-ad01-4e57-bcd1-68e2d1200662.mov

<strong>Navigation bar feature</strong>, works as intended. When you press on each navigation link they move you to different site within the website, and gives you an hover effect plus an active feature when you are in "Anatomy" for example the name is highlighted.

https://user-images.githubusercontent.com/104900271/174786863-d86d2c2c-3079-4be5-98c7-5eeb05071675.mov

<strong>Back to top button feature</strong>, works as intended. It gets you back to the top of the page, and when you hover over it it changes color.

https://user-images.githubusercontent.com/104900271/174760759-38c74a64-377f-4cf0-bd9e-6e6d46469bce.mov

<strong>Images fading and hover feature</strong>, works as intended. When entering the site the border of the images fade in and when hovering them they give a more clear color.

https://user-images.githubusercontent.com/104900271/174786801-e9dacb2e-4c02-4337-b79c-cbf83c38c9a1.mov

<strong>Read more feature</strong>, works as intended. When hovering it will change color and once you press on it will open a new tab where the full article is found.

https://user-images.githubusercontent.com/104900271/174786903-f613cccf-eb54-41ee-98b7-f0d172ee2fdf.mov

<strong>Video feature</strong>, works as intended. When entering the page the video will fade in and load, it will not play by it self nor with any audio. User has full control of the video.

https://user-images.githubusercontent.com/104900271/174786928-3fb3161a-4af0-4a95-b1d4-69c0f49d90c5.mov

<strong>Google Map feature</strong>, works as intended. It shows you the location and its fully functional.

https://user-images.githubusercontent.com/104900271/174786760-d96c1bd5-63eb-4af5-9c4e-3862f70aa795.mov

<strong>Contact form feature</strong>, works as intended. It gives you clear instructions on what's needed to fill out the form, and when submitted it gives you an confirmation that the form has been submited.

https://user-images.githubusercontent.com/104900271/174786740-c355a2fe-7ba9-4283-a0f4-2915dc02bc8c.mov
    
<strong>Footer links feature</strong>, works as intended. When hovering the the links, they change color to give feedback that they are links and will open up a new tab when pressed upon.

https://user-images.githubusercontent.com/104900271/174786656-13ea9281-9f24-4a05-9186-f7b5881e805a.mov

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
<strong>Chrome</strong>
    
![Chrome browser](assets/images/readme-files/Chrome.png)

<strong>Edge</strong>

![Chrome browser](assets/images/readme-files/Edge.png)

<strong>Firefox</strong>

![Chrome browser](assets/images/readme-files/Firefox.png)

<strong>Opera</strong>

![Chrome browser](assets/images/readme-files/Opera.png)

## <u>Validator Testing</u>
Ran through all the code and no errors were found.
    
**HTML**
- No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

**CSS**
- No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)    

<strong>index.html</strong>

https://user-images.githubusercontent.com/104900271/174791270-fe542175-b609-45f7-9715-1793b6508138.mp4
    
<strong>stretches.html</strong>
    
https://user-images.githubusercontent.com/104900271/174791303-211b00e3-7d52-4889-baa6-d90ba8fcbc83.mp4

<strong>anatomy.html</strong>

https://user-images.githubusercontent.com/104900271/174791374-6c983d0b-7d8c-413e-ac7b-21340fc2613d.mp4

<strong>contact.html</strong>

https://user-images.githubusercontent.com/104900271/174791405-ab2c6b02-f10d-4788-80bb-f10b7c0bfb08.mp4

<strong>contact-dump.html</strong>
    
https://user-images.githubusercontent.com/104900271/174791433-eb593c8c-1c0b-4d24-8287-7ce0bf67c489.mp4

<strong>style.css</strong>

https://user-images.githubusercontent.com/104900271/174791479-a719e019-a6cd-452e-93ca-d30ddfde2583.mp4
