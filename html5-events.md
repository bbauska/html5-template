<h2 id="3-html-events">HTML Events</h2>

<h3>Types of Events</h3>

<h4>There are muliple types; Window, Form, Keyboard, Mouse, Drag, Clipboard, 
Media, &amp; Miscellaneous.</h4>

<h4 id="global-events">Global Event Attributes</h4>
HTML has the ability to let events trigger actions in a browser, like starting a JavaScript when a user clicks on an element.

Below are the global event attributes that can be added to HTML elements to define event actions.

<h4 id="window-events">Window Event Attributes</h4>
<p>Events triggered for the window object (applies to the &lt;body&gt; tag):</p>

| Attribute      | Value  | Description |
|----------------|--------|--------------------------------------------------------------------------|
| onafterprint   | script | Script to be run after the document is printed |
| onbeforeprint  | script | Script to be run before the document is printed |
| onbeforeunload | script | Script to be run when the document is about to be unloaded |
| onerror        | script | Script to be run when an error occurs |
| onhashchange   | script | Script to be run when there has been changes to the anchor part of the a URL |
| onload         | script | Fires after the page is finished loading |
| onmessage      | script | Script to be run when the message is triggered |
| onoffline      | script | Script to be run when the browser starts to work offline |
| ononline       | script | Script to be run when the browser starts to work online |
| onpagehide     | script | Script to be run when a user navigates away from a page |
| onpageshow     | script | Script to be run when a user navigates to a page |
| onpopstate     | script | Script to be run when the window's history changes |
| onresize       | script | Fires when the browser window is resized |
| onstorage      | script | Script to be run when a Web Storage area is updated |
| onunload       | script | Fires once a page has unloaded (or the browser window has been closed) |

<h4 id="form-events">Form Events</h4>
<p>Events triggered by actions inside a HTML form (applies to almost all HTML elements, but is most used in form elements):</p>

| Attribute      | Value  | Description |
|----------------|--------|--------------------------------------------------------------------------|
| onblur         | script | Fires the moment that the element loses focus |
| onchange       | script | Fires the moment when the value of the element is changed |
| oncontextmenu  | script | Script to be run when a context menu is triggered |
| onfocus        | script | Fires the moment when the element gets focus |
| oninput        | script | Script to be run when an element gets user input |
| oninvalid      | script | Script to be run when an element is invalid |
| onreset        | script | Fires when the Reset button in a form is clicked |
| onsearch       | script | Fires when the user writes something in a search field (for &lt;input="search"&gt;) |
| onselect       | script | Fires after some text has been selected in an element |
| onsubmit       | script | Fires when a form is submitted |

<h4 id="keyboard-events">Keyboard Events</h4>

| Attribute  | Value  | Description |
|------------|--------|--------------------------------------------------------------------------|
| onkeydown  | script | Fires when a user is pressing a key |
| onkeypress | script | Fires when a user presses a key |
| onkeyup    | script | Fires when a user releases a key |

<h4 id="mouse-events">Mouse Events</h4>

| Attribute    | Value  | Description |
|--------------|--------|--------------------------------------------------------------------------|
| onclick      | script | Fires on a mouse click on the element |
| ondblclick   | script | Fires on a mouse double-click on the element |
| onmousedown  | script | Fires when a mouse button is pressed down on an element |
| onmousemove  | script | Fires when the mouse pointer is moving while it is over an element |
| onmouseout   | script | Fires when the mouse pointer moves out of an element |
| onmouseover  | script | Fires when the mouse pointer moves over an element |
| onmouseup    | script | Fires when a mouse button is released over an element |
| onmousewheel | script | Deprecated. Use the onwheel attribute instead |
| onwheel      | script | Fires when the mouse wheel rolls up or down over an element |

<h4 id="drag-events">Drag Events</h4>

| Attribute    | Value  | Description |
|--------------|--------|--------------------------------------------------------------------------|
| ondrag       | script | Script to be run when an element is dragged |
| ondragend    | script | Script to be run at the end of a drag operation |
| ondragenter  | script | Script to be run when an element has been dragged to a valid drop target |
| ondragleave  | script | Script to be run when an element leaves a valid drop target |
| ondragover   | script | Script to be run when an element is being dragged over a valid drop target |
| ondragstart  | script | Script to be run at the start of a drag operation |
| ondrop       | script | Script to be run when dragged element is being dropped |
| onscroll     | script | Script to be run when an element's scrollbar is being scrolled |

<h4 id="clipboard-events">Clipboard Events</h4>

| Attribute       | Value    | Description |
|----------------|--------|--------------------------------------------------------------------------|
| oncopy    | script  |   Fires when the user copies the content of an element |
| oncut    | script    | Fires when the user cuts the content of an element |
| onpaste  |   script   |  Fires when the user pastes some content in an element |

<h4 id="media-events">Media Events</h4>

<p>Events triggered by medias like videos, images and audio (applies to all HTML 
elements, but is most common in media elements, like &lt;audio&gt;, &lt;embed&gt;, &lt;img&gt;, 
&lt;object&gt;, and &lt;video&gt;).</p>

|Attribute       |Value    |Description |
|----------------|--------|--------------------------------------------------------------------------|
| onabort    | script |    Script to be run on abort |
| oncanplay    | script |    Script to be run when a file is ready to start playing (when it has buffered enough to begin) |
| oncanplaythrough |  script |    Script to be run when a file can be played all the way to the end without pausing for buffering |
| oncuechange    | script |    Script to be run when the cue changes in a <track> element |
| ondurationchange |    script |    Script to be run when the length of the media changes |
| onemptied   |  script  |   Script to be run when something bad happens and the file is suddenly unavailable (like unexpectedly disconnects) |
| onended    | script  |   Script to be run when the media has reach the end (a useful event for messages like "thanks for listening") |
| onerror    | script  |   Script to be run when an error occurs when the file is being loaded |
| onloadeddata  |   script |    Script to be run when media data is loaded |
| onloadedmetadata |    script |    Script to be run when meta data (like dimensions and duration) are loaded |
| onloadstart    | script  |   Script to be run just as the file begins to load before anything is actually loaded |
| onpause  |   script |    Script to be run when the media is paused either by the user or programmatically |
| onplay   |  script  |   Script to be run when the media is ready to start playing |
| onplaying  |   script |    Script to be run when the media actually has started playing |
| onprogress   |  script  |   Script to be run when the browser is in the process of getting the media data |
| onratechange   |  script |    Script to be run each time the playback rate changes (like when a user switches to a slow motion or fast forward mode) |
| onseeked   |  script  |   Script to be run when the seeking attribute is set to false indicating that seeking has ended |
| onseeking   |  script   |  Script to be run when the seeking attribute is set to true indicating that seeking is active |
| onstalled  |   script |    Script to be run when the browser is unable to fetch the media data for whatever reason |
| onsuspend |    script   |  Script to be run when fetching the media data is stopped before it is completely loaded for whatever reason |
| ontimeupdate |    script  |   Script to be run when the playing position has changed (like when the user fast forwards to a different point in the media) |
| onvolumechange |    script |    Script to be run each time the volume is changed which (includes setting the volume to "mute") |
| onwaiting   |  script  |   Script to be run when the media has paused but is expected to resume (like when the media pauses to buffer more data) |

<h4 id="misc-events">Misc Events</h4>

|Attribute       |Value    |Description |
|----------------|--------|--------------------------------------------------------------------------|
| ontoggle | script | Fires when the user opens or closes the &lt;details&gt; element |
