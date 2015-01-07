# Infinite Carousel Plugin

Example
    new InfiniteCarousel({
        element: '#myElement',
        margin: 0,
        imageHeight: '100px',
        hasPosindicator: true,
        posindicatorAlign: 'center',
        posindicatorInside: false,
        posindicatorColor: '#000000',
        hasZoom: false,
        hasLoop: true,
        hasLazyLoading: true,
        hasArrow: true,
        arrowInside: false,
        arrowColor: '#000000',
        complete: function(){
            alert('complete animation!');
        }
    })
