# Navigation Components

## Accordion
A vertically stacked set of interactive headings that each reveal a section of content.

**Components:**
* `Accordion`: The main container for the accordion.
* `AccordionItem`: A single item within the accordion.
* `AccordionTrigger`: The button that toggles the accordion item.
* `AccordionContent`: The content that is revealed when the accordion item is open.

**Props:**
* `type`: The type of accordion.
* `collapsible`: When `type` is `single`, allows the open item to be closed.
* `defaultValue`: The value of the item to be open by default.

## Breadcrumb
A breadcrumb navigation to show the user's current location.

**Components:**
* `Breadcrumb`: The main container for the breadcrumb navigation.
* `BreadcrumbList`: A list of breadcrumb items.
* `BreadcrumbItem`: A single breadcrumb item.
* `BreadcrumbLink`: A link to a previous page.
* `BreadcrumbPage`: The current page.
* `BreadcrumbSeparator`: A separator between breadcrumb items.
* `BreadcrumbEllipsis`: An ellipsis to indicate more items.

## DropdownMenu
A dropdown menu that appears when a trigger is clicked.

**Components:**
* `DropdownMenu`: The main container for the dropdown menu.
* `DropdownMenuTrigger`: The button that opens the dropdown menu.
* `DropdownMenuContent`: The content of the dropdown menu.
* `DropdownMenuGroup`: A group of items within the dropdown menu.
* `DropdownMenuItem`: A single item within the dropdown menu.
* `DropdownMenuLabel`: A label for a group of items.
* `DropdownMenuSeparator`: A separator between dropdown menu items.
* `DropdownMenuShortcut`: A shortcut key for a dropdown menu item.

## Menubar
A horizontal menu bar.

**Components:**
* `Menubar`: The main container for the menubar.
* `MenubarMenu`: A menu within the menubar.
* `MenubarTrigger`: The button that opens a menu.
* `MenubarContent`: The content of a menu.
* `MenubarGroup`: A group of items within a menu.
* `MenubarItem`: A single item within a menu.
* `MenubarLabel`: A label for a group of items.
* `MenubarSeparator`: A separator between menu items.
* `MenubarShortcut`: A shortcut key for a menu item.

## NavigationMenu
A navigation menu for website navigation.

**Components:**
* `NavigationMenu`: The main container for the navigation menu.
* `NavigationMenuList`: A list of navigation menu items.
* `NavigationMenuItem`: A single navigation menu item.
* `NavigationMenuTrigger`: The button that opens a navigation menu.
* `NavigationMenuContent`: The content of a navigation menu.
* `NavigationMenuLink`: A link within a navigation menu.
* `NavigationMenuIndicator`: The indicator for the current navigation menu.
* `NavigationMenuViewport`: The viewport for the navigation menu.

## Pagination
A component for navigating between pages.

**Components:**
* `Pagination`: The main container for the pagination.
* `PaginationContent`: A list of pagination items.
* `PaginationItem`: A single pagination item.
* `PaginationFirst`: A button to go to the first page.
* `PaginationLast`: A button to go to the last page.
* `PaginationNext`: A button to go to the next page.
* `PaginationPrevious`: A button to go to the previous page.
* `PaginationEllipsis`: An ellipsis to indicate more pages.

**Props:**
* `total`: The total number of items.
* `page`: The current page.
* `perPage`: The number of items per page.
* `siblings`: The number of siblings to show on each side of the current page.

## Tabs
A set of tabs for switching between different views.

**Components:**
* `Tabs`: The main container for the tabs.
* `TabsList`: A list of tab triggers.
* `TabsTrigger`: A button to activate a tab.
* `TabsContent`: The content of a tab.

**Props:**
* `modelValue`: The value of the active tab.
* `defaultValue`: The default value of the active tab.
