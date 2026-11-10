# Test questions

Keep this file out of the S3 bucket. If it is uploaded, the knowledge base will find the answers here.

Name the Guild in each question when you ask a plain model, for example "At the Quillon Bay Tinkerers' Guild, ...".

Start a new test session for each question: reload the page, turn on Generate responses and reselect the model. In one long session, question 8 answered $18. In new sessions it answered $24.

| # | Question | Expected answer | Source | What it shows |
| --- | --- | --- | --- | --- |
| 1 | What is the name of the Guild's mascot? | Sprocket, a one-eyed otter | guild-handbook | A fact no model can know |
| 2 | What is the fire blanket called, and where is it? | Expect a miss on the name. The location is right, but the chunk ends before "Members call it Gerald." Do not edit workshop-rules.md, because an edit can move that cut | workshop-rules | Chunking: the model only sees the pieces it gets back |
| 2b | What do members call the fire blanket? | Gerald | workshop-rules | Asking differently retrieves the next chunk |
| 3 | What do I need before I can use the laser cutter? | A Red Card, which requires an Orange Card and Filament level | workshop-rules | A rule with conditions |
| 4 | How long can I borrow Big Ada, and what is the deposit? | 3 days, $20 deposit | equipment-loans | Reading a table |
| 5 | I returned a multimeter 12 days late. What do I owe? | $15. 12 days at $1.50 is $18, and the fee stops at $15 | equipment-loans | The model has to apply a cap |
| 6 | What happens to a project left on the shelf for 30 days? | It was recycled. 21 days on the Project Shelf plus 7 on the Purgatory Shelf is 28 days | workshop-rules | Simple reasoning over retrieved text |
| 7 | When is the Soggy Bridge Challenge, and what weight must the bridge hold? | Saturday, October 24, 2026, 12 kg for 30 seconds | events-2026-27 | Two facts from one chunk |
| 8 | How much are dues in January 2027? | $24 per term | notice-dues-change, which replaces guild-handbook | Two documents disagree, and the newer one wins |
| 9 | What is the Wi-Fi password for the Boiler? | The documents do not say | None | A good system says it does not know |
