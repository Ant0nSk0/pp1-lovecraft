# Lovecraft
This project is about the life and works of H.P. Lovecraft. It contains useful information for both fans and people new to Lovecraft's works. 
![Lovecraft Mock-up](assets/images/readme-images/lovecraft-mock-up.PNG)
## Features
In the top left corner we have our header and in the top right corner we have our navigation section, with links to the three pages being Home, Works, and Biography. Centered we have a silhouette of Lovecraft with a subheading.  
![Lovecraft Header](assets/images/readme-images/lovecraft-header.PNG)
### Home 
- The front page features a short introduction to Lovecraft next to a photograph of him from around 1930. Under the introduction is a famous quote of his that perfectly describes his literature and philosophies.
![Lovecraft Introduction](assets/images/readme-images/lovecraft-introduction.PNG)
- Below we find some quotes about Lovecraft from different authors that he inspired.  
![Lovecraft Quotes](assets/images/readme-images/lovecraft-quotes.PNG)
- Also featured here is a form for the user to fill in if they want to sign up to the newsletter.
![Lovecraft Sign-Up](assets/images/readme-images/lovecraft-sign-up.PNG)
- At the bottom of the page is our footer with links to Goodreads, LibriVox and Wikipedia. There is also an arrow icon to take the user back to the top of the page.
![Lovecraft Footer](assets/images/readme-images/lovecraft-footer.PNG)
### Works
- On the Works page the user will first see the Works of Horror section, or if they have a larger viewport, both the works of horror section and the Cthulhu Mythos section will be visible side by side.  

- The Works of Horror section features a short description of his writings followed by a list of his horror fiction stories. At the bottom there's a link to Lovecraft's complete bibliography on Wikipedia, which opens in another tab.  
![Lovecraft Works](assets/images/readme-images/lovecraft-works.PNG)
- The Cthulhu Mythos section features a picture of Cthulhu and a description of what the mythos is.  
![Lovecraft Cthulhu](assets/images/readme-images/lovecraft-cthulhu.PNG) 
- Below these two sections is an audioplayer with an audiobook of The Nameless City - provided by LibriVox, Public Domain, via Wikimedia.  
![Lovecraft Audiobook](assets/images/readme-images/lovecraft-audiobook.PNG) 
- At the end of this page is a quote that the user will recognise from the audiobook provided above.  
![Lovecraft Aeons Quote](assets/images/readme-images/lovecraft-aeons-quote.PNG)

### Biography
- The Biography page features a matching structure to the home page, with text about Lovecraft next to a portrait from 1934.  
![Lovecraft Biography](assets/images/readme-images/lovecraft-biography.PNG)
- At the bottom there's another quote followed by a symbol.  
![Lovecraft Mind Quote](assets/images/readme-images/lovecraft-mind-quote.PNG)

## Testing
*All tests had a positive outcome unless stated otherwise*  
- Tested in Chrome with responsive device mode.
- Tested in Firefox.
- Tested in Edge.
- Tested on my phone (Samsung A224G) with Chrome and Samsung Internet.  
- All links were tested in all browsers mentioned above. All worked as intended.
- Tested in Google Lighthouse:  
### Home  
![Lighthouse Report Index](assets/images/readme-images/deployed-lovecraft-index.PNG)  
### Works  
![Lighthouse Report Works](assets/images/readme-images/deployed-lovecraft-works.PNG)  
### Biography  
![Lighthouse Report Biography](assets/images/readme-images/deployed-lovecraft-biography.PNG)
Lighthouse was run in Chrome incognito mode as recommended by various sources such as [Intellitonic](https://intellitonic.com/blog/google-lighthouse/) and [Flexiple](https://flexiple.com/developers/using-google-lighthouse-to-audit-your-web-application/)  
I did find it a bit inconsistent between audits, especially between using incognito or not. 
## Validator Testing
- HTML - There is no errors going through [W3C HTML Validator](https://validator.w3.org/) 
    - I had initially one error/warning because I had used a span instead of div. Simple solution to replace the span with the necessary div.
- CSS - There is no errors going through [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator)