Download Link: https://assignmentchef.com/product/solved-cinf362-week-7-rwd-part-ii-and-usability-accessibility
<br>
<strong>Agenda</strong>

<ul>

 <li>Responsive Web Design Part II

  <ul>

   <li>More Tips</li>

   <li>Responsive Page Assignment</li>

  </ul></li>

 <li>Usability/Accessibility

  <ul>

   <li>What are they?</li>

   <li>Page Usability/Accessibility Evaluation</li>

  </ul></li>

 <li>HTML Quiz</li>

 <li>Next Week</li>

</ul>




<h2>Responsive Web Design Part II</h2>

<strong>More Tips</strong>

With RWD, our focus must be on the screen’s “real estate” which the area we are able to work with when displaying our content. Users will visit websites on any number of devices: smart phones, tablets, desktops, etc. It is important to take all these devices into account. However, we should <strong>never </strong>build our website for any specific device. The best thing to do is to build our website and then determine where to add breakpoints to ensure a smooth transition from larger screens to smaller ones, no matter the device.

There are two main approaches to RWD which are often expressed as “progressive enhancement” or “graceful degradation.” Progressively enhanced websites may be developed for mobile devices first and then higher resolutions are targeted after. This allows you to start small and then add features as larger screens can fit them. You might start with the core features and then add things like image carousels, modals, etc. for larger screens when the space becomes available. Graceful degradation is the opposite in that you start building for desktop devices first. As the screen gets smaller, you remove features and other things that aren’t entirely necessary for the design. This could be removing images, extra text, etc. so that your core features are more accessible for users.

There are other approaches to RWD but these two are some of the most prominent ones. For this course’s term project, we will most likely have users access our content from desktops. As such, it might be worthwhile to embrace graceful degradation for the project. However, the approach is entirely up to you and what you are comfortable with.

<u>Additional Reading</u>

<ul>

 <li><a href="https://thenextweb.com/dd/2015/10/19/10-rules-of-best-practice-for-responsive-design/">https://thenextweb.com/dd/2015/10/19/10-rules-of-best-practice-for-responsive-design/</a></li>

 <li><a href="https://uxtricks.design/blogs/ux-design/responsive-design/">https://uxtricks.design/blogs/ux-design/responsive-design/</a></li>

 <li><a href="https://neilpatel.com/blog/mobile-design-best-practices/">https://neilpatel.com/blog/mobile-design-best-practices/</a></li>

 <li><a href="https://medium.com/@JuliSudi/mobile-first-design-vs-desktop-first-design-vs-element-first-design-5d1015632a61">https://medium.com/@JuliSudi/mobile-first-design-vs-desktop-first-design-vs-element-first-design-5d1015632a61</a></li>

</ul>

<strong><u>If you haven’t done so already, please read the “Creating and Viewing our Web Pages.docx” file on Blackboard. You will not be able to submit anything for the assignment without completing that portion first. </u></strong>




<strong>Responsive Page Exercise 2</strong>

Download the “Responsive-Page-Exercise-2.zip” folder from Blackboard under the Lecture Notes for this week or in the Assignments folder. Inside of this zip folder, you’ll find an HTML file and a CSS folder with a stylesheet inside of it. Using these files, your task is to make the news-page.html page responsive down to 400px. This means that your page should work on screen resolutions as small as 400px (I will not check anything below this). You can approach this however you’d like and even change the underlying HTML tags. <strong>No content should be removed from the page though.</strong> You can change tags or alter the CSS, but all the text content and images should still be present in the HTML. If you choose to remove things with CSS, that is fine (display: none, etc.). There shouldn’t be a horizontal scrollbar present when I shrink the browser width while checking your assignment.




<u>Responsive Page Exercise 2 Tips</u>

<ul>

 <li>Make sure the correct meta tag is included (present in class example)</li>

 <li>Use percentages for widths</li>

 <li>Use the max-width property where appropriate (when used on images, it helps them scale down better)</li>

 <li>Look at what is floating on the screen</li>

 <li>Adjust font sizes, padding, or margins on elements so they fit better in smaller screen sizes</li>

 <li>Keep your media queries simple (max-width will probably be best here)</li>

 <li>Remove floats (float: none) so elements end up in one column (if that’s your goal)</li>

</ul>

<u> </u>

To receive credit for this, submit a link to your responsive page by <u>Wednesday, March 11<sup>th</sup> at midnight</u>. The assignment with be called Responsive Page Exercise 2 in the assignments folder. It will also be accessible through the Lecture Notes for this week.




<h2>Usability &amp; Accessibility</h2>

<strong>What are they?</strong>

These are concepts that are very important to the success of all websites on the internet. When we develop with usability and accessibility in mind, it enables users to get through our content easier which could potential result in higher visits/revenue. If these concepts aren’t integrated into our development process, there is a greater chance that users will be frustrated with our website and leave. Depending on what your website’s purpose is, there could also be legal ramifications. Although they are often used interchangeably, they have different meanings in the context of web design. I’ve borrowed some definitions from w3.org below and will expand on them with a metaphor using a hypothetical toy.

<strong>Accessibility</strong>: addresses discriminatory aspects related to equivalent user experience for people with disabilities. Web accessibility means that people with disabilities can equally perceive, understand, navigate, and interact with websites and tools. It also means that they can contribute equally without barriers.

