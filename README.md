# italian-artists
List of Genius API IDs of italian artists. Artists are grouped by their main Genius genre.

### Finding IDs

Simply go to the artist webpage, paste the following command in the console (right-click inspect) and press enter.

```javascript
document.getElementsByTagName("meta")[20].content.match(/\d+/)[0];
```

Beware that this doesn't work correctly for verified artists' pages. If you are in doubt you can check the ID on [this page](https://docs.genius.com/#artists-h2) (requires a Genius account, don't share your bearer token for any reason).

### Building the full artists list

Run the `merge-lists.sh` script.
