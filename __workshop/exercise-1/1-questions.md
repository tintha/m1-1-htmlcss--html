# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screen reader is a form of assistive technology that renders text and image content as speech or braille output. Screen readers are essential to people who are blind, and are useful to people who are visually impaired, illiterate, or have a learning disability. (Source: https://en.wikipedia.org/wiki/Screen_reader)

We should care about them to make accessible websites.

Web accessibility is an inclusive design that ensures everyone can access your website, no matter their abilities. (Source: https://evolvingweb.ca/blog/what-web-accessibility-and-why-should-you-care)

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
`<img>`

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
`<a>`

c) You want to sell designer hats. You need to receive orders from the user.
`<form>`

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No, because the “permitted content” of a button is limited to “phrasing content”. Phrasing content defines the text and the mark-up it contains. (Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button)

## Q5 - What is the most generic tag you can use?
`<div>`

## Q6 - What do the following achronyms stand for?

a) `a` = anchor

b) `ol` = ordered list

c) `ul` = unordered list

d) `li` = list item

e) `tr` = table row

f) `th` = table header

g) `td` = table data

## Q7 - Usually, `td` elements are children of what kind of elements?
tr

## Q8 - What is the difference between td and th?
td are used for table data cells, th are used for table header cells

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
In void elements, where there is a lack of content.

## Q11 - What is autofilling and why is it important?
It predicts the rest of a word a user is typing. It's important because it helps users fill out form faster, resulting in a better user experience.

## Q12 - Which attributes are always present in an img element?
src

## Q13 - Which attribute is always present for an anchor tag?
href
