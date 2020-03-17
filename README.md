# Simply Static

Simply Static is a static site generator for WordPress that helps you create a static site that you can serve separately from your WordPress installation.

This repository is a fork of version 2.1.0 of the Simply Static plugin found in the WordPress Subversion repository.

## Notable changes

- PHP 7.3+ support. The original plugin is not compatible with PHP 7.3. This fork will support it.
- The original plugin called the `wp_mail_content_type` filter, and sets all mails to `text/html`. This effectively breaks most common mails (for example the password reset).
