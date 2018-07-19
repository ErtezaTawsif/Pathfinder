# How to contribute

I'm really glad you're reading this, because i need volunteer developers to help this project come to fruition.

If you haven't already, come find me in Linkedin [#ertezatawsif](https://www.linkedin.com/in/ertezatawsif/). I want you working on things you're excited about.

Here are some important resources:

  * [ErtezaTawsif in Hackster](https://www.hackster.io/ErtezaTawsif) tells you where i am,
  * [My researchgate](https://www.researchgate.net/profile/Erteza_Tawsif_Efaz) is the 10k foot view of where i'm going,
  * [Poject Hub](https://create.arduino.cc/projecthub/ErtezaTawsif) is my day-to-day project management space,
  * Mailing list: Find my [google mail](https://www.google.com/gmail/) at ertezatawsif.
  * Bugs: [GitHub](https://github.com/ErtezaTawsif) is where to report them.
  * Linkedin: [#ertezatawsif](https://www.linkedin.com/in/ertezatawsif/). I'm usually there during business hours.

## Testing

I have a handful of Cucumber features, but most of my testbed consists of C language examples. Please write C language examples for new code you create.

## Submitting changes

Please send a [GitHub Pull Request to ertezatawsif](https://github.com/ErtezaTawsif) with a clear list of what you've done (read more about [pull requests](https://help.github.com/articles/about-pull-requests/)). When you send a pull request, i will love you forever if you include C language examples. I can always use more test coverage. Please follow my coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    > git commit .m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact"

## Coding conventions

Start reading my code and you'll get the hang of it. I optimize for readability:

  * I indent using two spaces (no tabs).
  * I use HAML for all views.
  * I avoid logic in views, putting HTML generators into helpers.
  * I ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`, not `[1,2,3]`), around operators (`x += 1`, not `x+=1`), and around hash arrows.
  * This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.
  * So that i can consistently serve images from the CDN, always use image_path or image_tag when referring to images. Never prepend "/images/" when using image_path or image_tag.
  * Also for the CDN, always use cwd-relative paths rather than root-relative paths in image URLs in any CSS. So instead of url('/images/image.gif'), use url('../images/image.gif').

Thanks,
Erteza Tawsif Efaz, Electrical Engineer.
