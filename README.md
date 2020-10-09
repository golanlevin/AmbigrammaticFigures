# Ambigrammatic Figures

*55 Grotesque Ambigrams By Golan Levin with Lingdong Huang*

![Ambigrammatic Figure #0073](images/ambigrammatic_figure_0073_1024x1024.png)

---
### Overview

<table>
<tbody>
<tr>
<td width="33%"><img src="images/image0009.gif" width="100%" alt="Ambigrammatic Figure #0009"></td>
<td width="33%"><img src="images/image0074.gif" width="100%" alt="Ambigrammatic Figure #0074"></td>
<td width="33%"><img src="images/image0117.gif" width="100%" alt="Ambigrammatic Figure #0117"></td>
</tr>

<tr>

<td width="33%"><img src="images/image0373.gif" width="100%" alt="Ambigrammatic Figure #0373"></td>
<td width="33%"><img src="images/image0249.gif" width="100%" alt="Ambigrammatic Figure #0249"></td>
<td width="33%"><img src="images/image0315.gif" width="100%" alt="Ambigrammatic Figure #0315"></td>
</tr>

</tbody>
</table>

These faces are “ambigrams”: images that are legible both upside-down and right-side up. Created with a machine learning system, they may be displayed in any orientation. In this project, a collection of 55 such ambigrammatic faces have been generated in high resolution and printed as a limited edition deck of cards. 

![](images/ambigrammatic_cards.png)

In the deck's accompanying packaging, collectors of this artwork are encouraged to devise their own activities with these cards: 

> * *Sort the cards from most to least _________.*
> * *Give names to the depicted. Write the personal motto or epitaph for each half of their duality.*
> * *Select groups of nine cards, and organize them according to the Nine Alignments (chaotic neutral, lawful evil, etc.).*


---
### About These Images

![*Reversible Faces* (1931-32) by Rex Whistler](images/rex_whistler.jpg)

Some of the best known works of this kind are the “[Upside-down Pictures](https://ukiyo-e.org/image/mfa/sc168251)” (Dôke jôgemi no zu, c. 1861) by Edo illustrator Utagawa Yoshitora (active 1836–1887), and a series of “[Reversible Faces](https://commons.wikimedia.org/wiki/File:Rex_Whistler_-_Reversible_Face_-_Mayor_%26_Judge_1930.jpg)” (c. 1931), published posthumously by the British artist, Reginald John “Rex” Whistler (1905–1944). Interested readers are referred to additional examples in George Tscherny’s 2004 book, “[Changing Faces](https://www.amazon.com/Changing-Faces-George-Tscherny/dp/B000W7M2ZW)”, and Al Seckel’s 2006 book “[SuperVisions: Topsy-Turvy Optical Illusions](https://www.amazon.com/SuperVisions-Topsy-Turvy-Illusions-Al-Seckel/dp/1402718322)”.

![Left to right: anonymous Swiss painting (18th C., from Tscherny); anonymous English painting (19th C., from Tscherny); *Upside-down Pictures* (1861) by Utagawa Yoshitora](images/historic_examples.jpg)

In the eighteenth and nineteenth centuries, bivalent face illusions were often used to depict uncomplicated dualities, such as young-old, good-evil, or blessed-damned. The faces in this deck reflect the moral ambiguities of a darker and more uncertain time, marked by ecological crisis, misinformation, identitarianism, patriarchal authoritarianism, and the social unrest of a polity divided against itself.

---
### Technical Development


The images in this project were synthesized with the [StyleGAN2](https://github.com/NVlabs/stylegan2) generative adversarial network, using pre-trained weights from the [Flickr-Faces-HQ Dataset](https://github.com/NVlabs/ffhq-dataset) (FFHQ), and enhanced using the [waifu2x](https://github.com/nagadomi/waifu2x) super-resolution library. 

The machine's hallucinations were alchemically influenced by the faces of individuals in [NIST Special Database 18](https://www.nist.gov/srd/nist-special-database-18), to whom we acknowledge our debt. No identification with actual persons is intended or should be inferred, and any resemblance to actual persons, living or deceased, is purely coincidental.



---
### Acknowledgments

The Ambigrammatic Figures were developed by [Golan Levin](http://flong.com/archive/) and [Lingdong Huang](https://lingdong.works/) at the [Frank-Ratchye STUDIO for Creative Inquiry](https://studioforcreativeinquiry.org/), Pittsburgh, during the COVID-19 pandemic of spring 2020.

This project was realized in part through support from Nvidia Corporation and the [a2p curatorial initiative](https://a2p.bitmark.com/v2/artworks) by Casey Reas et al. The animated GIFs and reverse side of the cards were generated with [Processing](http://processing.org), an open source toolkit for the arts.

The *Ambigrammatic Figures* imagery and card deck are presented under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)).

Thanks to: Kyle McDonald, Claire Hentschker, Omer Shapira, roadrunner01 (@ak92501), Tero Karras et al. (NVlabs), C. Nagadomi, NIST, Casey Reas, Imin Yeh, Andrea Boykowycz, and the staff of the Frank-Ratchye STUDIO for Creative Inquiry at Carnegie Mellon University.