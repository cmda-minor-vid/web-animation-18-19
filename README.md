# ![Web Animationn - Course 2018-2019][banner]

## Table of Contents

*   [Synopsis](#synopsis)
*   [Description](#description)
*   [Communication](#communication)
*   [Goals](#goals)
*   [Grade](#grade)
*   [Resources](/resources.md)
*   [Conduct](#conduct)
*   [License](#license)

## Synopsis

The course **Web Animation** is given at [**@CMDA**][cmda] in 2019 between
6 May and 24 May.

*   **Course**: Web Animation - Minor ViD
*   **Coordinator**: [Danny de Vries][dangit]
*   **Lecturers**:
    [Danny de Vries][dangit] ([**@dandevri**][danweb]) (_vid-1_ and _vid-2_)
*   **SIS**: HTML/CSS
*   **Credit**: 3 ECTS
*   **Academic year**: 2018-2019
*   **Period**: Quarter 3 (spring)
*   **Programme**: Communication and Multimedia Design (full time bachelor)
*   **Language**: Dutch instructions and English resources
*   **Entry requirements**: Admission

## Description
In Web Animation we'll create a prototype that heavily focusses on interactivity and animations using _CSS animations_, _CSS transitions_ and _SVG_. Instead of static design and prototyping tools we'll work straight into the browser using in-browser (dev)tools. This course is part of the **Minor Visual (Interface) Design** before **Ontwerpen 3** alongside **Web Typography**, together making up **Visual Interface Design 2**. In _ontwerpen 3_  you’ll apply your newfound web skills.

## Communication

*   [GitHub][gh] — Main source of information, assignments, important dates,
    and more
*   [Examples][examples] — Example code from slides
*   [Moodle][moodle] — Schedulers


If you have questions:
*   [Browse examples][examples]
*   [Look at the additional resources][resources]
*   [Ask for other students to help you][moodle]
*   [Contact a lecturer][synopsis]

## Goals

#### Main goals

The main goals in this course are that you’re able to:

*   You can create different CSS3 `states`, `transitions` and `animations` to enhance your static design
*   You can tweak and adjust your prototype with `in-browser tooling` (devtools)
*   You can create and animate `.SVG`

#### Sub goals

In practice you’ll learn to:

* <a name="subgoal-1"></a>
    Create states using transitions ([**week 1**][w1])
*  <a name="subgoal-2"></a>
    Add interacitivity with CSS pseudo-classes([**week 1**][w1]) 
*  <a name="subgoal-3"></a>
    Tweak designs with in-browser devtools([**week 1**][w1])
*  <a name="subgoal-4"></a>
    Animate using CSS animations([**week 2**][w2])
*  <a name="subgoal-5"></a>
    Use CSS transforms ([**week 2**][w2])
* <a name="subgoal-6"></a>
    Animate scalable vector graphics ([**week 3**][w3])    
*  <a name="subgoal-7"></a>
    Use SVG filters ([**week 3**][w3])

The below table breaks down the general time needed per week.

| Week | Effort | Topic            | Activities                                             |
| ---- | -----: | ---------------- | ------------------------------------------------------ |
| 0    |  NaN   | getting started  | [getting started][gs]                                  |
| 1    |  9:20h | transitions      | [lab][w1lab], [lecture][w1lec], [assignments][w1a]     |
| 2    |  9:20h | animations       | [lab][w2lab], [lecture][w2lec], [assignments][w2a]     |
| 3    |  9:20h | svg              | [lab][w3lab], [lecture][w3lec], [assignments][w3a]     |

## Grade

| Task                                |   Weight |
| ----------------------------------  | -------: |
| [Assignment 1][grading]             |      25% |
| [Assignment 2][grading]             |      25% |
| [Assignment 3][grading]             |      25% |
| [Oral test][grading] (oral test)    |      25% |
| **Total**                           | **100%** |


```js
if (!a1 && !a2 && !a3 && !a4) {
  grade = 'GR'
} else if (a1 < 5.5 || a2 < 5.5 || a3 < 5.5 || a4 < 5.5) {
  grade = 1
} else {
  grade = (a1 * 0.25) + (a2 * 0.25) + (a3 * 0.25) + (a4 * 0.25)
}
```

## Programme

This course is given at [Communication and Multimedia Design][bachelor], a
design bachelor focused on interactive digital products and services.  CMD is
part of the [Faculty of Digital Media and Creative Industries][faculty] at the
[Amsterdam University of Applied Sciences][university].

## Conduct

This course has a [Code of Conduct][coc].  Anyone interacting with this
repository, organisation, or community is bound by it.

Staff and students of the Amsterdam University of Applied Sciences (Hogeschool
van Amsterdam) are additionally bound by the [Regulation Undesirable
Conduct][ruc] ([Regeling Ongewenst Gedrag][rog]).

## License

[`MIT`][license] © [Danny de Vries][dangit], docs and images are [CC-BY-4.0][].

[banner]: https://cmda-minor-vid.github.io/web-animation-18-19/assets/banner.svg
[cmda]: https://github.com/cmda
[dangit]: https://github.com/dandevri
[danweb]: https://github.com/dandevri
[gh]: https://github.com/cmda-minor-vid/web-animation-18-19
[examples]: /examples
[moodle]: https://moodle.cmd.hva.nl/course/view.php?id=575
[startpage]: https://www.startpage.com/
[resources]: /resources.md
[synopsis]: #synopsis
[grading]: grading.md
[bachelor]: https://www.cmd-amsterdam.nl/english/
[faculty]: https://www.amsterdamuas.com/faculty/fdmci/faculty-of-digital-media-and-creative-industries.html
[university]: https://www.amsterdamuas.com
[coc]: code-of-conduct.md
[ruc]: https://www.amsterdamuas.com/practical-matters/algemeen/hva-breed/juridische-zaken/legal-affairs/regulation-undesirable-conduct/regulation-undesirable-conduct.html#anker-3-complaints-authority
[rog]: https://www.hva.nl/praktisch/algemeen/hva-breed/juridische-zaken/loket-beroep-bezwaar-en-klacht/regeling-ongewenst-gedrag/regeling-ongewenst-gedrag.html?origin=gbS4rg%2FDTZuxQ6lGVF%2BN1A
[mit]: license.md#code
[license]: license.md
[cc-by-4.0]: license.md#documentation-and-images

[gs]: getting-started.md

[w1]: week-1.md
[w2]: week-2.md
[w3]: week-3.md

[w1lec]: week-1.md#lecture
[w2lec]: week-2.md#lecture
[w3lec]: week-3.md#lecture

[w1lab]: week-1.md#lab
[w2lab]: week-2.md#lab
[w3lab]: week-3.md#lab

[w1a]: week-1.md#assignments
[w2a]: week-2.md#assignments
[w3a]: week-3.md#assignments
