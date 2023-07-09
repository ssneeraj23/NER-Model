# NER-Model
A Named Entity recognition model using RNN. Its objective is to identify all the named entities present in
that sentence and predict their correct type (tag) from a predefined tag set.

Dataset: https://multiconer.github.io/dataset

Example:
Input sentence: Jim bought 300 shares of Acme Corp. in 2022.

Tagset: Person, Organization, Time

Output: [Jim] <sub>Person</sub> bought 300 shares of [Acme Corp.] <sub>Organization</sub> in [2022] <sub>Time</sub>.

