# vanilla-fade-io
fadeIn() and fadeOut() without jQuery, in pure JavaScript

# Installation
## Regular
    Clone this repository or download it
## NPM
`npm install git+https://github.com/turkelton31/vanilla-fade-io.git --save`

# Usage
```javascript
document.getElementById('in').addEventListener('click', function() {
    FX.fadeIn(document.getElementById('test'), {
        duration: 2000,
        complete: function() {
            alert('Complete');
        }
    });
}, false);

document.getElementById('out').addEventListener('click', function() {
    FX.fadeOut(document.getElementById('test'), {
        duration: 2000,
        complete: function() {
            alert('Complete');
        }
    });
}, false);
```

# Exemple
[CodePen](https://codepen.io/gabrieleromanato/pen/frIwl?editors=0010)
