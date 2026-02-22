# Bias-Aware Credit Approval System (EU AI Act Compliance)
Normally, an AI is like a sponge—it soaks up everything in the data you give it. If your historical data shows that banks mostly gave loans to men in the 90s, the AI thinks, _"Ah, being a man must be why they are good at paying back loans!"_ 🤦‍♂️ This is a __bias__.

A "Bias-Aware" system is one where you, the developer, have added a __special filter__ to make sure the AI isn't using illegal shortcuts to make decisions.
## 1. The "What & Why"
I’ve been hearing a lot about how AI is getting regulated in Europe (the EU AI Act), so I wanted to see if I could actually "break" a credit-scoring model and then fix it.
The goal here isn't just to make a model that's 99% accurate. It’s to build a model that doesn't accidentally become a jerk by discriminating against people based on their gender or age. In the EU, if your AI does that, you're in big trouble—so I’m playing "AI Ethics Lead" for a day to see how it works. 😁

## 2. How I know it discriminates?
In Europe, the concern about AI bias isn't just a "gut feeling"—it's based on high-profile cases where algorithms actually failed, combined with a very specific legal philosophy about human rights. notifications of The Dutch "Childcare Benefit" Scandal , The "CV Ghosting" in Recruitment, Predictive Policing in Belgium & Italy are some of them. Well I am not targetting to solve all of them but surely this usecase can help understand how it all works and how companies can buidl a robust system around it.
