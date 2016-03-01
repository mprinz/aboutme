# aboutme

### Milestone 2b Feedback
Take a look at the notes we went over below, and check in with me or Skyler this week. After some cleanup, you should be ready to deploy to ASO next week.

Your Milestone 2b passes at [Tier IV](https://bootcamp-coders.cnm.edu/projects/personal/rubric/)

#### Edits &amp; Suggestions
- Fix directory structure: move css, images out of /documentation. Create a /php directory for mailer.php file 
- clean up HTML: bootstrap class names (.col-md-4)
- add contact form
- sticky footer - see: https://bootcamp-coders.cnm.edu/~rlewis37/bootstrap-sample/
- to add footer, add it AFTER the closing <div class="sfooter-content">...</div>
- Animate.css? look at https://daneden.github.io/animate.css/

Set up ASO Host:
- Go over https://bootcamp-coders.cnm.edu/class-materials/php/email/, add composer.json (outside /public_html), and mailer.php (inside /public_html)
- enable shell access - chat live support and request them to enable this
- Add your public SSH key (CPanel, SSH Access)
- Add an email account, and add an email forwarder if you like :)
- Create a new deployment in PhpStorm that uploads to ASO, and upload your site there.
