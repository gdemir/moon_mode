# Moon Mode

## Usage

```html
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="author" content="Gökhan Demir" />
  <meta name="description" content="Moon Mode" />
  <meta name="keywords" content="moon mode, moon, mode" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <title>MoonMode</title>

  <!-- jQuery start -->
  <script src="http://code.jquery.com/jquery-latest.min.js"></script>
  <!-- jQuery end -->

  <!-- moonmode start -->
  <!-- source : http://github.com/gdemir/moonmode -->
  <link rel="stylesheet" type="text/css" href="moonmode.min.css" />
  <script type="text/javascript">
    $(document).ready(function() {
      $("#moonmode-logo").click(function() {
        $("body").toggleClass("moonmode-body");
        $("#page").toggleClass("moonmode-page");
      });
    });
  </script>
  <!-- moonmode end -->
</head>
<body>

  <!-- moonmode logo start -->
  <div id="moonmode-logo"></div>
  <!-- moonmode logo end -->
  
  <div id="page">
    Merhaba Dünya
  </div>

</body>
</html>
```

## License

Moon Mode is released under the [MIT License](http://www.opensource.org/licenses/MIT).
