# About
Each stylesheet in this repo contains some basic CSS that improves the appearance and usability of common learning management systems (LMSs).

The stylesheets were created by instructional designer and frontend web developer Amy Spielmaker as part of a conference session: "Hacking the LMS" at NWeLearn 2023. The stylesheets have been tested with standard LMS installations and default themes. If your LMS has other customizations, you may need to do some tweaking.
## How To Use
Copy and paste the CSS from the relevant stylesheet into your LMSs global stylesheet or a specific stylesheet that's linked in your theme. You will need the ability to add custom CSS in your LMS to do this. I also recommend you are familiar with CSS and feel comfortable modifying CSS as needed (usually necessary when your LMS updates to a new version).
### Moodle (Boost Theme)
1. Navigate to **Site administration** > **Appearance** > **Themes** > **Boost**
2. Click the 'Advanced settings' tab.
3. In the 'Raw initial SCSS' field, paste the CSS from the Moodle stylesheet in this repo.
### Canvas
[Follow these directions: How do I upload custom JavaScript and CSS files to an account?](https://community.canvaslms.com/t5/Admin-Guide/How-do-I-upload-custom-JavaScript-and-CSS-files-to-an-account/ta-p/253)
## Test First
I recommend first doing a test with Chrome Developer Tools to see how the styles will be applied.
1. In Chrome, open a course page in your LMS.
2. Right-click anywhere and then select **Inspect** from the context menu. This will open Chrome Developer Tools.
3. Make sure the 'Elements' tab is selected.
4. Click the plus icon in the top right corner of the styles panel. This will create a local stylesheet called `inspector-stylesheet` you can use for testing.
5. Click the `inspector-stylesheet` link beside the style. This will open the stylesheet in the source editor.
6. Paste the CSS from the stylesheet you're testing into the `inspector-stylesheet` stylesheet. The styles will be applied and you can see how it looks.
7. Repeat the steps above for any other pages you want to test.
[Learn more about stylesheets in Chrome Developer Tools](https://medium.com/@umarhamza/create-new-stylesheets-in-chrome-dev-tools-7e972c71f8a5)
