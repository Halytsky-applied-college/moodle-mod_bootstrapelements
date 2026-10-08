# Bootstrap Elements for Moodle

Bootstrap Elements allows teachers to add modal dialogs and expandable
content to Moodle courses, helping improve course layout while using
less space on the page.

The plugin works as an enhanced Label resource, with options to display
content as:

- Modal dialog — content displayed in a popup.
- Toggle — expandable and collapsible content.
- Enhanced Label — static content with a title.

## About this repository

This repository is an unofficial maintenance continuation of the
original `mod_bootstrapelements` plugin.

The original upstream repository was hosted on Bitbucket and is no
longer available. This repository was created from an existing copy
of the plugin to preserve its source code and provide a starting
point for further maintenance.

It is not a platform-linked GitHub fork of the original repository.

The goal of this continuation is to adapt the plugin for Moodle 5.3
and Bootstrap 5 while preserving existing plugin data and functionality
where possible.

This project is not an official release from the original authors
and is not affiliated with or endorsed by them.

## Theme compatibility

Currently tested only on Moodle 5.3 with Boost theme.
Installation on earlier Moodle versions is intentionally restricted
until compatibility has been verified.

Bootstrap Elements depends on Bootstrap components provided by the
active Moodle theme.

The original README listed the following themes as compatible with
the original plugin:

- BCU
- Adaptable
- Essential
- Shoehorn

This is historical information from the upstream project, not a
compatibility statement for current versions of these themes or Moodle.

Compatibility with modern Bootstrap 5-based themes will be evaluated
during development.

## Plugin identity

The Moodle component name remains:

`mod_bootstrapelements`

This project continues maintenance of the existing plugin rather
than introducing a new Moodle component.

## Contributing

Bug reports, compatibility feedback, and pull requests are welcome.

When reporting a problem, include:

- Moodle version.
- PHP version.
- Theme name and version.
- Steps to reproduce the issue.
- Relevant Moodle debugging output or browser console errors.

Do not include passwords, access tokens, personal data, or production
database dumps.

## Credits

Original plugin copyright notices credit:

2014 Birmingham City University / Michael Grant.

Original copyright and license notices are preserved in the source files.

Changes made as part of this continuation will be documented in Git
history and, where appropriate, in the source files and changelog.

## License

This plugin is licensed under the GNU General Public License, version 3.

See `LICENSE` for the full license text.

Any bundled third-party components remain subject to their respective
license notices.
