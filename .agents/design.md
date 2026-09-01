# instaclaw design context

## Overview

This repository currently contains a README and automation configuration. It
does not contain a user interface or an established design system. Use this
document to preserve that boundary until implemented design evidence exists.

## Colors

No product colors or semantic color roles are defined. New interface work must
define accessible light and dark tokens before it uses color. Do not copy
Instagram's palette or treat example colors as approved tokens.

## Typography

No product typeface, scale, weight system, or line-height rules are defined.
Choose typography for the interface being built. Document its source, license,
fallbacks, hierarchy, and code treatment with that implementation.

## Layout

No grid, spacing scale, breakpoint, content width, or navigation model is
defined. Base future layout decisions on real tasks and content. Record those
decisions in this file when the interface lands.

## Elevation & Depth

No shadows, overlays, stacking levels, or depth rules are defined. Introduce
them only when a component needs a clear hierarchy or interaction boundary.

## Shapes

No radius scale, icon geometry, border treatment, or illustration style is
defined. Do not infer shapes from the word `claw` or from Instagram branding.

## Components

No visual components exist. New components must define their states, keyboard
behavior, labels, focus treatment, and responsive behavior alongside the code.
Prefer shared components when repeated patterns emerge.

## Do's and Don'ts

- Do keep `instaclaw` lowercase.
- Do ground new rules in implemented source or approved assets.
- Do update this document when a design system starts to exist.
- Do test contrast, keyboard access, focus, and reduced motion.
- Don't invent a logo, palette, typeface, domain, or interface.
- Don't copy Instagram's protected visual identity.
- Don't claim unimplemented formats, workflows, or platform support.
