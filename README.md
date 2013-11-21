State Decoded jQuery
===================

A jQuery plugin for third-party sites to attach an informative tooltip to section citations.

Built atop [qTip](qTip2/qTip2), this will find every instance of a citation within the text of a page and wrap it in `<span class="law">...</span>` tags. Then it will use qTip to attach on-hover events to each of those span tags, which will issue a request to the site's API.

Each State Decoded site will distribute their own copy of this, customized with the regular expression for their legal code. It won't work with all localities—those that use non-unique section identifiers cannot provide references based on a simple regex. Sites may pre-populate the plugin with an API key, or they may require users to obtain their own API key.
