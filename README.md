# MMM-Meniny
Swedish name of day (namnsdag) (fork from https://github.com/eouia/MMM-Meniny)

## Installation
```shell
cd ~/MagicMirror/modules
git clone https://github.com/andersarstrand/MMM-Meniny
```

## Configuration
```javascript
{
  module: "MMM-Meniny",
	position: "top_left",
	config: {
	  //message: "Today is <i>$TODAY$</i>. <br/> Tomorrow is <i>$TOMORROW$</i>."
	  message: "Namnsdag idag: <i>$TODAY$</i>. <br/> Namnsdag imorgon: <i>$TOMORROW$</i>."
    // you can use $TODAY$ as name of today, $TOMORROW$ as name of tomorrow.
	}
},
```

I have been running this for year and it look fine.

## Issues
Days that has no name usually has a description in sweden. Like `01 Jan` is set to  "(ingen namnsdag) Nyårsdagen"

