# Catalyst @ UC

### Pagelets versus 'Cards'
Even though Catalyst is built on Peoplesoft Interaction Hub / Campus Solutions, the decision was made to not use the delivered pagelet model for the student portal tabs.  The main reason was fexibilty.  Because we are using custom javascript to render each inside each pagelet, it made sense to make the student tabs once javascript application instead of having multiple / isolated pagelets.  This allows use to reuse data across cards.  For example, we can easily search all the navigation collections.

In order to make this work, the student portal application is contained in one main pagelet.  This pagelet contains cards that make up the student portal experience. 

![]({{site.baseurl}}/academics.png)

### Collapsible Cards
In order to allow students to minimize noise and focus on the content that matters to them, the student portal will allow both navigation and information cards to be collapsed.  This is a per device setting that will be persisted using browser storage.

![]({{site.baseurl}}//card_collapse.gif)