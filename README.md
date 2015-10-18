# Performance Scorecard
Performance Scrorecard is a Chrome extension that analyzes web pages for performance best practices.  Analyzing a page only takes a few seconds, and at the end, you receive an overall score for the page plus a detailed report on what aspects of the page should be addressed to improve performance.  For many of the recommendations, the extension even produces optimized resources that you just need to save and then upload to your web server.

Performance Scorecard is a community supported successor to the PageSpeed Insights Chrome extension that was formerly available in the Chrome Store from Google.  It uses the same PageSpeed Insights SDK as before, only some of the text and graphics have been changed.  This extension is community supported, meaning issues should be reported here, not to Google.

## Downloading Performance Scorecard
For most people, you probably want to simply download the extension in the Chrome Web Store at the link ....

## Displaying the Page Score
By default, this is turned off in the options.  You probably want this on to get an overall barometer of how well your page is implementing the practices covered by the tool.  To turn on the Page Score:
1. Bring up all of the extensions for Chrome by typing 'chrome://extensions/' into the address bar in Chrome
2. Locate Performance Scorecard in the list
3. You will see a link that says 'Options'.  Click on this link.
4. Check the box that says 'Show Performance Score'

## Running Performance Scorecard
To use Performance Scorecard to analyze a page, you want to do the following:
1. Navigate to the page that you wish to analyze
2. Open the Chrome Developer Tools.  You can do this a couple ways
  * Go to the Chrome Menu, Select "More Tools" and finally "Developer Tools"
  * Hit the "F12" key
  * Hit the hotkeys Control-Shift-I
2. Once the developer tools open, you will see a menu at the top of the dev tools.  The far right menu item will be titled "Performance Scorecard".  Click on this item
3. When this tab pops up in the Developer Tools, simply click on the "Analyze" button to analyze your page.

One of the main advantages of using the Chrome Extension to analyze pages is that you can analyze any page that you can navigate to within your browser.  This includes web pages that are on your internal corporate network or pages that are only available after a user logs into a website.  

## Future Directions
The initial goal of this project was to make make the extension available again in the Chrome Store.  There are a few enhancements I am considering adding in the future at some point:
*  Having the score turned on by default
*  The ability to export results to a file
*  Summarizing the timing information for a page in the results summary
*  Summarizing the number of bytes loaded for each resource type in the results summary
*  Adding back in support for languages other than English

Feel free to make additional suggestions.  Also feel free to take a look at the code yourself if you feel like there is something you would like to see implemented.

## Licensing
The license for this project is Apache 2.0 as that was the origianl license of the Google Code.  Also, a special thank you is in order for the PageSpeed Insights team for the original development of this extension and for allowing a community supported version to mve forward.
