# A-self-made-tutorial-for-GitHub-Flavored-Markdown-GFM
A self-made tutorial for GitHub Flavored Markdown (GFM)

## A self-made tutorial for GitHub Flavored Markdown (GFM)

Takao Inoue, Aug 4, 2016

   GitHub provides users with a syntax for formatting text called GitHub Flavored Markdown (GFM). 
The filename extension for GFM is md, used as (filename).md. 
This file is "A-self-made-tutorial-for-GitHub-Flavored-Markdown-GFM.md". 
This short tutotial gives a set of concrete descriptions and their sources written by using GFM. 
There is little explanation and one will directly understand the contents from the sources. 

### Heading
#### small heading
## Quoting text
Proverb of Latin:
> fortuna favet fortibus．

Nice words:

>“Not all of us can do great things. But we can do small things with great love.” 
>― Mother Teresa

```
(The source of the above)
# A-self-made-tutorial-for-GitHub-Flavored-Markdown-GFM
A self-made tutorial for GitHub Flavored Markdown (GFM)

## A self-made tutorial for GitHub Flavored Markdown (GFM)

Takao Inoue, Aug 4, 2016

   GitHub provides users with a syntax for formatting text called GitHub Flavored Markdown (GFM). 
The filename extension for GFM is md, used as (filename).md. 
This file is "A-self-made-tutorial-for-GitHub-Flavored-Markdown-GFM.md". 
This short tutotial gives a set of concrete descriptions and their sources written by using GFM. 
There is little explanation and one will directly understand the contents from the sources. 

### Heading
#### small heading
## Quoting text
Proverb of Latin:
> fortuna favet fortibus．

Nice words:

>“Not all of us can do great things. But we can do small things with great love.” 
>― Mother Teresa
```

## Styling text
*This text is italic.*
**This text is bold.**

**This text is bold and _partly italic_.**

~~This is an enigma.~~

```
(The source of the above)
## Styling text
*This text is italic.*
**This text is bold.**

**This text is bold and _partly italic_.**

~~This is an enigma.~~
```
## Unordered lists
* Good morning : bread and coffee
* Good afternoon : rice, pork, and vegitables
* Good evening : rice, chicken curry and ice cream

### Programming
- C++
- Python
- Qt

## Orderd lists
1. STL
2. C++/CLI
3. clang
 
```
(The source of the above)
## Unordered lists
* Good morning : bread and coffee
* Good afternoon : rice, pork, and vegitables
* Good evening : rice, chicken curry and ice cream

### Programming
- C++
- Python
- Qt

## Orderd lists
1. STL
2. C++/CLI
3. clang
```

# Hierarchy lists (Nested lists) Part 1
### Mathematical logic
1. Proof theory
  1. Cut elimination theorem
  2. Consistency
2. Model theory
  1. Classic theory
    1. Quantifier elimination
    2. Compactness theorem
  2. Stability theory
3. Recursion theory
  1. Recursion theorem
  2. Arithmetical hierarchy
4. Set theory
  1. Forcing
  2. Large cardinals
5. Computer science and logic
  1. Mizar
  2. Category theory

## Hierarchy lists (Nested lists) Part 2
### Mathematical logic
1. Proof theory
   1. Cut elimination theorem
   2. Consistency
2. Model theory
   1. Classic theory
      1. Quantifier elimination
      2. Compactness theorem
   2. Stability theory
3. Recursion theory
   1. Recursion theorem
   2. Arithmetical hierarchy
4. Set theory
   1. Forcing
   2. Large cardinals
5. Computer science and logic
   1. Mizar
   2. Category theory 
  
```
(The source of the above)
# Hierarchy lists (Nested lists) Part 1
### Mathematical logic
1. Proof theory
  1. Cut elimination theorem
  2. Consistency
2. Model theory
  1. Classic theory
    1. Quantifier elimination
    2. Compactness theorem
  2. Stability theory
3. Recursion theory
  1. Recursion theorem
  2. Arithmetical hierarchy
4. Set theory
  1. Forcing
  2. Large cardinals
5. Computer science and logic
  1. Mizar
  2. Category theory

## Hierarchy lists (Nested lists) Part 2
### Mathematical logic
1. Proof theory
   1. Cut elimination theorem
   2. Consistency
2. Model theory
   1. Classic theory
      1. Quantifier elimination
      2. Compactness theorem
   2. Stability theory
3. Recursion theory
   1. Recursion theorem
   2. Arithmetical hierarchy
4. Set theory
   1. Forcing
   2. Large cardinals
5. Computer science and logic
   1. Mizar
   2. Category theory 
```

## Backslash escapes

\*literal asterisks\*   

\*\*\*\*\*\*\*\*\*\*  (ten asterisks)

