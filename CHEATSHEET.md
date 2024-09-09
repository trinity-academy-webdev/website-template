Solutions for the Trinity Coding Club web development project.

These aren't the only correct answers, but hopefully will serve as a useful reference if you're trying to nudge students in the right direction.

Note that line number references are correct for the initial, broken site. Students will add and remove content so the actual locations might change.
# Session 2: Starting Development

All modifications are made to `index.html.`

## 1. Changing the title
The title is located on line 27.
It is up to the student to decide what their page title is.

The tagline is located immediately below the title.

## 2. Changing the description
The description paragraph begins on line 35.
It is up to the student to decide what it contains. Some suggestions might be:
- A description of the types of charity work they do
- The goals of the charity
- Head of the charity (i.e. the student themselves)

## 3. Adding an image
The student can insert an image immediately after the description section.
Make sure they're using the appropriate path for the image (i.e. if it's located in the Charity Images subdirectory, they should include this in the path.)

## 4. Changing the chosen charity
The "CHARITY 2024-2025" text is located on line 42.
The student can change this to any charity of their choice.

## 5. Adding a hyperlink to charity website
This can be done by modifying the above text:
```
<a href="www.link.goes.here.com"><h1>CHARITY 2024-25</h1></a>
```

# Session 3: Gallery and Styles
Students will modify both `gallery.html` and `gallery-styles.css`.

## 1. Changing the background
The `hero-section` styling is located on line 77 of `gallery-styles.css`. They can insert a background and create a gradient with two lines like this:

```
background-color: #8BC6EC;
background-image: linear-gradient(135deg, #8BC6EC 0%, #9599E2 100%);
```

The first argument of `linear-gradient` controls the angle of the gradient.

## 2. Centre the gallery element
There are likely multiple ways of centering the gallery, but the simplest is to add the following line to the `slideshow-container` styling (located at line 99 of `gallery-styles.css`)
```
margin: auto;
```

To centre the navigation dots, they can modify line 47 of `gallery.html` to add inline CSS.
```
<div style="text-align:center">
```

## 3. Change the image border
The border can be added by modifying the `slideshow-container` styling (located at line 99 of `gallery-styles.css`). They have creative control here. An example of an appropriate value is:
```
border: 3px solid #f1f1f1;
```

# Session 4. Events Section
All modifications are made to `events.html.
## 1. Add the listed information to the past events table

More sensible values for the table row widths are:
```
<th style="width: 20%;">Event</th>
<th style="width: 40%;">Description</th>
<th style="width: 20%;">Location</th>
<th style="width: 20%;">Amount Raised</th>
```

Students should take the appropriate values from the long-form description and insert them into their respective columns in the table.

## 2. Create a future events table and come up with innovative charity events to put in it!

The table header for the student's new table should look like:
```
<table>
	<tr>
		<th>Event</th>
		<th>Description</th>
		<th>Target Money Raised</th>
	</tr>
```
