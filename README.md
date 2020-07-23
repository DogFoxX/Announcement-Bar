# Announcement-Bar
Customizable Announcement Bar for Shopify websites

# Getting Started

Open your Shopify Theme Code by:

    • Going to Online Store
    • Click Actions on the theme you wish to edit
    • Choose Edit Code

First Locate your Theme.Liquid file in the Layout section.
Now in the Theme.Liquid file, look for the start of

    <body ...>

And copy the following directly under it
  
    {% section "announcement-bar" %}
  
Save Theme.Liquid


The final Step to add all the Options for the Announcement Bar:
Go to Sections, and create a new Section by Clicking on "Add a new Section"

Name the new Section:

    announcement-bar

(this is case sentitive, and needs to be the same name as given in Theme.Liquid)


Remove any generated code from the file, and Save the file.
Now copy the code from Announcement Bar Code file, paste in your announcement-bar.Liquid file, and Save.

# Using the new Announcement Bar

Now go to your Theme again, and click on Customize.
If everything was done right, you should see Announcement Bar at the very top of your Theme Settings.
Here you can customize at your will. All text field accept HTML syntax.

# Settings
## Behviour

**Show Announcement**

This will disbale or enable the entire Announcement

**Show again after close**

Enabled State:

    When a cutomer or visitor closes the bar, it will be closed until the page is refreshed, or when navigating to another page.
    
Disabled State:
    
    When a cutomer or visitor closes the bar, it will be closed for the whole session and won't be displayed again.
    It will only be visible again when a new session is activated.
    For instance, when a visitor closes your webpage the session is closed.
    A neew session will start when a visitor opens your website from fresh.
    
**Text Alignment**

This sets all the text to either **Left, Right or Center**

**Background Colour**

This will set the colour of the Bar Background

## Close Button

**Enable**

Disabled State:

    A close button will not be visible
    
Enabled State:

    A close button will be visible and accessible
    
**Button Colour**

This sets the colour of the **X**

**Button Background Colour**

This sets the colour of the close button's background

**Background Colour on Hover**

This sets the colour when mouse hovers over the close button

**Corner Radius**

Setting this to 0 will make the close the button square with sharp corners
Use the slider to set the corner "roundness"

**X Width**

Use the slider to adjust the size of the **X**

**Background Width** and **Background Height**

Use the sliders to adjust the size of the close button background

## Free Shipping Announcement

**Free Shipping Threshold**

Use only numbers here, no currency Symbols.
The Threshold is the amount a customer has to spend in order to get Free Shipping.

**Qualified Text**

This is the Message a customer sees when the amount in their cart is equal to, or larger than the Threshold.

**Not Qualified Text**

Set your Not Qualified Message, and add [price] (with square brackets) wherever you want.
This message will tell the customer how much more to spend in order to get Free Shipping.

Example:

    Spend [price] more to get Free Shipping.

Output, eg

    Spend $40.00 more to get Free Shipping.
