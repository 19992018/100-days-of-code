# 100 Days Of Code - Log

## Day 0: November 14, 2023

### Project: High School

Today I was to start by working on the frontend. I expected to complete at least a half a web page.
Using bootstrap however slowed down my pace of progress. Apparently I am not as efficient with bootstrap as I thought I would be. I fumbled for hours trying to align the header elements. I was trying to achieve CSS’s justify content space-between. Eventually I realised I was using a bootstrap class (container-fluid) in an improper manner thus the content would just not justify with a space between. I realised this after reading the Bootstrap documentation, which was really helpful compared to the Traversy Media crash course.

## Day 1: November 16, 2023

### Project: High School

Worked on the website's carousel as well as the welcome message (The landing page in general).

The images on the carousel were a bit hard to size. However, adding a height, to particular divs solved the issue.

I also used display-flex to position the elements within the landing-page section. However, Mark advised me to add a class of row instead. And that enabled the elements within the section to still display side by side.

It has all in all been a successful day. Tomorrow I polish the landing page and majorly work on the Sign Up/Sign In Page.

## Day 2: November 20, 2023

### Project: High School- Modal

#### 11 to 12noon

This is actually day 3. Sigh! Im indicating it as day 2 because the on actual day 2 I didn't make much progress. I mean I did a quite a lot towards the project but there was not much visible progress. I worked on the modal but using html and javascript; not bootstrap as I am supposed to. This should be the very last time I am making such an entry. All work towards this challenge must be recorded.

So, about today... I worked on the modal that contains the sign in form. It was a bit of a challenge at first getting the modal to appear since the bootstrap documentation was not up to date with the version. I got to know this from stack overflow. Eg. "data-toggle" does not work anymore on modals; it should be "data-bs-toggle".

Besides that little in hitch getting the modal to work, I feel that bootstrap is really convenient since the sign-in page/modal was cute and pre-made. I feel that once I familiarize myself with all the classes and elements Bootstrap will be really convenient to use. Tho I kinda miss CSS. I had gotten so comfortable with it. But still I feel Bootstrap will be an asset once I get comfortable with it.

Im going on a break now. I might pick up from where Ive left after the break or do something else. Either way Ill write the update of what Ive been up to here.

### Project: High School- About Page

#### 2 to 4 pm

I worked on the about page. I initially thought of using ejs to make the about page but I thought it would complicate things so I continued with Bootstrap.

On the bright side I figured out that the node modules folder is only visible once express is installed. I was wondering why I couldnt see the node modules folder despite having installed npm.

Its been an okay session all in all.

Tomorrow I finish up the mock ups to get a sense of direction, add a footer to the pages and also develop another page.

## Day 3: November 21, 2023

### Project: High School- Navigation Page

#### 8 to 10 am

I drew up mockups for 30 minutes
The next one hour was spent on the navigation.html page. I added cards to the page in a grid format. It was pretty easy.

I also edited the image sizes using photos editor.

##### 11 to 12noon

### Project: High School- Navigation Page responsive and Events Page

Ive been working on the responsiveness of the navigation.html page. I also added the events. html page which is quite similar to the navigation page. I feel like there is a better way to make these similar/ repetitive html pages. But Illjust work with what I know then research later.

Ill be back for the 3rd session in a few. Ill indicate what I'll do.

##### 4 to 5pm

### Project: High School- Clubs page

I worked on the clubs and societies page.

I contemplated using ejs since the html pages are becoming many but I thought I should have a guideline for the templates once I make them.

Tomorrow I finish the few remaining pages and style everything correctly.

I should also consider researching on ejs.

## Day 4: November 22, 2023

### Project: High School- Results and school rules page

#### 8 to 9 am

Worked on Results and school rules page successfully

### Project: High School- Results and school rules page

#### 11 to 12 noon

Worked on the contact form. I was intending to import one from the internet but the one I imported is not working. I am considering changing forms because of this to save on time.

After my break I hope to finish up the contact form and perhaps add ready-made footers.

### Project: High School- Contact form

#### 12 noon to 1pm

Finished up the contact form (It is yet to be styled)
I also added a footer to index.htl

I customize the footer in the next session. I also start beautifying and properly styling the website.

### Project: High School- Footer

#### 2pm to 3pm

Customized the footer. For some reason it looks okay on the index.html page but not the other pages.

Tomorrow I beautify and style everything Including the footer.

## Day 4: November 23, 2023

### Project: High School- Footer Styling

#### 11 to 12 noon

Worked on the footers.
Fixed the odd look it had on most pages.
Take it up from results page.

## Day 5: November 23, 2023

### Project: High School- Styling pages - Home, Contact, About

#### session 1: 8 to 10am

Styled Home Contact and About Page
Home: only sizing images remaining

Research on making grid system responsive. Continue with research after the break.

### Project: High School- Styling pages

#### session 1: 1pm to 2pm- Clubs, Events Navigation.

I was able to style the pages that have a grid layout. After more than an hour of research trying to do this, I decided to seek help from my Love and Mentor Mark❤❤, who showed me how to.

The other pages look okay. In the next session, I will size the images correctly and probably fix up the navbar for it to be responsive. From there I can look into how to integrate backend into the project.

## Day 6: November 28, 2023

### Project: High School- Backend: Sign In modal page

#### session: 3:30 to 5pm

I attempted to make the login page work. Its still working but thats probably because I havent connected it to the backend.

In the next session I attempt have a fully working login page.

## Day 7: November 28, 2023

### Project: High School- Backend: EJS

#### 1st session: 11:38 to 12:10

I switched my focus from trying to make the login page/section work to incorporating EJS into my project as Mark adviced. I went through old projects and the ejs documentation, trying to find out how ejs works.

EJS works by adding a partials folder to the views folder of the project. The partials folder contains the ejs files that are consistent in all the pages. Id say it contains the recurring template code, if that makes sense.

The following are also key to know when using EJS:
<%- %> - For HTML templating
<% %> - For control flow statements
<%= %> - When expecting a JS output.

One can link the EJS files to the server or javascript file using the line:

app.set('view engine', 'ejs');

For more details I can always check the documentation or other websites. These two were really fundamental in helping me understand:

https://ejs.co/#:~:text=EJS%20is%20a%20simple%20templating,of%20iteration%20and%20control%2Dflow.

https://www.digitalocean.com/community/tutorials/how-to-use-ejs-to-template-your-node-application

In the next session I put what I have learnt into action.
