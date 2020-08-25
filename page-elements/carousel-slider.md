# Carousel Slider

```markup
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class=""></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner" role="listbox">
        <!-- Slide One - Set the background image for this slide in the line below -->
        <div class="carousel-item carousel-size-item-example active carousel-item-left" style="background-image: url('assets/img/1.png');">
            <div class="carousel-caption d-none d-md-block">
                <h2 class="display-4">First Slide</h2>
                <p class="lead">This is a description for the first slide.</p>
            </div>
        </div>
        <!-- Slide Two - Set the background image for this slide in the line below -->
        <div class="carousel-item carousel-size-item-example carousel-item-next carousel-item-left" style="background-image: url('assets/img/2.png');">
            <div class="carousel-caption d-none d-md-block">
                <h2 class="display-4">Second Slide</h2>
                <p class="lead">This is a description for the second slide.</p>
            </div>
        </div>
        <!-- Slide Three - Set the background image for this slide in the line below -->
        <div class="carousel-item carousel-size-item-example" style="background-image: url('assets/img/3.png');">
            <div class="carousel-caption d-none d-md-block">
                <h2 class="display-4">Third Slide</h2>
                <p class="lead">This is a description for the third slide.</p>
            </div>
        </div>
    </div>
    <a class="carousel-control-prev left-0" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next right-0" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```

