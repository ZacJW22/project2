# Reflection Markdown
This site is my submission for the 3rd project of Front End Web Design - Outside the Grid

For this project, we were allowed to base the topic on anything we liked and I decided to do my site on my most recent karting race. I chose this as karting is pretty much my entire life outside of work and university. I spend hours and hours every week either tinkering with it or ripping laps at the local track trying to find that extra little bit of lap time to get me closer to the front. I won't go into detail about how I went in this markdown, as I'll let you read that for yourself. That is what the site is based on after all.

Below will be all my thoughts and ideas while creating the site, however there also comments within the code outlining specific features of the design from both a design perspective and technical perspective.

## Design
This section will cover the design and presentation of the site, starting from the top.

The first item of note isn't actually on the site itself, rather the head of the site. What you'll see is that the title of the site in the browser is Warren Racing, and I have also added a Favicon to the head, which is the W section of my main logo. In normal circumstances I would've added the wings as well, however due to the proportions of the logo with wings, and favicons being square, this looked horrible and the only way to get a half decent looking favicon with wings would've been to compress the whole thing down to nearly nothing. This would've essentially made it unreadable, whereas just having the W looks far better.

Now onto the site itself, starting with the header. The header features my main Warren Racing logo and the name of the site, Warren Racing. In normal circumstances, the site would have more than one page and this header would've remained constant throughout all pages, with the probable addition of a navigation bar/menu. If you look carefully at the header, you'll also notice that the background is actually a gradient background, which I beleieve adds a nice effect to the header, rather than a dull, boring, solid charcoal colour. Black/dark grey are the main colours of my racing page and logo, so keeping these colours consistent was important to the brand image. The title text has also been given a bit of extra weight, just to help it stand out from the rest of the page.

Moving down the page, next we have the hero title. Once again, you'll notice there's a gradient on the background here, once again, it helps to give the site a bit more excitement and energy. The colour choice here was really important, as it matches with the colours used on the logo for the Circuit Mark Webber, which is where the event was (Google it, you'll see). The lighter blue of the gradient as well also resembles the primary blue colour for the Karting New South Wales state title events. Both of these colour choices help link the race meet to the event and the track it was held at. The underline and italics are there purely to help it stand out.

In racing, results are what count, so it's important to show what those results were to interested readers. Having this at the top allowed it to stand out from the rest of the article/reflection and gives readers a solid idea of how the weekend went before reading a massive paragraph where I go over the weekend in detail. Making the font size a little bit bigger compared to the rest of the article/reflection also helps it stand out.

The reflection part of the site is important because it helps readers get an understanding of how the weekend unfolded. Raw results while important only paint a certain amount of the picture. The reflection helps finish it off. Due to the amount of text in this section, it's important not to make the font size too big for ease of reading.

Images are always a good thing and add excitement and energy to any site. If it were to just be dull and boring with black text on a white background and nothing else, no one would read or engage with it. Using the right images are important to conveying the story as well. This one in particular, featuring 3 karts nose to tail through a corner, helps emphasise the competitiveness of the weekend. I covered the whole width of the screen to add as much energy as possible to the site. If the resolution of the image was underwhelming, I would naturally make it smaller as no one likes looking at overly pixelated images. The bigger the image and resolution, the better.

The footer once again features my logo, as well as the tags for my social channels. Keeping the footer and header in a similar format helps contain the site, showing it has a clear beginning and end. In most modern day websites, should the author/organisation have social channels, 90% of the time you'll find it at the bottom in the footer. This site is no different. The last addition to the footer is identifying the author of the site.

## Technical Aspect
The biggest focus for this assignment was to create a site that uses a SSG. The SSG that was used in this assignment was eleventy.js. Initially, we were supposed to be using Jekyll, however that proved unrelaible so that idea was scrapped. Using an SSG helps speed up the load time of a site as it pre renders most of it when users google search something that will make the site appear on the search page. This is not only a quality of life improvement, but it has also been found to help increase user engagement and sales for businesses.

Most of the technical information is explained using comments within the code. Most of it is located in the Stylesheet CSS, however there are a few others here and there that explain most of my reasoning behind the site.

The breaking point for this site is 480px wide, as this is the width of the logo png. This however is a respectable size, as very few devices currently in circulation have a screen width less than that.

## What was good in the site? What wasn't so good?
As good as I think the site looks, I know there are some flaws with it. I do believe the addition of background gradients and images dramatically increase the attractiveness of the site, and it would look awful without it. I also believe the layout of each individual section helps convey the message and focus of the site as best as it can. My biggest concerns however come from the header and footer. Incorporating the logo into each of these sections proved a challenge, especially when thinking about the responsive width aspect of the site. Particularly with margins and spacing, the logos didn't really want to behave how I wanted them to. When the screen gets too small, it starts to overcrowd the accompanying text, giving it a rather messy look. The site certainly looks better on desktop/tablet rather than mobile.

The next issue I have with the site is the fact it is rather simple. If I had more time on my hands, I would add some more on screen effects and play around with text box shaping to give it a more professional look in line with current industry standards. I would also implement Javascript to help nail these effects, however I decided against it as my history with coding JS has been rocky at best and the risk was too high to implement it.


Written by Zachary Warren (U3200999)