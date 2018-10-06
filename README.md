# InteractivePlotter
Infrastructure for Interactive figures, in which the limits of the axes are changed dynamically by scrolling and dragging the mouse.

InteractiveFigure

    This class allows creation of 1-axes interactive figure, in which the limits
    of the axes can be modified interactively using pointer ("mouse") dragging or
    scrolling.
    It also supports printing information into a text-box next to the main axes.

Limitations

    No support in log-scaled axes.
    (Certainly there're additional unknown limitations)

Credits

    This class is heavily based on code examples from StackOverflow question:
    "Matplotlib plot zooming with scroll wheel"
    https://stackoverflow.com/questions/11551049/matplotlib-plot-zooming-with-scroll-wheel

TODO

    BUGS
    side panels location: currently the side panels may cover the main axes labels.
    FEATURES
    interactive plotting: plot only whatever within the current limits.
