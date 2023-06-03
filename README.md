# Pawsome Pudding
Pawsome Pudding is a website for a cat cafe. Visitors to the site can view the menu, read about the resident cats, enter into a prize draw, and find the contact information and address of the cafe. The website is aimed at cat lovers.

## Features
### Existing Features
- Header
  - The Header includes the website name, tagline, logo and navigation bar, and is the same on all pages of the website.
  - The navigation bar contains links to the Home, Our Cats, and Prize Draw pages. This will allow the user to easily move between pages. 
- The Why We Love Cats section has a brief description of the cafe and why its owners decided to open a cat cafe.
- The Food and Drink Menus allow the user to see allergen information and determine if Pawsome Pudding will cater to their dietary needs.
- The Contact section features the telephone, email address, and the physical address of the cafe.
- A Map section features an embedded map so visitors can also have a visual guide for the location of the cafe.
- The footer section features links to social media sites. The footer is the same across all pages.
### Features Left to Implement
- The Our Cats page will feature three short bios of the cafe's resident cats, including a photo of each cat.
- The Prize Draw page will feature a form with various inputs, allowing the user to submit their details for the chance to win a prize. It should also include a brief description of the prize.
- The submit button for the form will redirect the user to a Thank You page with a short message thanking them for filling out the form, and assuring them that they will be contacted soon. This page will only be accessible by clicking the submit button, and should otherwise be invisible to site visitors.

## Testing
### Bugs
- Incorrect syntax in the [style.css](assets/css/style.css) file prevented CSS styling showing in the deployed webpage. Changing 
```
body {
    background-color: aqua;
    color: crimson;
}
``` 
to 
```
p {
    background-color: aqua;
    color: crimson;
}
```
resolved the issue.
- An unneccessary space in the markdown for the inline links in the Credits section of this README was causing both the display text and the full url to show.


### Validator Testing

### Unfixed Bugs
- Google Maps iframe refuses to display in Firefox, Google Chrome and Microsoft Edge browsers. Other browsers untested.
## Deployment

## Credits
### Content
- The README was created and formatted based on Code Institute's [Sample README](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSSE_PAGPPF+2021_Q2/courseware/66cf361c769a41d496f5001fae6f9be7/3b5cd5dc8313462aa5975a3c9b9a1a3c/) and [README Template](https://github.com/Code-Institute-Solutions/readme-template)
- The [Github tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) was used to learn the markdown syntax for the README
- The address used for the Google Maps iframe in the [index.html](index.html) file is that of [The Seafood Bar at Kirwan's](https://www.google.com/maps/place/The+Seafood+Bar+at+Kirwan's/@53.2713828,-9.0548901,19z/data=!4m6!3m5!1s0x485b96e594d6a7bb:0xc070c1f7418154b2!8m2!3d53.2713828!4d-9.0543641!16s%2Fg%2F1v1tmhd2?entry=ttu)
### Media
