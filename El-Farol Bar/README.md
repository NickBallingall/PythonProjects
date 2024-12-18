
This project is a modified El-Farol Bar problem that has two types of agent: producers & consumers. It is an extension of the 'generating user data' project, and instead of trying to track transactions, tracks user behaviour.

Consumers want to be with producers at 'the bar (alternative funding platform)', and more consumers attract more producers. However, producers are also sensitive to how crowded 'the bar' is, and would be better off not joining if it's ratio of producers:consumers ≥ 0.6. They have no way of knowing what the ratio is until they join, and must make a decision on whether to join or not.

Similarly, consumers don't want to join if the ratio drops below a certain threshold (getting these two problems to work in tandem is a WIP).