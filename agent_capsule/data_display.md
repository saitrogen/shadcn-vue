# Data Display Components

## Avatar
An image element with a fallback for representing a user.

**Components:**
* `Avatar`: The main container for the avatar.
* `AvatarImage`: The image to be displayed.
* `AvatarFallback`: The fallback to be displayed if the image fails to load.

## Badge
Renders a small badge or tag.

**Props:**
* `variant`: The visual style of the badge.

**Variants:**
* `default`
* `secondary`
* `destructive`
* `outline`

## Card
A container for content with a header, content, and footer.

**Components:**
* `Card`: The main container for the card.
* `CardHeader`: The header of the card.
* `CardTitle`: The title of the card.
* `CardDescription`: The description of the card.
* `CardContent`: The content of the card.
* `CardFooter`: The footer of the card.

## Carousel
A carousel for displaying a series of items.

**Components:**
* `Carousel`: The main container for the carousel.
* `CarouselContent`: The content of the carousel.
* `CarouselItem`: A single item within the carousel.
* `CarouselNext`: A button to go to the next item.
* `CarouselPrevious`: A button to go to the previous item.

**Props:**
* `orientation`: The orientation of the carousel.
* `opts`: Options for the carousel.

## Table
A table for displaying data in rows and columns.

**Components:**
* `Table`: The main container for the table.
* `TableHeader`: The header of the table.
* `TableBody`: The body of the table.
* `TableFooter`: The footer of the table.
* `TableRow`: A row in the table.
* `TableHead`: A header cell in the table.
* `TableCell`: A cell in the table.
* `TableCaption`: A caption for the table.

## Tooltip
A popup that displays information related to an element when the element receives keyboard focus or the mouse hovers over it.

**Components:**
* `TooltipProvider`: The provider for the tooltip.
* `Tooltip`: The main container for the tooltip.
* `TooltipTrigger`: The trigger that opens the tooltip.
* `TooltipContent`: The content of the tooltip.

**Props:**
* `delayDuration`: The delay in milliseconds before the tooltip appears.
