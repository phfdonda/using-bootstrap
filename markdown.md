# INDEX

## MOBILE




## DESKTOP (991px and up)

### 1.0 - NAV-BAR:

Called **navbar**. Big and red. Logo centered. Date to the left. Sign In and Subscribe to the right. Links below. In scroll down, position stick to the top.

#### 1.1 - Navigation:

##### Links: 
11 links. "U.S.", "World", "Business", "Tech & Science", "Culture", "Newsgeek", "Sports", "Health", "The Debate", "Vantage", "Weather". They are called **"nav-link"**.

Expected behavior: on hover, changes color to red; on click, opens respective link in the same tab. On scroll down, the links disappear, and go to a hamburger menu on the right, on the right of Subscribe.

#### 1.2 - Search bar.

Expected behavior: on click, expands bar and replaces all links for the search bar. Caret on the far left. On scroll down it disappears.

### 2.0 - MAIN (main):

Three vertical columns. Left one is "Featured Stories"(**featured-column**). Middle one (**top-and-more-column**) . The third column (**opinion-and-latest-column**) At the end of the third column we have a CtA to subscribe (**cta-subscribe**).

#### 2.1 - Columns

##### First column - "featured-column"

It takes at this screen-size 41% of the width of the page. It contains only one subsection, **featured-stories-subsec**.

##### Second column - "top-and-more-column"

It takes at this screen-size 59% of the width of the page. Has three sub-sections inside, in this order: "Top Story" (**top-stories-subsec**), "Culture & Travel" (**culture-subsec**), "More Stories" (**more-stories-subsec**)

##### Third column - "opinion-and-latest-column"

It takes at this screen-size 29% of the width of the page. Has two sub-sections, in this order: "Opinion" (**opinion-subsec**) and "Latest News" (**latest-news-subsec**).

#### 2.1 - Articles

Are composed of: Image (**article-img**), Title (**article-title**) and Subtitle(**article-subtitle**). In some cases only the image and title will be displayed. We'll call the full articles, and the incomplete "half-article".

##### Image:

Square. In "full-article", the inside category name (**in-categ-name**) is on the left and bottom, in red. In "half-article" the category name is gone.

##### Section name:

Font is (_"Roboto Condensed",sans-serif"_), color dark grey (_#333_)

##### Title:

Font same as Section name, color black, capitalized. We have two different hover effects, so we'll create two classes, one for underline on hover (**und-hover**), and another for red on hover (**red-hover**).

##### Subtitle:

Font is (_Arial,Helvetica,sans-serif_), color dark grey (_#333_).

##### Links:

On image and title.

#### 2.2 - Featured Stories

It contains 4 full-articles.

#### 2.3 - Top Story

It contains only 1 full-article.

#### 2.4 - Culture & Travel

It has a different style. It contains 4 full-articles with some properties overriden. Background-color is light blue(_#f4f5f7_), Title font is (_"Lora, serif"_), subtitle font is (_"Helvetica Neue", Helvetica, Arial, sans-serif;_) and font color is grey (_rgb(39, 39, 39)_); category name is show below subtitle, in a darker blue (_#c2d4d7_), black font. Category name goes to the bottom, after the subtitle. We'll call these articles **cult-article**.

##### Link:

On image, title and category name.

##### Expected behavior:

Category name, on hover, changes background-color to black and text becomes light blue (_#c2d4d7_).

#### 2.2 - More Stories

It has 11 full-articles. Between each of them there's a **divisor** of 1px and color light grey (_#ddd_).

##### Image:

Float to the left.

##### Title and subtitle:

On top of each other.

#### 2.2 - Opinion

We have six **opinion**, a different type of "half-article". It has a round image, and there's the **author** text on the bottom of each.

##### Link:

On the image and title.

##### Image:

Float to the left. Round.

##### Author:

Same font as title, uppercase, color grey (_#555_).

#### 2.3 - Latest News:

We have seven 

### ***** FINAL COMMENTS *****

I have added the "@" symbol with the sections for easy navigation. To quickly navigate the code, search for the respective section you want, like header or small-footer, preceded by an @, like this: @example.
