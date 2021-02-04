## Color in CSS
- Colors can be defined in many ways
    - Named colors / keywords: pink, blue, purple, silver, palegoldenrod...
    - Hex colors / Hexadecimal colors: #FF   00     00
                                       255   00     00
                                       RED   GREEN  BLUE
    - rgb(255, 0, 0);
- Transparency
    - CSS property
        - `opacity` -- "How opaque something is"
        - Ranges from 1.00 to 0.00, for example "0.50"
    - CSS color
        - rgba - Red,   Green,  Blue,   Alpha
                 0-255, 0-255,  0-255,  0-1
- Other color schemes
    - Self study
    - CMYK
    - HSL
    - HSLA
## Important! 
    In CSS it matters in what order your declarations are in
## CSS Pseudo classes
- link states are a great example of these!
    - visited link
        - CSS with pseudoclass: `a:visited { color: black; }`
    - active link
        - CSS with pseudoclass: `a:active { color: black; }`
    - hovered link#
        - CSS with pseudoclass: `a:hover { color: red; }`+
- Try out link pseudoclass styles in different orders
    - visited after active
    - active after visited
    - hover before either
    - hover after either 
    - etc
    - the order matters!