# Working with Jekyll
Their [website](https://jekyllrb.com/) speaks for itself but as I understand it, Jekyll a static site generator that allows you to create websites without doing too much coding. I wanted to try creating a website but didn't want to use a completely premade website editor (like Wordpress) but also didn't know how to code one from scratch. So this was a nice midpoint between those options.

There's other static site generators out there but I was recommended Jekyll so this is the one I used, and based on what little I know about running websites, I think I like it a lot.

## Static Sites
My layman's understanding of static sites is that they're sites that aren't dynamic (to state the obvious). What does this mean? The webpage isn't rendered upon every request. The files behind it can't be edited on the fly, essentially.

Whenever I type up these posts or make some other adjustment to the site, I need to 'build' the site again so that the changes show up.

# The Process
## Initial Research
I briefly talked about this above, but after I decided I wanted to make a website I spent some time browsing potential ways of acheiving it. I was unfamiliar with HTML, JS, CSS, and webdev in general so I didn't really know where to start. There were obvious options like Squarespace or Wordpress but I wanted to make something that was more of my 'own' than just made through a tool someone else made.

(To be clear, Jekyll is a tool someone else made but it feels like I went through more putting this together than just making a Wordpress site.)

## Understanding Git
To use Jekyll you need to have Git installed. So I installed Git for windows and learned some basic commands. Do I really understand how Git works? No. But I think I have a better grasp overall of what it does.

As I understand it, it's essentially a version control system. For the purposes of this project though, I had no collaborators so version control wasn't a huge deal.

### Bash Terminal

I've used several different kinds of terminals in the past[^1] so I was familiar with the process of executing basic commands. There's a feeling of satisfaction in executing `git commit` and `git push` in a terminal that you don't get from just using the GitHub client.

## Sublime Text
I soon realized that I was going to be working with a lot of text based files, like markdown, YAML, CSS, HTML, etc. I was going to go with Notepad++, the editor I've always used, but I wanted to try something more... aesthetically pleasing. Which is how I found [Sublime Text](https://www.sublimetext.com/).

Sublime Text is seriously pretty. It makes me want to spend more time working with text files just because of how clean the interface is. Of course, I had to spend some time finding a proper theme. I settled on [Material Theme](https://packagecontrol.io/packages/Material%20Theme), the 'Palenight' variant. Trying to install this theme is how I discovered Package Control.

### Package Control
[Package Control](https://packagecontrol.io/) is a great plugin(?) for Sublime Text. It lets you install other plugins easily within Sublime Text. 

Another plugin I installed with Package Control was [MarkdownLivePreview](https://packagecontrol.io/packages/MarkdownLivePreview) which is great for editing markdown files like this blogpost.

## Jekyll Themes
I spent some time messing around with Jekyll, setting up my own layouts and styles until I discovered that there are Jekyll themes other people have made. The one I settled on is [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/). It's pretty simple in appearance but has a lot of functionality and configurability. For example, I changed the color scheme to reflect the 'minty orange' theme.

All the layouts, styles, assets, etc. are all already made which makes spinning up your own webpage very easy. It saved me the headache of trying to design my own webpage layout from scratch (although that is something I want to try eventually).

## GitHub Pages
GitHub very conveniently allows you to host webpages through it. You can either make a webpage for your GitHub profile or for an individual repo. This one is based on my profile.

Even more conveniently Jekyll works very well with GitHub pages so the process of getting the site setup went very smoothly.

# Takeaways and Future Steps
When I first started doing research into creating websites ~1 month ago I didn't know where to start. Now I have a functional site that can be accessed from anywhere.

In the process, I also learned about Git, Jekyll, basic HTML and CSS. Creating this site was pretty fun and it's nice that I have somewhere to post stuff like this.

I'm currently trying how to figure out how to host a personality test on this site because I want to collect some data based on the [Big 5 personality traits](https://en.wikipedia.org/wiki/Big_Five_personality_traits). I might have to learn some Javascript but I suspect in won't be too difficult because I'm familiar with Java syntax.



[^1]: In middle school I spent a lot of time working with Linux terminals running Minecraft servers for my friends.

