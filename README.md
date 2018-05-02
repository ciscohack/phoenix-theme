# Phoenix Theme

Dark & Light custom UI themes with colors variations for Sublime Text 2

## Todo's

- Add more alternate colors for Light Theme (green, red, orange)

## Installation

Phoenix theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2.

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Phoenix Theme via the `Package Control: Install Package` menu item. The Phoenix Theme package is listed as `Theme - Phoenix` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

You can locate your Sublime Text 2 `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/netatoo/phoenix-theme/ "Theme - Phoenix"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Phoenix`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activating the theme

To configure Sublime Text 2 to use the theme:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Phoenix Light.sublime-theme"` or `"theme": "Phoenix Dark.sublime-theme"`

#### Example User Settings

    {
        "theme": "Phoenix Dark.sublime-theme"
    }

## Alternate Colors

Phoenix Theme ships with 6 alternate color styles. To configure your favorite color:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) the `phoenix_color_*` entry
  
**Light theme :** `blue`, `darkblue` - **Dark Theme :** `red`, `green`, `blue`, `orange`, `yellow` and `pink`

#### Example for Blue variant

 	"phoenix_color_blue": true

## Hightlight text label on selected tab

You can hightlight or not the text label (filename) of the selected tab :

    "phoenix_highlight_current_tab": true    

## Eighties mode for selected tab

If you use Phoenix Dark Eighties or Tomorrow Night Eighties color scheme, you will love having this option enabled!

    "phoenix_eighties": true    

## Solid selected tabs

Enable this setting to get **solid** background color on the selected tab :

    "phoenix_solid_current_tab": true

## Alternate dirty state for inactive tabs

Enable this setting to get a **bottom bar** on inactive dirty tabs (inspired from [Nil Theme by Noel Cower](https://github.com/nilium/st2-nil-theme)) :

    "phoenix_dirty_bottom_bar": true

Also, you can choose the color of the bottom bar (default is white, colors available are `red`, `green`, `blue`, `orange`, `yellow` and `pink`). Example for red :

    "phoenix_dirty_bottom_bar_red": true

## Adjust row's height on sidebar tree

Example for large sidebar tree :

    "phoenix_sidebar_tree_large": true

For now, five additionnal height are available : `xsmall`, `small`, `medium`, `large`, and `xlarge`

## Colorize opened folders on Dark Theme

Enable this setting to colorize opened folder icons on sidebar, when using Dark Theme with color variation.

    "phoenix_color_expanded_folder": true

## Simply choose the height of your tabs!

Prefer small tabs? No problem, there is a custom setting for this!

    "phoenix_tabs_small": true

For now, five height are available : `small`, `medium`, `normal` (by default), `large`, and `xlarge`

## Adjust tab label font size

You can adjust the font size of your tab labels via custom setting:

    "phoenix_tabs_font_small": true

For now, four sizes are available : `small`, `normal` (by default), `large`, and `xlarge`

## Automatic width tabs

You want your tabs with automatic width? there is a custom setting for this!

    "phoenix_tabs_auto_width": true

## Custom Color Scheme

#### Phoenix Dark
**Phoenix Theme provide six custom color schemes** according to Phoenix Dark colors variations : `red`, `green`, `blue`, `orange`, `yellow` and `pink`.

Each color scheme has a "Eighties" version with a slightly lighter background (recommend to activate the [`phoenix_eighties`](#eighties-mode-for-selected-tab)).

**You can see screenshots of these color schemes in the top page**

Also, Phoenix Theme provide two slightly modified color scheme to magnify the interface (just background update).

#### Clouds Midnight
Original theme : (http://fredhq.com/projects/clouds)

#### Tomorrow Night
Original theme : (https://github.com/chriskempson/Tomorrow-Theme)

### Retina Resolution UI

Phoenix Theme has been designed to take advantage of retina resolution (high-dpi) displays. Phoenix Theme support retina displays.

### Theme Customisation

Sublime Text 2 provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Phoenix Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page from Soda Theme.

## License

Based on Soda Theme by Ian Hill (http://buymeasoda.com/)
