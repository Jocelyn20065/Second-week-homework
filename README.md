# Second-week-homework -History :space_invader:

 > ** **updated on: 2021/8/14** :speech_balloon: <br> 
 > ** **added animation** <br>
 > ** **as seventh-week-homework** <br>


1. added animation effect into the second-week-homework as the seventh week homework.

2. mostly used AOS to process. 


3. reference link(animation.css):
    https://animate.style/
- add the link in the <header> space and use these two classe name ` animate__animated ` `animate__bounceIn `. 
    - **The second class depends on what function you would like to have, so it is changeable.**
    
4. reference link for aos:
    https://michalsnik.github.io/aos/
 - added below sentences before the end of the body ( mostly after </footer>)
        
 ```
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
 AOS.init();
</script> 
```
-  if you would like to have a customized one. add this one: 

 ```
 <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
AOS.init({
  // Global settings:
  disable: false, // accepts following values: 'phone', 'tablet', 'mobile', boolean, expression or function
  startEvent: 'DOMContentLoaded', // name of the event dispatched on the document, that AOS should initialize on
  initClassName: 'aos-init', // class applied after initialization
  animatedClassName: 'aos-animate', // class applied on animation
  useClassNames: false, // if true, will add content of `data-aos` as classes on scroll
  disableMutationObserver: false, // disables automatic mutations' detections (advanced)
  debounceDelay: 50, // the delay on debounce used while resizing window (advanced)
  throttleDelay: 99, // the delay on throttle used while scrolling the page (advanced)
  

  // Settings that can be overridden on per-element basis, by `data-aos-*` attributes:
  offset: 120, // offset (in px) from the original trigger point -->從哪個位置開始跑效果，預設的位置已經很好的。
  delay: 0, // values from 0 to 3000, with step 50ms
  duration: 400, // values from 0 to 3000, with step 50ms -->最好不要超過一分鐘，最好的值是400,600,800。
  easing: 'ease', // default easing for AOS animations
  once: true, // whether animation should happen only once - while scrolling down -->如果希望效果一直出現，就改false。
  mirror: false, // whether elements should animate out while scrolling past them
  anchorPlacement: 'top-bottom', // defines which position of the element regarding to window should trigger the animation

});
</script>
```
