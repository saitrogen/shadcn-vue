# Forms Components

## Button
Renders a clickable button.

**Props:**
* `variant`: The visual style of the button.
* `size`: The size of the button.

**Variants:**
* `default`: The default button style.
* `destructive`: A button style for destructive actions.
* `outline`: A button with an outline.
* `secondary`: A secondary button style.
* `ghost`: A button with no background or border.
* `link`: A button that looks like a link.

**Sizes:**
* `sm`
* `default`
* `lg`
* `icon`

## Checkbox
A checkbox that can be checked or unchecked.

**Props:**
* `checked`: Whether the checkbox is checked or not.
* `disabled`: Whether the checkbox is disabled or not.

## Input
A standard text input field.

**Props:**
* `modelValue`: The value of the input.
* `defaultValue`: The default value of the input.
* `disabled`: Whether the input is disabled or not.

## RadioGroup
A set of radio buttons where only one can be selected at a time.

**Components:**
* `RadioGroup`: The main container for the radio buttons.
* `RadioGroupItem`: A single radio button.

**Props:**
* `modelValue`: The value of the selected radio button.
* `defaultValue`: The default value of the selected radio button.
* `disabled`: Whether the radio group is disabled or not.

## Select
A dropdown menu for selecting a single value from a list.

**Components:**
* `Select`: The main container for the select menu.
* `SelectTrigger`: The button that opens the select menu.
* `SelectValue`: The currently selected value.
* `SelectContent`: The content of the select menu.
* `SelectGroup`: A group of items within the select menu.
* `SelectItem`: A single item within the select menu.
* `SelectLabel`: A label for a group of items.

**Props:**
* `modelValue`: The value of the selected item.
* `defaultValue`: The default value of the selected item.
* `disabled`: Whether the select menu is disabled or not.

## Slider
A slider for selecting a value from a range.

**Props:**
* `modelValue`: The value of the slider.
* `defaultValue`: The default value of the slider.
* `min`: The minimum value of the slider.
* `max`: The maximum value of the slider.
* `step`: The step value of the slider.
* `disabled`: Whether the slider is disabled or not.

## Switch
A two-state toggle switch.

**Props:**
* `checked`: Whether the switch is checked or not.
* `disabled`: Whether the switch is disabled or not.

## Textarea
A multi-line text input field.

**Props:**
* `modelValue`: The value of the textarea.
* `defaultValue`: The default value of the textarea.
* `disabled`: Whether the textarea is disabled or not.
