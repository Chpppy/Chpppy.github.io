---
layout: splash
header:
    overlay_image: "/asset/image/redflower.jpeg"
    overlay_filter: 0.5
    image_description: "Red Floawer, shooted in DLUT"
tagline: "Be happy forever!"
title: "Chpppy"

gallery:
  - url: /asset/image/sakura.jpeg
    image_path: /asset/image/sakura.jpeg
    alt: "Sakura"
    title: "Sakura"
  - url: /asset/image/sakura2.jpeg
    image_path: /asset/image/sakura2.jpeg
    alt: "Sakura2"
    title: "Sakura"
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--inverse"
  - url: /asset/image/sakura3.jpeg
    image_path: /asset/image/sakura3.jpeg
    title: "Sakura"
    alt: "Sakura3"

gallery_2:
  - url: /asset/image/dalian8.jpg
    image_path: /asset/image/dalian8.jpg
    alt: "Ginkgo"
    title: "Ginkgo"
  - url: /asset/image/dalian7.jpg
    image_path: /asset/image/dalian7.jpg
    title: "Tower"
    alt: "Tower"
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--inverse"
  - url: /asset/image/sunflower.jpeg
    image_path: /asset/image/sunflower.jpeg
    alt: "Sunflower"
    title: "Sunflower"

gallery_3:
  - url: /asset/image/dalian.jpg
    image_path: /asset/image/dalian.jpg
    title: "Dalian, Liaoning"
    alt: "Sea"
  - url: /asset/image/dalian3.jpeg
    image_path: /asset/image/dalian3.jpeg
    title: "Dalian, Liaoning"
    alt: "Sea"
  - url: /asset/image/dalian2.jpeg
    image_path: /asset/image/dalian2.jpeg
    title: "Dalian, Liaoning"
    alt: "Sea"
---
<h1>Photo Gallery</h1>
<!-- {% include feature_row %} -->
{% include gallery caption="Shot in 2025 at the Development Zone Campus of Dalian University of Technology, China." %}

{% include figure popup=true image_path="/asset/image/redflower.jpeg" alt="Redflower" caption="Shot in Dalian University of Technology, China in 2024." %}

{% include gallery id="gallery_2" %}

{% include figure popup=true image_path="/asset/image/anji.jpg" alt="Mountain" caption="Shot in 2024, Anji, Zhejiang Province." %}

{% include gallery id="gallery_3" caption="Shot in 2024, Dalian, Liaoning Province."%}