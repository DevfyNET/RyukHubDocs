# Grid

See how aspects of the Bootstrap grid system work across multiple devices with a handy table.

|  | Extra small &lt;576px | Small ≥576px | Medium ≥768px | Large ≥992px | Extra large ≥1200px |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Max container width | None \(auto\) | 540px | 720px | 960px | 1140px |
| Class prefix | `.col-` | `.col-sm-` | `.col-md-` | `.col-lg-` | `.col-xl-` |
| \# of columns | 12 |  |  |  |  |
| Gutter width | 30px \(15px on each side of a column\) |  |  |  |  |
| Nestable | Yes |  |  |  |  |
| Column ordering | Yes |  |  |  |  |

![](../.gitbook/assets/grid.png)

```markup
<section id="Grid">
    <div class="container">
        <div class="row my-5">
            <div class="col-12 col-md-6 offset-md-3 text-center">
                <h3 class="heading">Grid <mark>Template.</mark></h3>
            </div>
        </div>
        <h6 class="mb-3">Stacked-to-horizontal</h6>
        <div class="row">
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
            <div class="col-md-2">
                <div class="card p-3">.col-md-2</div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-8">
                <div class="card p-3">.col-md-8</div>
            </div>
            <div class="col-md-4">
                <div class="card p-3">.col-md-4</div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4">
                <div class="card p-3">.col-md-4</div>
            </div>
            <div class="col-md-4">
                <div class="card p-3">.col-md-4</div>
            </div>
            <div class="col-md-4">
                <div class="card p-3">.col-md-4</div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
                <div class="card p-3">.col-md-6</div>
            </div>
            <div class="col-md-6">
                <div class="card p-3">.col-md-6</div>
            </div>
        </div>
        <h6 class="mb-3">Mobile and desktop</h6>
        <!-- Stack the columns on mobile by making one full-width and the other half-width -->
        <div class="row">
            <div class="col-12 col-md-8">
                <div class="card p-3">.col-12 .col-md-8</div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card p-3">.col-6 .col-md-4</div>
            </div>
        </div>
        <!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
        <div class="row">
            <div class="col-6 col-md-4">
                <div class="card p-3">.col-6 .col-md-4</div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card p-3">.col-6 .col-md-4</div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card p-3">.col-6 .col-md-4</div>
            </div>
        </div>
        <!-- Columns are always 50% wide, on mobile and desktop -->
        <div class="row">
            <div class="col-6">
                <div class="card p-3">.col-6</div>
            </div>
            <div class="col-6">
                <div class="card p-3">.col-6</div>
            </div>
        </div>
        <h6 class="mb-3">Mobile, tablet, desktops</h6>
        <div class="row">
            <div class="col-12 col-sm-6 col-md-8">
                <div class="card p-3">.col-12 .col-sm-6 .col-md-8</div>
            </div>
            <div class="col-6 col-md-4">
                <div class="card p-3">.col-6 .col-md-4</div>
            </div>
        </div>
        <div class="row">
            <div class="col-6 col-sm-4">
                <div class="card p-3">.col-6 .col-sm-4</div>
            </div>
            <div class="col-6 col-sm-4">
                <div class="card p-3">.col-6 .col-sm-4</div>
            </div>
            <!-- Optional: clear the XS cols if their content doesn't match in height -->
            <div class="clearfix visible-xs-block"></div>
            <div class="col-6 col-sm-4">
                <div class="card p-3">.col-6 .col-sm-4</div>
            </div>
        </div>
        <h6 class="mb-3">Offsetting columns</h6>
        <div class="row">
            <div class="col-md-4">
                <div class="card p-3">.col-md-4</div>
            </div>
            <div class="col-md-4 ml-auto">
                <div class="card p-3">.col-md-4 .ml-auto</div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3 ml-auto">
                <div class="card p-3">.col-md-3 .ml-auto</div>
            </div>
            <div class="col-md-3 ml-auto">
                <div class="card p-3">.col-md-3 .ml-auto</div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6 ml-auto">
                <div class="card p-3">.col-md-6 .ml-auto</div>
            </div>
        </div>
        <h6 class="mb-3">Column ordering</h6>
        <div class="row">
            <div class="col-md-9 order-md-2">
                <div class="card p-3">.col-md-9 .order-md-2</div>
            </div>
            <div class="col-md-3 order-md-1">
                <div class="card p-3">.col-md-3 .order-md-1</div>
            </div>
        </div>
    </div>
</section>

```

