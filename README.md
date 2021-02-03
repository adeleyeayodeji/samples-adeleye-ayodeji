```php
<?php
    if (!isset($_GET["sample"]) && !empty($_GET["sample"])) header("location: https://adeleyeayodeji.com/");
    else $url = $_GET["sample"];
    if ($url == "") {
        header("location: https://adeleyeayodeji.com/");
    }
?>
<!DOCTYPE html>
<html class="no-js" lang="en">

    <head>
        <meta http-equiv="content-type" content="text/html; charset=UTF-8">
        <meta charset="utf-8">
        <script type="text/javascript" src="include/NRBR-281af528f2b1e2422b5"></script>
        <script async="" src="include/main.js"></script>
        <script type="text/javascript" async="" src="include/core.js" nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>
        <script type="text/javascript" async="" src="include/bat.js" nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>
        <script type="text/javascript" async="" src="include/conversion_async.js" nonce="NHFSgFb4dmLzYpVbLaZx2Q==">
        </script>
        <script async="" src="include/gtm.js"></script>
        <script src="include/nr-1198.js"></script>
        <script type="text/javascript" charset="UTF-8" async="" src="include/cc.js"></script>
        <script type="text/javascript" async="" src="include/js" nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>
        <script type="text/javascript" async="" src="include/linkid.js" nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>
        <script type="text/javascript" async="" src="include/ec.js" nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>
        <script type="text/javascript" async="" src="include/analytics.js"></script>
        <meta http-equiv="X-UA-Compatible" content="chrome=1">
        <title>Adeleye Ayodeji - Sample Site</title>
        <meta name="viewport" content="width=device-width, minimum-scale=1, maximum-scale=1">

        <link rel="stylesheet" media="all"
            href="include/index-6e294e9c28580b492d27bcaaaada9a0076a7fc2dff6bc9df9de894.css">
        <link rel="stylesheet" media="all"
            href="include/index-004d35cdd5d555cdd3e956d1b916825642de06529f0fe91fd9f390.css">
        <link rel="stylesheet" media="all" href="include/cookiebot.css">
        <script src="include/index-0761a67821063364aae0c110e00f283d54710f2090e2a9312eb487a.js"
            nonce="NHFSgFb4dmLzYpVbLaZx2Q=="></script>

        <style type="text/css">
        .cookieconsent-optin,
        .cookieconsent-optin-preferences,
        .cookieconsent-optin-statistics,
        .cookieconsent-optin-marketing {
            display: block;
            display: initial;
        }

        .cookieconsent-optout-preferences,
        .cookieconsent-optout-statistics,
        .cookieconsent-optout-marketing,
        .cookieconsent-optout {
            display: none;
        }
        </style>

    </head>

    <body class="full-screen-preview">
        <div class="preview__header" style="line-height: 30px;">
            <div class="preview__envato-logo">
                <img src="img/logo-adeleye-w.png" alt="Adeleye Ayodeji" onclick="loadurl()"
                    style="height: 43px;padding-top: 7px;cursor: pointer;">
            </div>

            <div id="js-preview__actions" class="preview__actions">
                <div class="preview__action--buy">
                    <a class="header-buy-now e-btn--3d -color-primary"
                        href="https://api.whatsapp.com/send?phone=2347034803384&text=Hello%20Adeleye%20Ayodeji,%20your%20service%20is%20requested%20on%20<?php echo $url; ?>."
                        style="box-shadow: 0 2px 0 #db02b0;background: #db02b0;margin-top: 7px;" target="_blank">Order
                        now</a>
                </div>

            </div>
        </div>
        <iframe class="full-screen-preview__frame" name="preview-frame" noresize="noresize"
            data-view="fullScreenPreview" allow="geolocation 'self'; autoplay 'self'" src="<?php echo $url; ?>"
            frameborder="0" style="height:98vh;">
        </iframe>
        <script>
        function loadurl() {
            var url = "https://adeleyeayodeji.com/";
            window.open(url, '_blank');
        }
        </script>
    </body>

</html>

```
