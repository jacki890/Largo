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
***

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
<hr>

#### Q: SEO, categories and tags, OH MY! How does Largo organize info on my site so people can find it easily?

We have a great article on [how Largo handles taxonomies](https://github.com/INN/Largo/wiki/Custom-taxonomies) (a way to label and organize posts on your site). Essentially, **categories** should be the top level containers for content, while **tags** are more for keywords (people, cities, organizations, narrower topics, etc).

Following that, we're working to build SEO rules into the theme (using the categories and tags as keywords for Google News, for example) so you don't have to do anything extra.

**Writing good, keyword-rich headlines** matters far more than categories and tags in determining how a given page ranks in search results for a given set of keywords.

There are a number of other things you can do to improve rankings:

* Make sure the **authors** on your site have completely filled out profiles that are linked with their Google+ profiles
* Make sure partners or sites that republish your content are linking back to you whenever possible
* Check out this [beginner's guide to SEO](http://moz.com/beginners-guide-to-seo)
<hr>

#### Q: Some of my embedded elements are gone or their appearance changed unexpectedly. What happened?
**A:** Most often, this happens when a post is saved originally in **Text edit view**, and later it is switched to **Visual edit view** and saved. WordPress can strip out embedded JavaScript in posts when you switch between those views.

**Best practice** is to only save posts in the **Text edit view**.
<hr>

#### Q: What kind of plugins can I use with Largo?
**A:**  We have a list of [[recommended plugins|Using-plugins]] that were originally created by NPR project Argo, which Largo is based on. We also have a list of [[curated plugins|Using-plugins#curated-plugins]] that we know to work with Largo. [[Utilities|Using-plugins#utilities]] are there as well as Unsupported Plugins which we know to be incompatible with Largo. Check those lists first before choosing plugins and that should cover most of the functionality you need on your website. There are thousands of plugins out there and they vary as greatly in quality as they do in functionality. Keep this in mind when choosing to download one that isn't on our list and be sure to backup your site before activating it so you can revert back if it causes problems.
<hr>

#### Q: How do I include/exclude a specific category from being displayed on the homepage?
**A:** There are many reasons why you might want your readers to see some categories of posts, but not others on the homepage. We have a way to explicitly specify that in the Largo Theme Options.

1. First, find the **category ID** for the post in question.
	* Go to **Posts > Categories** and click on the category as though you were going to edit it
	* The URL will be something like "http://.../wp-admin/edit-tags.php?action=edit&taxonomy=**category&tag_ID=62**&post_type=post"
	* The **tag ID** is the number you want. It's **62** in this example
2. Once you have that ID, go to **Appearance > Theme Options** and choose the **Layout Options** tab
3. Scroll down to the section labeled **Other Homepage Display Options**
4. To exclude the category in this example, put "-62" in the box in front of **Categories to include or exclude**
	* A minus will exclude a category
	* no minus will limit the loop to that category

5. You can add more as comma separated values
<hr>

#### Q: What can I use for analytics on my site?
**A:** With Google Analytics, you can do everything from very basic traffic analysis to more complex analytics by tagging links, creating goals, etc. There are many resources available. Here are just a few:

* [Overview of Google Analytics with WordPress](http://www.wpbeginner.com/beginners-guide/how-to-install-google-analytics-in-wordpress/)
* Info on [setting up goals](http://searchengineland.com/a-beginner%E2%80%99s-guide-to-setting-goals-in-google-analytics-101826)
* Some of our members use [Chartbeat](https://chartbeat.com/)
* This site is great and offers free services for nonprofits [Web Analytics Demystified](http://www.webanalyticsdemystified.com/ae/)
<hr>

#### Q: Does Largo provide a way to customize the headline and excerpt for Google so they fit the character requirements of the SERP (Search Engine Results Page)?
**A:** Not specifically at this time. We're planning to add some additional (optional) custom fields to address this need and also for things like tweeting text selections if somebody shares via the Twitter button, etc. and modify the theme accordingly to handle it in the background, but that has yet to be implemented.

We don't recommend using SEO plugins, because they duplicate much of the functionality built into Largo. e.g.

* Twitter card markup
* Open graph tags
* Canonical URLs, etc.
<hr>

#### Q: Can I make all external links (off my site) open in a new window?
**A:** While that isn't a global option, you can set this on a case by case basis. When you insert a link into a post, there is a check box labeled "open link in a new window." Check it for external links and leave it unchecked for links to other elements on your site.
<hr>

#### Q: How do I change how an excerpt looks in the footer?
**A:** The excerpt is determined by the first few sentences of the post, so edit that to your liking. If you want a post to be displayed in the footer:

* Open the **post's edit screen**
* Go to the **Post Prominence** box on the right
* Check the box for **Footer Featured Widget**
<hr>

#### Q: How do I change the link for the Donate button?
**A:** Go to **Appearance > Theme Options** on the **Basic Settings** tab. There is a section labeled **Donate Button** and an option to show/hide it in the top header as well as to enter the **link to your donation page** and the text displayed on the button. "Donate Now" is the default.
