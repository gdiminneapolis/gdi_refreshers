# JavaScript 101 Photo Gallery

In this refresher, we'll be implementing the Photo Gallery execerise
at the end of the JavaScript 101 (Intro to JS) course on Day Two. We
hardly ever get to this exercise in class, usually leaving it up to
the students to write it up on their own.

This refresher lab will run about 2 hours, and we cover the steps
needed to make the gallery using the HTML, CSS, and JavaScript skills
you've learned in the GDI courses.

You don't need to know more than what's been taught in the HTML&CSS
101 and 201 courses and JavaScript 101.

## Course Slides

You can find the course slides for this refresher at the same site
they were for the course:

* Day 1: http://amlyhamm.com/gdi/intro-to-js/day-one
* Day 2: http://amlyhamm.com/gdi/intro-to-js/day-two

We'll be using the Day 2 slides, and the Photo Gallery project is near
the end of the slide deck. (It should start on or about slide
http://amlyhamm.com/gdi/intro-to-js/day-two/#/57)

## Project Files

The project files are also available online
at [project files location](#)

> TODO: add the link

Download the files and unzip them to your Desktop. Open the entire
project directory in your editor (Visual Code, Atom, Sublime Text,
e.g.)

We'll be using the files in the `gallery` folder.

## Steps

We'll follow the steps on the slides, listed here. After each step is
done by the class, we'll hold a live review to make sure everyone is
on the same page, and share any learnings.

1. In your editor, open the `index.html` file in the `gallery` folder.
   - Add a `<script>` tag to the bottom of the `body` (before the
     closing `</body>` tag).
   - Refer to the `galleryScripts.js` file in the `<script>` tag's `src`
     attribute.

   Live Review

5. Create two `div` elements. Set the first `div`'s `id` attribute to
   `gallery` and the second `div`'s `id` tag to `large_image`. Doing
   so will let you use the given CSS and you won't have to write your
   own.

   Live Review

6. In the `gallery` `div`, create 6 thumbnail `div`s (to match the
   number of images)

   Live Review

7. Save the `index.html` file and open it in your browser.

   Live Review

8. Open the `galleryScripts.js` file in your editor
9. Using JavaScript, find and select the `gallery` element and save it
   in a variable of your choice

   Live Review


10. Find and select the `large_image` element and save it in a
    variable of your choice

    Live Review

11. Find and select **all** the thumbnail elements and save that in a
    variable

   Live Review

12. Verify that you have selected the right elements in each
    case. (How will you do that?)

   Live Review

13. Think about how you want the gallery to act? What interactions are
    we expecting the user to perform?
	- when a user clicks on a thumbnail, the full-size image replaces
      the current image in the large area
	- the selected thumbnail is highlighted
	- any previously selected thumbnails are un-highlighted

   Live Review

14. Set up a *click* handler for each thumbnail (How will you do
    that?)

   Live Review

15. Test you've done this correctly (How will you do that?)

   Live Review

16. When the user clicks on the thumbnail, we want to take the
    contents of the thumbnail `div` (which should be the `img`
    element) and replace the contents of the `large_image` div with
    that content.

   Live Review

17. Also, when the user clicks on the thumbnail, make the clicked
    thumbnail become highlighted. Use the `selected_thumb` class to
    highlight it

   Live Review

18. Remove any previously selected highlights by removing
    `selected_thumb` from any other thumbnail `div`s

   Live Review


## Wrap up

What did you learn?

What can you do to practice some more?

What resources do you recommend to others?

What else would you like to cover?
