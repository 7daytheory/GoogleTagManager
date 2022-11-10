# Google Tag Manager
## Setting up Google Tag Manager with a file
<h3>Termninology</h3><br />
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

## Clarifying that GTM and GA4 are connected
<p>
In GTM - Click preview and enter in the URL that you set up with GTM tags<br />
When it loads, you will see a popup that will confirm if it's set up correctly<br />
In the tag manager, you will also see that is connected and a new workspace is added - under
</p>

## Viewing information on GA4
<p>
Once you have confirmed that you have set everything up correctly, go to your Analytics page. Under configure > DebugView > you will be able to see lots of information like session_id , page_location, page_referer, scroll, title etc.
</p>

## Versions and/or making updates live
<p>
Once you have tested everything using publish and have found the tags are working as expected. Click the "Submit" button and <strong>Label</strong> your update. Once completed you will see the new live version in the versions tag of the tag manager.<br />
<italic>
You have published and there is an error (oh no!) : You can go to the version tab and go back to a version that you know was working properly. Click on that version and click publish - that version will now be live. * That's why labelling is so important!
</italic>
</p>
