# SNOW 
Snow is an amazing faxstore theme that adds well snow to your pages for the winter season :)

![Cool Gif](https://cdn.shawnengmann.com/shawn/6IBnrQ.gif)

To install this just add the `snow.css` file to your themes folder and set it as the theme and add the `snowheader.ejs` to `/src/views/_header`.
> **Note:** If you are using a theme already add the code found in `snow.css` and add it to your theme. Also if you use a custom header add the code below into your custom header.

```html
<div id="snow"></div>
	<script>
		document.addEventListener('DOMContentLoaded', function(){
    var script = document.createElement('script');
    script.src = 'https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js';
    script.onload = function(){
        particlesJS("snow", {
            "particles": {
                "number": {
                    "value": 125, // Edit THIS FOR NUMBER OF PARTICALS
                    "density": {
                        "enable": true,
                        "value_area": 600
                    }
                },
                "color": {
                    "value": "#ffffff"
                },
                "opacity": {
                    "value": 0.3, // EDIT THIS FOR OPACITY
                    "random": false,
                    "anim": {
                        "enable": false
                    }
                },
                "size": {
                    "value": 5,
                    "random": true,
                    "anim": {
                        "enable": false
                    }
                },
                "line_linked": {
                    "enable": false
                },
                "move": {
                    "enable": true,
                    "speed": 0.6, // EDIT THIS FOR SPEED
                    "direction": "bottom",
                    "random": true,
                    "straight": false,
                    "out_mode": "out",
                    "bounce": false,
                    "attract": {
                        "enable": true,
                        "rotateX": 300,
                        "rotateY": 1200
                    }
                }
            },
            "interactivity": {
                "events": {
                    "onhover": {
                        "enable": false
                    },
                    "onclick": {
                        "enable": false
                    },
                    "resize": false
                }
            },
            "retina_detect": true
        });
    }
    document.head.append(script);
});
	</script>
```
