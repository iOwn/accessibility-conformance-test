| ID | axe-core ID / Title | Description | Impact | WCAG references |
|----|---|-----|---|---|
| AVT-1-1 | area-alt | Ensures `<area>` elements of image maps have alternate text | Critical | wcag-2-4-4, wcag-4-1-2 |
| AVT-1-2 | aria-allowed-attr | Ensures ARIA attributes are allowed for an element's role | Serious, Critical | wcag-4-1-2 |
| AVT-1-3 | aria-command-name | Ensures every ARIA button, link and menuitem has an accessible name | Serious | wcag-4-1-2 |
| AVT-1-4 | aria-hidden-body | Ensures aria-hidden='true' is not present on the document body. | Critical | wcag-4-1-2 |
| AVT-1-5 | aria-hidden-focus | Ensures aria-hidden elements are not focusable nor contain focusable elements | Serious | wcag-4-1-2 |
| AVT-1-6 | aria-input-field-name | Ensures every ARIA input field has an accessible name | Moderate, Serious | wcag-4-1-2 |
| AVT-1-7 | aria-meter-name | Ensures every ARIA meter node has an accessible name | Serious | wcag-1-1-1 |
| AVT-1-8 | aria-progressbar-name | Ensures every ARIA progressbar node has an accessible name | Serious | wcag-1-1-1 |
| AVT-1-9 | aria-required-attr | Ensures elements with ARIA roles have all required ARIA attributes | Critical | wcag-4-1-2 |
| AVT-1-10 | aria-required-children | Ensures elements with an ARIA role that require child roles contain them | Critical | wcag-1-3-1 |
| AVT-1-11 | aria-required-parent | Ensures elements with an ARIA role that require parent roles are contained by them | Critical | wcag-1-3-1 |
| AVT-1-12 | aria-roledescription | Ensure aria-roledescription is only used on elements with an implicit or explicit role | Serious | wcag-4-1-2 |
| AVT-1-13 | aria-roles | Ensures all elements with a role attribute use a valid value | Minor, Serious, Critical | wcag-4-1-2 |
| AVT-1-14 | aria-toggle-field-name | Ensures every ARIA toggle field has an accessible name | Moderate, Serious | wcag-4-1-2 |
| AVT-1-15 | aria-tooltip-name | Ensures every ARIA tooltip node has an accessible name | Serious | wcag-4-1-2 |
| AVT-1-16 | aria-valid-attr-value | Ensures all ARIA attributes have valid values | Serious, Critical | wcag-4-1-2 |
| AVT-1-17 | aria-valid-attr | Ensures attributes that begin with aria- are valid ARIA attributes | Critical | wcag-4-1-2 |
| AVT-1-18 | audio-caption | Ensures `<audio>` elements have captions | Critical | wcag-1-2-1 |
| AVT-1-19 | blink | Ensures `<blink>` elements are not used | Serious | wcag-2-2-2 |
| AVT-1-20 | button-name | Ensures buttons have discernible text | Critical | wcag-4-1-2 |
| AVT-1-21 | bypass | Ensures each page has at least one mechanism for a user to bypass navigation and jump straight to the content | Serious | wcag-2-4-1 |
| AVT-1-22 | color-contrast | Ensures the contrast between foreground and background colors meets WCAG 2 AA contrast ratio thresholds | Serious | wcag-1-4-3 |
| AVT-1-23 | definition-list | Ensures `<dl>` elements are structured correctly | Serious | wcag-1-3-1 |
| AVT-1-24 | dlitem | Ensures `<dt>` and `<dd>` elements are contained by a `<dl>` | Serious | wcag-1-3-1 |
| AVT-1-25 | document-title | Ensures each HTML document contains a non-empty `<title>` element	 | Serious | wcag-2-4-2 |
| AVT-1-26 | duplicate-id-active | Ensures every id attribute value of active elements is unique | Serious | wcag-4-1-1 |
| AVT-1-27 | duplicate-id-aria | Ensures every id attribute value used in ARIA and in labels is unique	 | Critical | wcag-4-1-1 |
| AVT-1-28 | duplicate-id | Ensures every id attribute value is unique	 | Minor | wcag-4-1-1 |
| AVT-1-29 | form-field-multiple-labels | Ensures form field does not have multiple label elements | Moderate | wcag-3-3-2 |
| AVT-1-30 | frame-focusable-content | Ensures `<frame>` and `<iframe>` elements with focusable content do not have tabindex=-1	 | Serious | wcag-2-1-1 |
| AVT-1-31 | frame-title | Ensures `<iframe>` and `<frame>` elements have an accessible name	 | Serious | wcag-4-1-2 |
| AVT-1-32 | html-has-lang | Ensures every HTML document has a lang attribute	 | Serious | wcag-3-1-1 |
| AVT-1-33  | html-lang-valid | Ensures the lang attribute of the `<html>` element has a valid value	 | Serious | wcag-3-1-1 |
| AVT-1-34 | html-xml-lang-mismatch | Ensure that HTML elements with both valid lang and xml:lang attributes agree on the base language of the page	 | Moderate | wcag-3-1-1 |
| AVT-1-35 | image-alt | Ensures `<img>` elements have alternate text or a role of none or presentation	 | Critical | wcag-1-1-1 |
| AVT-1-36 | input-button-name | Ensures input buttons have discernible text | Critical | wcag-4-1-2 |
| AVT-1-37 | input-image-alt | Ensures `<input type="image">` elements have alternate text	 | Critical | wcag-1-1-1, wcag-4-1-2 |
| AVT-1-38 | label | Ensures every form element has a label	 | Minor, Critical	 | wcag-4-1-2 |
| AVT-1-39 | link-name | Ensures links have discernible text	 | Serious | wcag-4-1-2, wcag-2-4-4 |
| AVT-1-40 | list | Ensures that lists are structured correctly		 | Serious | wcag-1-3-1 |
| AVT-1-41 | listitem | Ensures `<li>` elements are used semantically | Serious | wcag-1-3-1 |
| AVT-1-42 | marquee | Ensures `<marquee>` elements are not used	 | Serious | wcag-2-2-2 |
| AVT-1-43 | meta-refresh | Ensures `<meta http-equiv="refresh">` is not used for delayed refresh	 | Critical | wcag-2-2-1, wcag-2-2-4, wcag-3-2-5 |
| AVT-1-44 | nested-interactive | Ensures interactive controls are not nested as they are not always announced by screen readers or can cause focus problems for assistive technologies	 | Serious | wcag-4-1-2 |
| AVT-1-45 | no-autoplay-audio | Ensures `<video>` or `<audio>` elements do not autoplay audio for more than 3 seconds without a control mechanism to stop or mute the audio	 | Moderate | wcag-1-4-2 |
| AVT-1-46 | object-alt | Ensures `<object>` elements have alternate text	 | Serious | wcag-1-1-1 |
| AVT-1-47 | role-img-alt | Ensures `[role='img']` elements have alternate text	 | Serious | wcag-1-1-1 |
| AVT-1-48 | scrollable-region-focusable | Ensure elements that have scrollable content are accessible by keyboard	 | Moderate | wcag-2-1-1 |
| AVT-1-49 | select-name | Ensures select element has an accessible name | Minor, Critical | wcag-4-1-2 |
| AVT-1-50 | server-side-image-map | Ensures that server-side image maps are not used	 | Minor | wcag-2-1-1 |
| AVT-1-51 | svg-img-alt | Ensures `<svg>` elements with an img, graphics-document or graphics-symbol role have an accessible text | Serious | wcag-1-1-1 |
| AVT-1-52 | td-headers-attr | Ensure that each cell in a table that uses the headers attribute refers only to other cells in that table	 | Serious | wcag-1-3-1 |
| AVT-1-53 | th-has-data-cells | Ensure that `<th>` elements and elements with `role=columnheader/rowheader` have data cells they describe	 | Serious | wcag-1-3-1 |
| AVT-1-54 | valid-lang | Ensures lang attributes have valid values | Serious | wcag-3-1-2 |
| AVT-1-55 | video-caption | Ensures `<video>` elements have captions	 | Critical | wcag-1-2-2 |
| AVT-1-56 | autocomplete-valid | Ensure the autocomplete attribute is correct and suitable for the form field	 | Serious | wcag-1-3-5 |
| AVT-1-56 | avoid-inline-spacing | Ensure that text spacing set through style attributes can be adjusted with custom stylesheets | Serious | wcag-1-4-12 |
| AVT-1-56 | color-contrast-enhanced | Ensures the contrast between foreground and background colors meets WCAG 2 AAA contrast ratio thresholds | Serious | wcag-1-4-6 |
| AVT-1-57 | identical-links-same-purpose | Ensure that links with the same accessible name serve a similar purpose	 | Minor | wcag-2-4-9 |
| AVT-1-58 | meta-refresh-no-exceptions | Ensures `<meta http-equiv="refresh">` is not used for delayed refresh	 | Minor | wcag-2-2-4, wcag-3-2-5 |

| <!--ID--> | <!--axe-core ID / Title--> | <!--Description--> | <!--Impact--> | <!--WCAG references--> |