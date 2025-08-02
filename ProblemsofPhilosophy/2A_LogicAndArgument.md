# Elementary Logic — Validity & Soundness

## 1 · What Is an “Argument”?

> A *logical* argument is simply a **list of statements** (premises) followed by a **conclusion**—not a quarrel!

```
P1  Premise  
P2  Premise  
…  
Pn  Premise  
C   Conclusion
```

---

## 2 · Two Key Properties

| Term          | Formal Definition                                                                                                                                    | Intuitive Idea                             |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| **Validity**  | It is **impossible** for *all* premises to be true **and** the conclusion false.  Equivalent form: “Necessarily, if P1…Pn are true, then C is true.” | *Truth-preserving form.*                   |
| **Soundness** | The argument is **valid** *and* **all premises are actually true**.                                                                                  | *Valid + true premises → true conclusion.* |

> Every sound argument is valid, but not every valid argument is sound.

---

## 3 · Worked Examples

| # | Argument (simplified form)                                                                                                         |       Valid?      |    Sound?    | Notes                                                     |
| - | ---------------------------------------------------------------------------------------------------------------------------------- | :---------------: | :----------: | --------------------------------------------------------- |
| 1 | 1. **Socrates** is a Martian.  <br>2. If Socrates is a Martian, **Plato** is from Venus.  <br>∴ Plato is from Venus.               | ✔︎ (Modus Ponens) | ✘ (P1 false) | **Valid but unsound**                                     |
| 2 | 1. **Aristotle** is **not** a Martian.  <br>∴ Aristotle is **not** a Martian.                                                      |         ✔︎        |      ✔︎      | Tautological; sound but unpersuasive.                     |
| 3 | 1. **Democritus** is from Venus.  <br>2. Democritus is **not** from Venus.  <br>∴ Aristotle is a Martian.                          |         ✔︎        |       ✘      | Premises inconsistent → still *valid* in classical logic. |
| 4 | 1. No **professors** are **ignorant**.  <br>2. All ignorant people are **vain**.  <br>∴ No professors are vain.                    |         ✘         |       ✘      | Venn-diagram shows counter-example → **invalid**.         |
| 5 | 1. **Lions** are **fierce**.  <br>2. Some lions do **not** drink coffee.  <br>∴ Some coffee-drinking creatures are **not** fierce. |         ✘         |       ✘      | Counter-model exists → **invalid**.                       |

---

## 4 · Key Logical Form Cited

| Name             | Schema                                  | Link                                                                                      |
| ---------------- | --------------------------------------- | ----------------------------------------------------------------------------------------- |
| **Modus Ponens** | 1. *If P then Q*  <br>2. *P*  <br>∴ *Q* | [https://en.wikipedia.org/wiki/Modus\_ponens](https://en.wikipedia.org/wiki/Modus_ponens) |

---

## References

1. **Logical Validity** – [https://en.wikipedia.org/wiki/Validity\_(logic)](https://en.wikipedia.org/wiki/Validity_%28logic%29)
2. **Soundness** – [https://en.wikipedia.org/wiki/Soundness](https://en.wikipedia.org/wiki/Soundness)
3. **Classical Logic** – [https://plato.stanford.edu/entries/logic-classical/](https://plato.stanford.edu/entries/logic-classical/)
4. **Venn Diagram Technique** – [https://en.wikipedia.org/wiki/Venn\_diagram](https://en.wikipedia.org/wiki/Venn_diagram)
5. **Socrates** – [https://en.wikipedia.org/wiki/Socrates](https://en.wikipedia.org/wiki/Socrates)
6. **Plato** – [https://en.wikipedia.org/wiki/Plato](https://en.wikipedia.org/wiki/Plato)
7. **Aristotle** – [https://en.wikipedia.org/wiki/Aristotle](https://en.wikipedia.org/wiki/Aristotle)
8. **Democritus** – [https://en.wikipedia.org/wiki/Democritus](https://en.wikipedia.org/wiki/Democritus)
9. **Lewis Carroll & Logic** – [https://en.wikipedia.org/wiki/Lewis\_Carroll#Logic\_and\_mathematics](https://en.wikipedia.org/wiki/Lewis_Carroll#Logic_and_mathematics)
