---
title: Playing a bit with photos
header:
  overlay_image: /assets/images/headertest - 1.jpeg
  opacity_filter: 0.5
  caption: "Photo credit: Gentry Bieker"
gallery:
  - url: /assets/images/queen_of_hearts.jpg
    image_path: /assets/images/queen_of_hearts.jpg
    alt: "Queen of Hearts"
    title: "The queen of hearts - at an amazing party"
  - url: /assets/images/fanning_oneself.jpg
    image_path: /assets/images/fanning_oneself.jpg
    alt: "Keeping Cool"
    title: "Keeping Cool at The Wiley St. Fair (2018)"

gallery2:
  - url: /assets/images/portrait1.jpg
    image_path: /assets/images/portrait1.jpg
    
gallery3:
  - url: /assets/images/wstreet_fair.jpg
    image_path: /assets/images/wstreet_fair.jpg
    alt: "Another Character"
    title: "Another Character"
    
gallery4:
  - url: /assets/images/gallerytest-1.jpg
    image_path: /assets/images/gallerytest-1.jpg
  - url: /assets/images/gallerytest - 2.jpeg
    image_path: "/assets/images/gallerytest - 2.jpeg"
  - url: "/assets/images/gallerytest - 3.jpeg"
    image_path: "/assets/images/gallerytest - 3.jpeg"
  - url: /assets/images/gallerytest - 4.jpeg
    image_path: "/assets/images/gallerytest - 4.jpeg"
  - url: "/assets/images/gallerytest - 5.jpeg"
    image_path: "/assets/images/gallerytest - 5.jpeg"
  - url: "/assets/images/gallerytest - 6.jpeg"
    image_path: "/assets/images/gallerytest - 6.jpeg"
  - url: "/assets/images/gallerytest - 7.jpeg"
    image_path: "/assets/images/gallerytest - 7.jpeg"
---

So, I'm starting to try and work out the visual aspects of the site at this
point, and it's about time I started playing with photos - at least in a draft.

# The first Gallery

First, a gallery, this one contains two different photos:

{% include gallery caption="Two random square photos" %}

# A larger Gallery

Here's a gallery with a few more pictures.

{% include gallery id="gallery4" caption="More Picture" %}

# Single Portrait Galleries
And now, another gallery, but this one with a single picture that shows a
portrait view, this of the queen of hearts.  The other of a random awesome
person from the Williamson St. Fair in 2018.

{% include gallery id="gallery2" caption="Portrait of the Queen of Hearts" %}

And here's one more of the portrait gallery

This guy might like the cat in the hat.
{: .notice--info}

{% include gallery id="gallery3" caption="Cat in the hat?" %}


