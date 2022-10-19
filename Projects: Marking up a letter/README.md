<h1> Project brief </h1>

For this project, your task is to mark up a letter that needs to be hosted on a university intranet. The letter is a response from a research fellow to a prospective PhD student concerning their application to the university.

Skills learned:
<ul>
<li>!DOCTYPE, lang, meta tags, utf-8, author, link css (initial setup)</li>
<li>Using semantic heading</li>
<li>Unordered list and ordered list</li>
<li>Description lists</li>
<li>&lt;address&gt; element</li>
<li>&lt;pre&gt; element</li>
<li>Markup appropriate words with strong and emphasis</li>
<li>Semantically machine-readable dates with &lt;time&gt;</li>
<li>&lt;abbr&gt; element for abbreviations and acronyms</li> 
<li>Subscript and superscript on text</li>
<li>Create hyperlinks</li>
<li>Good pratices on link names</li>  
<li>&lt;cite&gt; element for quotes</li>
</ul>

<h2> Requirements: </h2>
<h3> Block/structural semantics </h3>
<ul>
<li>Use appropriate document structure including doctype, and <html>, <head> and <body> elements.</li>
<li>In general, the letter should be marked up as an organization of headings and paragraphs, with the following exception. There is one top level heading (the "Re:" line) and three second level headings.</li>
<li>Use an appropriate list type to mark up the semester start dates, study subjects, and exotic dances.</li>
<li>Put the two addresses inside <address> elements. Each line of the address should sit on a new line, but not be in a new paragraph.</li>
</ul>

<h3>Inline semantics</h3>
<ul>
<li>The names of the sender and receiver (and Tel and Email) should be marked up with strong importance.</li>
<li>The four dates in the document should have appropriate elements containing machine-readable dates.</li>
<li>The first address and first date in the letter should have a class attribute value of sender-column. The CSS you'll add later will cause these to be right aligned, as it should be in the case in a classic letter layout.</li>
<li>Mark up the following five acronyms/abbreviations in the main text of the letter — "PhD," "HTML," "CSS," "BC," and "Esq." — to provide expansions of each one.</li>
<li>The six sub/superscripts should be marked up appropriately — in the chemical formulae, and the numbers 103 and 104 (they should be 10 to the power of 3 and 4, respectively).</li>
<li>Try to mark up at least two appropriate words in the text with strong importance/emphasis.</li>
<li>There are two places where the letter should have a hyperlink. Add appropriate links with titles. For the location that the links point to, you may use http://example.com as the URL.</li>
<li>Mark up the university motto quote and citation with appropriate elements.</li>
</ul>

<h3>Hints and tips</h3>
<ul>
<li>Use the W3C HTML validator to validate your HTML. Award yourself bonus points if it validates.</li>
<li>You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside an HTML element.</li>
</ul>



Dr. Eleanor Gaye
Awesome Science faculty
University of Awesome
Bobtown, CA 99999,
USA
Tel: 123-456-7890
Email: no_reply@example.com

20 January 2016

Miss Eileen Dover
4321 Cliff Top Edge
Dover, CT9 XXX
UK


Re: Eileen Dover university application

Dear Eileen,

Thank you for your recent application to join us at the University of Awesome's science faculty to study as part of your PhD next year. I will answer your questions one by one, in the following sections.

Starting dates

We are happy to accommodate you starting your study with us at any time, however it would suit us better if you could start at the beginning of a semester; the start dates for each one are as follows:

First semester: 9 September 2016
Second semester: 15 January 2017
Third semester: 2 May 2017

Please let me know if this is ok, and if so which start date you would prefer.

You can find more information about important university dates on our website.


Subjects of study

At the Awesome Science Faculty, we have a pretty open-minded research facility — as long as the subjects fall somewhere in the realm of science and technology. You seem like an intelligent, dedicated researcher, and just the kind of person we'd like to have on our team. Saying that, of the ideas you submitted we were most intrigued by are as follows, in order of priority:

Turning H2O into wine, and the health benefits of Resveratrol (C14H12O3.)
Measuring the effect on performance of funk bassplayers at temperatures exceeding 30°C (86°F), when the audience size exponentially increases (effect of 3 × 103 increasing to 3 × 104.)
HTML and CSS constructs for representing musical scores.

So please can you provide more information on each of these subjects, including how long you'd expect the research to take, required staff and other resources, and anything else you think we'd need to know? Thanks.


Exotic dance moves

Yes, you are right! As part of my post-doctorate work, I did study exotic tribal dances. To answer your question, my favourite dances are as follows, with definitions:

Polynesian chicken dance
A little known but very influential dance dating back as far as 300BC, a whole village would dance around in a circle like chickens, to encourage their livestock to be "fruitful".
Icelandic brownian shuffle
Before the Icelanders developed fire as a means of getting warm, they used to practice this dance, which involved huddling close together in a circle on the floor, and shuffling their bodies around in imperceptibly tiny, very rapid movements. One of my fellow students used to say that he thought this dance inspired modern styles such as Twerking.
Arctic robot dance
An interesting example of historic misinformation, English explorers in the 1960s believed to have discovered a new dance style characterized by "robotic", stilted movements, being practiced by inhabitants of Northern Alaska and Canada. Later on however it was discovered that they were just moving like this because they were really cold.

For more of my research, see my exotic dance research page.

Yours sincerely,
Dr Eleanor Gaye

University of Awesome motto: "Be awesome to each other." -- The memoirs of Bill S Preston, Esq


<h3>Example</h3>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter/letter-update.png"> Example </a>

Validator:
https://validator.w3.org/  <br><hr>
  
<strong>See it below</strong><br>
<a href="https://htmlpreview.github.io/?"> Render </a><br>

<strong>MDN skill tests</strong><br>
<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter"> Link to this test </a>

<strong>Assessment on mozilla discourse</strong><br>
<a href=" ">Link to Assessment </a>
