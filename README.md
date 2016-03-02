# Actionable Text &#38; Icons

Predix Experience Actionable Text &#38; Icons module is used to initiate an action associated to the text string or icon.


## Dependencies

Px's Text &#38; Icons module depends on two other Px modules:

* [px-colors-design](https://github.com/PredixDev/px-colors-design)
* [px-defaults-design](https://github.com/PredixDev/px-defaults-design)


## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.com/PredixDev/px-actionable-text-icons.git

Once installed, `@import` into your project's Sass file in its Objects layer:

    @import "px-buttons-design/_objects.buttons.scss";

## Usage

These flags are available and, if needed, should be set to `true` prior to importing the module:

    $inuit-enable-btn--small
    $inuit-enable-btn--large
    $inuit-enable-btn--huge
    $inuit-enable-btn--full
    $inuit-enable-btn--primary
    $inuit-enable-btn--tertiary
    $inuit-enable-btn--disabled
    $inuit-enable-btn--icon
    $inuit-enable-btn--bare
    $inuit-enable-btn--bare-primary
    $inuit-enable-btn--bare-select
    $inuit-enable-btn--bare-disabled

The following variables are available for use in the module:

    $inuit-btn-color
    $inuit-btn-background
    $inuit-btn-background--hover
    $inuit-btn-background--pressed
    $inuit-btn-border-color
    $inuit-btn-border-color--hover
    $inuit-btn-border-color--pressed
    $inuit-btn-shadow
    $inuit-btn-shadow--light
    $inuit-btn-primary-color
    $inuit-btn-primary-background
    $inuit-btn-primary-background--hover
    $inuit-btn-primary-background--pressed
    $inuit-btn-primary-border-color
    $inuit-btn-tertiary-color
    $inuit-btn-tertiary-background
    $inuit-btn-tertiary-background--hover
    $inuit-btn-tertiary-background--pressed
    $inuit-btn-disabled-color
    $inuit-btn-disabled-background
    $inuit-btn-disabled-border-color

## Options

These classes are available if the variable flags listed above are set to `true`:

* `btn--[small|large|huge]`: Small, large or huge buttons
* `btn--[primary|tertiary|disabled]`: Primary, tertiary, or disabled buttons
* `btn--full`: Full width buttons
* `btn--icon`: Circular button for icons
* `btn--bare[primary|select|disabled]`: Text and Icon Buttons
