<h2 class="c-project-heading--task">Give your robot eyes</h2>

Choose an image and use the `id` to style it.

## Step 1

Click on the `style.css` file. 

<div class="c-project-output">
![screenshot](images/step2a.png)
</div>

## Step 2

Add the CSS code below to style the robot eyes. Experiment with `width` to make the eyes bigger or smaller.

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 4
line_highlights: 7-9
---
#face {
	width: 400px;
}
#eyes1 {
    width: 400px;
    }

--- /code ---

</div>

## Now run your code

Run your code and check that the robot’s eyes change size when you scroll down.

Try changing the `width` on different features. For example, you can use `#eyes2` or `#eyes3`.


<div class="c-project-output">

![screenshot](images/robot-eyes-width.png)

</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

Each image in this project has its own name (or `id`). For example, `<img id="face" ...>` or `<img id="eyes1" ...>`. This allows you to style each image separately.

</div>

