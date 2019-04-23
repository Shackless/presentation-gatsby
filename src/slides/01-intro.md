# JAMstack & Gatsby

## Make static sites great again!

Simon Hopstätter  
E.ON DD&T  
05 / 2019

---

> Inscrutable icons litter the face of the devices even though the research
> community has long demonstrated that people cannot remember the meaning of
> more than a small number of icons […] Who can remember what each icon
> means? Not me.
> <cite>Don Norman</cite>

---

# 🤫

---

```javascript
export const query = graphql`
  query SlideQuery($index: Int!) {
    slide(index: { eq: $index }) {
      html
      index
    }
  }
`;
```

---

## Slides are written in Markdown!

Here's the source of the first slide:

    # Gatsby Deck

    Create presentations using Gatsby & React.
