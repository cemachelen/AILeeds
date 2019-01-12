---
layout: post
project: webstuff
---
Today I've been learning to use Jekyll to build a quick simple site. I've decided to do blog style site on various things I'm interested in. I found so many different templates but nothing I quite liked so decided to start from scratch and slowly build up a website - starting simple and then adding features. The first 3 steps can be done over a weekend to create a smart looking site!

Jekyll allows for a lot of the hard work to be automated and not have to repeat text e.g. Create default layouts in `_layouts` and use them as templates simply by adding
```
---
layout: default
title: My Page Title
---
```

This will set up the nav bar, css , js calls etc. This is familiar to me from my python flask work.

## Step 1 - Initial basic site build.

Following the [step-by-step tutorial](https://jekyllrb.com/docs/step-by-step/), with a few adjustments for example rather than authors I have different project themes. The fonts hurt eyes a little so I also added:

```html
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
```

above the text style sheet. This allows to use the vast bootstrap css library. With the text style sheets below allowing for customisation.

## Step 2 - Population with Initial information.

Personally I think there's not point in having a fancy empty site. So creating an example blog post, the project format. Thinking about what sort of things I would like to display is the next logical step. It starts out looking quite clunky but we can 'prettyfy' the site later.

* Adding images. Personal jpgs can stored in the /img directory. I like to add in a silly [404](https://github.com/cemachelen/cemachelen.github.io/blob/master/404.html) pages as when you're building a site you're most likely going to see [this](https://cemachelen.github.io/hoot) from time to time.
* Populating the home page.
  * Add some containers to start introducing a layout to the page.
    ```html
    <div class="jumbotron text-center">
      <h1>My Fancy Big Heading</h1>
    </div>
    ```
  * Link to github, twitter, linked in:
    * I decided to go for slightly bespoke buttons found [here](https://codepen.io/ruandre/pen/howFi). This requires directly coding the button as in the examples. This is done by adding a [/assets/css/social.css](https://github.com/cemachelen/cemachelen.github.io/blob/master/assets/css/social.css) and loading it in either to the default.html or to index.html if you think you're only adding to home page. Then relevant html code is added to index html.
    * I've then edited the hex colours to match the  relevant logos. And to hover to grey on a turquoise background.
* Thinking about layout of nav bar.

So we end up with a very basic looking site like this:

*image coming soon*

## Step 3 - "Fancyfy"

*Under development*

* Page width
* Header and footers
* Swish nav bar
* Responsive pages


## Step 4 - Improve along the way

As I work in software development I'm likely to come across new features tips etc. To improve my site and will be adding them. I'll try to add these either here or in separate blod posts with I'll link here.

1. *Improvements will be listed here*
