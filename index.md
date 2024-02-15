# Research Integrity

_- in brainstorming phase -_

This project is about using nanopublications to ensure research integrity and improve the scientific paper workflows.

---

## Demos and APIs

- The links below go to quick technical **demos**
- These are fully built upon decentralizied **APIs**
- Therefore, all this can easily be built into **your own systems**

These are all just **starting points for discussion**, to show what kind of things we could do. But they'd need further discussion and work, of course, and there are many other options.

---

## Publishing

For editors/reviewers to **positively flag papers**:

- [Publishing form](https://nanodash.knowledgepixels.com/publish?template=https://w3id.org/np/RA7QYvH8CeADZsPqopmTnBw1pk2CpqFavj1QVQMzd7zCA) (or [with pre-filled DOI](https://nanodash.knowledgepixels.com/publish?189&template=https://w3id.org/np/RA7QYvH8CeADZsPqopmTnBw1pk2CpqFavj1QVQMzd7zCA&param_paper=https://doi.org/10.1038/sdata.2016.18))
- [Example nanopublication](https://w3id.org/np/RAnpjDJ4pkVBIC0hyjYX5kGsfD9SPD2pmriZnYDHPAkA8)

For authors to **declare manuscripts** (which can then be confirmed by others, e.g. the mentioned organization):

- [Publishing form](https://nanodash.knowledgepixels.com/publish?template=https://w3id.org/np/RAN5Mdzqj_aO88RRAS4FC5NiPOCWf8l6zV7v-XJ4raUZk)
- [Example nanopublication](https://w3id.org/np/RAXOw75dxZsZ9YBwVAo2KdH6zdC8cxehT7lB8i0DYUtpY)

For editors/reviewers/researchers to **make plain-text comments** about papers:

- [Publishing form](https://nanodash.knowledgepixels.com/publish?template=http://purl.org/np/RA3gQDMnYbKCTiQeiUYJYBaH6HUhz8f3HIg71itlsZDgA) (or [with pre-filled DOI](https://nanodash.knowledgepixels.com/publish?template=http://purl.org/np/RA3gQDMnYbKCTiQeiUYJYBaH6HUhz8f3HIg71itlsZDgA&param_thing=https://doi.org/10.1038/sdata.2016.18))
- [Example nanopublication](https://w3id.org/np/RAD2nMxJb-BVqTdHY3CRxLEkcYXA2K6GhZg7dqpZHWRhA)

---

## Querying

The knowledge entered above can then be queried globally, for example:

- [Get all paper flags](https://tapas.knowledgepixels.com/tapas.html?api=knowledgepixels/research-integrity&op=/get-paper-flags&autosubmit=on)
- [Get all paper flags](https://tapas.knowledgepixels.com/tapas.html?api=knowledgepixels/research-integrity&op=/get-declared-manuscripts&autosubmit=on)
- [Get all statements mentioning a given paper](https://tapas.knowledgepixels.com/tapas.html?api=knowledgepixels/nanopub-query-api&op=/get-subj-refs&autosubmit=on&param_subj=https://doi.org/10.1038/sdata.2016.18)

---

## Background

Publishing and querying is performed on the global decentralized network of nanopublication services. See for example [this monitor](https://monitor.knowledgepixels.com/).
