Changes
=======

4.7.13.9 (2021-02-18)
---------------------

- Add format_value method to TinyMCERichTextArea so it can be rendered correctly on latest wagtail versions
that relies on telepath to render Streamfield blocks

4.7.13.8 (2021-01-24)
---------------------

- Add anchor link


4.7.13.7 (2019-08-21)
--------------------

- Fix document chooser icon

4.7.13.6 (2019-04-24)
--------------------

- Add support of table related options

4.7.13.5 (2019-03-20)
--------------------

- Import image-chooser and image-chooser-modal for the image plugin

4.7.13.4 (2019-03-05)
--------------------

- Import page-chooser and page-chooser-modal for the link plugin

4.7.13.3 (2018-11-01)
--------------------

- Update to support Wagtail 2.3 and Django 2.1.2

4.7.13.2 (2018-10-05)
--------------------

- Update to support Wagtail 2.2.2

4.7.13 (2018-05-31)
--------------------

- Update to TinyMCE 4.7.13
- Update to support Wagtail 2

4.4.3.1 (2018-05-29)
--------------------

- Update to TinyMCE 4.4.3


4.2.1.5 (2016-06-08)
--------------------

- Alter doclink editing fixes in line with Wagtail 1.5.1 Hallo editor.
- Change page chooser to use parent page ID in line with Wagtail 1.5.1 Hallo editor.

4.2.1.4 (2016-06-01)
--------------------
- Update to use Wagtail 1.5 pluggable rich text editor mechanism.
- Refactor link and doclink plugins to remove race condition.
- Add link editing and unlinking in line with Wagtail 1.5 Hallo editor.
- Fixes around editing of doclinks with link editor.
- Refactored settings to allow per-field variation.
- Made default menu/toolbar settings more Wagtail friendly.

4.2.1.3 (unreleased)
--------------------
- No changes.

4.2.1.2 (unreleased)
--------------------
- Add further button and menubar settings.
- Persist TinyMCE content to form on change to avoid losing content on preview with validation errors.

4.2.1.1 (unreleased)
--------------------
- Bug fixes relating to page/document link handlers.
- Add image/embed editing (requires custom Wagtail).
- Add image/embed caption field (requires custom Wagtail).

4.2.1.0 (unreleased)
--------------------
- Initial release.
