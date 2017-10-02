# Audubon Chapter Template For Squarespace #

A modified version of Squarespace's popular Bedford theme, styled with Audubon's brand colors & fonts, with a few design tweaks here and there. It should be a great starting point for your new chapter website, providing a foundation for further customizations and tweaks.

## Installation Instructions ##

Video walk-through of install process: https://vimeo.com/236494907

You'll need:
* A Squarespace account ([register here](https://www.squarespace.com/); use code AUDUBON when making your first purchase to get 10% off)
* An FTP client (The instructions below use Cyberduck, which is a free FTP client available for both Mac or Windows. [Download it here](https://cyberduck.io/?l=en).)
* The Audubon Squarespace template itself, [downloaded here](https://github.com/audubongit/squarespace-template/archive/master.zip) and unzipped to a folder on your computer.

### Prepare Your Squarespace Account ##
1. When you set up your Squarespace account, select the Bedford template to start with. You may also want to select "Community/Nonprofit" and "Business/Organization" to describe your site's content in the short questionnaire that follows.

2. After you've finished setup and you see the gray config panel to the left, select "Settings". Then choose "Advanced". And finally, choose "Developer Mode" and click to enable Developer Mode. Click "Continue" on the message that appears.

*Note: Putting your website in Developer Mode to load the Audubon template is the fastest way to get all of the styling tweaks applied to your new site. You will still be able to receive help from Squarespace with your theme in developer mode. Squarespace periodically upgrades its web publishing platform as a whole, and you will still receive these updates with your theme in developer mode. It also periodically makes small tweaks to its individual templates, such as the Bedford template on which Audubon's template is based. In developer mode you will not receive changes made to the base Bedford template in the future, but these changes are typically  relatively minor—the risk of missing out on something big here is low.*

*If you would like to modify the Bedford template yourself to apply the Audubon styling tweaks, see "Making These Changes Yourself." This will take more work initially, but does not require you to turn on Developer Mode for your site.*

4. Take note of the "SFTP Hostname" and "SFTP Port" under "Connectivity Details"—you'll need to enter this information in the next step.

![ftp connecting instructions](https://d2fbmjy3x0sdua.cloudfront.net/cdn/farfuture/ZGgf68awxpkjVFrS08kRkz8bgIc_Xw6DPkLT1FquuBQ/mtime:1497297513/sites/default/files/styles/bean_wysiwyg_full_width/public/2017-06-12_at_3.47_pm.png?itok=oy0fUVqN)

*Step 4 illustrated. Note: Your address and port number may be different from what's pictured here.*

### Transfer the Audubon template files to your Squarespace site using FTP ###

5. Launch Cyberduck, or the FTP application of your choice (the instructions below are specific to Cyberduck, but if you've used FTP before, it should be familiar.)

6. Once Cyberduck has opened, press the "Open Connection" button or choose "Open Connection" from the File menu. Open the dropdown that says "FTP (File Transfer Protocol)" and select "SFTP (SSH File Transfer Protocol)"

7. In the "Server" field, enter the contents of the "SFTP Hostname" field you noted in step 4 (it's most likely dev.squarespace.com). In the "Port" field, enter the "SFTP Port" number from step 4. In the "username" and "password" fields, enter your Squarespace username (your email address) and password. If you only see a field for "Username" in Cyberduck, just fill that one in—you'll be asked for your password later. With all the fields filled in, press "Connect"

It may take several seconds to connect, and you may be asked to confirm the server's RSA fingerprint. You can say "OK" or "Continue" to any dialog boxes that appear.

![connecting with Cyberduck](https://d2fbmjy3x0sdua.cloudfront.net/cdn/farfuture/Khn2TeVeAjsZoPk8tioxz7bRXXJqkVTrrj2RJ0lJF9Y/mtime:1497298184/sites/default/files/styles/bean_wysiwyg_full_width/public/2017-06-12_at_4.07_pm.png?itok=XqUriUU2)

*Step 7 illustrated*

8. You'll now be connected, and should see a folder with a name that looks like "your-name-xxxx" where "xxxx" is a random series of four letters and numbers. Double click this folder to open it.

9. Find the folder where you downloaded the Audubon template (the file will be called audubon-template-master.zip). If you haven't yet, double click this ZIP file to expand it into a folder named audubon-template-master. Open this folder and you should see files and folders with similar names as your Cyberduck window.

10. Select all the files and folders in the audubon-template-master folder on your computer, and drag them over into the Cyberduck window. You'll be asked if you want to overwrite all of the existing files—choose "Continue" to overwrite them. Cyberduck will do its thing, and once you see the "Upload complete" message, the files have been copied completely.

11. Back in your web browser, refresh the page containing your Squarespace site. You should see the Audubon colors and fonts appear (the "Learn More" button in the header should turn orange). You're done!

In certain cases, you may receive an error message when trying to copy the files based on file permissions. If the copying action fails for any reason, follow steps 12 through 14 below to copy the files in smaller batches.

12. **Only if necessary** Start by dragging over the files "site.region" and "templates.conf" from the folder on your computer into the folder you see in the Cyberduck window. You'll be asked if you want to overwrite the existing files—choose yes, or continue, to overwrite the files.

13. **Only if necessary** Now, click and drag the "scripts" folder from your computer over to the Cyberduck window—it should copy automatically.

14. **Only if necessary** Finally, open each of the remaining folders ("styles" "blocks" and "collections") in both the folder on your computer and in the Cyberduck window. Copy each folder's entire contents (most should have multiple files inside) from your computer to the corresponding folder in the Cyberduck window, again choosing to overwrite all files. Once you've copied the contents of all three, you're done!

## Performing These Tweaks Yourself ##

Squarespace's built-in Style Editor is very powerful. Using it, you can customize the look and feel of nearly every element of your website without knowing any code whatsoever. The Audubon template is essentially just a long list of Style Editor settings that get loaded automatically upon installation—all of the styles found in the Audubon template can be configured with the Style Editor by hand. If you choose, you can apply the tweaks manually using the Style Editor in your Squarespace config panel.

To access the Style Editor, click Design in your main config bar, then click Style Editor. You'll see a long list of things to tweak. **Tip: With the Style Editor open, you can hover over an element of your website. If a blue box appears, click it, and the corresponding Style tweak will be displayed in the gray panel at left. This makes it easier to figure out which settings control what parts of your website.**

Unfortunately, there are too many specific tweaks the list them all by name, but in general we can provide a few guidelines:

**Body Text Font**
* Noto Serif (Google Fonts)
* Weight: 400
* Style: normal
* Size: 18px
* Letter spacing: 0px
* Line Height: 1.5em

**Headings/Everything Else Font**
* Source Sans Pro (Google Fonts)
* Weight: 300 (occasionally 400 for only the biggest headings)
* Style: normal
* Size: 40px (for Heading 1)
* Letter spacing: 0px
* Text Transform: None
* Line Height: 1.2em

**Colors**
* Link color (Audubon blue): #0AA8E3
* Button color (Audubon orange/red): #F15936
* Accent color (Audubon green): #7BA701

I recommend downloading and using the Audubon template if you can, as we've made sure that the many required style tweaks have been made consistently for a clean look (you'll need to change these font and color settings across dozens of different tweaks to cover all the elements of your site). Plus, you can always tweak them further yourself after you install the Template.

# A Demo Site Using the Audubon Template
We've set up a demo Squarespace site using the Audubon template. It includes several different types of content pages (blog posts, events, donation pages, etc) that should allow you to get a feel for the range of content types Squarespace offers.

[Access the demo site here](https://john-mahoney-jsc3.squarespace.com). *Note—click the "Guest Access" button and enter the code.*

There isn't content here to be duplicated directly, but hopefully seeing these examples will get your own creative ideas percolating. You may also find the basic [Bedford template demo site](https://bedford-demo.squarespace.com/) useful—the Audubon template was based on Bedford and shares its functionality.

# Where to Get Squarespace Help #

One of the most important factors driving our recommendation of Squarespace for your chapter website was its rich support materials. Here we'll point you in the direction of the resources you can use to learn how to make a great Squarespace website, and to get help when you run into a problem.

**[Getting Started](https://support.squarespace.com/hc/en-us/articles/206756327)**. Start here. This will not only help you answer questions like how to migrate from other platforms or purchase a domain. It will also show you where to get more detailed help when it's needed.

**[Squarespace Knowledge Base](https://support.squarespace.com/hc/en-us/categories/200352188-Knowledge-Base)**. Tons of videos and articles covering both common and uncommon tasks. Note: the support pages often refer to how individual templates may treat some aspects of your content differently. The Audubon Template is based on the Bedford theme, so anything that applies to the Bedford template in the support pages should also apply to the Audubon theme.

**[Contact Customer Care](https://support.squarespace.com/hc/en-us/requests/new)** Squarespace offers live support chat, as well as emailed questions. Start here to get personalized help.

There are so many users of Squarespace that, the odds are, if you have a question, someone else has had the same one.

# Tips and Tricks #

* In many of the "Banner" or "Description" fields of the Bedford/Audubon themes, bold text appears as a much larger heading. This allows you to create a bold, brief header with a more detailed description of the page below in a smaller font. We use this technique on the main header of the demo site ("Protecting Birds and the Places They Need Since 1972" is made larger by simply making it **bold** in the editor box.)
