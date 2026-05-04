### **1.<nav>**

##### &#x20;      

##### This element is used to hold the main navigation links of a website like menus and breadcrumbs. Screen readers will announce it as a "navigation" area. You can use more than one nav on a page, but give each one an aria-label so they can be told apart. Do not use it for every group of links, only for the important ones.



##### **What it does:** 

##### It groups the main navigation links of a website together and tells the browser that this area is for navigation.



##### **When to use:** 

##### Use it when you have a site menu, breadcrumb links, or pagination links. Use it only for major navigation, not for every small group of links on the page.

&#x20;      

### **2.<main>** 

&#x20; 

##### This element holds the main content of the page, the part that changes from page to page. You can only have one main element per page. Things like header and footer should not go inside it. Screen readers announce it as the "main" area of the page. 

##### 

##### **What it does:**

##### It wraps the main and unique content of the page. It tells the browser that this is the most important part of the page.

##### 

##### **When to use:** 

##### Use it once per page to hold the content that is different on every page. Do not put your header, footer, or sidebar inside it. 

##### 

### **3.<header>** 



##### This element holds the opening content of a page or section. When used at the top of a page it usually contains the logo and navigation. When used inside an article or section it holds the title and author name. At page level it is treated as a "banner" by screen readers. Inside an article it has no special role.

##### 

##### 

##### **What it does:** 

##### It holds the opening or introductory content of a page or a section. At page level it acts as a banner area.

##### 

##### **When to use:** 

##### Use it at the top of the page to hold the logo, site name, and navigation. Also use it inside an article or section to hold the title, author name, and date of that content.

##### 

### **4.<footer>**

##### 

##### This element holds the closing content of a page or section. At page level it usually contains copyright and legal links and screen readers treat it as "contentinfo". Inside an article it can hold tags, author bio, or related links and has no special role there.

##### 

##### 

##### **What it does:** 

##### It holds the closing content of a page or a section. At page level it acts as the content info area.

##### 

##### **When to use:** 

##### Use it at the bottom of the page to hold copyright text, legal links, and contact information. Also use it inside an article to hold tags, related links, or author details.





### **5.<section>**

##### 

##### This element is used to group content that belongs together under one topic. It should always have a heading inside it. If there is no heading, just use a div instead. It is not for styling purposes, only for grouping meaningful content.

##### 

##### 

##### **What it does:** 

##### It groups content that belongs together under one topic or theme. It adds structure to the page like chapters in a book.

##### 

##### **When to use:** 

##### Use it when you want to divide your page into meaningful parts like a features section, a pricing section, or a testimonials section. Always put a heading inside it. If there is no heading, use a div instead.

##### 

### **6.<article>**



##### This element is used for content that can stand alone and make sense by itself, like a blog post, a news story, a comment, or a product card. A simple way to check is to ask yourself if this content could be shared or published on its own. If yes, use article. You can put one article inside another, like comments inside a blog post.

##### 

##### **What it does:** 

##### It marks content that is complete and can stand alone by itself without needing the rest of the page to make sense.

##### 

##### **When to use:** 

##### Use it for a blog post, a news article, a product card, a comment, or any content that could be shared or published independently. Ask yourself if the content makes sense on its own. If yes, use article.

##### 

### **7.<aside>**





##### This element is used for content that is related to the main content but not a necessary part of it. Examples are sidebars, pull quotes, and related post links. If you remove it, the main content should still make complete sense. Screen readers treat it as a "complementary" area.

##### 

##### **What it does:** 

##### It holds content that is related to the main content but is not a necessary part of it. It is extra or supporting information.

##### 

##### **When to use:** 

##### Use it for sidebars, pull quotes, related post links, advertisements, or author bios that sit beside the main content. If you remove it, the main content should still be fully understandable.

##### 

### **8.<figure>**





##### This element is used to wrap media like images, charts, code blocks, or tables along with a caption. The caption is written using figcaption and must be placed as the first or last item inside figure. The image and caption are connected together so they can be moved anywhere in the page without losing meaning.

##### 

##### 

##### **What it does:** 

##### It wraps media content like an image, chart, diagram, or code block along with its caption. It connects the media and the caption together as one unit.

##### 

##### **When to use:** 

##### Use it whenever you have an image or media that needs a caption below or above it. Place the caption using figcaption as the first or last child inside figure. Do not use it for images that are just decorative.

##### 

### 

### **9.<time>**



##### This element is used to show dates and times on a page. The datetime attribute holds the date in a format that machines can read, while the text you write inside can be in any readable format. Search engines use this to understand when an article was published or when an event happens.

##### 

##### **What it does:** 

##### It marks a date, time, or duration on the page. The datetime attribute holds the value in a machine readable format so browsers and search engines can understand it.

##### 

##### **When to use:** 

##### Use it when showing a publish date on a blog post, an event date, or a time duration. Write the readable text inside the tag and put the machine readable value in the datetime attribute.

##### 

### **10.<mark>**  



##### This element is used to highlight text that is important in the current context, like when you search for a word and it gets highlighted in the results. It is not for making text bold or italic. By default the browser gives it a yellow background. Do not use it just for styling, use it only when the highlighted text has a specific reason to stand out.   



##### **What it does:** 

##### It highlights a piece of text to show that it is relevant or important in the current context. Browsers give it a yellow background by default.

##### 

##### **When to use:** 

##### Use it to highlight search result matches or to mark the key part of a quoted text. Do not use it for general bold or italic styling. Use it only when the highlighted text has a specific reason to stand out in that context.            

