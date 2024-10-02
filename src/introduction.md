# Introduction to APB
<image class="right" alt='Symbolic image of the APB method' src="/images/apb-icon.png">[^apb-icon]

APB was originally developed by James Straughon aka. Athefre. It stands for Athefre's Pair and Block.
## Steps
Standard APB consists of 5 steps:
1. [**2x2x3**](tutorial/223.md): Solve a 2x2x3 block in the bottom-left. This is usually accomplished by building a Roux-style 1x2x3 block and then extending it by solving the DF and DB edges.
2. [**dBR Pair**](tutorial/pair.md): The back-right F2L pair is solved intuitively.
3. [**EO**](tutorial/eo.md): The edge-orientation of the remaining edges is solved algorithmically (11 algorithms).
4. [**LXS**](tutorial/lxs.md): The remaining three F2L pieces are solved algorithmically (116 algorithms).
5. [**ZBLL**](tutorial/zbll.md): The last layer is solved (493 algorithms).

This resolves to a hefty number of 620 algorithms. This number can be reduced to 39, by solving LXS intuitively (for which you do need to know the 20 F2L last slot cases) and using OCLL + PLL for the last layer.

<hr>

## Image generation parameters
[^apb-icon]: { "width": 250, "height": 250, "facelets": [ "n", "o", "n", "o", "u", "f", "n", "o", "f", "r", "r", "n", "r", "r", "r", "n", "o", "r", "n", "o", "d", "f", "f", "d", "f", "f", "n", "d", "d", "n", "d", "d", "o", "d", "d", "d", "n", "o", "n", "l", "l", "l", "l", "l", "l", "n", "o", "n", "b", "b", "b", "b", "b", "b" ] }