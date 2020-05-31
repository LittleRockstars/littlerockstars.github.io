---
layout: page
description: 'Little Rockstars presents an awesome Girls Rock T-Shirt for music fans everywhere.
    This quality sparkly top in purple or gold lettering makes a perfect girls birthday gift or present for any little drummer girl, music fan or little rock star.'
image1:  '/assets/images/products/girls-rock-black.jpg'
image2: '/assets/images/products/folded-image.jpg'
size-description: 'Sizes to fit all ages up to 13 years. Sizes 1-2 years , 3-4 years, 5-6 years, 7-8 years, 9-11 years, 12-13 years.'
color-description: 'black, purple, pink, red and white quality t-shirt and with glitter lettering.'
---

{% include product/logo.html%}

{% include product/store-information.html%}

{% include product/product-details.html
    description = page.description
    image1 = page.image1
    image2 = page.image2
    size-description = page.size-description
    colour-description = page.colour-description
%}

{% include product/product-table1.html%}

{% include product/other-products.html productId='/products/girls-rock' %}
