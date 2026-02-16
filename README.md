Form Elements
Definition: Elements that collect and submit user input data
form - Container that holds all form elements
input - Creates various fields (text, email, password, radio, checkbox)
label - Provides description for form fields
select - Creates dropdown list with option items
textarea - Multi-line text input box
button - Clickable button that performs actions
fieldset - Groups related form elements visually
legend - Provides caption for fieldset group
datalist - Provides auto-complete suggestions for input
output - Displays calculation or script results
optgroup - Groups related options inside select dropdown

Formatting
Definition: Tags that change text appearance and meaning
b - Makes text bold (visual only)
strong - Makes text bold with semantic importance
i - Makes text italic (visual only)
em - Makes text italic with emphasis (semantic)

mark - Highlights text with yellow background
small - Makes text smaller (fine print, disclaimers)
del - Shows deleted text with strikethrough
ins - Shows inserted text with underline
sub - Lowers text below baseline (chemical formulas)
sup - Raises text above baseline (exponents, footnotes)

Graphics
Definition: Visual elements drawn on web pages
Canvas - JavaScript-based pixel drawing (bitmap graphics)
SVG - XML-based vector graphics (scalable without quality loss)
Canvas is resolution-dependent (pixelates when zoomed)
SVG scales perfectly at any size
Canvas draws shapes with JavaScript commands
SVG uses XML tags like circle, rect, path, polygon

Images
Definition: Visual content embedded in web pages
img tag - Embeds images in HTML
src attribute - Specifies image source URL or path
alt attribute - Provides text description for screen readers (accessibility)
width and height - Sets image dimensions in pixels
title attribute - Shows tooltip text on hover

Quotation and Citation
Definition: Elements that mark quoted content and references
blockquote - Long quotation (indented from both sides)
q - Short inline quotation (adds quotation marks)
cite - Title of creative work (book, painting, song)
abbr - Abbreviation with full form in title attribute
address - Contact information (italic, block display)
bdo - Changes text direction (rtl for right-to-left)

Tables
Definition: Grid structure to display data in rows and columns
table - Creates the table container
tr - Defines table row
th - Table header cell (bold, centered)
td - Table data cell (regular text)
caption - Provides title/description for table
border - Adds borders around cells (attribute or CSS)

Hyperlinks
Definition: Clickable links that navigate to other pages or sections
a tag - Anchor tag creates hyperlinks
href attribute - Specifies link destination URL
target="_blank" - Opens link in new browser tab
Anchor links - Links to specific page sections using #id
Email links - mailto:email@example.com opens email client

Media
Definition: Multimedia content embedded in web pages
video - Embeds video files (MP4, WebM, Ogg)
audio - Embeds audio files (MP3, WAV, Ogg)
source - Provides multiple media formats for compatibility
controls - Adds play, pause, volume controls
iframe - Embeds YouTube videos or external content
object - Embeds external content (PDF, Flash - legacy)
embed - Alternative plugin embedding method

APIs
Definition: Web APIs allow HTML pages to interact with browser features and device capabilities
Geolocation - Gets user's current position (latitude and longitude)
Web Storage - Saves data locally in browser (localStorage/sessionStorage)
Drag and Drop - Allows dragging elements across the page
Web Workers - Runs JavaScript in background without affecting page performance
SSE (Server-Sent Events) - Auto-updates from server without requesting

Background Image
Definition: An image placed behind HTML content using CSS
Added using CSS background-image property
Syntax: style="background-image: url('image.jpg')"
Can be applied to any HTML element (div, body, section, etc.)
Properties: background-repeat (tile), background-size (cover/contain), background-position
