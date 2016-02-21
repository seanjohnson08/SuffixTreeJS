## SuffixTree JS

SuffixTree JS is a javascript implementation of [Ukkonen's algorithm](https://www.cs.helsinki.fi/u/ukkonen/SuffixT1withFigs.pdf) for "generalized suffix tree". The code is essentially based on the snippets provided here : http://www.allisons.org/ll/AlgDS/Tree/Suffix/. 

### Visualization

My main contribution is this website : http://mrnoutahi.com/SuffixTreeJS/ that enable suffix trees visualisation using [d3js](https://d3js.org/). 

Each internal node can be collapsed.

The suffix on each leave end with ```[start, number]``` where ```start``` is the position of the suffix (indexing start at 0) and ```number``` is the sequence number of the sequence the suffix is from. I also use different colors for each sequence in the representation. 

Check the **gh-pages** branch if you're interested in the visualization part. The theme used is [Solo](http://chibicode.github.io/solo). I'm open to any suggestions.


### License

This is licensed under the MIT License
