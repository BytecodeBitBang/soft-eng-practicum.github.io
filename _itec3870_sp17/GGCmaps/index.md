---
layout: project_page
title: GGCmaps
date: 2017-08-16 14:49:25
categories: itec3870 create
collection: itec3870_sp17
photos:
- IMG_20170427_145146955.jpg
- IMG_20170427_144410982.jpg
- IMG_20170427_144413728.jpg
- IMG_20170427_144433983.jpg
- IMG_20170427_145050656.jpg
- IMG_20170427_145114857.jpg
- IMG_20170427_145202939_HDR.jpg

phrase: "Search rooms. Find rooms. Don't get lost in A (even offline!)"
demo-url: http://ggcmaps.com/
members: David Rivera-Rocha, Josh Gerth, Carlos Pacheco-Perez, Margaret "Maggie" Muse
client: "Dr. Catherine Moore & Michael Deiters"
client-url: http://www.ggc.edu/about-ggc/directory/catherine-moore
description: "Webapp that allows finding GGC campus rooms from their numbers (second semester)."
tech: "Progressive webapp that can work offline with a custom Javascript front-end. It requires no back-end to function. It can save itself as a desktop shortcut on mobile platforms."
logo-full: flyer-ggcmaps.png
logo-thumb: thumb-flyer-ggcmaps.png
repo-url: https://github.com/soft-eng-practicum/ggcmaps
---

Detailed information about the {{ page.title }} development process.

<!-- lightgallery -->
<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
<script src="https://cdn.jsdelivr.net/lightgallery/1.3.7/js/lightgallery.min.js">
</script>
<script src="https://cdn.jsdelivr.net/g/lg-zoom"></script>

<script type="text/javascript">

    $(document).ready(function() {

        $("body").lightGallery({

            zoom: true,
            selector: 'a#lightgallery',
            selectWithin: 'body'

        });

    });

</script>

[ggc]: http://www.ggc.edu
[gunay-ggc]: http://www.ggc.edu/about-ggc/directory/cengiz-gunay
