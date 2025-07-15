# Etc Components

## Collapsible
An interactive component which expands/collapses a content section.

**Components:**
* `Collapsible`: The main container for the collapsible.
* `CollapsibleTrigger`: The button that toggles the collapsible.
* `CollapsibleContent`: The content that is revealed when the collapsible is open.

**Props:**
* `open`: Whether the collapsible is open or not.
* `defaultOpen`: Whether the collapsible is open by default or not.
* `disabled`: Whether the collapsible is disabled or not.

## Combobox
A combobox for selecting a value from a list of options.

**Components:**
* `Combobox`: The main container for the combobox.
* `ComboboxAnchor`: The anchor for the combobox.
* `ComboboxEmpty`: The content to display when there are no items.
* `ComboboxGroup`: A group of items within the combobox.
* `ComboboxInput`: The input field for the combobox.
* `ComboboxItem`: A single item within the combobox.
* `ComboboxItemIndicator`: The indicator for a selected item.
* `ComboboxList`: The list of items.
* `ComboboxSeparator`: A separator between items.
* `ComboboxViewport`: The viewport for the list of items.
* `ComboboxCancel`: The cancel button for the combobox.
* `ComboboxTrigger`: The trigger that opens the combobox.

## Command
A command menu for searching and executing commands.

**Components:**
* `Command`: The main container for the command menu.
* `CommandDialog`: A dialog that contains a command menu.
* `CommandEmpty`: The content to display when there are no results.
* `CommandGroup`: A group of commands.
* `CommandInput`: The input field for searching.
* `CommandItem`: A single command.
* `CommandList`: The list of commands.
* `CommandSeparator`: A separator between commands.
* `CommandShortcut`: A shortcut key for a command.

## ContextMenu
A menu that appears upon right-clicking or long-pressing.

**Components:**
* `ContextMenu`: The main container for the context menu.
* `ContextMenuTrigger`: The trigger that opens the context menu.
* `ContextMenuContent`: The content of the context menu.
* `ContextMenuGroup`: A group of items within the context menu.
* `ContextMenuItem`: A single item within the context menu.
* `ContextMenuLabel`: A label for a group of items.
* `ContextMenuSeparator`: A separator between context menu items.
* `ContextMenuShortcut`: A shortcut key for a context menu item.
* `ContextMenuCheckboxItem`: A checkbox item within the context menu.
* `ContextMenuRadioGroup`: A radio group within the context menu.
* `ContextMenuRadioItem`: A radio item within the context menu.
* `ContextMenuSub`: A sub-menu within the context menu.
* `ContextMenuSubTrigger`: The trigger that opens a sub-menu.
* `ContextMenuSubContent`: The content of a sub-menu.

## DatePicker
A component for selecting a date or a range of dates. This is a composition of other components.

**Components:**
* `Popover`: The main container for the date picker.
* `PopoverTrigger`: The button that opens the date picker.
* `PopoverContent`: The content of the date picker.
* `Calendar`: The calendar for selecting a date.
* `RangeCalendar`: The calendar for selecting a range of dates.

## Form
A component for building forms with validation. This is a composition of other components and the `vee-validate` library.

**Components:**
* `Form`: The main container for the form.
* `FormField`: A single field in the form.
* `FormItem`: A container for a form field.
* `FormLabel`: The label for a form field.
* `FormControl`: The control for a form field.
* `FormDescription`: The description for a form field.
* `FormMessage`: The error message for a form field.

## NumberField
A number input with increment and decrement buttons.

**Components:**
* `NumberField`: The main container for the number field.
* `NumberFieldInput`: The input field for the number.
* `NumberFieldDecrement`: The button to decrement the value.
* `NumberFieldIncrement`: The button to increment the value.

**Props:**
* `modelValue`: The value of the number field.
* `defaultValue`: The default value of the number field.
* `min`: The minimum value of the number field.
* `max`: The maximum value of the number field.
* `step`: The step value of the number field.
* `disabled`: Whether the number field is disabled or not.

## PinInput
A pin input for entering a sequence of characters.

**Components:**
* `PinInput`: The main container for the pin input.
* `PinInputGroup`: A group of pin input slots.
* `PinInputSeparator`: A separator between pin input slots.
* `PinInputSlot`: A single pin input slot.

**Props:**
* `modelValue`: The value of the pin input.
* `defaultValue`: The default value of the pin input.
* `placeholder`: The placeholder for the pin input.
* `disabled`: Whether the pin input is disabled or not.
* `type`: The type of the pin input (`text` or `password`).

## RangeCalendar
A calendar for selecting a range of dates.

**Components:**
* `RangeCalendar`: The main container for the range calendar.
* `RangeCalendarCell`: A single cell in the range calendar.
* `RangeCalendarCellTrigger`: The trigger for a cell in the range calendar.
* `RangeCalendarGrid`: The grid for the range calendar.
* `RangeCalendarGridBody`: The body of the grid.
* `RangeCalendarGridHead`: The head of the grid.
* `RangeCalendarGridRow`: A row in the grid.
* `RangeCalendarHeadCell`: A header cell in the grid.
* `RangeCalendarHeader`: The header of the range calendar.
* `RangeCalendarHeading`: The heading of the range calendar.
* `RangeCalendarNextButton`: The button to go to the next month.
* `RangeCalendarPrevButton`: The button to go to the previous month.

**Props:**
* `modelValue`: The value of the range calendar.
* `defaultValue`: The default value of the range calendar.
* `disabled`: Whether the range calendar is disabled or not.

## ScrollArea
A scrollable area with a scrollbar.

**Components:**
* `ScrollArea`: The main container for the scroll area.
* `ScrollBar`: The scrollbar for the scroll area.

**Props:**
* `orientation`: The orientation of the scrollbar.

## TagsInput
A tags input for entering a list of tags.

**Components:**
* `TagsInput`: The main container for the tags input.
* `TagsInputItem`: A single tag.
* `TagsInputItemText`: The text of a tag.
* `TagsInputItemDelete`: The delete button for a tag.
* `TagsInputInput`: The input field for adding new tags.

**Props:**
* `modelValue`: The value of the tags input.
* `defaultValue`: The default value of the tags input.
* `placeholder`: The placeholder for the input field.
* `disabled`: Whether the tags input is disabled or not.

## Toggle
A two-state button that can be either on or off.

**Props:**
* `pressed`: Whether the toggle is pressed or not.
* `defaultPressed`: Whether the toggle is pressed by default or not.
* `disabled`: Whether the toggle is disabled or not.
* `variant`: The visual style of the toggle.
* `size`: The size of the toggle.

**Variants:**
* `default`
* `outline`

**Sizes:**
* `sm`
* `default`
* `lg`

## ToggleGroup
A group of toggle buttons.

**Components:**
* `ToggleGroup`: The main container for the toggle group.
* `ToggleGroupItem`: A single toggle button.

**Props:**
* `type`: The type of toggle group (`single` or `multiple`).
* `modelValue`: The value of the toggle group.
* `defaultValue`: The default value of the toggle group.
* `disabled`: Whether the toggle group is disabled or not.
* `variant`: The visual style of the toggle buttons.
* `size`: The size of the toggle buttons.
