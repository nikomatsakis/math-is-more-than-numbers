class: center
name: title
count: false

# Math is more than numbers

.me[.grey[*by* **Nicholas Matsakis**]]
.left[.citation[View slides at `https://nikomatsakis.github.io/math-is-more-than-numbers/`]]

---

# What is math?

--

![Math Baby](./images/math-baby.gif)

---

# So...math is numbers?

![Numbers](./images/racoon-abacus.gif)

---

# I claim...

Math is **not just numbers**.

In fact, math can be **philosophy** -- or anything at all.

--

![Suspicious](./images/steven-universe-suspicious.gif)

---

# I want to convince you...

Math is two things

* Speaking precisely and unambiguously
* Abstraction

---

# Precisely and unambiguously

--

![Spock](./images/spock-precisely.gif)

---

# Precisely and unambiguously

Is this true?

## All kids like candy

???

How many say yes? (raise your hands)

How many say no? (raise your hands)

OK, so some say yes, some say no, let's see.

Let's test it!

Bring out a bag of dum-dums.

OK, I've got some candy. Who wants some?

Get out the black licorice. OK, good, this is some candy I brought home from the Netherlands. It's called Double Salt Licorice. Does anybody want to try it?

OK, who can tell me what's the problem?

(give them a piece of candy)

---

# How to write this more clearly

What exactly does "all kids like candy mean"...

* All kids like *all* candy?
* All kids like *some* candy?
* Most kids like *some* candy?

It's kind of hard to tell.

---

# Answer: equations

* Write $(K) for a kid
* Write $(C) for a kind of candy
* Then we can write a predicate $(K\:likes\:C)

A **predicate** is something that can be *true* or *false*

???

So, is `K likes C` true... or false?

(If somebody answers, good, and give them candy if they seem to have made a good effort. 

If not, we'll start to probe -- how many say yes, no, not sure.)

The answer is "it depends". Which kid, which candy?

K and C are *variables*, just like you've seen elsewhere.

So depending on what values we give them, this might be true or false. 

Pick a kid who seems shy -- so, what's your name. And do you like dum-dums or jolly ranchers?

Write, so if K is X, and C is dum-dums, the statement is true. But if C is double salt licorice, maybe not.

(give them candy too)

---

# "For all"

Here is a predicate

$$\forall K:Kid. \forall C:Candy. K\:likes\:C$$

What does it mean?

"For any kid $(K)

and any kind of candy $(C)

the kid $(K) likes the candy $(C)"

**So, what would it take to make this true?**

---

# "There exists"

Here is a predicate

$$\exists K:Kid. \exists C:Candy. K\:likes\:C$$

What does it mean?

"There exists some kid $(K)

and some kind of candy $(C)

such that the kid $(K) likes the candy $(C)"

**So, what would it take to make this true?**

---

# What does this mean?

Here is a predicate

$$\forall K:Kid. \exists C:Candy. K\:likes\:C$$

--

What does it mean?

"For any kid $(K)

there is some kind of candy $(C)

such that the kid $(K) likes the candy $(C)"

---

# What does this mean?

Here is a predicate

$$\exists K:Kid. \forall C:Candy. K\:likes\:C$$

---

# How do you know what is *true*?

Go back to this one...

$$\forall K:Kid. \forall C:Candy. K\:likes\:C$$

...how did we know it is *false*?

???

Idea: counterexample

---

# Philosophy

<div style="float: right; margin-left: 2em; width: 200px;">
    <img src="./images/Aristotle.jpg" alt="Chrysippus" style="width: 100%;">
    <span class="small">Aristotle (384BC - 322BC)</span>
</div>

* Studied under Plato
* Taught Alexander the Great
* Developed the idea of analyzing the *structure* of an argument

---

# Logic in other parts of the world

* Logic also developed in [China](https://en.wikipedia.org/wiki/Logic_in_China), where **Mozi** (470 - 391 BC) taught about correct conclusions, but didn't use mathematical reasoning.
* And in [India](https://en.wikipedia.org/wiki/Logic_in_India), where **Panini** (5th century BC) and the **Nyaya** school (~200 CE) is the closest to what we are discussing here.

Indian logic in particular influenced a lot of what we are describing here.

.footnote[
    I'm leaving out a *lot* of details. Read the Wikipedia pages!
]

---

# Aristotelian logic

* All people are mortal
* Socrates is a person
* therefore...?

---

# Aristotelian logic

* Every $(P) predicate can be either **true** or **false**
    * It must be one or the other; and it cannot be both
* We can combine to make bigger predicates
    * $(P \wedge Q) -- **$(P) *and* $(Q)** are both true
    * $(P \vee Q) -- **$(P) *or* $(Q)** is true (or both!)
    * $(\neg P) -- **not $(P)**, true if $(P) is false

