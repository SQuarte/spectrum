# Spectrum

##

This is a fork of the work done by Brian Grinstead, You can get his original work over at: https://github.com/bgrins/spectrum

## The No Hassle colorpicker

See the demo and docs: http://anarcie.github.io/spectrum.

I wanted a colorpicker that didn't require images, and that had an API that made sense to me as a developer who has worked with color in a number of applications.  I had tried a number of existing plugins, but decided to try and make a smaller, simpler one.

I started using canvas, then switched to CSS gradients, since it turned out to be easier to manage, and provided better cross browser support.

### Basic Usage

Head over to the [docs](http://anarcie.github.io/spectrum) for more information.  There is a visual demo of the different options hosted at: http://anarcie.github.io/spectrum.

    <script src='spectrum.js'></script>
    <link rel='stylesheet' href='spectrum.css' />

    <input id='colorpicker' />

    <script>
    $("#colorpicker").spectrum({
        color: "#f00"
    });
    </script>
