# CLAUDE.md — melayerka_hub

## SCSS conventions

- All variables (colours, fonts, weights, spacing, breakpoints) belong in `_sass/_variables.scss`. Never hardcode values in component files.
- All typography rules (font-size, letter-spacing, text-transform, font-family, font-weight, line-height, cursor on text elements) belong in `_sass/_typography.scss`. Component files handle layout and structural properties only.
- Component files (`_cards.scss`, `_contact.scss`, etc.) may use variables and reference colour/spacing tokens, but must not define new values inline.
