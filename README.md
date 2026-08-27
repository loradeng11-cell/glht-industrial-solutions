# GLHT Industrial Solutions — V6.5 FIXED

This release fixes the two missing-image areas reported in V6.4.

Root cause:
The HTML references were correct, but the CSS still contained old hardcoded rules that:
- hid the Manufacturing Reality video/poster, and
- hid the Production Capacity image,
while pointing to a deleted old team image.

V6.5 fixes those CSS rules and uses a new stylesheet filename (`style-v65.css`) to bypass browser/GitHub Pages cache.

Confirmed:
- From Engineering Intent to Manufacturing Reality: visible video/poster.
- Production Capacity That Scales With the Program: visible factory image.
- Requirements Evolve team image remains separate.
- Floating Talk to Our Team remains unchanged.

Upload the CONTENTS of this folder to the repository root and replace the old files.
