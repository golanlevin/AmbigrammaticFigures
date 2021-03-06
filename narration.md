# Ambigrammatic Figures

*55 Grotesque Ambigrams By Golan Levin with Lingdong Huang, 05/05/2020*


![Ambigrammatic Figure #0073](images/ambigrammatic_figure_0073_1024x1024.png)

This video documents "Ambigrammatic Figures", a variable-format, generative artwork by Golan Levin and Lingdong Huang. Developed in May 2020 using artificial intelligence techniques, the project operates as an expressive meditation on themes of identity, illness, and social unrest. 

### Overview

<table>
<tbody>
<tr>
<td width="33%"><a href="images/ambigrammatic_card_06_0009.png"><img src="images/image0009.gif" width="100%" alt="Ambigrammatic Figure #0009"></a></td>
<td width="34%"><a href="images/ambigrammatic_card_03_0074.png"><img src="images/image0074.gif" width="100%" alt="Ambigrammatic Figure #0074"></a></td>
<td width="33%"><a href="images/ambigrammatic_card_45_0117.png"><img src="images/image0117.gif" width="100%" alt="Ambigrammatic Figure #0117"></a></td>
</tr>

</tbody>
</table>


These faces are “ambigrams”: images that are legible both upside-down and right-side up. Created with a machine learning system, they may be displayed in any orientation. In this project, we generated a collection of 55 such ambigrammatic faces, and present them in a variety of different formats. 


![](images/rex_whistler_16x9.jpg)

Some of the best-known ambigrams are a series of "reversible faces" by the British artist, “Rex” Whistler, created in 1931,

![](images/yoshitora_16x9.jpg)

and a collection of playful “Upside-down Pictures”, created circa 1861, by the Japanese illustrator Utagawa Yoshitora. 

![](images/tscherny_swiss18thc_16x9.png)

But this illusion has older roots. In the eighteenth and nineteenth centuries, bivalent face illusions were often used to depict uncomplicated dualities, such as young-old, male-female, or good-wicked. 

<table>
<tbody>

<tr>
<td width="33%"><a href="images/ambigrammatic_card_14_0373.png"><img src="images/image0373.gif" width="100%" alt="Ambigrammatic Figure #0373"></a></td>
<td width="34%"><a href="images/ambigrammatic_card_24_0249.png"><img src="images/image0249.gif" width="100%" alt="Ambigrammatic Figure #0249"></a></td>
<td width="33%"><a href="images/ambigrammatic_card_40_0315.png"><img src="images/image0315.gif" width="100%" alt="Ambigrammatic Figure #0315"></a></td>
</tr>

</tbody>
</table>


The faces in our *Ambigrammatic Figures* project reflect the moral ambiguities of a darker and more uncertain time — marked by ecological crisis, misinformation, identitarianism, authoritarianism, and the social unrest of a polity divided against itself.

### Presentation 

![](images/faces_512x512_16x9.jpg)

The Ambigrammatic Figures project is a variable-format work. When the faces are offered as *still images*, we orient them sideways, to preserve their ambiguity.

![](images/puppet.gif)

In time-based media, we present the faces as spinning loops — or, alternatively, in bivalent videos, puppeteered by facial motion capture recordings and reanimated by an image warping algorithm.

![Ambigrammatic Figures card deck](images/ambigrammatic_cards.png)

The Ambigrammatic Figures are also presented in a tangible, open-ended, interactive format as a deck of printed poker-sized cards. Participants are encouraged to devise their own activities with these cards, such as sorting them according to subjective criteria, or giving names and epitaphs to the faces.

### Technical Implementation 

![](images/initial_gan_16x9.jpg)

Our initial attempt to implement the project entailed the development of a custom generative adversarial network, or GAN. In particular, our GAN's discriminator was modified so that it examined its generator’s output both upside-down and right-side-up, and produced a score that was a function of both. Unfortunately, the results of this technique failed to converge well.

![](images/development_16x9.jpg)

Ultimately, our faces were synthesized with a "projection" technique, in which a GAN attempts to find a given face in its latent space, starting its search from a “generic” “neutral” face. We provide the StyleGAN network with an upside-down face as a query — and the projector tries its best to find it, but can never serve a perfect match, because it has only been trained on exclusively right-side-up faces. In short, the GAN projector finds upside-down faces in the latent space—or "generatable manifold"—of right-side up faces. Through the struggle to match an upside-down face using right-side-up ones, the GAN tends to converge on a face that can be looked at both ways.   

---
### Acknowledgments

The *Ambigrammatic Figures* were developed by Golan Levin and Lingdong Huang at the Frank-Ratchye STUDIO for Creative Inquiry, Pittsburgh, during the COVID-19 pandemic of spring 2020. This project was realized in part through inadvertent support from Nvidia Corporation and the a2p curatorial initiative by Casey Reas. 

We acknowledge our debt to the individuals whose faces alchemically influenced our machine's hallucinations. No identification with actual persons is intended or should be inferred, and any resemblance to actual persons, living or deceased, is purely coincidental.

Additional thanks to: Kyle McDonald, Claire Hentschker, Omer Shapira, Mikael Christensen, roadrunner01 (@ak92501), Tero Karras et al. (NVlabs), C. Nagadomi, NIST, Casey Reas, Imin Yeh, Andrea Boykowycz, and the staff of the Frank-Ratchye STUDIO for Creative Inquiry at Carnegie Mellon University.
