# hannibal
Hannibal is a particular financial tool that seeks to answer three specific questions about an account.
- Growth: When will this account hit a particular value?
- Maintenance: Under what conditions can this account maintain value?
- Depletion: When will this account run out of value?
These questions are answered by manipulating the compound interest formula and providing additional parameters:
- regular deposits and/or withdrawals
- adjustments for inflation
- adjustments for standard of living
Future work may include:
- specifying asset classes under a specific account, with variable growth rates
- specifying expenses in the form of a budget, with expected growth rates per category
- storing asset / expense profiles in a secure manner
- modeling normal (earnings misses) and black swan (pandemics) risk probabilities
Hannibal is written in Python3 and Flask.
