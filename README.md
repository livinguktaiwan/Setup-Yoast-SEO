# Setup-Yoast-SEO

<h1>The first step to increase your Wordpress site's traffic using Yoast SEO and Google Search Console</h1>

<center>http://livinguktaiwan.com/wp-content/uploads/2018/09/by-the-beach.jpg</center> <br/>The other day @catwomanteresa asked me about submitting a blog's sitemap to Google, and how to verify your blog before you do that.  I knew this was something to do with Search Engine Optimisation (SEO) which helps to increase your site's traffic. However I always found this area to be so complicated and confusing that I reckon you need a PhD to understand it.  As such during my 2 years of blogging, I never paid much attention to it.

Her question aroused my interest in the subject, and with the help of my other half who is much more inquisitive than me, we started to do a bit of digging around.  Here's a tutorial on my findings that I want to share with you

<h2>What Will I Learn?</h2>

<ul>
    <li>how verify your site with Google</li>
    <li>how optimise your site and generate a sitemap</li>
    <li>how to submit your site's sitemap to Google</li>
</ul>

<h2>Requirements</h2>

<ul>
    <li>a self hosted Wordpress blog site</li>
    <li>a Google account</li>
</ul>

<h2>Difficulty</h2>

<ul>
    <li>This is an easy level tutorial with screenshots to guide you</li>
</ul>

<h2>Tutorial Contents</h2>

<ul>
    <li>verify your site with Google</li>
    <li>optimise your site and generate a sitemap</li>
    <li>submit your site's sitemap to Google</li>
</ul>


<h2>Repository</h2>
https://github.com/Yoast/wordpress-seo

<h2>Proof of Work</h2>
My proof of work can be found in my Github repository below
https://github.com/livinguktaiwan/Setup-Yoast-SEO



<hr />

<h2>WHAT IS SEO AND HOW CAN YOU INCREASE YOUR SITE'S TRAFFIC</h2>

This is my very simple interpretation of the first part of the above question.  I am sure you can find a much better description, but here you go.

To put very simply,  SEO is about how to increase your site's traffic.  You can use various strategies to do this so it ranks higher when people search for a particular word or phrase relevant to your site.  When someone Google searches something, Google will crawl through all the sites for the relevant word or phrase, and include them in the search result.  SEO is about how Google does this, and how you can optimise your site to make it easier for Google to find your content. Sounds simple? It's not really, but let's keep it like this for the time being.

The rest of this tutorial is some initial steps to help you start your journey to increase your site's traffic in the long run.

<h2>VERIFYING YOUR SITE WITH GOOGLE</h2>

If order to increase your chances of Google crawling  your site from the millions out there, you have to get onto their radar first.  The first thing to do is verify your site.  This means logging into your Google account to confirm that your site is owned and managed by you.  Here's how you do it.

<strong>ONE</strong> : Go to you website and download a plug-in called<a href="https://yoast.com/wordpress/plugins/seo/" target="_blank" rel="noopener"><em> Yoast</em>.</a>  It's free.  We'll come back to Yoast in a minute.<center><img class="aligncenter size-large wp-image-11877" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-1024x576.png" alt="" width="640" height="360" /></center><br/>

&nbsp;

<strong>TWO</strong> : Search for<a href="https://www.google.com/webmasters/tools/home" target="_blank" rel="noopener"><em> Google Search Console</em></a>, and you will see a screen like the one below, but with no sitename.  If you have multiple Google accounts, make sure you're logged into the one  you want to use to 'own' your site. Click on the red button called 'Add a Property' and type in your site name.  Make sure its the external one,  and not the internal one when you're logged on and working to write your post.  Your screen should look like this now.

<center><img class="aligncenter size-large wp-image-11878" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-32-1024x326.png" alt="" width="640" height="204" /></center><br/>

&nbsp;
<p><strong>THREE</strong> : Click on 'Verify this property', it will open up a new window. <center><img class="aligncenter size-full wp-image-11879" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-33.png" alt="" width="853" height="768" /></center><br/></p>

&nbsp;

<strong>FOUR</strong> : Click on the Alternate methods tab.  Click on HTML tag, then click on 'Show me an example', highlight the meta tag ie verification code and copy that.  That's the code in between the " " which I've highlighted below.  Each code is unique but I've blurred over mine so it doesn't confuse people.  Keep this page open, don't close it!!!

<center><img class="aligncenter size-large wp-image-11882" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-16_LI-1024x576.jpg" alt="" width="640" height="360" /></center><br/>

&nbsp;

<strong>FIVE</strong> :  Remember the Yoast plug-in I asked you to download earlier on?  Now go to you site and open the plug-in.  Go to General, and Webmaster Tools.  Paste the verification code in the Google Verification code box.   Click save. Note here's a link to take you to the Google Search Console.  So if you're still reading and haven't actually started the verification process, you can start Step 2 from here.  You can also verify you site with other search engines here.  I haven't done it, but I imagine the process is pretty much the same.  <center><img class="aligncenter size-full wp-image-11884" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-19_LI.jpg" alt="" width="814" height="740" /></center><br/>

&nbsp;

<strong>SIX</strong> : Go back to the Google Search Console page in step four.  Now click on "Verify" at the bottom of the page.  You should get confirmation that your site is now verified to be owned by your chosen Google account.  If you go back to the Search Console webmaster homepage you should now see your blog site there.  Your site is verified with Google now.<center><img class="aligncenter size-large wp-image-11885" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-03-3-1024x313.png" alt="" width="640" height="196" /></center><br/>

