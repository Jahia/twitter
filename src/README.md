Jahia Twitter module

This module provides a component that displays and customize twitter widgets defined in a twitter Account

To create a new widget, go to https://twitter.com/settings/widgets and click on Create new

The customization from the Jahia module overrides the settings from the widget

The Jahia module allows you to set more options. List of options can be found here : https://dev.twitter.com/docs/embedded-timelines#customization

To get the widgetID : edit any widget then you can get this id from :
    - the url  https://twitter.com/settings/widgets/[WidgetId]/edit . ex : https://twitter.com/settings/widgets/344081607688347648/edit
    - the generatd script in data-widget-id attribute. ex : data-widget-id=344081607688347648

Due to new Twitter authentication that not allow anonymous search on twitter, the two previous components (twitterFeed and twitterSearch) are not working anymore.
