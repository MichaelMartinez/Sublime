# snake_case for Sublime Text 2

Converts the source text with accents and non-word characters into a lowercase, "source code friendy" snake_case representation.

## Examples

    Lorem ipsum dolor sit amet -> lorem_ipsum_dolor_sit_amet
    Árvíztűrő tükörfúrógép -> arvizturo_tukorfurogep

I's useful to create proper labels within in Ruby on Rails fixtures.

## RoR fixture example:

    fullname: John Appleseed
    username: john

Copy the `John Appleseed` text and paste it above the fullname line. Select the text and press Ctrl+Shift+- or select Edit/Convert Case/snake_case:

    john_appleseed:
      fullname: John Appleseed
      username: john