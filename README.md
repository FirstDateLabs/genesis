## Question: What features does the Internet as we know it lack, that we need blockchains?

**AUDITABILITY AND PREDICTABILITY ARE KEY!**

Current blockchains do not respect their developers. Why? Because they do not allow the developers to migrate to some other platform natively. Basically, you're stuck with the chain for the entire life of the application.

Of course, you can name many examples that have done such migrations successfully. Okay, I totally agree with you on that. But I have a question: Can they do it again? I mean, yeah, what's stopping them after all, right? They can employ the same process they did for the first migration. But is this scalable? If some key feature is missing on the host platform, your first engineering solution would not be to simply make use of the new technology wherever it is being offered. You have to come up with hacks, tricks, ad-hoc solutions. SUCH A WASTE OF ENGINEERING TIME. What we could do is to respect the developers.

By now, I have used the word "developer" a bunch of times. A developer is an abstraction for all the applications being built on top of those platforms. They could be individuals, start-ups, big corps, etc. In this model of "Blockchain," the collective performance of those developers is wasted just because they are stuck with a choice they made before their application even became alive. On top of all that, they are stuck with a limited set of choices if they want any kind of verifiable "auditability" and "predictability." THEY ARE NOT FREE TO FULLY EXPLORE THE TRADE-OFF SPECTRUM of "auditability" and "predictability."

Some of the tools that we have in our toolbox to make the Internet as we know it have arbitrary degrees of "auditability" and "predictability" without loss of compatibility with the current infrastructure.

1. **SSL (Secure Sockets Layer)**: Secure communication using digital signatures.
2. **MPC (Multi-Party Computation)**: Using MPC, untrusted clients can verifiably prove communication among different servers.

Communication is verifiable through the SSL protocol, using MPC on the client side, without needing to trust the client.

**Scenario**: A client collaborates with server A to generate a verifiably generated request. The request is then sent to server B along with a validity proof.

If you "trust" the server...
