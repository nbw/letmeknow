# Let Me Know

An embarrassing simple command line tool that triggers a notification when a command has completed.

## Usage

```
lmk {{command}}
```

Example:
```
lmk ps aux
```

Also:

```
lmk --help
```

## Mac Install

`curl -o /usr/local/bin/lmk https://raw.githubusercontent.com/nbw/letmeknow/master/lmk | chmod +x lmk`

## Supported Platforms

_Let Me Know_ leverages [osascript](https://ss64.com/osx/osascript.html) to trigger notifications and so for the time being is **Max OSX only**. 

## Alias Limitation

At the moment _Let Me Know_ doesn't support local aliases (such as those defined in .bash_profile or a .zschrc). 

## Looking for something better?

_Let Me Know_ is incredibly simple. Check out [noti](https://github.com/variadico/noti) if you're looking for something with way more support (including support for windows and linux). It's a super cool CLI written Golang and uses NSUserNotifcations (refer [here](https://github.com/variadico/noti/tree/master/service/nsuser)). 

## Contributions?

Feel free to contribute or send me a suggestion at contact@nathanwillson.com.
