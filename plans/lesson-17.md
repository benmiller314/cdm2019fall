---
layout: bottomnav
---

# Generative Studio

**Work to have done**:
* As much of the [Interneting is Hard (but it doesn't have to be)](http://web.archive.org/web/20190213013947/https://internetingishard.com/html-and-css/) tutorial as you can – at least parts 1-4 (from "Introduction" through "Hello, CSS")

**Plan for the day**:

1. Key Concepts and Practical Takeaways (10-15 min)
2. Homework preview and parachute prompts (5 min)
3. Loop writing (10 min)
4. Offline sketching (10 min)
5. Studio (30 min)

## 1. Key Concepts and Practical Takeaways (10-15 min)

At your tables, work through the following questions, and be ready to discuss with the whole class if time allows. Some you should be able to go through rather quickly, while others may require more discussion.

Ask if you can't come to a resolution!

EXT: If your group finishes early, (a) let me know you're done, and (b) check out these [example web-design sketches](http://designbeep.com/2012/05/17/33-great-examples-of-web-design-sketches/). What design patterns do you notice? What drawing conventions?

### Organizing files

* True or False: filenames are not case sensitive, so it doesn't matter if something is uppercase or lowercase.
* T / F: web browsers know how to handle spaces in filenames, so it doesn't matter if you have spaces in a filename or not.
* T / F: all files referred to in an html document have to be in the same folder as that html document.
* What are some html elements can you use to refer to an external file? (Hint: you should know at least three already.) Where would you put the filename within each of those elements? <!-- <a href="">, <img src="">, <link href=""> -->
* What's one advantage of using a relative link? <!-- easier to change folder names / servers --> What's one risk? <!-- link could break -->

### HTML basics
* What kind of information goes in the `<head>`?
* How do you mark up comments in HTML?
* T / F: every HTML element has an opening tag, some element content, and a closing tag.
* T / F: in rendering an HTML file, there's no difference between a space, a blank line, or five blank lines.
* EXT: What information should pretty much every page's `<head>` include? <!-- <title>, <meta charset='UTF-8'/>, <link rel="stylesheet"> -->

### Image basics
* T / F: every `<img>` tag should specify a source file.
* T / F: every `<img>` tag should specify a width and a height.
 - EXT: what happens if you only set one?
* T / F: every `<img>` tag should specify alternative text with `alt`.
* What makes .jpg files better for photographs than .png files? What makes .png files better for simple diagrams?

### CSS basics
* Name three different places you could store CSS rules. <!-- external stylesheet, page-specific <style> in the <head>, inline style in the attributes of an html element -->
* How do you mark up comments in CSS?
* What's one advantage of using `em` as a unit rather than `px`?
* How can you apply a single CSS rule to multiple HTML elements?  
* What happens if you have multiple CSS rules for the same selected HTML element?
* Why is using inline styles generally a bad idea?

## 1b. Let's discuss!

If you're waiting for others to finish,

## 2. Homework preview and parachute prompts (5 min)



## 3. Loop writing (10 min)

Take a few minutes to think in writing about the websites you might want to make. I'll read a series of questions aloud. Repeat them silently to yourself, and when you feel yourself answering, make a list.

These lists will remain private, unless you choose to share. I won't ask for them.

1. What have you been working on, in or out of this class, that you'd like to show the world? What have you made, or done, or pursued?
    - Or: if you'd rather the site not focus on _you_, what groups, things, or events might you represent?
2. Is there anything else you might add to the list? A wider context for one of the projects already there, or a related next step?
3. Is there anything you're forgetting? Something you were recently talking about, or planning for? Add it to the list.
    - If you haven't yet included your work for this class, be sure to add it now.

Take a moment now to read back over your lists. **How might you _group_ or _divide_ these items? What clusters do they form?** Mark these in some way.

Is there one cluster that stands out, that says, _me, pick me_? Choose one group to work with, at least for today, and name it in some way. Then copy the name into a clean page.

With that chosen subject, write again:

4. What terms or images come to mind when you think of this subject? ... Think about actions... things... descriptors.
5. I'm going to interrupt you now and ask you to set aside the list, just for now, and ask: **What's the heart of this?** What's the essential component for this cluster of things? What ties them together? <br/><br/>See if you can summon up the whole of this idea, like it's right here in the room with you. Where does it live? Is it above you? Inside you? In the palm of your hand? Just sit with your idea for a moment, feeling where you connect to it.

## 4. Offline sketching (10 min)
And now, draw. Given what's essential, given your knowledge of how websites work, and given the principles of designing for attention we learned last unit, **make a few quick sketches of your possible website's landing page.**

Consider: How will it look on a phone? On a laptop? What might you add to the layout for a full-sized desktop monitor?

Not sure what that should look like? Here are [33 examples](http://designbeep.com/2012/05/17/33-great-examples-of-web-design-sketches/) (but no one is asking you to be as elaborate as the most elaborate of these)

* EXT: Finished one drawing? Make another, using a different system of visually organizing your information.


## 5. Studio / Practice (30 min)

Options!

* If you haven't yet done so, why not start the tutorial sections from the homework?
* I won't have assigned time for *all* the sections of the tutorial; you can look ahead in the [schedule](/{{site.course.base_path}}schedule) to see what's expected, and what's beyond baseline
* Start gathering materials toward your website, to check feasibility
* Above all, **call me over for help as needed**.

NB: I'm not sure if the lab computers don't have Atom, but they should at least have SublimeText, which is very similar.

EXT: If you're good on what a CSS class is, and how to add it to an HTML element, read up on [Bootstrap](https://getbootstrap.com/), a very widely used CSS framework. What that essentially means is that they've pre-created a bunch of CSS classes for you, so you can start using them to design your own layout from scratch. It's a little like Lego for web design, only free.


## Homework for Next Time

* **View/Read** documentation on using GitHub Pages at [pages.github.com](https://pages.github.com/).
* **Do** more of the [tutorial](http://web.archive.org/web/20190213013947/https://internetingishard.com/html-and-css/), getting through at least The Box Model (5) and CSS Selectors (6), if you haven't yet.
* **Read** more about [how CSS selectors work](https://css-tricks.com/how-css-selectors-work/)
* **Write** a website proposal, posted to the [Issue Queue]({{site.github.repository_url}}/issues), including:
    - some text about the idea or appeal you're hoping to make;
    - some sense of what pages and page sections you expect to include;
    - a prospective assets chart (what you'll need, where you might get it);
    - at least one design sketch, showing possible layouts; and
    - a link to your repository.
