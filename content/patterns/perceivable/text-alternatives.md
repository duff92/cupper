+++
title = "1.1.1 Non-text Content"
weight = 1
+++

Text alternatives must be provided for non-text content like images, controls, and multimedia to ensure equal access to information. This enables the content to be converted into formats that users need, like braille, speech, or large print.

## Intent

Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.

## How to Meet

1. For images:
   - Add descriptive alt text that conveys the purpose/meaning
   - Use empty alt="" for decorative images
   - Include longer descriptions via figcaption, aria-describedby, or links for complex images
   - Ensure charts and graphs have text equivalents explaining the data

2. For controls and input:
   - Label all form controls with descriptive text
   - Use aria-label or aria-labelledby when needed
   - Ensure buttons and links have clear text describing their action
   - Provide transcripts for audio/video content

## Common Failures

- Missing or inadequate alt text on images
- Using placeholder text as the only label for form fields
- Generic descriptions like "image" or "photo" that don't convey meaning
- Lack of text alternatives for multimedia content
- Missing labels on buttons and form controls

{{% wcag include="1.1.1" %}}