Markdown(GFM) provides backslash escapes for the following characters:

* \\   backslash
* \`   backtick
* \*   asterisk
* \_   underscore
* \{\}  curly braces
* \[\]  square brackets
* \(\)  parentheses
* \#   hash mark
* \+   plus sign
* \-   minus sign (hyphen)
* \.   dot
* \!   exclamation mark

```
(The source of the above)
## Backslash escapes

\*literal asterisks\*

\*\*\*\*\*\*\*\*\*\*  (ten asterisks)

Markdown(GFM) provides backslash escapes for the following characters:

* \\   backslash
* \`   backtick
* \*   asterisk
* \_   underscore
* \{\}  curly braces
* \[\]  square brackets
* \(\)  parentheses
* \#   hash mark
* \+   plus sign
* \-   minus sign (hyphen)
* \.   dot
* \!   exclamation mark
```

## Quoting code, a la carte

GitHub's URL is `https://github.com/github`.

**Boldface** of Boldface is written as `**Boldface**`.

```
#include <cstdio>

int main() {

   printf("\n Hello GitHub!\n");
   
   return 0;
}
```

```
(The source of the above)
## Quoting code, a la carte

GitHub's URL is `https://github.com/github`.

**Boldface** of Boldface is written as `**Boldface**`.

` ` ` (Delete two spaces between ` and ` . )
#include <cstdio>

int main() {

   printf("\n Hello GitHub!\n");
   
   return 0;
}
` ` ` (Delete two spaces between ` and ` . )
``` 

## Link

The hyperlink to GitHub (https://github.com/github)  with `Let's begin GitHub!` is as follows: 

