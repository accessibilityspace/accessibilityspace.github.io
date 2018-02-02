---
layout: post
title:  "Summary from WebAIM screen reader survey"
categories: accessibility WebAIM a11y screen-reader survey
---
<section class="post-section">
    <h2 class="post-section-title">The 2017 edition is out <a href="https://webaim.org/projects/screenreadersurvey7/" target="_blank">now</a></h2>
    <p class="post-paragraph">This is the 7th edition of the survey that started in 2009.</p>
    <div class="post-fact-container">
        <p tabindex="-1" aria-label="Aproximately 1792" class="post-fact">1792</p>
        <em tabindex="-1" aria-label="is the number of participants this year">Is the number of participants this year</em>
    </div>
    <p class="post-paragraph">
        The most surveyed region was North America with <strong class="post-paragraph-fact">60%</strong> participants followed by <strong class="post-paragraph-fact">23%</strong> participants from Europe/UK and <strong class="post-paragraph-fact">8.5%</strong> participants from Asia.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">Primary screen reader</h2>
    <div class="post-fact-container">
        <p class="post-fact">46.6%</p>
        <em>Participant percentage who use <a href="http://www.freedomscientific.com/Products/Blindness/JAWS" target="_blank">JAWS</a> as their main screen reader</em>
    </div>
    <p class="post-paragraph">
        Followed somewhat closely by <a href="https://www.nvaccess.org/" target="_blank">NVDA</a> with a <strong class="post-paragraph-fact">31.9%</strong> of participants and <a href="https://www.apple.com/lae/accessibility/mac/vision/" target="_blank">VoiceOver</a> with <strong class="post-paragraph-fact">11.7%</strong>.
    </p>
    <p class="post-paragraph">
        However, this is <em>only</em> the main screen reader surveyed users use. In my opinion, the next stats help grasping the big picture better.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">So... which screen readers do they commonly use?</h2>
     <div class="post-fact-container">
        <p class="post-fact">66%</p>
        <em>Participant percentage who use <a href="http://www.freedomscientific.com/Products/Blindness/JAWS" target="_blank">JAWS</a> commonly</em>
    </div>
    <div class="post-fact-container">
        <p class="post-fact">64.9%</p>
        <em>Participant percentage who use <a href="https://www.nvaccess.org/" target="_blank">NVDA</a> commonly</em>
    </div>
    <p class="post-paragraph">
        Here we can see the clear tie there is between these two in terms of usage.
    </p>
    <div class="post-fact-container">
        <p class="post-fact post-fact-alternate-color">39.6%</p>
        <em>Participant percentage who use <a href="https://www.apple.com/lae/accessibility/mac/vision/" target="_blank">VoiceOver</a> commonly</em>
    </div>
    <p class="post-paragraph">
        This seems to point to the fact that VoiceOver is used a lot as a secondary screen reader. It's also relevant to mention that <strong class="post-paragraph-fact">68%</strong> of the respondents use more than one screen reader.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">Browsers</h2>
    <p class="post-paragraph">
        When it comes to screen readers though, it's not only a matter of the tool you choose. It is also important under what operating system it is running and what web browser it's being used with. Next, we can see which are the most commonly found combinations.
    </p>
    <div class="post-fact-container">
        <p class="post-fact">41%</p>
        <em>Is the percentage of users who use <a href="https://www.mozilla.org/en-US/firefox/new/" target="_blank">Firefox</a> together with their most common screen reader</em>
    </div>
    <p class="post-paragraph">
        The other top contestants in this category were: 
    </p>
    <ol class="post-list">
        <li class="post-list-item"><a href="https://en.wikipedia.org/wiki/Internet_Explorer_11" target="_blank">Internet Explorer 11</a> with a <strong class="post-paragraph-fact">23.3%</strong></li>
        <li class="post-list-item"><a href="https://www.google.com/chrome/browser/desktop/index.html" target="_blank">Chrome</a> with a <strong class="post-paragraph-fact">15.5%</strong></li>
        <li class="post-list-item">and <a href="https://www.apple.com/safari/" target="_blank">Safari</a> (<strong class="post-paragraph-fact">10.5%</strong>)</li>
    </ol>
    <p class="post-paragraph">
        So now that we know what tools are being used, let's see what are the preferred ways to navigate and discover the content of a website.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">Finding Information</h2>
    <p class="post-paragraph">
        How screen reader users approach and navigate lengthy websites is a topic that I was especially interested in. 
    </p>
    <p class="post-paragraph">
        Given the nature of web accessibility, where different screen readers convey the same structures in slightly different ways, sometimes it is more important to craft an experience that provides extra context.
    </p>
    <p class="post-paragraph">Sometimes, that can turn out to be as important as having all the items checked in the accessibility auditing tool of choice.
    </p>
    <p class="post-paragraph">
        But don't forget those either :)
    </p>
    <div class="post-fact-container">
        <p class="post-fact">67.5%</p>
        <em>Participant percentage who navigates through the headings of the page</em>
    </div>
    <p class="post-paragraph">
        It is clearly the preferred option when it comes to moving through the content.
    </p>
    <p class="post-paragraph">
        "Using the find function" follows with a discrete <strong class="post-paragraph-fact">14.4%</strong>. Users who prefer going through links take a <strong class="post-paragraph-fact">6.8%</strong> of the total and navigating through landmark/regions has a <strong class="post-paragraph-fact">3.9%</strong>. The rest prefer to read through the page accounting to a quite small <strong class="post-paragraph-fact">7.3%</strong>.
    </p>
    <p class="post-paragraph">
        That would tell us to test taking the approach of <em>going through headers</em> when manually testing the usability and accessibility of a site. Try to adapt the site to achieve an understandable experience through proper markup if explored in this way.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">Skip links</h2>
    <p class="post-paragraph">
        Another topic that I recently looked into is having a skip link to the main content of the page. The question of the survey was about how often respondents use a "skip to main content" or "skip navigation" link when it is available on a page.
    </p>
    <p class="post-paragraph">
        There's no choice that got a strong representation here. If we order the options by most usage to least we get two top ones: "always use them when available" with a <strong class="post-paragraph-fact">15.8%</strong> and "often use them" with <strong class="post-paragraph-fact">16.4%</strong>. These two account to a third of the total which is notable. There's almost another third taken by the middle option, "sometimes", which is also the most common option with a <strong class="post-paragraph-fact">27.8%</strong>.</p>
    <p class="post-paragraph"> The two options that lay at the bottom of the results are "seldom" and "never use them" with <strong class="post-paragraph-fact">21.6%</strong> and <strong class="post-paragraph-fact">18.4%</strong> respectively.
    </p>
</section>
<section class="post-section">
    <h2 class="post-section-title">There is more than this</h2>
    <p class="post-paragraph">
        If you still want to know more about how to build your markup or app to be accessible and usable, I totally recommend you to check the <a href="https://webaim.org/projects/screenreadersurvey7/" target="_blank">original survey from WebAIM</a>.
    </p> 
    <p class="post-paragraph">
        It contains many more facts and further detail. I honestly believe it to be a very valuable source of information when trying to grow your understanding of how to implement web accessibility in a way that actually helps people :).
    </p>
    <p class="post-paragraph"> 
        Please ping me on <a href="https://twitter.com/j2thekay" target="_blank">Twitter</a> if you have any comments or just liked this!
    </p>
</section>