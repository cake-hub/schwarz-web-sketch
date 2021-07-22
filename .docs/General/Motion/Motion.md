<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these motions.
</AlertWarning>

# Motion

For SCHWARZ Brand, an effective UI animation makes a visual statement that combines both form and function. It enhances visual feedback, facilitates orientation and directs users' attention. The SCHWARZ Brand animation effects enhance a sense of causal relationships and bring a distinct personality.

## General principles

The core principles of the SCHWARZ Brand identity are **proximity**, **diversity** and **foresight**.

**Proximity** | **Diversity** |**Foresight**
---------|----------|---------
As a leading retailer, SCHWARZ Group is a part of the daily lives of millions of people and it is serving people's needs on a local level. | SCHWARZ Group has diverse fields of activity – the entire value chain of food goods, from production to distribution/trade, to disposal and recycling. Diversity is also reflected in international orientation and the different cultural environments in which retail formats operate. | SCHWARZ Group is farsighted in regard to the customer experience and sets its course today in order to be successful tomorrow. New challenges such as digitalization are seen as opportunities and are embraced in business models.

## Motion principles

Motion principles exist to ensure that SCHWARZ core brand principles are conveyed through animation.

**Assistive**| **Simple** | **Focused**
---------|----------|---------
To ensure that information sources are transported efficiently, motion is used to assist the flow of information. | Motion is used purposefully and clearly in visualization of simple, easy-to-follow actions. | There should be a clear focus on the harmonious relationship between design and functionality.

### Recommendation

We recommend combining the easing specification with the time tokens to create the SCHWARZ brand experience. The listed examples serve as orientation for possible applications.

> Motion effects should be carefully selected.

## Specifications

### Easing

Easing determins the rate of change of a parameter over time.<br>
The easing function defines how an animation changes speed over the course of the action. In reality, objects tend to accelerate or decelerate during their motion.
<br>SCHWARZ Motion defines these easing functions.


Preview | Transition specification
---------|----------
![schwarz-ease-out: example](assets/easing/schwarz-ease-out.gif) | **schwarz-ease-out** <br>This transition specification is best suited for animation of fade-in objects.<br> cubic-bezier (0.61, 1, 0.88, 1)
![schwarz-ease-in: example](assets/easing/schwarz-ease-in.gif) | **schwarz-ease-in** <br>This animation is especially suitable for objects that leave a section of the image or are faded out from the image.<br> cubic-bezier (0.55, 0, 1, 0.45)
![schwarz-easeInOutCubic: example](assets/easing/schwarz-easeInOutCubic.gif) | **schwarz-easeInOutCubic** <br>This effect softens objects and draws attention to itself, so it should be used specifically for larger movements.<br> cubic-bezier (0.68, -0.6, 0.32, 1.6)

### Duration / Timing

When choosing the right duration, consider the complexity of the element and the amount of movement.


Micro animations | Macro animations
---------|----------
Micro animation cover a small area, e.g color, hover states, accordions, tooltips, slider (indicators), etc. | Macro animation cover a larger visual area which includes a movement across the screen, larger panel or popover, page transition, etc.


### Duration tokens

Token | Duration time (milliseconds) | Duration type
---------|----------:|:---------:
schwarz-duration-10 | 200 ms | Micro ▒
schwarz-duration-20 | 400 ms | Micro ▒
schwarz-duration-30 | 600 ms | Micro ▒
schwarz-duration-40 | 800 ms | Micro ▒
schwarz-duration-50 | 1200 ms | Macro █
schwarz-duration-60 | 1400 ms | Macro █
schwarz-duration-70 | 1600 ms | Macro █
schwarz-duration-80 | 1800 ms | Macro █
schwarz-duration-90 | 2000 ms | Macro █
schwarz-duration-100 | 2200 ms | Macro █
schwarz-duration-110 | 2400 ms | Macro █

## Effect examples

Preview | Type
---------|---------
![fade-in: example](assets/effects/fade-in.gif) | **Fade-in**<br> schwarz-ease-out<br>schwarz-duration-40
![slide-fade: example](assets/effects/slide-fade.gif) | **Slide-fade**<br> schwarz-ease-in<br>schwarz-duration-40
![fill: example](assets/effects/fill.gif) | **Fill**<br> schwarz-easeInOutCubic<br>schwarz-duration-40
![color: example](assets/effects/color.gif) | **Color**<br> schwarz-ease-out<br>schwarz-duration-40
![side-fold: example](assets/effects/side-fold.gif) | **Side-fold**<br> schwarz-ease-in<br>schwarz-duration-20
![scale-fade: example](assets/effects/scale-fade.gif) |**Scale-fade**<br> schwarz-easeInOutCubic<br>schwarz-duration-50

## Examples

Preview | Specification
---------|---------
![rotation: example](assets/examples/rotation.gif) |  **Rotation**<br>schwarz-ease-out<br> schwarz-duration-20
![page-transition: example](assets/examples/page-transition.gif) | **Page transitions**<br>schwarz-ease-in<br> schwarz-duration-20, schwarz-duration-10
![Section scrolling: example](assets/examples/section-scrolling.gif) | **Section scrolling**<br>schwarz-ease-out<br>schwarz-duration-40
![contextual: example](assets/examples/contextual.gif) | **Contextual**<br>schwarz-easeInOutCubic<br>schwarz-duration-10, schwarz-duration-40
![parallax: example](assets/examples/parallax.gif) | **Parallax**<br>schwarz-ease-out<br> schwarz-duration-40
![key-visual: example](assets/examples/key-visual.gif) | **Key Visual**<br>schwarz-ease-out<br>schwarz-duration-40