sugarcrm-custom-quote-line-items
================================

Illustrates how to add custom fields to a quote line item.  I added to github as I thought marking up a commit would be a good way to see each of the parts involved.

### [View This Diff For Instructions](https://github.com/blak3r/sugarcrm-custom-quote-line-items/commit/33226031a15e43666b2d71ccdaf098c1c3b988b7)

Also, I'd recommend looking at [this blog](http://blog.sssworld.com/2013/10/25/customizing-line-item-in-sugarcrm-in-upgrade-safe-manner/) article:
It walks you through how to make these changes in an upgrade safe manner and provides more commentary.
But, doesn't show how to add a "custom" field (just a standard field that isn't normally there).

### Notes:
- For the javascript files, on my instance they were minified.  I "beautified" them using this website: http://jsbeautifier.org/
- It's possible (but unlikely) I modified these files prior to to making custom line item changes.  So, it's a good idea to not blindly overwrite your files.
- In the process of doing this I also removed the Tax column and the cost column.  So, the vast majority of lines in the diff are modified for that purpose.  This makes the diff a bit more complicated then it needs to be, I annoted the important ones.

### My Use Case
I wanted to make quoting easier for our sales reps.  We have products with certain accessories reps would forget to add and also wanted quantity price breaks to be more self documenting.
So, I added a new field to the product template in Studio called ```internal_notes_c```
![Example Quote With Modified Line Items](https://raw.github.com/blak3r/sugarcrm-custom-quote-line-items/master/SampleWithCustomLineItem.png)


### Related Posts

- http://forums.sugarcrm.com/f6/how-add-new-fields-line-item-quote-80327/#post279583
- http://stackoverflow.com/questions/15784338/hide-discount-from-line-items-in-quotes-in-sugarcrm
