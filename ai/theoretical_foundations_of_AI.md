# The **theoretical foundations of AI and computer science** that Buchanan also referenced.

---

## 🔹 Lambda Calculus (Alonzo Church, 1903–1995)

* **Definition**: A formal system (1930s) for expressing computation via **function abstraction and application**.
* Everything in lambda calculus is built from:

  * **Variables**
  * **Functions (λ-expressions)**
  * **Applications (applying a function to an argument)**

👉 Example:
The function $f(x) = x + 1$ in lambda calculus is written as:

$$
\lambda x. (x+1)
$$

If we apply it to `2`:

$$
(\lambda x. (x+1)) \; 2 \quad \Rightarrow \quad 3
$$

So, lambda calculus is basically **mathematics of computation**.

---

## 🔹 Equivalence of Formalisms

In the 1930s, multiple definitions of “effective computability” emerged:

1. **Turing Machines** (Alan Turing, 1936) → abstract machines manipulating symbols on tape.
2. **Lambda Calculus** (Alonzo Church) → rewriting symbolic expressions.
3. **Recursive Functions** (Gödel, Kleene).

**Key result**:

* These different models all compute the **same set of functions**.
* Meaning: what is computable in one model is computable in all the others.

---

## 🔹 The Church–Turing Thesis

* **Statement**:

  > Anything that can be effectively computed (i.e., by an algorithm) can be computed by a Turing machine (or equivalently, in lambda calculus).

* It’s **not a formal theorem** (because “effectively computable” is an intuitive notion), but it’s a widely accepted principle in computer science.

* It forms the **foundation of modern computer science**: programming languages, compilers, and AI are all ultimately rooted in these models.

---

✅ **Why it matters for AI**:

* AI is built on the assumption that **intelligence is computable**.
* If human reasoning can be formalized, it should, in theory, be representable in **lambda calculus, recursive functions, or a Turing machine**.
* That’s why Buchanan (2005) included this in his history: it’s the bridge between **mathematical theory** and **building real intelligent systems**.

<img width="1589" height="1010" alt="image" src="https://github.com/user-attachments/assets/ae819153-0f2f-4431-b317-9f77d05939fd" />
