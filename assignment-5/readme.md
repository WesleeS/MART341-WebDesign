1) **Explain how web browsers function**  
Browsers cover the full extent of what's displayed. Not to be confused with the search engine, one such example are "Chromium" browsers, which run on the chromium backend to display content not otherwise possible.
Another example being the Quantum browser backend that Firefox uses. Using these backends, browsers are able to adeptly display information otherwise too advanced for just text renders alone. This display is
processed and developed by the frontend design of the individual webpage, but relies on common weblanguages such as HTML to communicate what to render.

2) **Define and describe DOM**  
The Document Object Model (DOM) is a particular structure for weblanguages designed in order to have superior access over displayed elements. For example, using javascript you can specify an HTML object and apply various
transformations or alterations to the styling. The DOM is contstructed in a way not unlike the nestled order produced by html flags, and you can consider its structure as nestled containers/elements.

3) **What is the difference between HTML XML and XHTML?**  
HTML is by far the most known among the 3 stylings provided, as if often the easiest to learn. It provides existing and accessible structure that can be used for fairly robust webdesigns even on its own. However,
due to this 'robust' construction, it's hard to assure that the experience is the same among all platforms due to minor dependandies, updates, or possible bloat.  
XML is the 'opposite' so to speak. It's ligthweight, largely compatible, but requires more tuning to get it to work properly in the first place. You'll have to handle more initial descriptions whereas html comes with
prefab flags such as <p>aragraphs, <h>eaders, <d>ividers, so on and so forth. CSS is still usable with XML however, and with proper setup it can look just as good as an HTML page with a fraction of the load.
XHTML is a midground, and requires a bit more precision than base HTML to write as you must fulfill the standards of XML writing aswell, but it's a largely compatiable format for writing webpages with still being able
to code it in HTML's language.

4) **What are the 4 elements your HTML pages need?**  
The is the Doctype, which is invisible to the end user but marks the version of HTML the webpage displays to the browser. The root element, which contains all elements within an <html></html> flag. Useful if for some
reason you want to contain your CSS in the same file but more likely that you'll have javascript content on the page contained within <script></script> flags. Finally, within the root element is your <head> and <body> elements.
The header is useful for well, page headers. It'll be the title of the tab, and you can occasionally do some dynamic displays with it. Further, the body element contains information regarding, well, the page! Everything is in
there for what's displayed as the meat of the page.

6) **What is the index.html page for? Where does it go?**  
The index.html page is more often not an actual, accessed page. It's accessed in the sense that you open it in your browser, but typically it will reroute you to a designated url. Such as, site.com/ sends you to the index, which
upon opening redirects you to site.com/home.

7) **Review: What are some of the best naming practices?**  
Assuming you mean filenames, it's best to keep page names/html files short and consistant. Not only does this speed up human access to particular pages (e.g., if they're not using hyperlinks, /home versus '/LandingPage' has a clear
choice), it can also make it easier to write overall navigation code even for a sidebar. Take a simple biography site for example. you've got your homepage, your biography, perhaps projects or prior experience, etc. That might be
contained to /home, /bio, and /experience.
If we're talking element names like for styling, I like to be as precise as possible if I'm naming things outside of the overarching style.css document. Lets say we've got the home page containing a flexbox with 2 containers. Left side
is a picture of me and underneat a list of experience, and to the right a biography. I may just name these HomeFlexLeft, or HomeFlexRight. These aren't observed by the end user, and let me know exactly what I'm tuning when I modify the
styling for the page.
