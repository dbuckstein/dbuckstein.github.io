---
markdown: kramdown
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


# Greetings

Welcome to the shiny new portfolio website of **Daniel S. Buckstein**, game programmer and lifelong learner.  I enjoy many types of math-intensive programming, including graphics programming, and shaders, animation and physics programming, tools programming, from low-level to high-level engineering, from back-end to front-end interfaces, from older to modern languages, etc.  My only regret at this very moment is that web programming is not among the things I was ever deeply passionate about.  Therefore, dear reader, please forgive me for this plain old website, powered by [GitHub Pages](https://pages.github.com/), [Jekyll](https://jekyllrb.com/) and [MathJax](https://www.mathjax.org/), and evidently void of the hassle of style, so that I may focus on producing and publishing only the finest portfolio materials for your reading and viewing pleasure.  Then again, this _is_ an open-source repository, so feel free to beautify as you see fit... please just don't break the build!


## Links

[Blog](/blog/)


### Social Media

Find me @dbuckstein on [GitHub](https://github.com/dbuckstein), [LinkedIn](https://www.linkedin.com/in/dbuckstein/) and [Twitter](https://twitter.com/dbuckstein).


## Tests

### Code Test

The first trial: hopefully some code appears here...
```c
/*
    This is a block comment.
    Fun fact: I usually use tabs to indent but spaces look better here.
*/
#ifndef _FSCALAR_H_
#define _FSCALAR_H_

#ifdef __cplusplus
extern "C" {
#endif // __cplusplus

    typedef struct fscalar
    {
        float value;        // the scalar's value
        float valueSq;      // value squared
        float valueInv;     // value inverse (reciprocal)
        float valueSqInv;   // value squared inverse
    } fscalar;
    
    fscalar fscalarNew(float const value);

#ifdef __cplusplus
}
#endif // __cplusplus

#endif // _FSCALAR_H_
```

### Math Test

The second trial: hopefully these right here, $$ y = x^2 $$ and \\( x = \sqrt{y} \\), are some inline math, and some blocks of math appear here...

$$ y = x^2 $$

\\[ x = \sqrt{y} \\]


### Materials

The third trial: I really just need code and math to make this all work, so if those two tests passed, then we're good to go!  Check back later for stuff...
