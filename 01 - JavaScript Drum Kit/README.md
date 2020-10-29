# 01- Drum Kit

30 Day Challenge

## Notes

- The HTML data-* attribute allows us to store custom data on any HTML element. Each div.key and audio element have a data-key attribute that binds them together.
- The <audio> element in the provided HTML file has a data-key attribute which corresponds with a keyboard button.
- Notice that when a key is pressed, and it is not one we are looking for, we can then stop the function.
- for querySelector, see: https://www.w3schools.com/jsref/met_document_queryselector.asp
    - we want to use query selector to select the proper class/div so that we can apply animation.

```
  <div data-key="65" class="key playing">   
      <kbd>A</kbd>
      <span class="sound">clap</span>
    </div>
```
- note that playing got added to the div class. 