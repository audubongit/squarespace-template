#Audubon Chapter Template For Squarespace#

A modified version of Squarespace's popular Bedford theme, styled with Audubon's brand colors & fonts, with a few design tweaks here and there. It should be a great starting point for your new chapter website, providing a foundation for further customizations and tweaks.

##Installation Instructions##

You'll need:
* A Squarespace account ([register here](https://www.squarespace.com/); use code AUDUBON when making your first purchase to get 10% off)
* An FTP client (The instructions below use Cyberduck, which is a free FTP client available for both Mac or Windows. [Download it here](https://cyberduck.io/?l=en).)
* The Audubon Squarespace template itself, [downloaded here](https://github.com/audubongit/squarespace-template/archive/master.zip) and unzipped to a folder on your computer.

###Prepare Your Squarespace Account##
1. When you set up your Squarespace account, select the Bedford template to start with. You may also want to select "Community/Nonprofit" and "Business/Organization" to describe your site's content in the short questionnaire that follows.

2. After you've finished setup and you see the gray config panel to the left, select "Settings". Then choose "Advanced". And finally, choose "Developer Mode" and click to enable Developer Mode. Click "Continue" on the message that appears.

*Note: Putting your website in Developer Mode to load the Audubon template is the fastest way to get all of the styling tweaks applied to your new site. You will still be able to receive help from Squarespace with your theme in developer mode. Squarespace periodically upgrades its web publishing platform as a whole, and you will still receive these updates with your theme in developer mode. It also periodically makes small tweaks to its individual templates, such as the Bedford template on which Audubon's template is based. In developer mode you will not receive changes made to the base Bedford template in the future, but these changes are typically  relatively minor—the risk of missing out on something big here is low.

If you would like to modify the Bedford template yourself to apply the Audubon styling tweaks, see "Making These Changes Yourself." This will take more work initially, but does not require you to turn on Developer Mode for your site.*

4. Take note of the "SFTP Hostname" and "SFTP Port" under "Connectivity Details"—you'll need to enter this information in the next step.

###Transfer the Audubon template files to your Squarespace site using FTP###

5. Launch Cyberduck, or the FTP application of your choice (the instructions below are specific to Cyberduck, but if you've used FTP before, it should be familiar.)

6. Once Cyberduck has opened, press the "Open Connection" button or choose "Open Connection" from the File menu. Open the dropdown that says "FTP (File Transfer Protocol)" and select "SFTP (SSH File Transfer Protocol)"

7. In the "Server" field, enter the contents of the "SFTP Hostname" field you noted in step 4 (it's most likely dev.squarespace.com). In the "Port" field, enter the "SFTP Port" number from step 4. In the "username" and "password" fields, enter your Squarespace username (your email address) and password. If you only see a field for "Username" in Cyberduck, just fill that one in—you'll be asked for your password later. With all the fields filled in, press "Connect"

8. You'll now be connected, and should see a folder with a name that looks like "your-name-xxxx" where "xxxx" is a random series of four letters and numbers. Double click this folder to open it.

9. Find the folder where you downloaded the Audubon template (the file will be called audubon-template-master.zip). If you haven't yet, double click this ZIP file to expand it into a folder named audubon-template-master. Open this folder and you should see files and folders with similar names as your Cyberduck window.

10. Start by dragging over the files "site.region" and "templates.conf" from the folder on your computer into the folder you see in the Cyberduck window. You'll be asked if you want to overwrite the existing files—choose yes, or continue, to overwrite the files.

11. Now drag the "scripts" folder from your computer over to the Cyberduck window—it should copy automatically.

12. Finally, open each of the remaining folders ("styles" "blocks" and "collections") in both the folder on your computer and in the Cyberduck window. Copy each folder's contents (most should have multiple files inside) from your computer to the corresponding folder in the Cyberduck window, again choosing to overwrite all files. Once you've copied the contents of all three, you're done!

13. Return to your web browser logged into Squarespace and reload the page. You should see a similar view, but now with fonts and colors that match Audubon's branding.

##Performing These Tweaks Yourself##

Squarespace's built-in Style Editor is very powerful. Using it, you can customize the look and feel of nearly every element of your website without knowing any code whatsoever. The Audubon template is essentially just a long list of Style Editor settings that get loaded automatically upon installation. But if you choose, you can apply the tweaks manually using the Style Editor in your Squarespace config panel.  

To access the Style Editor, click Design in your main config bar, then click Style Editor. You'll see a long list of things to tweak. **Tip: With the Style Editor open, you can hover over an element of your website. If a blue box appears, click it, and the corresponding Style tweak will be displayed in the gray panel at left. This makes it easier to figure out which settings control what parts of your website.** 

Unfortunately, there are too many specific tweaks the list them all by name, but in general we can provide a few guidelines.
