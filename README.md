# assignment2-katreddy

# Venkata Krishna Reddy Katreddy

###### My favourite place in the world is Ladakh which is situated in northern part of India.


Ladakh is most famous for breathtaking landscapes, the crystal clear skies, the highest mountain passes, thrilling adventure activities, Buddhist Monasteries and festivals. Ladakh gains a lot of popularity for being the only cold desert in India apart from bordering the World’s highest saltwater Lake **Pangong Lake**. Riding up the highest motorable road in the world, **Khardung la** is a dream come true for many. The Hunder sand dunes, frozen river trek and snow leopards all find their only home in Ladakh.


---

### Directions to Niagara Falls:

1. Start from missouri by road
2. On the way to Indiana
3. Then to colombus
   1. Then last destination to Niagara Falls 
   2. Which takes around 4 hours drive from there
4. Finally after a long 14 hours drive we'll reach to destination


* Food Items
* Camp equipment
* Friends
* Alcohol
* Playing Cards

[Link to AboutMe](https://github.com/krish11189/assignment2-katreddy/blob/main/AboutMe.md)


---

## Items to recommend:

Here there are some famous and delicios food items that I would like to recommend my friend he/she in Hyderabad.

| Food/Drink | Place | Expected Price |
|---|---|---|
| Bamboo Biryani | Lambasingi | 10$|
| Butter Chicken | Jalandhar | 15$ |
| Pasta | DLF towers | 15$ |
| Pizza-Dosa | Ramki Bandi | 12$ |
| KFC | KFC | 20$ |

---

### Pithy Quotes

> "Life is what happens when you're busy making other plans". - *John Lennon*

> "The best and most beautiful things in the world cannot be seen or even touched — they must be felt with the heart". - *Helen Keller*

---

## Algebra/Fibonacci Numbers

> In mathematics, the Fibonacci numbers, commonly denoted Fₙ, form a sequence, called the Fibonacci sequence, such that each number is the sum of the two preceding ones, starting from 0 and 1. That is, and for n > 1. The sequence starts: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...

[Click here to know more](https://en.wikipedia.org/wiki/Fibonacci_number)

```
pair<int, int> fib (int n) {
   if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

```

[Code Source](https://cp-algorithms.com/algebra/fibonacci-numbers.html)


