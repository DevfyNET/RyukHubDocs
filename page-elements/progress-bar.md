# Progress Bar

[https://luis92.gitbook.io/ryukhub/getting-started/google-maps-api](https://luis92.gitbook.io/ryukhub/getting-started/google-maps-api)

```markup
<section class="container my-5">
    <h2>Basic Progress Bar</h2>
    <p>To create a default progress bar, add a .progress class to a container element and add the progress-bar class to its child element. Use the CSS width property to set the width of the progress bar:</p>

    <div class="progress">
        <div class="progress-bar w-75" role="progressbar" aria-valuenow="69" aria-valuemin="0" aria-valuemax="100" style="width: 69%; background-color: rgb(52, 125, 241);"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <h2>Colored Progress Bars</h2>
    <p>Use any of the contextual color classes to change the color of the progress bar:</p>
    <!-- Blue -->
    <div class="progress">
        <div class="progress-bar" style="width: 10%;"></div>
    </div>
    <br>

    <!-- Green -->
    <div class="progress">
        <div class="progress-bar bg-success" style="width: 20%;"></div>
    </div>
    <br>

    <!-- Turquoise -->
    <div class="progress">
        <div class="progress-bar bg-info" style="width: 30%;"></div>
    </div>
    <br>

    <!-- Orange -->
    <div class="progress">
        <div class="progress-bar bg-warning" style="width: 40%;"></div>
    </div>
    <br>

    <!-- Red -->
    <div class="progress">
        <div class="progress-bar bg-danger" style="width: 50%;"></div>
    </div>
    <br>

    <!-- White -->
    <div class="progress border">
        <div class="progress-bar bg-white" style="width: 60%;"></div>
    </div>
    <br>

    <!-- Grey -->
    <div class="progress">
        <div class="progress-bar bg-secondary" style="width: 70%;"></div>
    </div>
    <br>

    <!-- Light Grey -->
    <div class="progress border">
        <div class="progress-bar bg-light" style="width: 80%;"></div>
    </div>
    <br>

    <!-- Dark Grey -->
    <div class="progress">
        <div class="progress-bar bg-dark" style="width: 90%;"></div>
    </div>
    <br>
    <h2>Labels</h2>
    <p>Add labels to your progress bars by placing text within the .progress-bar.</p>
    <!-- Blue -->
    <div class="progress">
        <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">25%</div>
    </div>
    <br>
    <h2>Height</h2>
    <p>
        We only set a <code class="highlighter-rouge">height</code> value on the <code class="highlighter-rouge">.progress</code>, so if you change that value the inner <code class="highlighter-rouge">.progress-bar</code> will
        automatically resize accordingly.
    </p>
    <!-- Blue -->
    <div class="progress" style="height: 1px;">
        <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress" style="height: 20px;">
        <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <h2>Multiple bars</h2>
    <p>Include multiple progress bars in a progress component if you need.</p>
    <!-- Blue -->
    <div class="progress">
        <div class="progress-bar" role="progressbar" style="width: 15%;" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100"></div>
        <div class="progress-bar bg-success" role="progressbar" style="width: 30%;" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100"></div>
        <div class="progress-bar bg-info" role="progressbar" style="width: 20%;" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar bg-success" style="width: 40%;">
            Free Space
        </div>
        <div class="progress-bar bg-warning" style="width: 10%;">
            Warning
        </div>
        <div class="progress-bar bg-danger" style="width: 20%;">
            Danger
        </div>
    </div>
    <br>
    <h2>Striped</h2>
    <p>Add <code class="highlighter-rouge">.progress-bar-striped</code> to any <code class="highlighter-rouge">.progress-bar</code> to apply a stripe via CSS gradient over the progress bar’s background color.</p>
    <!-- Blue -->
    <div class="progress">
        <div class="progress-bar progress-bar-striped" role="progressbar" style="width: 10%;" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar progress-bar-striped bg-success" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar progress-bar-striped bg-warning" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <div class="progress">
        <div class="progress-bar progress-bar-striped bg-danger" role="progressbar" style="width: 100%;" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
    <br>
    <h2>Animated stripes</h2>
    <p>
        The striped gradient can also be animated. Add <code class="highlighter-rouge">.progress-bar-animated</code> to <code class="highlighter-rouge">.progress-bar</code> to animate the stripes right to left via CSS3 animations.
    </p>

    <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%;"></div>
    </div>
    <br>
</section>
```

