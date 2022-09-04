# Amazon Prime: Trending
Question (medium)

Amazon Prime: Trending
Amazon Prime Videos keeps a slide show of trending shows on the top. Let's try and build that slide show with some text data and eventually we can choose to add posters and trailers of different shows
Acceptance Criteria:-


• The App component takes an array of slides as a prop. Each element of this array denotes a single slide and is an object with 2 properties: title(string) and text(string).

• On application launch, the first slide must be rendered.

• Clicking on the "Next" button shows the next slide. This button is disabled when the current slide is the last one.

• Clicking on the "Prev" button shows the previous slide. This button is disabled when the current slide is the first one.

• Clicking on the "Restart" button returns to the first slide. This button is disabled when the current slide is the first one.

• You can assume that the passed slides array contains at least one slide.

• Slides data is in src/data.js.

• Initially, the file is filled with boilerplate code.<br>
<b>Note the following:</b>

• The "Restart" button must have data-testid="button-restart".

• The "Prev" button must have data-testid="button-prev".

• The "Next" button must have data-testid="button-next".

• Each slide's title must be rendered as an < h1 > element with data-testid="title".

• Each slide's text must be rendered as a < p > element with data-testid="text".
