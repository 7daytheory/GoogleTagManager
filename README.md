# Google Tag Manager
## Setting up Google Tag Manager with a file
<h3>Termninology<h3><br />
<strong>3 Main components: Tags, Triggers and Variables</strong> <br />
<p>Tag: Tracking code implemented on the site (ex: Event tag, Google ads conversion code, google analytics page view etc<br />
Triggers: Conditions when you want your tags to fire(ex: User signing up for newsletter. page view, btn click etc)<br />
Variables: Data points that can be used in tags or triggers</p>

<h3>When to use each?</h3>
<p>Tags - Track a conversion, implementing a chat widget, tracking a page view to send to google anayltics<br />
Triggers -When a form is submitted, a button is clicked - Triggers <br />
Variable - Fire your tag on page view, or specific page view - variable<br /></p>

<h3>Specific Examples (Google ads conversion tag</h3>
<p><bold>Tags</bold> are the form and the <strong>Trigger</strong> gets fired when it's completed is 'triggered' once completed on the Thank you page<br />
<strong>Variable</strong> can be send from the tag to the trigger so it can receive a value. Perhaps a cost so it can show that value on the thank you page</p>

## Setting up Google Tag Manager / Google analytics
<p>
Create your Tag Manager account as well as a Google Analytics accounts. <br />
Create a data stream in Google Analytics and fill out the prompted form <br />
<bold>
Make sure to save the Measurement ID - as it will be used with GTM
</bold><br />
Create a new tag with Google Tag Manager. Lots of tag options including 3rd party tags but in this example I will be using G4A Config<br />
Enter your measurement ID <br />
Setup triggering - for now it will be all pages
</p>
<h3>Google Chrome - Tag Assistant Companion</h3>
<p>
URl : https://chrome.google.com/webstore/detail/tag-assistant-companion/jmekfmbnaedfebfnmakmokmlfpblbfdm/related?hl=en
</p>
