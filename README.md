# mvp-o-matic

(still very experimental - I'll keep going)

## What is it?

mvp-o-matic aims at making the use of the Model-View-Presenter (MVP) the easiest and most convenient way to work with [vaadin](https://vaadin.com). So writing clean, maintainable code becomes the most natural and self-evident way of work (also b/c it's the lazy option that works perfectly in brain-off-/late-night mode). mvp-o-matic uses (a simplified version of) the patterns from [vaadinator](https://github.com/akquinet/vaadinator).

## How 2 use it?

Import templates.xml into eclipse (Java > Editor > Templates) and use the templates provided w/in. Currently, that's
- editpresenterif
- editpresenterimpl
  - field2view
  - view2field
- editviewif
  - viewfieldif
  - viewselfieldif
- editviewimpl
  - viewfieldimpl
  - viewselfieldimpl
  
In the editor, type the template name (or the beginning of it), press CTRL+SPACE and have the template expand. Fill out all placeholders (TAB between them) and finally press ENTER to get into typing mode again. Resolve remaining TODOs and you're done!
  
(hardening, more templates, InteliJ IDEA support is in the making)
  
Licence: Apache License 2.0