Storybook Tutorial

```
npx create-react-app float-app

cd float-app

npx -p @storybook/cli sb init
```

In the root folder of the project add a new file called `.env` with the following:

```
SKIP_PREFLIGHT_CHECK=true
```

check that the various environments of our application are working properly:

```bash
# Run the test runner (Jest) in a terminal:
yarn test --watchAll

# Start the component explorer on port 6006:
yarn storybook

# Run the frontend app proper on port 3000:
yarn start
```

Edit style in [LESS files](https://github.com/chromaui/learnstorybook-code/tree/master/src/style).

To match the intended design, you'll need to download both the font and icon directories and place its contents inside your `src/assets` folder. Issue the following commands in your terminal:

```bash
npx degit chromaui/learnstorybook-code/src/assets/font src/assets/font
npx degit chromaui/learnstorybook-code/src/assets/icon src/assets/icon
```

![img](/Users/jhwncho/Documents/GitHub/choprairie/static/dc1fc4c56aed1be833af6ef12fbf2ead.png)

![img](/Users/jhwncho/Documents/GitHub/choprairie/static/Troupe+Style+Guide-20210114091904528.png)

ABCDEFGHIJKLM
NOPQRSTUVWXYZ
abcdefghijklm
nopqrstuvwxyz
1234567890<img src="/Users/jhwncho/Documents/GitHub/choprairie/static/Airbnb+UI+Kit.jpg" alt="Airbnb UI Kit.jpg" style="zoom:200%;" />

<details>    <input class="variation" id="bluepurple" type="radio" value="1" name="color" checked="checked"/>
<label for="bluepurple"></label>
<input class="variation" id="sunset" type="radio" value="2" name="color"/>
<label for="sunset"></label>
<input class="variation" id="godiva" type="radio" value="3" name="color"/>
<label for="godiva"></label>
<input class="variation" id="dark" type="radio" value="4" name="color"/>
<label for="dark"></label>
<input class="variation" id="pinkaru" type="radio" value="5" name="color"/>
<label for="pinkaru"></label>
<main>
  <section class="colors">
    <h6>colors</h6>
    <div class="palette main">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Primary</h5>
    </div>
    <div class="palette secondary">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Secondary</h5>
    </div>
    <div class="palette accent1">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #1</h5>
    </div>
    <div class="palette accent2">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #2</h5>
    </div>
    <div class="palette accent3">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #3</h5>
    </div>
    <div class="palette neutrals">
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Neutrals</h5>
    </div>
  </section>
  <section class="typography">
    <h6>typography</h6>
    <div class="font-family">
      <div class="font-family-bold">
        <h1>Aa</h1>
        <h4>Poppins Bold</h4>
      </div>
      <div class="font-family-medium">
        <h1>Aa</h1>
        <h4>Poppins Medium</h4>
      </div>
      <div class="font-family-light">
        <h1>Aa</h1>
        <h4>Poppins Light</h4>
      </div>
    </div>
    <div class="font-example">
      <div class="font-example__headline">
        <h6 class="subheader">Headlines</h6>
        <h1>h1 headline</h1>
        <h2>h2 headline</h2>
        <h3>h3 headline</h3>
        <h4>h4 headline</h4>
        <h5>h5 headline</h5>
        <h6>h6 headline</h6>
      </div>
      <div class="font-example__bodytext">
        <h6 class="subheader">Body Text</h6>
        <p>I think we need to start from scratch. Jazz it up a little bit- use a funky color like purple.</p>
        <p><strong> Can you add a bit of pastel pink and baby blue because the purple alone looks too fancy.</strong></p>
        <p><em> Make the purple more well, purple-er. Try a more powerful colour, it needs to be the same, but totally different.</em></p>
      </div>
    </div>
  </section>
  <section class="buttons-wrapper">
    <h6>Buttons</h6>
    <div class="buttons"><a class="button">Default Button</a>
      <input class="button hover" type="button" value="Hovered Button"/>
      <button class="button active">Active Button</button><a class="button disabled">Disabled Button</a><a class="button secondary">Secondary Button</a><a class="button accent">Other Button</a><a class="button accent2">Other Button</a><a class="button accent3">Another Button</a>
      <div><a class="button medium">Medium Button</a><a class="button small">Smol Button</a></div>
    </div>
  </section>
  <section class="links">
    <h6>Links</h6>
    <div class="links__sec"><a class="link">Sample Link</a><br/><a class="link hover">Hovered Link</a></div>
    <div class="links__sec"><a class="link primary">Sample Link</a><br/><a class="link primary hover">Hovered Link</a></div>
    <div class="links__sec"><a class="link secondary">Sample Link</a><br/><a class="link secondary hover">Hovered Link</a></div>
  </section>
  <section class="inputs-selects">
    <h6>Inputs & Selects</h6>
    <div class="inputs">
      <div class="input__wrapper">
        <label class="label-form">A Normal Input</label>
        <input class="input-form" type="text" placeholder="Placeholder"/>
        <p class="feedback-form">A message here.</p>
      </div>
      <div class="input__wrapper">
        <label class="label-form">An Active Input</label>
        <input class="input-form active" type="text" placeholder="Placeholder" value="Typing Here..."/>
      </div>
      <div class="input__wrapper">
        <label class="label-form">A Disabled Input</label>
        <input class="input-form" type="text" placeholder="Placeholder" disabled="disabled"/>
      </div>
      <div class="input__wrapper">
        <label class="label-form">A Normal Select</label>
        <select type="text" placeholder="Placeholder">
          <option value="1">Option 1</option>
          <option value="2">Option 2		</option>
        </select>
      </div>
    </div>
    <div class="textarea-select">
      <div class="input__wrapper input-success">
        <label class="label-form">A Right Input</label>
        <div class="input__validator">
          <input class="input-form" type="text" placeholder="Placeholder"/>
          <div class="input__validator__status"></div>
        </div>
        <p class="feedback-form">Awesome job.</p>
      </div>
      <div class="input__wrapper input-error">
        <label class="label-form">A Left Input</label>
        <div class="input__validator">
          <input class="input-form" type="text" placeholder="Placeholder"/>
          <div class="input__validator__status"></div>
        </div>
        <p class="feedback-form">You shall not pass.</p>
      </div>
      <div class="input__wrapper">
        <label class="label-form">Textarea</label>
        <textarea type="text" placeholder="Placeholder"></textarea>
      </div>
    </div>
    <div class="toggle-buttons">
      <h6 class="subheader">Toggle Buttons</h6>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox" type="checkbox"/>
        <label for="toggle-checkbox"></label>
      </div>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox-1" type="checkbox" checked="checked"/>
        <label for="toggle-checkbox-1"></label>
      </div>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox-2" type="checkbox" disabled="disabled"/>
        <label for="toggle-checkbox-2"></label>
      </div>
    </div>
    <div class="checkboxes">
      <h6 class="subheader">Checkboxes</h6>
      <div class="checkbox">
        <input id="checkbox-1" type="checkbox"/>
        <label for="checkbox-1">Checkbox<span class="box"></span></label>
      </div>
      <div class="checkbox">
        <input id="checkbox-2" type="checkbox" checked="checked"/>
        <label for="checkbox-2">Checked Box<span class="box"></span></label>
      </div>
    </div>
    <div class="radio-buttons">
      <h6 class="subheader">Radio Buttons</h6>
      <div class="radio">
        <input id="radio-1" type="radio" name="radio-test" value="1" checked="checked"/>
        <label for="radio-1">Radio Button</label>
      </div>
      <div class="radio">
        <input id="radio-2" type="radio" name="radio-test" value="1"/>
        <label for="radio-2">Selected Radio Button</label>
      </div>
    </div>
  </section>
  <section class="badges">
    <h6>Badges</h6><span class="badge status-primary">Received</span><span class="badge status-secondary">Pending</span><span class="badge status-info">Pending</span><span class="badge status-success">Approved</span><span class="badge status-error">Rejected</span>
  </section>
  <section class="tooltips">
    <h6>Tooltips</h6>
    <div>
      <div class="tooltip top hovered" data-tooltip="Show a helpful tooltip here 😄"> <span>Light Tooltip</span></div>
      <div class="tooltip top dark hovered" data-tooltip="Show a helpful tooltip here 😄"> <span>Dark Tooltip</span></div>
      <div class="tooltip bottom" data-tooltip="Hello 👋"> <span>Bottom Tooltip</span></div>
    </div>
  </section>
  <section class="alerts">
    <h6>Alerts</h6>
    <div class="alert status-primary">A normal alert here.</div>
    <div class="alert status-secondary">A normal alert here.</div>
    <div class="alert status-info">A normal alert here.</div>
    <div class="alert status-success">A happy alert here.</div>
    <div class="alert status-error">A sad alert here.</div>
  </section>
  <section class="loading">
    <h6>loading indicators</h6>
    <div class="spinner-1">
      <div class="spinner" data-loading="Loading..."></div>
      <label>Please wait...</label>
    </div>
    <div class="spinner-2">
      <div class="spinner" data-loading="Loading..."></div>
      <label>Loading...</label>
    </div>
  </section>
</main>     A keyboard. </details>

```html
<input class="variation" id="bluepurple" type="radio" value="1" name="color" checked="checked"/>
<label for="bluepurple"></label>
<input class="variation" id="sunset" type="radio" value="2" name="color"/>
<label for="sunset"></label>
<input class="variation" id="godiva" type="radio" value="3" name="color"/>
<label for="godiva"></label>
<input class="variation" id="dark" type="radio" value="4" name="color"/>
<label for="dark"></label>
<input class="variation" id="pinkaru" type="radio" value="5" name="color"/>
<label for="pinkaru"></label>
<main>
  <section class="colors">
    <h6>colors</h6>
    <div class="palette main">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Primary</h5>
    </div>
    <div class="palette secondary">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Secondary</h5>
    </div>
    <div class="palette accent1">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #1</h5>
    </div>
    <div class="palette accent2">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #2</h5>
    </div>
    <div class="palette accent3">
      <div class="palette__main"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Accent #3</h5>
    </div>
    <div class="palette neutrals">
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <div class="palette__shade"></div>
      <h5>Neutrals</h5>
    </div>
  </section>
  <section class="typography">
    <h6>typography</h6>
    <div class="font-family">
      <div class="font-family-bold">
        <h1>Aa</h1>
        <h4>Poppins Bold</h4>
      </div>
      <div class="font-family-medium">
        <h1>Aa</h1>
        <h4>Poppins Medium</h4>
      </div>
      <div class="font-family-light">
        <h1>Aa</h1>
        <h4>Poppins Light</h4>
      </div>
    </div>
    <div class="font-example">
      <div class="font-example__headline">
        <h6 class="subheader">Headlines</h6>
        <h1>h1 headline</h1>
        <h2>h2 headline</h2>
        <h3>h3 headline</h3>
        <h4>h4 headline</h4>
        <h5>h5 headline</h5>
        <h6>h6 headline</h6>
      </div>
      <div class="font-example__bodytext">
        <h6 class="subheader">Body Text</h6>
        <p>I think we need to start from scratch. Jazz it up a little bit- use a funky color like purple.</p>
        <p><strong> Can you add a bit of pastel pink and baby blue because the purple alone looks too fancy.</strong></p>
        <p><em> Make the purple more well, purple-er. Try a more powerful colour, it needs to be the same, but totally different.</em></p>
      </div>
    </div>
  </section>
  <section class="buttons-wrapper">
    <h6>Buttons</h6>
    <div class="buttons"><a class="button">Default Button</a>
      <input class="button hover" type="button" value="Hovered Button"/>
      <button class="button active">Active Button</button><a class="button disabled">Disabled Button</a><a class="button secondary">Secondary Button</a><a class="button accent">Other Button</a><a class="button accent2">Other Button</a><a class="button accent3">Another Button</a>
      <div><a class="button medium">Medium Button</a><a class="button small">Smol Button</a></div>
    </div>
  </section>
  <section class="links">
    <h6>Links</h6>
    <div class="links__sec"><a class="link">Sample Link</a><br/><a class="link hover">Hovered Link</a></div>
    <div class="links__sec"><a class="link primary">Sample Link</a><br/><a class="link primary hover">Hovered Link</a></div>
    <div class="links__sec"><a class="link secondary">Sample Link</a><br/><a class="link secondary hover">Hovered Link</a></div>
  </section>
  <section class="inputs-selects">
    <h6>Inputs & Selects</h6>
    <div class="inputs">
      <div class="input__wrapper">
        <label class="label-form">A Normal Input</label>
        <input class="input-form" type="text" placeholder="Placeholder"/>
        <p class="feedback-form">A message here.</p>
      </div>
      <div class="input__wrapper">
        <label class="label-form">An Active Input</label>
        <input class="input-form active" type="text" placeholder="Placeholder" value="Typing Here..."/>
      </div>
      <div class="input__wrapper">
        <label class="label-form">A Disabled Input</label>
        <input class="input-form" type="text" placeholder="Placeholder" disabled="disabled"/>
      </div>
      <div class="input__wrapper">
        <label class="label-form">A Normal Select</label>
        <select type="text" placeholder="Placeholder">
          <option value="1">Option 1</option>
          <option value="2">Option 2		</option>
        </select>
      </div>
    </div>
    <div class="textarea-select">
      <div class="input__wrapper input-success">
        <label class="label-form">A Right Input</label>
        <div class="input__validator">
          <input class="input-form" type="text" placeholder="Placeholder"/>
          <div class="input__validator__status"></div>
        </div>
        <p class="feedback-form">Awesome job.</p>
      </div>
      <div class="input__wrapper input-error">
        <label class="label-form">A Left Input</label>
        <div class="input__validator">
          <input class="input-form" type="text" placeholder="Placeholder"/>
          <div class="input__validator__status"></div>
        </div>
        <p class="feedback-form">You shall not pass.</p>
      </div>
      <div class="input__wrapper">
        <label class="label-form">Textarea</label>
        <textarea type="text" placeholder="Placeholder"></textarea>
      </div>
    </div>
    <div class="toggle-buttons">
      <h6 class="subheader">Toggle Buttons</h6>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox" type="checkbox"/>
        <label for="toggle-checkbox"></label>
      </div>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox-1" type="checkbox" checked="checked"/>
        <label for="toggle-checkbox-1"></label>
      </div>
      <div class="checkbox-toggle">
        <input id="toggle-checkbox-2" type="checkbox" disabled="disabled"/>
        <label for="toggle-checkbox-2"></label>
      </div>
    </div>
    <div class="checkboxes">
      <h6 class="subheader">Checkboxes</h6>
      <div class="checkbox">
        <input id="checkbox-1" type="checkbox"/>
        <label for="checkbox-1">Checkbox<span class="box"></span></label>
      </div>
      <div class="checkbox">
        <input id="checkbox-2" type="checkbox" checked="checked"/>
        <label for="checkbox-2">Checked Box<span class="box"></span></label>
      </div>
    </div>
    <div class="radio-buttons">
      <h6 class="subheader">Radio Buttons</h6>
      <div class="radio">
        <input id="radio-1" type="radio" name="radio-test" value="1" checked="checked"/>
        <label for="radio-1">Radio Button</label>
      </div>
      <div class="radio">
        <input id="radio-2" type="radio" name="radio-test" value="1"/>
        <label for="radio-2">Selected Radio Button</label>
      </div>
    </div>
  </section>
  <section class="badges">
    <h6>Badges</h6><span class="badge status-primary">Received</span><span class="badge status-secondary">Pending</span><span class="badge status-info">Pending</span><span class="badge status-success">Approved</span><span class="badge status-error">Rejected</span>
  </section>
  <section class="tooltips">
    <h6>Tooltips</h6>
    <div>
      <div class="tooltip top hovered" data-tooltip="Show a helpful tooltip here 😄"> <span>Light Tooltip</span></div>
      <div class="tooltip top dark hovered" data-tooltip="Show a helpful tooltip here 😄"> <span>Dark Tooltip</span></div>
      <div class="tooltip bottom" data-tooltip="Hello 👋"> <span>Bottom Tooltip</span></div>
    </div>
  </section>
  <section class="alerts">
    <h6>Alerts</h6>
    <div class="alert status-primary">A normal alert here.</div>
    <div class="alert status-secondary">A normal alert here.</div>
    <div class="alert status-info">A normal alert here.</div>
    <div class="alert status-success">A happy alert here.</div>
    <div class="alert status-error">A sad alert here.</div>
  </section>
  <section class="loading">
    <h6>loading indicators</h6>
    <div class="spinner-1">
      <div class="spinner" data-loading="Loading..."></div>
      <label>Please wait...</label>
    </div>
    <div class="spinner-2">
      <div class="spinner" data-loading="Loading..."></div>
      <label>Loading...</label>
    </div>
  </section>
</main>
<footer>
  <div class="explanation">Part of the  <a href="https://codepen.io/collection/DQvYpQ" target="_blank">CSS Grid collection here</a>.</div>
  <div class="social"><a href="https://twitter.com/meowlivia_" target="_blank"><i class="icon-social-twitter icons"></i></a><a href="https://github.com/oliviale" target="_blank"><i class="icon-social-github icons"></i></a><a href="https://dribbble.com/oliviale" target="_blank"><i class="icon-social-dribbble icons"></i></a></div>
</footer>
```



dfdfd



input#bluepurple.variation(type="radio", value="1", name="color", checked)
label(for="bluepurple")

input#sunset.variation(type="radio", value="2", name="color")
label(for="sunset")

input#godiva.variation(type="radio", value="3", name="color")
label(for="godiva")

input#dark.variation(type="radio", value="4", name="color")
label(for="dark")

input#pinkaru.variation(type="radio", value="5", name="color")
label(for="pinkaru")

main
	section.colors
		h6 colors
		.palette.main
			.palette__main
			- for (var i=0; i<6; i++)
				.palette__shade
			h5 Primary
		.palette.secondary
			.palette__main
			- for (var i=0; i<6; i++)
				.palette__shade
			h5 Secondary
		.palette.accent1
			.palette__main
			- for (var i=0; i<6; i++)
				.palette__shade
			h5 Accent #1
		.palette.accent2
			.palette__main
			- for (var i=0; i<6; i++)
				.palette__shade
			h5 Accent #2
		.palette.accent3
			.palette__main
			- for (var i=0; i<6; i++)
				.palette__shade
			h5 Accent #3
		.palette.neutrals
			- for (var i=0; i<8; i++)
				.palette__shade
			h5 Neutrals
	section.typography
		h6 typography
		.font-family
			.font-family-bold
				h1 Aa
				h4 Poppins Bold
			.font-family-medium
				h1 Aa
				h4 Poppins Medium
			.font-family-light
				h1 Aa
				h4 Poppins Light
		.font-example
			.font-example__headline
				h6.subheader Headlines
				h1 h1 headline
				h2 h2 headline
				h3 h3 headline
				h4 h4 headline
				h5 h5 headline
				h6 h6 headline
			.font-example__bodytext
				h6.subheader Body Text
				p I think we need to start from scratch. Jazz it up a little bit- use a funky color like purple.
				p
					strong Can you add a bit of pastel pink and baby blue because the purple alone looks too fancy.
				p
					em Make the purple more well, purple-er. Try a more powerful colour, it needs to be the same, but totally different.
	section.buttons-wrapper
		h6 Buttons
		.buttons
			a.button Default Button
			input.button.hover(type="button", value="Hovered Button")
			button.button.active Active Button
			a.button.disabled Disabled Button
			a.button.secondary Secondary Button
			a.button.accent Other Button
			a.button.accent2 Other Button
			a.button.accent3 Another Button
			div
				a.button.medium Medium Button
				a.button.small Smol Button
	section.links
		h6 Links
		.links__sec
			a.link Sample Link
			br
			a.link.hover Hovered Link
		.links__sec
			a.link.primary Sample Link
			br
			a.link.primary.hover Hovered Link
		.links__sec
			a.link.secondary Sample Link
			br
			a.link.secondary.hover Hovered Link
	section.inputs-selects
		h6 Inputs & Selects
		.inputs
			.input__wrapper
				label.label-form A Normal Input
				input.input-form(type="text", placeholder="Placeholder")
				p.feedback-form A message here.
			.input__wrapper
				label.label-form An Active Input
				input.input-form.active(
					type="text",
					placeholder="Placeholder",
					value="Typing Here..."
				)
			.input__wrapper
				label.label-form A Disabled Input
				input.input-form(type="text", placeholder="Placeholder", disabled)
			.input__wrapper
				label.label-form A Normal Select
				select(type="text", placeholder="Placeholder")
					option(value="1") Option 1
					option(value="2") Option 2
		.textarea-select
			.input__wrapper.input-success
				label.label-form A Right Input
				.input__validator
					input.input-form(type="text", placeholder="Placeholder")
					.input__validator__status
				p.feedback-form Awesome job.
			.input__wrapper.input-error
				label.label-form A Left Input
				.input__validator
					input.input-form(type="text", placeholder="Placeholder")
					.input__validator__status
				p.feedback-form You shall not pass.
			.input__wrapper
				label.label-form Textarea
				textarea(type="text", placeholder="Placeholder")
		.toggle-buttons
			h6.subheader Toggle Buttons
			.checkbox-toggle
				input#toggle-checkbox(type="checkbox")
				label(for="toggle-checkbox")
			.checkbox-toggle
				input#toggle-checkbox-1(type="checkbox", checked)
				label(for="toggle-checkbox-1")
			.checkbox-toggle
				input#toggle-checkbox-2(type="checkbox", disabled)
				label(for="toggle-checkbox-2")
		.checkboxes
			h6.subheader Checkboxes
			.checkbox
				input#checkbox-1(type="checkbox")
				label(for="checkbox-1") Checkbox
					span.box
			.checkbox
				input#checkbox-2(type="checkbox", checked)
				label(for="checkbox-2") Checked Box
					span.box
		.radio-buttons
			h6.subheader Radio Buttons
			.radio
				input#radio-1(type="radio", name="radio-test", value="1", checked)
				label(for="radio-1") Radio Button
			.radio
				input#radio-2(type="radio", name="radio-test", value="1")
				label(for="radio-2") Selected Radio Button
	section.badges
		h6 Badges
		span.badge.status-primary Received
		span.badge.status-secondary Pending
		span.badge.status-info Pending
		span.badge.status-success Approved
		span.badge.status-error Rejected
	section.tooltips
		h6 Tooltips
		div
			.tooltip.top.hovered(data-tooltip="Show a helpful tooltip here 😄") 
				span Light Tooltip
			.tooltip.top.dark.hovered(data-tooltip="Show a helpful tooltip here 😄") 
				span Dark Tooltip
			.tooltip.bottom(data-tooltip="Hello 👋") 
				span Bottom Tooltip
	section.alerts
		h6 Alerts
		.alert.status-primary A normal alert here.
		.alert.status-secondary A normal alert here.
		.alert.status-info A normal alert here.
		.alert.status-success A happy alert here.
		.alert.status-error A sad alert here.
	section.loading
		h6 loading indicators
		.spinner-1
			.spinner(data-loading="Loading...")
			label Please wait...
		.spinner-2
			.spinner(data-loading="Loading...")
			label Loading...

footer
	.explanation
		| Part of the
		a(href="https://codepen.io/collection/DQvYpQ", target="_blank") CSS Grid collection here
		| .
	.social
		a(href="https://twitter.com/meowlivia_", target="_blank")
			i.icon-social-twitter.icons
		a(href="https://github.com/oliviale", target="_blank")
			i.icon-social-github.icons
		a(href="https://dribbble.com/oliviale", target="_blank")
			i.icon-social-dribbble.icons