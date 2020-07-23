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
Here you can customize at your will.

I've also included a Free Shipping Counter, which needs to be enabled in the part of the Announcement you want it to be visible.
  
    • Set the Free Shipping Threshold (only numbers, no currency Symbols).
        The Threshold is the amount a customer has to spend in order to get Free Shipping.
    • Set your Qualified Message. This is the Text a Customer sees when the Threshold is met
    • Set your Not Qualified Message, and add [price] (with square brackets) wherever you want.
        This message will tell the customer how much more to spend in order to get Free Shipping.
        eg. Spend [price] more to get Free Shipping. The output will be, eg: Spend $40.00 more to get Free Shipping
