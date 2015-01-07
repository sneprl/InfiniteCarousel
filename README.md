#Infinite Carousel Plugin

###Installation
Include JavaScript files.

- If your project contains a new version of jQuery or jquery.hammer you can remove this part.

        <script src="InfiniteCarousel/jquery-1.9.1.min.js"></script>
        <script src="InfiniteCarousel/jquery.hammer.js"></script>

- Include InfiniteCarousel js and css.

        <script src="InfiniteCarousel/InfiniteCarousel.js"></script>
        <link rel="stylesheet" href="./js/InfiniteCarousel-dev/InfiniteCarousel.css">
                
- Element on which is applied the carousel.

        <div id="myElement">
            <span>First test content in span element</span>
            <div>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
                Cras tristique nunc lorem.
            </div>
            <div>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
                Pellentesque ac vulputate ipsum. Maecenas at elit dapibus, interdum ante eget, dapibus erat.<br>
                Sed at maximus nibh, in imperdiet magna. Curabitur tincidunt lobortis tellus id suscipit.<br>
                Etiam eleifend enim ut turpis volutpat molestie.
            </div>
        </div>

- On document ready init Carousel on element #myElement.

        $(document).ready(function () {
            new InfiniteCarousel({element: '#myElement'});
        });
