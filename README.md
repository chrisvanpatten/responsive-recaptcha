# Responsive reCAPTCHA

This is a quick theme for <a href="https://www.google.com/recaptcha">reCAPTCHA</a> that makes it friendlier to responsive websites, specifically on mobile interfaces where you might need the captcha narrower than 300px wide.

<img src="http://i.imgur.com/qfwQu.png" alt="Responsive reCAPTCHA screenshot">

## Prerequisites

Here's what you need:

*   You should have reCAPTCHA set up already
*   If you want to work with the SASS file, you will need <a href="http://compass-style.org/">Compass</a>.
*   <a href="http://fortawesome.github.com/Font-Awesome/">Font-Awesome</a> is referenced for the icons (but any icon font, or images, would work)

## Other notes

If you're using an existing reCAPTCHA library, you might want to add the custom HTML to the `recaptcha_get_html` output function to simplify the process of adding reCAPTCHAs.

Also, in my original implementation (visible above) I used the wonderful <a href="https://github.com/nathansmith/formalize">Formalize</a> from @nathansmith. It's not required, but I can't recommend it highly enough.

If you want to customize this further and have questions, feel free to ask or consult <a href="https://developers.google.com/recaptcha/docs/customization">Google's documentation</a> on the subject.

## Unlicense

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>