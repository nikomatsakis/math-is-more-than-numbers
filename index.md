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

In other words, how would you say this in "plain English"?

---

# vs English

Compare

$$\forall K:Kid. \exists C:Candy. K\:likes\:C$$

to "every kid likes some kind of candy".

What else could this mean?

