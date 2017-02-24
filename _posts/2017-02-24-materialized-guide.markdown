---
layout: post
title:  "Materialized Guide"
date:   2017-02-24
tag: materialize, guide
categories: guide
author: "Lahiru Pathirage"
---

Please simply follow this guide to manipulate **Materialized**.

<h3>New Page</h3>
Simply create a {name}.md file in `Materialized` home directory. It will be shown in the navbar. And add these headings.

<pre>
---
layout: page
title:  "{PAGE_NAME}"
permalink : "/page_name/"
category: "page-name"
---
</pre>
<br>

<h3>New Post</h3>
Create a new file in `_posts` directory and name it as yyyy-mm-dd-{POST_SHORTNAME}.markdown and add these headings,

<pre>
---
layout: post
title:  "{POST_NAME}"
date:   yyyy-mm-dd
categories: ["archive"]
author: "Author"
---
</pre>