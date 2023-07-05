# Gavin's Obsidian snippets

Apply these snippets on top of the default Obsidian theme.

To use snippets, add the `.css` files to `yourvault/.obsidian/snippets/` and then go into the Obsidian Appearance preferences and toggle them on.

## Snippet functionality

### Accent colors

(These are snippets so they can be adjusted for light vs dark mode)

- `accent-blue.css` uses Apple's Blue accent colors
- `accent-yellow.css` uses Apple Notes' accent colors

The accent color snippets are mutually exclusive in use.

### UI cleanup

- `pickiness.css`, `cleanup.css` makes minor UI changes to reduce visual clutter. Note this does hide the file directory sort options because I don't use them. Delete lines 10–12 of `cleanup.css` to show them.

### Tabs

- `safaritabs.css` offers Safari style UI tabs on macOS
- `square-tabs.css` offers Figma style UI tabs on macOS

The tab snippets are mutually exclusive in use.

### Mobile

- `mobile.css` provides iPhone specific changes
- `ipad.css` provides iPad specific changes (these still need work...)

### Misc

- `faint-yaml.css` is pretty particular—it minimizes the diaply of YAML frontmatter in a very opinionated and pretty fragile way. Disclaimer is this might not work for you at all if you use a lot of YAML. My use for it is to take frontmatter that includes only the created date in a specific format, and display it as shown below:
<img width="314" alt="CleanShot 2023-07-05 at 10 26 37@2x" src="https://github.com/gavinmn/obsidian-theme/assets/59900904/f45a4e62-ebd6-4232-840c-1d031133a1b4">

- `sidebar-redesign.css` cleans up the sidebar a bit and removes a lot of UI detail on Mobile
- `sf-symbols.css` replaces the Obsidian checkmark svg with the SF Symbols checkmark
- `highlight-color.css` changes the highlight color to a teal
- `code-color.css` changes inline code styling to use blue
