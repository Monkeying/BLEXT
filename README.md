# BLEXT —— One stop blog supplier

BLEXT is a blog website where you can finish the whole "edit - store - publish" blogging process in one place, providing ultimate personal blog experience.

## Versions

Use `git checkout <version>` to checkout any version.

Example: `git checkout dev1.0`

### Development

- dev1.0: Initialization. Configuring and initializing.
- dev1.0.1: Created index & sign_in & sign_up front pages without adding functions.
- dev1.1: Finished basic user authentication. Added database migration.
- dev1.1.1: Added three utilities for user profiles. Including changing/resetting password and resetting email.
- dev2.0: Added user page, able to upload `.md` file and show on user index. **Potential bugs remain!** Gonna sleep :)
- dev2.1: Added blog page route, able to read pure text blog. Next step **Mistune**!
- dev3.0: Mistune added, able to read blog pages. :)))
- dev3.1: Added user blogs pagination.
- dev3.2: Added BlogParser.
- dev3.2.1: BlogParser bug fixed.
- dev3.2.2: Added visiting control.
- dev4.0: Added user settings, supported about_me, bio, avatar and blog title. Also moved changing password function to settings.
- dev5.0: Added online markdown edit. Issues: pictures storage, page arrangement.
- dev5.1: Page arrangement unsaticefactorily but practically solved.
- dev5.1.1: Added navbar to editor page.
- dev5.2: Editor can now publish new blogs.
- dev6.0: Brand new markdown editor supported by [Bootstrap-Markdown](http://www.codingdrama.com/bootstrap-markdown/), still cannot full-height the `textarea`. :(