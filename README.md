sugarcrm-custom-quote-line-items
================================

Illustrates how to add custom fields to a quote line item.  I added to github as I thought marking up a commit would be a good way to see each of the parts involved.

### [View This Diff For Instructions](https://github.com/blak3r/sugarcrm-custom-quote-line-items/commit/33226031a15e43666b2d71ccdaf098c1c3b988b7)

Also, I'd recommend looking at [this blog](http://blog.sssworld.com/2013/10/25/customizing-line-item-in-sugarcrm-in-upgrade-safe-manner/) article:
It walks you through how to make these changes in an upgrade safe manner and provides more commentary.
But, doesn't show how to add a "custom" field (just a standard field that isn't normally there).

![Example Quote With Modified Line Items](https://raw.github.com/blak3r/sugarcrm-custom-quote-line-items/master/SampleWithCustomLineItem.png)

### Notes:
- For the javascript files, on my instance they were minified.  I "beautified" them using this website: http://jsbeautifier.org/
- It's possible that I may have made some changes to these core files prior to today.  So, it's a good idea to not blindly overwrite your files.
- Unfortunately, in the process of doing this I also removed the Tax column and the cost column.  So, the vast majority of lines in the diff are modified for that purpose.  I marked up the important ones.

### Related Posts

- http://forums.sugarcrm.com/f6/how-add-new-fields-line-item-quote-80327/#post279583
- http://stackoverflow.com/questions/15784338/hide-discount-from-line-items-in-quotes-in-sugarcrm
