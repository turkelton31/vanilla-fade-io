# vanilla-fade-io
fadeIn() and fadeOut() without jQuery, in pure JavaScript

# Installation
Clone this repository or download it

# Usage
`
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
`
