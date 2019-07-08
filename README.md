# wpgtk-colorschemes
:earth_americas: A community driven repository to submit and share colorschemes for [wpgtk](https://github.com/deviantfero/wpgtk)

From this repository you will be able to download and use JSON formatted colorschemes submitted
by other `wpgtk` users, you're free to fork this repository to create your own personal collection
of colorschemes too!

To submit a new colorscheme, just open a pull request, the colorscheme in question, should have one
of these formats, for simplicity anything other than the 16 primary colors will be ignored when importing
so you can of course include other keys in your colorscheme, but only the `color` or `colors` key will be read:

### Exporting Colorschemes

Remember, you can use `wpgtk` to export your handcrafted colorschemes, do it like this:

```
wpg -o <theme-to-export> [<path-to-export-to>]
```

If no path is provided, the current directory will be used, 
you can also specify a filename in the path, then the exported json will have that name.

#### terminal.sexy format

```json
{
  "color": [
    "#272822",
    "#f92672",
    "#a6e22e",
    "#f4bf75",
    "#66d9ef",
    "#ae81ff",
    "#a1efe4",
    "#f8f8f2",
    "#75715e",
    "#f92672",
    "#a6e22e",
    "#f4bf75",
    "#66d9ef",
    "#ae81ff",
    "#a1efe4",
    "#f9f8f5"
  ]
}
```

#### pywal format

```json
{
  "colors": {
    "color0": "#211b16",
    "color1": "#A86645",
    "color2": "#356E53",
    "color3": "#BB9951",
    "color4": "#897198",
    "color5": "#469750",
    "color6": "#576055",
    "color7": "#95966a",
    "color8": "#392e25",
    "color9": "#e97f4a",
    "color10": "#3a996c",
    "color11": "#ffcd57",
    "color12": "#b681d6",
    "color13": "#4cd25d",
    "color14": "#698862",
    "color15": "#dadc9b"
  }
}
```

### Colorschemes

In this section you can checkout the colorschemes this JSON files produce in `wpgtk`, while submitting
the sample is not necessary for submitting a new colorscheme, it would be greatly appreciated, as it gives
other users a preivew of what they're downloading.

#### default.json
![default-sample](./samples/default-sample.png)

#### monokai.json
![monokai-sample](./samples/monokai-sample.png)

#### coffe-like.json
![coffe-like-sample](./samples/coffe-like-sample.png)

#### bikes.json
![bikes-sample](./samples/bikes-sample.png)

#### vending.json
![vending-sample](./samples/vending-sample.png)

#### sea.json
![sea-sample](./samples/sea-sample.png)

#### moon.json
![moon-sample](./samples/moon-sample.png)

#### purple-power.json
![moon-sample](./samples/purple-power.png)
