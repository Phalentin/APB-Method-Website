# EO
<image class="right" alt="Rubik's Cube with the EO step completed" src="/images/tutorial/eo/eo.svg">[^eo]<br>

Edge orientation is the hardest concept in APB. If you already know what EO is, you can skip to [How to solve EO in APB](#how-to-solve-eo-in-apb). 
## What is edge orientaiton?
[zzmethod.com](https://www.zzmethod.com/) already made a great video explaining edge orientation in the context of ZZ, if you only want to know about EO in general, you only have to watch until 7:42 minutes. Alternatively you can read the written tutorial below.
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/fxwVmTI5nGM?si=-Q63PMa-NS9tqTja&amp;start=13" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The orientation is a property of each edge on the cube. An edge can either be *good* or *bad*. An edge is good, if it can be solved with R, U, L, D and B moves. An edge is bad, if F or B moves are required to solve it.

## How to recognize if an edge is good or bad
You can recognize the orientation of an edge by looking at its colors. If the edge has white or yellow on it (or the top/bottom color respectively), the white face must be:
- on the top or bottom for U and D layer edges
- on front or at the back for the E layer edges

for the edge to be considered *good*.
If the edge doesn't have white or yellow on it, the front/back color takes the role of white or yellow respectively.
## How to solve EO in APB
<div class="warning"><b>Note:</b><br>In the beginnings of APB, the pair was created and then left where it happened to be. It was then inserted while doing edge orientation in the next step. To learn more about this, see <a href="variations/eopair.md">EOPair</a>. This way of doing the pair and edge oriantation was disbanded, because it only saved 0.3 moves on average, but required 117 more algorithms.</div>

### Recognition
In the EO step, six edges have to be oriented. Five of them have white or yellow on them, so the recognition is no problem. The sixth edge, beloning into FR, should be tracked during pair creation. Make sure not to look at the back or left face of the UL and UB edges respectively. Since you have already tracked edge belonging into FR, if the top color is not white/yellow, the edge is misoriented (except if the edge beloning into FR is in one of these places of course).
### Orienting the edges

In APB, the edges are oriented algorithmically. These algorithms can be found in the [EOpair sheet](https://docs.google.com/spreadsheets/d/1Hs9ikHz-4cfbqBfqvuvE8X9sjCb4Jtm482ZvsFQA2rY/). Note that this sheet is not fully up do date and thus still includes all the 128 EOPair algorithms. You only need to learn the algorithms in the "dBR Solved EO" tab.

<hr>

## Image generation links
[^eo]: <https://visualcube.api.cubing.net/?fmt=svg&size=250&fc=dsdsysdsddsdsrrdsrdsdbbsbbd&r=y30x-30&bg=t>