Formatting in word is hard at least in my opinion, you know what's easier for me 
formatting in CSS and HTML 

Originally I was using a latex template, this was passable since 
I could just find the spots to update, but I wanted to change the format and templating. Learning latex
was going to take too much time, and I'd only use it for applying to jobs, so it wouldn't be worth the effort and 
same applied to learning how to format a Word document to exactly the way I wanted it.
Then I woke up at 3am in a cold sweat and thought "media queries" so a quick early morning googling and I found the 
[print media query](https://developer.mozilla.org/en-US/docs/Web/CSS/Paged_Media)

Implementing the design was super easy, a couple *flex boxes* later and had just the resume I wanted

# the benefits
at first, I thought this was a bit extra, but then I realized this actually prevents a lot of big headaches you get from word
## inconstant formatting 
Word formatting is designed to try and figure out what you want, giving you the tools to do so and guessing half the time 
for example, if I select a group of words and try and centre them it will assume I also want to centre some of the words around the highlighted text
![image](https://user-images.githubusercontent.com/54285948/209968943-088d5ae7-d082-43ca-8f80-602331414c82.png)

this is good for people who don't know what they want but for people with a design in mind it gets in the way, and this is how every formatting tool in 
word like apps work, whereas in CSS I can simply make a div for the words I want centred and make a CSS rule for that div
![image](https://user-images.githubusercontent.com/54285948/209969895-e000f890-5224-4a4e-86c8-9f4c0d68f152.png)

## Easier to update
often when updating a word document you can have these instances where the style/format gets removed or completely changed when adding content
![image](https://user-images.githubusercontent.com/54285948/209970743-4ee606dd-ba39-436b-8a6d-e1a49e74a4d2.png)
in this example I accidentally selected some words that were in a different style, and it decided the surrounding style was better. This happens a lot 
when you set up a style, but your cursor is just off by a bit and the style goes weird. This is completely removed by using CSS and HTML since all
the style lives on the tags so if you want to update a tag to say something you just change what's in the tag making it *waaaaaaaaayyyyy* easier

# Conclusion
This project made me confident in my skills with CSS. I also learned from this that applying a skill somewhere it might fit might just produce better 
then expected results 

# Roadmap
- [ ] find a way to automate printing 
- [ ] turn into a react app for quick templating 
