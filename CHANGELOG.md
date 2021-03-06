# Changelog

## Next version: 0.8.0

### New features

- Style (breaking change):
    - Added support for bold/italic/underlined text
    - Added `StyledString` for markup text
    - Refactored line-break module
- Colors (breaking change):
    - Added ColorStyle and PaletteColor for more flexible colored text
- Buttons:
    - Added `Dialog::buttons` to iterate on buttons
    - Added `Button::set_label` and `Button::label`
- TextView:
    - Added TextContent, a way to separate model and view for TextView
    - Added manual scrolling methods
- Allow multiple global callbacks per event
- Allow buttons and delimiters in top-level menubar
- StackView:
    - Added `StackView::move_layer`
    - `StackView::pop_layer` now returns the pop'ed view

### Bugfixes

- Fix a bug in `TextArea::set_content`
- Fix `Color::from_256colors` for grayscale colors
- Fix resize detection on windows

### Doc

- Add per-distributions instructions to install ncurses
- Improved comments in examples
- Improve doc for `Cursive::find_id`
- Improve doc for `Identifiable::with_id`
