## Largo Theme FAQ
#### Q: How do I change the color of the Theme?
**A:** The default color is light blue. Here is how you choose a different color:

* Under **Appearance** > **Theme Options** there is an **Advanced tab** that has an option to **enable custom LESS to CSS for theme customization**
*  Check that box and **save the theme options**
*  On the **Appearance** > **CSS Variables** menu that appears, you can now do some basic customization of the theme (mostly colors)
*  You can use custom CSS to further refine the colors, but this will generally reduce the amount of custom CSS you need to use
<hr>

#### Q: Can I change the size of the text on the Nav bars and Widgets?
**A:** No, you can't change those values in the Admin UI. That can only be done through custom CSS. We have tested this theme extensively for appearance on desktop to mobile devices to ensure that these elements display properly in all screen sizes. Changing this is not recommended. While you may improve the appearance in one view, it will often look worse on a different device.
<hr>

#### Q: How do I change the prominence of posts and other items?
**A:** When you edit a post you'll see a number of boxes in the right column with various checkboxes (categories, etc.) one of these is labelled **Prominence**. This controls where certain posts are displayed on the site (i.e. The **top story** on the homepage is selected by checking the **Top Story** box).

* By default, the footer has a widget called **Footer Featured** that will show up to three posts that you select by checking the **Footer Featured widget** box from this prominence box when editing a post
* If you don't see the pProminence box, make sure you're in the **Post Edit** screen, click on **Screen Options** at the top right corner of the screen and make sure the **Prominence** box is checked
<hr>

#### Q: We switched to a new host, but it's still pointing to the old site. How long does it take for those changes to propagate?
**A:** While the changes may propagate within a couple hours, it can actually take up to **48 hours** for them to take effect. If you **clear your cache** and **try the site from a new internet browser** and still see the old site, or it's pointing to the old host, the changes have not taken effect yet, and you just have to wait it out.
<hr>

#### Q: As an INN member, can I install WordPress plugins?
**A:** Largo is a theme on a network with many other sites. We keep control of the plugin installation so we can avoid conflicts with the theme and with approved plugins. WordPress has thousands of plugins available, and the potential for them to cause problems is pretty high. If there's a plugin you'd like to install, **ask your Largo administrator to install it for you**. If it's one of our approved and tested plugins, they will install it for you. If not, they'll discuss it on a case-by-case basis.
<hr>

#### Q: The CSS Customizer doesn't let me change what I want to. How do I make changes to the CSS?
**A:**

* Send us a list of the changes you are requesting and we'll work with you to implement them
* Make those changes in your staging environment and commit them to your Child Theme's repository so we can push them live for you
<hr>

#### Q: In Largo, can I get the social media buttons to open in a new tab/window?
**A:** Not at this time.
<hr>

#### Q: In the Largo Follow Widget, can I change the appearance of the social media buttons?
**A:** Those come to us from the providers, so we have very little control over their appearance.
<hr>

#### Q: Why do my HTML tags get stripped from excerpts, etc?
**A:**

* We strip code from the html to prevent issues, like photos and embedded media, coming through to the homepage
* We also try to keep things looking good across a wide variety of devices with our responsive theme. What looks good in your desktop browser may look terrible in a mobile browser or vice versa
* We recommend using the **custom excerpt field** and writing a **short, plain text excerpt** for the best results
<hr>

#### Q: How do I control what appears in the lower right footer menu?
**A:** Go to **Appearance > Menus**. The one you're looking for is called *footer navigation*. Here is more info on how to use [WordPress menus](http://codex.wordpress.org/Appearance_Menus_Screen?utm_content=buffer7debc&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
<hr>

#### Q: I see the option to add sticky posts to the homepage, but how do I make a post sticky?
**A:** Only one post can be sticky at a time. To make a post sticky:
	
* Go to **post edit** view
* Click the **Visibility** status (Public, Private, etc)
* Click the checkbox in front of **Stick this post to the front page**
* It will appear on the homepage
<hr>

#### Q: How can I create a custom sidebar for a single post?
**A:** Do the following:

1. Go to **Appearance > Theme Options**
2. Click on the **Layout Options** tab
3. Midway down that page, there is an area labeled **Sidebar Options**
4. One per line, you can enter names of **additional sidebar regions**
5. Save the Theme Options
6. Go to the **Appearance > Widgets** menu where the new widget area you created in step #4 should be available
7. Add the widgets you want to display (the same way you'd add them for the main sidebar)
8. Go to the **edit screen** for the post where you want to display the custom sidebar
9. Find **Layout Options** along the right side
10. Under **Custom Sidebar**, select the sidebar you created from the drop down menu
11. Publish the post, and it should now be displayed

**Note:** This option is only available on posts, pages and series landing pages, but will soon be available on category and tag pages as well.
<hr>

#### Q: Why doesn't anything happen when I click on a tag in a post? It doesn't appear to work like tags are supposed to.
**A:** There's a plugin called [Simple Tags](https://wordpress.org/plugins/simple-tags/) on some Largo sites are using that helps to recommend tags for a given article. This is what is causing the behavior to differ from what you see in the WordPress documentation. You can find documentation for that plugin here: [https://wordpress.org/plugins/simple-tags/](https://wordpress.org/plugins/simple-tags/)