[Let's begin GitHub!](https://github.com/github)

```
(The source of the above)
## Link

The hyperlink to GitHub (https://github.com/github)  with `Let's begin GitHub!` is as follows: 

[Let's begin GitHub!](https://github.com/github)
```

## Using emoji

* :crescent_moon: (crescent_moon)
* :herb: (herb)
* :cherry_blossom: (cherry_blossom)

For a full list of available emoji and codes, check out [emoji-cheat-sheet.com](http://www.webpagefx.com/tools/emoji-cheat-sheet/).

So many emojis there! Wow! :tada:

```
(The source of the above)
## Using emoji

* :crescent_moon: (crescent_moon)
* :herb: (herb)
* :cherry_blossom: (cherry_blossom)

For a full list of available emoji and codes, check out [emoji-cheat-sheet.com](http://www.webpagefx.com/tools/emoji-cheat-sheet/).

So many emojis there! Wow! :tada:

```

## Task lists

- [x] Let's take a coffee break.
- [ ] Let's go for a walk.
- [ ] Let's learn more GitHub.

```
(The source of the above)
## Task lists

- [x] Let's take a coffee break.
- [ ] Let's go for a walk.
- [ ] Let's learn more GitHub.

```

## Mentioning users and teams

When you mention me, use @Takao-Inoue.

```
(The source of the above)
## Mentioning users and teams

When you mention me, use @Takao-Inoue.
```

## Underscores are ignored in multiple occrrences

MUSSER-1997-Software-_Practice_and_Experience.pdf

(Musser's imporant paper: David R. Musser, Introspective Sorting and Selection Algorithms, Software-Practice and Experience, Vol. 27(8), 1997, pp. 983–993.) Introspective sorts, that is, Heapsorts after quicksorts are faster than quicksorts only.

```
(The source of the above)
## Underscores are ignored in multiple occrrences

MUSSER-1997-Software-_Practice_and_Experience.pdf

(Musser's imporant paper: David R. Musser, Introspective Sorting and Selection Algorithms, Software-Practice and Experience, Vol. 27(8), 1997, pp. 983–993.) Introspective sorts, that is, Heapsorts after quicksorts are faster than quicksorts only.
```

## Syntax highlighting

```C++
#include <iostream>
#include <string>
#include <utility>

using namespace std;

int main(int argc, char** argv) {
    
    pair<string, string> myPair_year("2016", "8");
    pair<string, string> myPair_greetings("Hello", "GitHub!");
    pair<int, string> myPair_great(2016, "Congratulations!");

    cout << "*****************************************" << endl;

    cout << "Year: " + myPair_year.first + ", " + "Month: " + myPair_year.second << endl;
    cout << myPair_greetings.first + " " + myPair_greetings.second << endl;

    cout << "*****************************************" << endl;

    cout << myPair_great.first << " year! " << myPair_great.second << endl;

    return 0;
}

result:

*****************************************
Year: 2016, Month: 8
Hello GitHub!
*****************************************
2016 year! Congratulations!
```

For this syntax highlighting, [linguist](https://github.com/github/linguist) is made use of.

```
(The source of the above)
## Syntax highlighting

` ` `C++ (Delete two spaces between ` and ` . )
#include <iostream>
#include <string>
#include <utility>

using namespace std;

int main(int argc, char** argv) {
    
    pair<string, string> myPair_year("2016", "8");
    pair<string, string> myPair_greetings("Hello", "GitHub!");
    pair<int, string> myPair_great(2016, "Congratulations!");

    cout << "*****************************************" << endl;

    cout << "Year: " + myPair_year.first + ", " + "Month: " + myPair_year.second << endl;
    cout << myPair_greetings.first + " " + myPair_greetings.second << endl;

    cout << "*****************************************" << endl;

    cout << myPair_great.first << " year! " << myPair_great.second << endl;

    return 0;
}

result:

*****************************************
Year: 2016, Month: 8
Hello GitHub!
*****************************************
2016 year! Congratulations!
` ` ` (Delete two spaces between ` and ` . )

For this syntax highlighting, [linguist](https://github.com/github/linguist) is made use of.
```

## Tables

Examples1-3 are the same tables whose sources are different. 

(Each ninja (group) below  was finally hired by the corresponding shogun.)

### Example 1

Ninja         | Shogun
------------- | -------------
Iga           | Tokugawa
Kouga         | Oda
Fuuma         | None

### Example 2

|Ninja         | Shogun       |
|------------- | -------------|
|Iga           | Tokugawa     |
|Kouga         | Oda          |
|Fuuma         | None         |

### Example 3

Ninja | Shogun
--------- | -------------
Iga    | Tokugawa
Kouga         | Oda
Fuuma     | None

### Example 4

Ninja | Shogun
------------- | -------------
Iga    | _Tokugawa_
**Kouga**         | *Oda*
~~Fuuma~~     | **~~None~~**

```
(The source of the above)
## Tables

Examples1-3 are the same tables whose sources are different.

(Each ninja (group) below  was finally hired by the corresponding shogun.)

### Example 1

Ninja         | Shogun
--------- | -------------
Iga           | Tokugawa
Kouga         | Oda
Fuuma         | None

### Example 2

|Ninja         | Shogun       |
|------------- | -------------|
|Iga           | Tokugawa     |
|Kouga         | Oda          |
|Fuuma         | None         |

### Example 3

Ninja | Shogun
------------- | -------------
Iga    | Tokugawa
Kouga         | Oda
Fuuma     | None

### Example 4

Ninja | Shogun
------------- | -------------
Iga    | _Tokugawa_
**Kouga**         | *Oda*
~~Fuuma~~     | **~~None~~**
```
### Example 5 (text-align)

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| Bach          | Bach       | Bach |
| Mozart     | Mozart        |   Mozart |
| Brahms | Brahms         |    Brahms  |
| Chopin | Chopin         |    Chopin  |

### Example 6

| Fruits | Name | Taste | Comments |
| :------------: | :---------------: | :---------------: | :----- |
|:apple: | Apple | | Apples produced in Nagano in Japan are one of the best.
|:green_apple: | Green apple | 
|:tangerine: | Tangerine | | |
|:lemon: | Lemmon | Sour!|
|:cherries: | Cherries | | Cute!
|:grapes: | Grapes | |
|:watermelon: |Watermelon  | | I like it! But don't eat too much.
|:strawberry: | Strawberry|| Recent Japanese strawberry varieties have good taste and appearance.|
|:peach: | Peach |||
|:melon: | Melon| Sweet |
|:banana: | Banana | | I have a custom to have one banana in the morning.|
|:pear: | Pear | Special nice taste |
|:pineapple: | Pinapple | | It is very good as a topping for humburgers, I think.|

```
(The source of the above)
### Example 5 (text-align)

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| Bach          | Bach       | Bach |
| Mozart     | Mozart        |   Mozart |
| Brahms | Brahms         |    Brahms  |
| Chopin | Chopin         |    Chopin  |

### Example 6

| Fruits | Name | Taste | Comments |
| :------------: | :---------------: | :---------------: | :----- |
|:apple: | Apple | | Apples produced in Nagano in Japan are one of the best.
|:green_apple: | Green apple | 
|:tangerine: | Tangerine | | |
|:lemon: | Lemmon | Sour!|
|:cherries: | Cherries | | Cute!
|:grapes: | Grapes | |
|:watermelon: |Watermelon  | | I like it! But don't eat too much.
|:strawberry: | Strawberry|| Recent Japanese strawberry varieties have good taste and appearance.|
|:peach: | Peach |||
|:melon: | Melon| Sweet |
|:banana: | Banana | | I have a custom to have one banana in the morning.|
|:pear: | Pear | Special nice taste |
|:pineapple: | Pinapple | | It is very good as a topping for humburgers, I think.|

```
