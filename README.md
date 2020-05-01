This is my fork of pywal.  The changes I've made are
- Support for `alacritty`: `colors-allacritty.yml` is added as an output format in `~/.cache/wal`.
- Better support for `st`: a few extra escape sequences and Xresources colors have been set up so that `st` get's its foreground and background colors set correctly.
- Themes removed: I removed the dark themes that I didn't like, so that `wal --theme random_dark` always gives me a good theme.