&nbsp;

<h2>OPTIMISE YOUR SITE AND GENERATE A SITEMAP</h2>

Now you have confirmed with Google that you own your site, you can generate your blog's sitemap. The sitemap is a file containing all your post URLs and images for your blog site.  This makes it easier for Google to crawl through your site and see if it has any key words or phrases that people have Google searched for.  Therefore it potentially increases the chances of your site being included in a search, and hence increase your site's traffic.

You can generate your sitemap using the Google XML Sitemaps plug-in, or other websies, or you can use Yoast to do it. This tutorial uses Yoast.  But before we do that, we need to configure your site first so Yoast knows how to help you optimise your site.

<strong>ONE</strong>: Go to the Yoast plug in on your site.  Click on Dashboard, and open the SEO Configuration Wizard.

<center><img class="aligncenter size-large wp-image-11892" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-34-1024x673.png" alt="" width="640" height="421" /></center><br/>

&nbsp;

<strong>TWO  : </strong>Follow the  12 steps to configure your site, they're very straight forward so I'm not going to go through all 12 screens here.

<center><img class="aligncenter size-large wp-image-11893" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-4-1024x576.png" alt="" width="640" height="360" /></center><br/>

&nbsp;

<strong>THREE</strong> : The only screen I want to shout out is step 8.  Here, it will ask you to authenticate your site with Google. Click on the "Get Google Authorisation Code" panel and there will be a pop up window asking you to select you Google account.  Make sure you select the one you used to verify your site.  Click on that, then click "allow" at the bottom right of the pop up window, and you will see an authentication code.  Copy that.  I forgot to take a screen shot of the authentication code, so can't show you that.  Enter this in step 8 of the Yoast wizard setup.  Continue to finish the rest of the setup.

<center><img class="aligncenter size-large wp-image-11894" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-13_LI-1024x576.jpg" alt="" width="640" height="360" /></center><br/>

&nbsp;

<strong>FOUR</strong>: Now go to the Features tab in Yoast.  You will see some settings here, make sure XML sitemaps is enabled

<center><img class="aligncenter wp-image-11899 size-full" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-03-7_LI.jpg" alt="" width="822" height="768" /></center><br/>

&nbsp;

&nbsp;

<strong>FIVE</strong> : Click on the ? next to it, and then click on "See the XML sitemap".  It will open up a new window.  These are you sitemaps and contains all the urls for your blog posts and photos.

<center><img class="aligncenter wp-image-11904 size-full" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-03-9_LI.jpg" alt="" width="870" height="730" /></center><br/>

&nbsp;

<center><img class="aligncenter wp-image-11898 size-full" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-05-3.png" alt="" width="851" height="391" /></center><br/>

<h3>SUBMIT YOUR SITE'S SITEMAP TO GOOGLE</h3>

Now you have generated your sitemap, you want to submit it to Google so they can index your site's URLs.  This make it easier for their bots to crawl through your site when people do a Google search, and potentially increase  your site's traffic.

<strong>ONE</strong> : Go back to you Google Search Console.  Go to Crawl, and sitemaps.  Click on the red box on the right which says "Add/Test Sitemap".  Since you've already verified you blog you will see a pop up window with your blog name.  Enter the latter part of your sitemap file names that were just generated and click submit.

<center><img class="aligncenter size-medium wp-image-11905" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-22-1024x576.png" alt="" width="1024" height="576" /></center><br/>

&nbsp;

<strong>TWO</strong> :  Adding the top level "sitemap_index.xml"  should pull in the other four sitemaps, but my PC was rather slow and nothing happened for a while so I continued to add the other sitemaps one by one.

<center><img class="aligncenter size-medium wp-image-11915" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-27-1024x576.png" alt="" width="1024" height="576" /></center><br/>

All the sitemaps are submitted to Google now, but the status is still pending.  This means Google has yet to start crawling through all the URLs to understand your site.  This process can take anything from 4 days to 4 weeks.

<center><img class="aligncenter size-medium wp-image-11914" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-02-24-1024x576.png" alt="" width="1024" height="576" /></center><br/>

I submitted my sitemap on 2nd September and by 7th September it had all been indexed, so in my case it was much quicker.

<center><img class="aligncenter size-medium wp-image-11916" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-08-1-1024x576.png" alt="" width="1024" height="576" /></center><br/>

I just want to mention the Google Search Console interface.  In the four days since I took the screenshots above in this section,  Google have released the <a href="https://search.google.com/search-console/welcome" target="_blank" rel="noopener">new Google Search Console</a>.  The new version has been tested for a year and it has just come out of beta pretty much just after I took my screenshots.  The screenshot below is the status of my sitemap compared to the old version above this paragraph.

<center><img class="aligncenter size-medium wp-image-11918" src="http://livinguktaiwan.com/wp-content/uploads/2018/09/2018-09-08-1024x576.png" alt="" width="1024" height="576" /></center><br/>

&nbsp;

If you are looking to increase your site's traffic, this is just the first few steps of a very long journey.  Completing these steps are just the first baby steps, so <strong><em>don't expect your site traffic to grow overnight</em> </strong>by just doing this.   There is much much more to the whole SEO topic to increase your site's traffic, but hopefully this will set you off.

I hope this has been useful and please do let me know what you think about this tutorial.  Happy blogging! <br /><center><hr/><em>Posted from my blog with <a href='https://wordpress.org/plugins/steempress/'>SteemPress</a> : http://livinguktaiwan.com/the-first-step-to-increase-your-sites-traffic/ </em><hr/></center>
