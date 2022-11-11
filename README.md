# Google Tag Manager
## Setting up Google Tag Manager with a file
<h2>A lot of this is done on GTM and GA4 - so I will be documenting non-code steps in the README file.</h2>
<h3>Terminology</h3><br />
<strong>3 Main components: Tags, Triggers and Variables</strong> <br />
<p>Tag: Tracking code implemented on the site (ex: Event tag, Google ads conversion code, google analytics page view etc <br />
Triggers: Conditions when you want your tags to fire(ex: User signing up for newsletter. page view, button click etc)<br />
Variables: Data points that can be used in tags or triggers</p>

<h3>When to use each?</h3>
<p>Tags - Track a conversion, implementing a chat widget, tracking a page view to send to google analytics <br />
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

### Fixing a version with an error
<p>
Once you have gone back to a previous version to fix an issue. You can go back to some of the overview above and publish(not live) the version that has an issue. Once you have fixed the issue  "Submit" and add a note like "Fixes from Version 4" ; this will now be version 5 and it will go live.
</p>

## Implementing Custom Scripts (Chat Widget)
<p>
If you don't have an account you can create one, and then you will be able to grab a code snippet under the "Drift Widget" tab; insert into your GTM like below <br />
Tags : <strong>Create a new tag</strong> and select "Custom HTML" - paste the code snippet from Drift <br />
Triggering : Drift docs says to trigger on all pages so select "All Pages" <br />
Publish to test like before, you should see 2 tags - once confirmed it is worked then you can click "publish" and it will become live.<br />
<italic>
Note - There is an option for GTM snippet - but there's no option for it in the list so you must get the JS snippet, and put it in the custom HTML Tab Configuration
</italic>
</p>
