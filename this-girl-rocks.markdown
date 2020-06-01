---
layout: page
productId: '/products/this-girl-rocks'
description: 'Little Rockstars presents a fabulous This Girl Rocks kids glittery skull top for music fans everywhere. This quality sparkly top available in purple or black with silver glitter text and white and pink glitter skulls makes a perfect girls birthday gift or present for your little musicians, music fan or little rock star.'
image1: '/assets/images/products/this-girl-rocks-purple.jpg'
image2: '/assets/images/products/folded-image.jpg'
size-description: 'Sizes to fit ages from 3-4. Sizes 3-4 years, 5-6 years, 7-8 years, 9-11 years'
colour-description: 'black, purple quality t-shirt and with glitter lettering.'
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

{% include product/other-products.html productId=page.productId %}