<strong>Usability</strong>: is about designing products to be effective, efficient, and satisfying. Usability includes <em>user experience design</em>. This may include general aspects that impact everyone and do not disproportionally impact people with disabilities. Usability practice and research often does not sufficiently address the needs of people with disabilities.

If we have a toy that is in good condition and is in within our reach, we would say that it is both usable and accessible. If this toy was in poor shape but still within reach, it would be accessible but not usable. A toy that is not within reach (on top of a taller bookshelf) but in good condition would be usable but not accessible. A toy that isn’t within reach and in poor condition would be neither usable or accessible. In general, if something isn’t accessible, we would consider it to not be usable as well.

There are many ways to incorporate these ideals in our web pages and I’ve provided links below to expand on what I’ve written above. On Blackboard in the Resources &gt; PowerPoint Slides folder, I’ve included a PowerPoint file with some information. Also, there is a checklist in the folder with today’s Lecture Notes. These files along with the links below will give you a better idea of why they’re important and how we can implement them.

Here’s a list of basic things to do that will set you on the right track with usability/accessibility:

<ul>

 <li>Use alternative text with images</li>

 <li>Identify page language (lang attribute in html tag)</li>

 <li>Use HTML to convey meaning and structure (semantic tags)</li>

 <li>Use labels with forms</li>

 <li>Structure content appropriately</li>

 <li>Include appropriate roles for elements</li>

 <li>Make all interactive elements keyboad accessible</li>

 <li>Use a “skip to main” button</li>

 <li>Use easily identifiable and accurate links (“click here” isn’t descriptive)</li>

 <li>Ensure color contrast is high</li>

 <li>Don’t use flashing or blinking elements</li>

 <li>Don’t use HTML tables for layout</li>

 <li>Give users enough time to read content in slideshows or other interactive items</li>

</ul>




<u>Additional Reading</u>

<ul>

 <li><a href="https://www.w3.org/WAI/fundamentals/accessibility-usability-inclusion/">https://www.w3.org/WAI/fundamentals/accessibility-usability-inclusion/</a></li>

 <li><a href="https://www.usability.gov/what-and-why/user-experience.html">https://www.usability.gov/what-and-why/user-experience.html</a></li>

 <li><a href="https://www.usability.gov/how-to-and-tools/methods/writing-for-the-web.html">https://www.usability.gov/how-to-and-tools/methods/writing-for-the-web.html</a></li>

 <li><a href="https://www.usability.gov/what-and-why/visual-design.html">https://www.usability.gov/what-and-why/visual-design.html</a></li>

 <li><a href="https://www.nngroup.com/articles/usability-101-introduction-to-usability/">https://www.nngroup.com/articles/usability-101-introduction-to-usability/</a></li>

</ul>

<strong> </strong>

<strong>Page Usability/Accessibility Evaluation</strong>

Visit 3 websites of your choosing and evaluate their usability and accessibility based on the information provided above in addition to the files located on Blackboard. Is the website you’re looking at usable/accessible to you? Why or why not? Defend your evaluation with items mentioned above or below in a write up of at least two paragraphs (at least 5 sentences each) for each website, but feel free to write more. Specifically, I’d like you to consider some of the following ideas:

<ul>

 <li>Is the site easy to use?</li>

 <li>How is the information architecture?

  <ul>

   <li>Does a clearly established hierarchy exist?</li>

   <li>Can you tell where the main navigation is?

    <ul>

     <li>How do they handle their navigation on smaller screens?</li>

    </ul></li>

   <li>Can you use your keyboard to navigate the website? (try to press tab)</li>

   <li>Does the website work well on a mobile device?</li>

   <li>Is the color contrast high enough?</li>

   <li>Does it let you accomplish the tasks it says it will?</li>

   <li>Can you identify the website’s purpose from the homepage?</li>

  </ul></li>

</ul>

<u>Page Usability/Accessibility Evaluations Tips</u>

<ul>

 <li>Use websites that have a lot of content</li>

 <li>Make sure to mention principles or concepts mentioned in class notes or the articles provided</li>

 <li>Use various web tools to aid your evaluation

  <ul>

   <li><a href="https://webaim.org/resources/contrastchecker/">https://webaim.org/resources/contrastchecker/</a> (plug in color values)</li>

   <li><a href="https://wave.webaim.org/">https://wave.webaim.org/</a> (copy and paste link)</li>

   <li>Google has a built-in accessibility audit (inspect the page, go to the “Audits” tab all the way to the right. Uncheck everything except “Accessibility” and then click “Generate Report”</li>

  </ul></li>

 <li>Use complete sentences and avoid colloquialisms as this will be graded for grammar</li>

</ul>

If you aren’t sure where to start as far as websites go, you can use any of the ones listed below:

<ul>

 <li><a href="http://best-electronics-ca.com/">Atari Best Electronics</a></li>

 <li><a href="http://art.yale.edu/Home">Yale University School of Art</a></li>

 <li><a href="http://www.feedmusic.com/">Feed Music</a></li>

 <li><a href="https://www.cnn.com/">CNN </a></li>

 <li><a href="https://css-tricks.com/">CSS Tricks</a></li>

</ul>




To receive credit for this assignment, submit your write up to Blackboard by <u>Wednesday, March 11<sup>th</sup> at midnight</u>. The submission area will be titled “Page Usability &amp; Accessibility Evaluations” and will be in the Assignments folder in addition to this week’s Lecture Notes. You can submit it as a word document, text file, or even as a comment.