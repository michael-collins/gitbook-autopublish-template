# OER License

The content of this OER book is licensed as [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). Some content is taken from other sources and cited throughout. However, this work is a living draft, presented as is, and may be changed or updated without notice.

## Attribution

You are welcomed and encouraged to use the content in this book for your own teaching needs.  At a minimum, please provide attribution via html source schema, see below for usage. Use the [Google Structured Data Testing tool](https://search.google.com/structured-data/testing-tool/u/0/) to test that the schema is functioning properly. More information can be found on [OERSchema.org](http://oerschema.org).

If your publishing method prohibits schema, please use the visible attribution method provided.

### OER Schema metadata attribution:

Add [OER Schema](http://oerschema.org) and CC License to HTML source:

```
<!-- Add OERSchema and CC schema vocabulary to object -->
<div prefix="oer: http://oerschema.org/ cc:http://creativecommons.org/ns dc:http://purl.org/dc/terms/" resource="#oer-source">



        <!-- Add OER resource text and media here. -->


        <!-- Link the license and attribution to the page -->
        <link about="#oer-source" property="cc:license" content="https://creativecommons.org/licenses/by/4.0/">
        <meta about="#oer-source" property="cc:attributionUrl" content="https://www.gitbook.com/book/michael-collins/gitbook-autopublish-template">
        <meta about="#oer-source" property="cc:attributionName" typeof="oer:Resource" content="Michael Collins">

</div>
```

### Visible attribution

“[Creative Research](https://www.github.com/book/michael-collins/gitbook-autopublish-template/details)” by Michael Collins is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

`“<a href="https://github.com/michael-collins/gitbook-autopublish-template">Creative Research</a>” by Michael Collins is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC-BY-4.0</a>.`

