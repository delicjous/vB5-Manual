---
title: Tagging Options
slug: tagging_options
taxonomy:
    category:
        - settings
    tag:
        - options
        - tagging
visible: false
template: article
version: 5.3.3
date: 12/06/2017 11:16pm
---

## Enable Topic Tagging
This is a global option to enable or disable the topic tagging system. You may choose which usergroups can apply tags to topics in the usergroup permissions section.


The minimum number of characters in a tag name. This can be between 1 and 100.


The maximum number of characters in a tag name. This can be between 0 and 100.


These words will be checked in addition to those listed in includes/searchwords.php to form a list of words whose use is banned in tagging.<br />
<br />
Separate each word with a space or carriage return.


Words entered here will be allowed as tags, regardless of whether or not their use would be otherwise disallowed due to length, censorship, commonality etc.<br />
<br />
If a word is specified in the 'Banned' words group <em>and</em> here, it <em>will</em> be allowed.<br />
<br />
Separate each word with a space or carriage return.


This option allows you to specify additional tag separators. Regardless of the value here, a comma will always be used as a separator.<br />
<br />
Separate each tag separators with a space. If you would like to use a space in a tag separator, click the '?' for information on the advanced separator syntax. 


If you enable this option, "A" through "Z" will be replaced with "a" through "z" in tag names. Other characters will not be changed.


The maximum number of tags to display in the tag cloud.


The number of <em>levels</em> to be shown in the tag cloud.<br />
<br />
By default, there are 5 levels named level1 to level5, with the font size growing from its smallest size at level 1 to its largest at level 5.<br />
<br />
Increasing this value above 5 requires a template change.


Amount of time in minutes before the tag cloud data cache is regenerated.<br />
<br />
A value of 0 will generate the tag cloud on each view.


The number of days worth of data that should be used to generate the usage-based tag cloud<br />
<br />
Tags added more than this many days ago will not change the size of the link in the cloud.


The tag cloud pulls together data from topics in many forums. Users may not be able to see all the topics that make up the tag cloud results. With this option, you can force the tag cloud to be built as if it were viewed by a particular usergroup.<br />
<br />
Live permission checking is the most accurate, but disables the above specified caching.


Amount of days that the system will keep a record of tag searches for use in the search tag cloud.<br />
<br />
0 means to use all data available.


