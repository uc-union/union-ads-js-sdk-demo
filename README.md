### union-ads-js-sdk-demo

***

## Integration Guide

union_html_sdk.js  (<8k with gzip encoded)

### Banner ad

Put the following code inside `<body>` tag

```javascript
<script src="http://admaster.union.ucweb.com/js/union_html5_sdk.js"></script>
<script type="text/javascript">
try {
    Umobi.AdView({
        pub: '<unqiue identifier for a ad placement>',
        format_type:Umobi.AdFormatType.BANNER
    });
} cache(e) {}
</script>
```

### Text ad

Put the following code inside `<body>` tag

```javascript
<script src="http://admaster.union.ucweb.com/js/union_html5_sdk.js"></script>
<script type="text/javascript">
try {
    Umobi.AdView({
        pub: '<unqiue identifier for a ad placement>',
        format_type:Umobi.AdFormatType.TEXT
    });
} cache(e) {}
</script>
```

### Specify ad container

JS sdk support specify ad container on demands

Put the following code inside `<head>` tag

```javascript
<script src="http://admaster.union.ucweb.com/js/union_html5_sdk.js"></script>
<script type="text/javascript">
try {
    Umobi.AdView({
        pub: '<unqiue identifier for a ad placement>',
        format_type:Umobi.AdFormatType.BANNER,
        container: '<container id>'
    });
} cache(e) {}
</script>
```

Usually `container id` is refer to a `div`'s id in `<body>` tag

```javascript
<body>
...
<div id="<container id>"></div>
...
</body>
```

###  Lite version

We also provide a lite version js sdk (<3k with gzip encoded).

Just use the js url below instead.

```javascript
<script src="http://admaster.union.ucweb.com/js/unionads.js"></script>
```
