Jahia Twitter module

This module provides a Jahia component that displays a twitter widget

To create a new widget

- Log-in with a Twitter account (the one of your company for instance)

- Go to https://twitter.com/settings/widgets

- Define the type of Widget you want (usertimeline, favorites, lists, search based)

- Define the widgets settings if you wish (this can be done later directly in Jahia)

- Click on Create new

- To get the widgetID : edit any widget then you can get this id from :
    - the url  https://twitter.com/settings/widgets/[WidgetId]/edit . ex : https://twitter.com/settings/widgets/344081607688347648/edit
    - the generatd script in data-widget-id attribute. ex : data-widget-id=344081607688347648


To use the Jahia component

- Install your module on your Jahia Server
- Deploy the module to make it available on the targeted website
- Drag and drop the component "Twitter Widget" wherever you want in a page
- Fill the form that pops-up, the only mandatory field is the Widget ID

If you don't fill the different settings, the widget will use the ones defined when creating the widget on twitter.com
If you define your settings locally in Jahia, it will override the settings define on twitter.com

The Jahia module allows you to set more options than the ones proposed directly by Tiwtter

List of options can be found here : https://dev.twitter.com/docs/embedded-timelines#customization

Since 2013 June 11 Twitter changed its API and does not allow anonymous search anymore. Accordingly the two previous components (twitterFeed and twitterSearch) stopped working and only the new Twitter Widget Component works correctly.
