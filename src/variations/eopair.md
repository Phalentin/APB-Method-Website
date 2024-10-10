# EOPair
<image class="right" alt="Rubik's Cube before the EOPair step was completed." src="/images/variations/eopair/eopair.png">

EOPair is an algorithm set for solving edge orientation while inserting the dBR pair. This was the standard way of doing APB, until it was replaced by solving the pair completely and then doing edge orientation in early 2024. The reasons for this change where the following:
- **Algorithm Count:** EOPair had 128 algorithms while pair followed by EO only requires 11 algorithms.
- **Not much less Efficient:** Inserting the pair and then solving EO only averages about 0.3 moves worse.
- **EOPair recognition:** Due to needing to check the BR edge for EOPair recognition, quick recognition is quite difficult. With pair + EO, the BR spot is already occupied with the pair, so the recognition is much faster.

Still, there is an argument about the utility of the misoriented U subset. Since the pair has to be inserted into dBR no matter its orientation in standard APB, a misoriented pair requires three moves to be inserted, that could be used to orient some edges.<br>
The algorithms can be found in the [EOPair sheet](https://docs.google.com/spreadsheets/d/1Hs9ikHz-4cfbqBfqvuvE8X9sjCb4Jtm482ZvsFQA2rY/).