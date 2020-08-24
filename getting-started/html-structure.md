# HTML Structure

RyukHub follows a simple coding structure that is easy to understand and implement. Make sure that you follow some of the Important Rules to avoid unexpected errors:

* Always enclose all the Content inside the  &lt;body&gt;.
* Never use nested **.container** &lt;div&gt;s. Close the Previous **.container** &lt;div&gt; and then open a New &lt;div&gt;. Otherwise, it will cause Formatting Issues.
* Validate your HTML Codes for errors on [https://validator.w3.org/](https://validator.w3.org/). Follow these rules:
  1. Check and Fix Unclosed HTML Tags.
  2. Check and Fix Duplicate IDs.
  3. **Ignore** Google Fonts, `type` Attribute unnecessary or not needed related errors.

## Code Example

```markup
<!doctype html>
<html lang="en">

<head>
    <!-- Stylesheets & Title
	============================================= -->
	...
</head>

<body id="pre-load">
    <!-- Navbar
		============================================= -->
    <nav class="navbar navbar-expand-md navbar-light bg-white fixed-top">
    </nav>
    
    <!-- Breadcrumb
		============================================= -->
    <div class="header-title-breadcrumb relative mt-5-5">
        <div class="header-title-breadcrumb-overlay text-center">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-7 text-left">
                        <h4>Page</h4>
                    </div>
                    <div class="col-12 col-md-5">
                        <ol class="breadcrumb-transparent float-md-right">
                            <li class="breadcrumb-item"><a href="index.html">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">Page</li>
                        </ol>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Site Content
    ============================================= -->
    <section id="section-name">
        <div class="container">
            <div class="row">
                ...
            </div>
        </div>
    </section>
    <!-- Footer
		============================================= -->
    <!-- Brand -->
    <section class="brand">
        <div class="container">
            <div class="row mt-3">
            <!-- Brands
                ============================================= -->
                ...
            </div>
        </div>
    </section>
    <!-- Brand/End -->
    <hr>
    <!-- Footer -->
    <footer class="container py-2 site-footer">
        <div class="row">
            <!-- Footer Menu
                ============================================= -->
                ...
        </div>
        <hr>
        <div class="row">
            <div class="col-6 col-md-3 col-lg-3 order-1 order-md-1">
                <!-- Feeback
                    ============================================= -->
                    ...
            </div>
            <div class="col-12 col-md-6 mt-3 mt-lg-0 col-lg-6 order-3 order-md-2">
                <!-- Copyrights
			        ============================================= -->
                    ...
            </div>
            <div class="col-6 col-md-3 col-lg-3 order-2 order-md-3">
                <div class="dropdown dropup float-right">
                    <!-- Change of Language
                        ============================================= -->
                        ...
                </div>
            </div>
        </div>
        <!-- Back To Top Button -->
        <div id="backtotop">
            <a href="#"></a>
        </div>
    </footer>
	<!-- Scripts
        ============================================= -->
        ...
</body>

</html>
```

## **Layout Settings**

This theme is compatible with the preload screen. Add the .pre-load class to the :

```markup
<body id="pre-load">
```

