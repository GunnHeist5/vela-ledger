# vela-ledger

Each line of `hashes.txt` is `<sha256 of a forecast record> <previous record's hash> <time UTC>`: one line per forecast locked by Vela (before a launch, or before the quarter it forecasts ended), and one per forecast later marked void. The records themselves are kept privately and will be shown with their results; anyone can then check each one against its hash here. The commit times of this repository are an independent timestamp: a record existed, unchanged, by the time its line was committed.

Lines are only ever added, never changed or removed; each line names the one before it.

Model forecast for research purposes. Not investment advice.
