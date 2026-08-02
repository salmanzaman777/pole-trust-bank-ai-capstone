# Pole Trust Bank UI Shell Refinement Requirements and Corrections

**Status:** Local implementation record — pre-deployment

## Corrected understanding

1. The document-navigation pane is hidden by default so the active document receives maximum layout space.
2. The navigation control is an ultra-modern, glowing, accessible and professional toggle.
3. The toggle is positioned at the extreme left, directly below the shared fixed application header; it must not sit over the header on the right.
4. The shared application header retains its original height, spacing, logo scale, typography, information layout and responsive behavior. The individual document hero sections are unchanged.
5. Tables remain fully readable without internal left-right scrolling through wrapping on wide screens and labelled responsive rows on compact screens.
6. The expanded navigation drawer uses a sleek separator and a narrower, usable scrollbar, while preserving document navigation and accessibility.

## Scope boundary

The header restoration applies only to the common application header containing NED University branding, course and project identity, preparer, Sponsor/Course Trainer, search and theme controls. The drawer and table improvements remain in scope; approved project content, document numbering, approvals, WBS, financial baseline and governance controls are unchanged.

## Acceptance evidence

- Default navigation state is closed, inert and accessible.
- The toggle opens/closes the drawer from the left edge below the header and supports the scrim, close control and Escape key.
- The restored desktop header retains the baseline height and original 88px logo scale.
- Desktop, tablet and mobile tables have no internal horizontal scrollbar and preserve all field values.
- Desktop and mobile layouts have no user-scrollable page-level horizontal overflow.
- Local structural and browser validators pass before hosted deployment.
