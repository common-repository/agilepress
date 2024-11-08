=== AgilePress ===
Contributors: vinlandmedia, kenshihan
Donate link: https://agilepress.io/
Tags: agile, scrum, kanban, task management, product management, project management, to-do
Requires at least: 4.8
Tested up to: 5.2.3
Stable tag: 1.609.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

AgilePress brings Agile product/project management to WordPress using Kanban and Scrum boards.

== Description ==

NOTE: AgilePress is now a product of KMD Enterprises, LLC, the company behind [Podz.io](https://podz.io/).  We'll be updating the software soon, as we're using it for our own projects.

Welcome to [AgilePress](https://podz.io/agilepress), the plugin that turns WordPress into an agile task management system!

AgilePress is based on the principles of [Scrum](https://en.wikipedia.org/wiki/Scrum_(software_development)) and [Kanban](https://en.wikipedia.org/wiki/Kanban_(development)), which are both methodologies used in [Agile](https://en.wikipedia.org/wiki/Agile_software_development) project management.  AgilePress isn't just for business or software development teams, however; our Kanban board is great for keeping track of and collaborating on personal, school, or household projects.

Our aim for AgilePress is to make the product management process simple, but if you’re the person setting it up, there are a number of things you should know.  We've written - and are constantly adding to - documentation for AgilePress on our website, [AgilePress.io](https://podz.io/agilepress/).

== Installation ==

1. Upload `agilepress.zip` to the `/wp-content/plugins/` directory
2. Uncompress the .zip file
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Why are the board columns all scrunched up? =

If at all possible, use a theme that provides a full-width template for pages.

= Can I use AgilePress on my mobile device? =

At the present time, dragging and dropping the notes on a board hasn’t been implemented for touch screens, however you can move the notes around by changing the status in the settings modal.

AgilePress looks great on tablets (view horizontally!) but phones, not so much.  We really need our space for our boards!

= Does AgilePress work with WordPress Multisite installations? =

As of version 1.497.3, yes; please consider the functionality "beta" and report any feedback to us.

== Screenshots ==

1. Adding a new task; AgilePress uses custom post types for its major components.
2. An example of the product edit screen.
3. All note (task) settings can be editing directly from the boards (for users who have rights).
4. An example of a Kanban board for a college research paper.
5. A list of sprints. All AgilePress list screens have extra drop-down boxes to allow for better filtering.
6. Changing the text of a note directly from a displayed board.
7. A portion of the settings/options screen. You can choose which colors and fonts are used for the notes on your boards.

== Quickstart Guide ==

First things first... AgilePress is like a roller-coaster: it has a back-end and you're welcome to use it, but it's a lot more fun up front. The best thing about AgilePress are the boards, and there isn't much that you can't do from the boards once they're set up. Which is why we want to mention, right up front:

- Boards live on pages;
- Pages should be full-width whenever possible;
- You need a product go get started.

=== Create a Product ===

The first thing you need to do is create a product. A product is the output of your process; it could be building a deck, picking the best car for your next purchase, writing a term paper, or - of course - developing software. Your first step is to go to AgilePress -> All Products on the admin menu and create a product.

After you've created a product, you need to record at least one of the things you want to see out of your product. Without getting too far into the weeds (stories and epics and backlog-items, oh my!), let's just go to AgilePress -> All Tasks and add at least one task. If you're product is to build a deck, then you might want tasks for creating a design, purchasing the raw materials, and scheduling time off from work, etc. The least you need to enter for your new task(s) is Associated Product (that's the product you just created in the previous step) and Task Status (which should probably be "To Do" for now).

=== Boards Live on Pages! ===

This is the front-end part. As long as you now have a product and at least one task associated with said product, you can jump into the board action. Go to your list of products and copy the shortcode for the Kanban board. Create a new WordPress page, paste in the Kanban shortcode, and view the page. Viola! You have a Kanban board for your product/project.

Go back to the WordPress admin panel and add the rest of your tasks (at least all of the tasks you can think of, for now). From the board notes - from the page view - you can change task settings, make comments, view attachments, and - of course - drag the notes to other columns as your tasks progress.

Now... get to work on that deck! (Or term paper, or software product, or whatever.) And if you get stuck, [visit the docs on our web site](https://agilepress.io/documentation/) or [hit us up with your questions](https://agilepress.io/contact/).

Thank you for choosing AgilePress!

== Changelog ==
= 1.609.2 =
* The script fonts are cool, but they take up space and can be difficult to read. Added six new Google fonts that seem to work better.
* Changed color of fonts and icons to black to get better contrast with the notes.

= 1.608.2 =
* README updated to reflect most recent state of the software.

= 1.608.1 =
* Minor update to cause visual differentiation in the function bar (bottom of notes) icon for attachements to indicate whether or not attachments are present.
* Dropped number of comments from the function bar icon for comments for consistency with the attachment icon. Counts on both would take up a lot of space, and the number of comments (or attachments) isn't as important as simply knowing that there are some.

= 1.602.7 =
* Target dates can now be added to tasks (user requested feature);
* Dragging a note to either the sprint or kanban "done" columns will set a completion date (this can be manually updated as well);
* Dragging a note "assigns" the task to the person who moved it (this can be manually updated when necessary);
* Target date or completion date (whichever is applicable at the time) are now displayed on notes;
* The assignee is now displayed on notes where applicable;
* Priorities (formally only available on tasks) have been incorporated into stories;
* Font sizes were made consistent (relative to one another, as some were really large and others very small);
* The "In Sprint" overlay text (for backlog items that have been sent to sprint) has been lightened to improve visibility of underlying text;
* Note headings now always use a bold font-weight to better distinguish from note text (especially when the same font is being used for both);
* Fixed a bug that was causing all users to get the "AgilePress Admin" responsibility by default.

= 1.548.8 =
* Updated CSS and made some visual tweaks to the various help/settings pages;
* Fixed some warnings shown by PHPStorm;
* Changed default colors for notes.

= 1.538.5 =
* Notes now allow for annonymous comments if permitted by AP admin;
* Tweaks around sprint backlog item add parent;
* Improved appearance of settings page.

= 1.529.1 =
* Fixed issue with hidden fields and URL redirects.

= 1.515.2 =
* Fixed some issues with sprint board display.

= 1.514.2 =
* For public users, Font Awesome icons (across bottom of notes) now only show when an action is available;
* File uploads and deletions now work from modal windows (on notes).

= 1.505.0 =
* Add new item button fixed so that it does not show for guests on public board;
* Fixed minor issue with a variable that is undefined in some cases.

= 1.497.3 =
* AgilePress now works with Multisite installations of WordPress;
* Deactivation no longer clears options or deletes custom tables; this is done in the uninstaller;
* Changed display priority of AP metaboxes and changed the name and description for excerpt boxes.

= 1.361.4 =
* Fixed issue where new tasks made from front-end were not showing on proper sprint board;
* Put back the sprint-overlay designation for tasks in column three of the backlog;
* Column descriptions are now customizable;
* FA icons now show pointer on hover; note itself show grab hand;
* Updated CSS for modals for better display on different themes plus a few more small fixes.

= 1.295.9 =
* Added getting started page that shows automatically on activation;
* Added button to allow adding of new items from the board;
* Fixed issue with Font Awesome includes;
* Task priority now shows on Kanban notes;
* Fixed issue where items where showing on sprint board when they weren't actually associated with that sprint;
* Other cosmetic tweaks and code refactoring.


= 1.220.7 =
* Added "public" parameter for board shortcodes;
* Addressed an issue where board columns were not resizing consistently.

= 1.066.0 =
* Initial Public Release.

== Additional Notes ==

We strongly recommend:

* Install User Role Editor (if you don’t already use it);
* Use a theme with a full-width template.

Your feedback is valuable to us; please let us know what features you might like to see or of any issue that you encounter.

We are currently rebuilding the AgilePress web site (https://podz.io/agilepress/); please bear with us!
