# Introduction to APB
<image class="right" alt="Symbolic image of the APB method" src="/images/apb-icon.svg">[^apb-icon]

APB was originally deveolped by James Straughon aka. Athefre. It stands for Athefre's Pair and Block.
## Steps
Standard APB consists of 5 steps:
1. [**2x2x3**](tutorial/223.md): Solve a 2x2x3 block in the bottom-left. This is usually accomplished by building a Roux-style 1x2x3 block and then extending it by solving the DF and DB edges.
2. [**dBR Pair**](tutorial/pair.md): The back-right F2L pair is solved intuitively.

<div class="warning"><b>Note:</b><br>In the beginnings of APB, the pair was created and then left where it happened to be. It was then inserted while doing edge orientation in the next step. To learn more about this, see <a href="variations/eopair.md">EOPair</a>. This way of doing the pair and edge oriantation was disbanded, because it only saved 0.3 moves on average, but required 117 more algorithms.</div>

3. [**EO**](tutorial/eo.md): The edge-orientation of the remaining edges is solved algorithmically (11 algorithms).
4. [**LXS**](tutorial/lxs.md): The remaining three F2L pieces are solved algorithmically (116 algorithms).
5. [**ZBLL**](tutorial/zbll.md): The last layer is solved (493 algorithms).

This resolves to a hefty number of 620 algorithms. This number can be reduced to 39, by solving LXS intuitively (for which you do need to know the 20 F2L last slot cases) and using OCLL + PLL for the last layer.

<hr>

## Image generation links
[^apb-icon]: <https://visualcube.api.cubing.net/?fmt=svg&size=250&fc=dsdsybdsbrrdrrrdsrdswbbwbbd&bg=t>