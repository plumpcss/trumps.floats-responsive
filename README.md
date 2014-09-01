# Floats-responsive

The plumpcss `floats-responsive` module is an extension of the default [`floats`
module](https://github.com/plumpcss/trumps.floats).

Install using Bower:

    $ bower install --save plumpcss-floats-responsive

`floats-responsive` will inherit the same settings used for `floats` (i.e.
symbol format (e.g. .f>) or an abbreviated format (e.g. .fl)).

`floats-responsive` loops through the breakpoints defined in
`settings.responsive` to generate prefixed breakpoint-based classes. If you are
using inuitcss’ default breakpoints, you will be given classes like
`lap-and-up-f>`, or `desk-fr`, etc.
