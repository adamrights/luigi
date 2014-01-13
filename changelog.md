#Changelog

##1.1.0 (2014-01-13)

- Adding delay attribute to transition mixin
- Adding font-face mixin
- Adding font-optimze mixin
- Adding transform property mixin

##1.0.0 (2014-01-02)

- Adding table of contents to each section on changelog
- Adding more docs to changelog (finishing Mixins folder)
- Re-ordering some files to be alphabetical
- Adding base var descriptions to the readme
- Changing `$basefont` et al to use hyphens to fit with conventions
- Ordering variables to be alphabetical

##0.4.0 (2014-01-02)
- Addition of **changelog.md**
- Addition of global box-sizing attribute (`predefined/box-sizing`) - can be turned off with **$global-box-sizing: false;**
- Changing order in **luigi.scss** so that global box-sizing uses the mixin
- Alphabetised mixins & corrected some typos/discrepancies (**_css3.scss)
- Removed **$inset** from box-shadow mixin as you can add it in to the beginning of the box-shadow property anyway
- Update of **readme.md** with **css3** mixins

##0.3.1 (2013-12-18)
- Add css3 spec non-prefix to $transition-prefix loop
- Merge branch 'master' of github.com:bozboz/luigi
- Amend vars on abs mixin - they were swapped (left-right)
- Initial update of Luigi readme

##0.3.0 (2013-12-13)
- Changing variable names to hyphens - new conventions
- Adding bg-size mixin and reformatting transition mixin
- Adding transition property mixin and slimming down transition mixin to use an @each loop
- Removing superfluous vendor prefixing in opacity mixin
- Duplicate box-shadow mixin - also tidying up if statement for inset

##0.2.0 (2013-12-10)
- Rewriting transition mixin to take each param individually
- Adding bp mixin for break points and bubbling
- Adding sticky footer into predefined
- Channing enable_rem var to use underscores and not hyphens

##0.1.2 (2013-12-09)
- Re-writing the css-triangle mixin to make more sense

##0.1.1 (2013-11-20)
- Removing erroneous characters
- Adding enable rem var to base vars to avoid compile error
- Adding readme

##0.1.0 (2013-11-06)
- Initial commit of Luigi, conversion of **Boss** to **Sass**