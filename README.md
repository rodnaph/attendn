
# Attendn

A simple Javascript snippet for meetup attendees!  Just set up a parse.com account, and use the snippet.

## Usage

Just include the script along with jQuery...

```html
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
<script type="text/javascript" src="attendn.js"></script>

<div class="attendn"
     data-meetupid="my_meetup_name"
     data-parseappid="..."
     data-parserestkey="..."></div>
```

And create the containing *div* to hold the widget.

### Options

All options are specified via data attributes.  To enable the delete
link...

```html
<div class="attendn"
     data-allowdelete="yes" />
```

## Disclaimer

There's no authentication or approval for adding and deleting attendees, so attendn
assumes you don't mind this.  Just to keep it simple. :D

