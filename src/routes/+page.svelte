 <script>
    import { Carousel, CarouselTransition } from 'flowbite-svelte'
    // ./imageData/+server.js has the following
    let showThumbs=false
    let showCaptions=false
    let  images = [
    {
      id: 0,
      name: "Cosmic timetraveler",
      imgurl: "https://i.pinimg.com/236x/72/60/9a/72609aab9efce68b96272338d5c2374d.jpg",
      attribution: "cosmic-timetraveler-pYyOZ8q7AII-unsplash.com",
    },
    {
      id: 1,
      name: "Cristina Gottardi",
      imgurl: "https://i.pinimg.com/236x/65/04/19/6504191cb955c31b8673805fd480512e.jpg",
      attribution: "cristina-gottardi-CSpjU6hYo_0-unsplash.com",
    },
    {
      id: 2,
      name: "Johannes Plenio",
      imgurl: "https://i.pinimg.com/236x/f2/cb/a0/f2cba03305d2f9630e018bc7a1a2986c.jpg",
      attribution: "johannes-plenio-RwHv7LgeC7s-unsplash.com",
    },
    // {
    //   id: 3,
    //   name: "Jonatan Pie",
    //   imgurl: "/images/carousel/jonatan-pie-3l3RwQdHRHg-unsplash.webp",
    //   attribution: "jonatan-pie-3l3RwQdHRHg-unsplash.com",
    // },
    // {
    //   id: 4,
    //   name: "Mark Harpur",
    //   imgurl: "/images/carousel/mark-harpur-K2s_YE031CA-unsplash.webp",
    //   attribution: "mark-harpur-K2s_YE031CA-unsplash",
    // },
    // {
    //   id: 5,
    //   name: "Pietro De Grandi",
    //   imgurl: "/images/carousel/pietro-de-grandi-T7K4aEPoGGk-unsplash.webp",
    //   attribution: "pietro-de-grandi-T7K4aEPoGGk-unsplash",
    // },
    // {
    //   id: 6,
    //   name: "Sergey Pesterev",
    //   imgurl: "/images/carousel/sergey-pesterev-tMvuB9se2uQ-unsplash.webp",
    //   attribution: "sergey-pesterev-tMvuB9se2uQ-unsplash",
    // },
    // {
    //   id: 7,
    //   name: "Solo travel goals",
    //   imgurl: "/images/carousel/solotravelgoals-7kLufxYoqWk-unsplash.webp",
    //   attribution: "solotravelgoals-7kLufxYoqWk-unsplash",
    // },
  ];
  </script> 


  
  <div class="max-w-4xl">
    <Carousel {images} loop {showCaptions} {showThumbs} duration="3000"/>
  </div>