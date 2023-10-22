[REFERENCE] How to Create a Custom WordPress Theme - Full Course
https://youtu.be/-h7gOJbIpmo?si=12p-YS7uZHn1giSR

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

=IMPORTANT TIMESTAMPS TO TAKE NOTE OF/TIPS THAT MIGHT HELP YOU=
(doing most [if not all] of the steps below is crucial for some theme functions to work
correctly)

*Note:
- (Kung hindi ka tinatamad, 'di naman sa pinipilit kita) change all instances of 'drei'
from all function names

- Under the comment section from 'style.css' and some lines under 'header.php' and
'footer.php', change every instance of information referencing me, with your own.

=======================================================================================

48:16 = Image sizes - width
(Settings > Media > Media Settings)

50:29 = Making the WordPress Loop function properly
(Settings > Reading, set homepage to static page)

56:24 = Dynamic page title heading

1:00:13 = Tuning settings for the site menu codes to take effect
(Appearance > Menus > under "Add Menu Items" > Pages)
- Select 'Pages' to output menus then click "Add to Menu", 'Menu Settings' > 'Display Location'
- Check "Desktop Primary Left Sidebar"

1:08:22 = (Click "Save Menu", Screen Options > "Show Advanced Menu Properties")
- check "Link Target" and "CSS Classes" then under every webpage settings that will output the
menu, type in the CSS class of the unordered list under "CSS Classes (Optional)"
- Under "Navigation Label" paste the '<i> element' that contains the icon for each buttons
Followed by text that whatever you want to label that button, then click "Save Menu")

1:17:31 = Custom logo code for WordPress (Appearance > Themes)
- Select [custom theme name] then click "Customize"
- Under "Site Identity" under logo, click "Select Logo"
- Choose the .jpg/.png file of your logo and edit the attachment details and crop the image to
your liking
- Publish your site for the changes to take effect

01:25:12 = Code implementation for featured images from posts
- Go to Image > Set Featured Image
- Upload an image and edit the attachment details to your liking then click "Set Featured
Image"
- go to Settings > Media to set thumbnail width and height ("Thumbnail Size" under "Media
Settings")

1:33:52 = Post metadata

1:55:42 = Add a blog page link to archive page for archive-related code to work 
- Go to Appearance > Menus > Add Menu Items > Pages
- Add new blog page for archive then click "Publish"
- Go to Settings > Reading then change "Post Page" drop-down item list to the blog site you've
just created, then click "Save Changes"
- Go to Appearance > Menus > Pages
- Under "View all" tab, check "Blog — Posts Page" then click "Save Menu")

01:57:34 = Blog archive, 'index.php' templates

01:59:13 = Create at least 10 posts with their own featured image to see if
'<?php the_excerpt(); ?>' is functioning correctly

02:06:17 = Set thumbnail size for all sizes under Settings > Media) for the PHP code
'<?php the_post_thumbnail_url('thumbnail'); ?>' to work properly

02:07:16 = Optimize WordPress settings for pagination
- Go to Settings > Reading then set both "Blog pages Show at Most" and "Syndication feeds show
the most recent" to 4 posts then click "Save Changes"

02:16:30 = you can now implement widgets on sidebar, specifically on sidebar 1 ("Text" is used
in the video)
- Go to Appearance > Widgets
- Drag the "Text" widget to "Sidebar 1"
- Copy and paste lines 68-74 from 'header.php' WITHOUT the comment tag then click "Save"

02:24:00 = You can now add widgets under "Footer Area" ("Archives" is used in the video)
- (Same procedure as above)

02:29:32 = Drag "Search Widget" to "Footer Area" for 'search.php' to function completely