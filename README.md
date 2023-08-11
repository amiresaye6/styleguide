Every major open-source project has its own style guide: a set of conventions (sometimes arbitrary) about how to write code for that project. It is much easier to understand a large codebase when all the code in it is in a consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to “never use global variables” to “never use exceptions.” This project (google/styleguide) links to the style guidelines we use for Google code. If you are modifying a project that originated at Google, you may be pointed to this page to see the style guides that apply to that project.

AngularJS Style Guide
Common Lisp Style Guide
C++ Style Guide
C# Style Guide
Go Style Guide
HTML/CSS Style Guide
JavaScript Style Guide
Java Style Guide
Objective-C Style Guide
Python Style Guide
R Style Guide
Shell Style Guide
Swift Style Guide
TypeScript Style Guide
Vim script Style Guide
This project also contains cpplint, a tool to assist with style guide compliance and google-c-style.el, an Emacs settings file for Google style.

If your project requires that you create a new XML document format, the XML Document Format Style Guide may be helpful. In addition to actual style rules, it also contains advice on designing your own vs. adapting an existing format, on XML instance document formatting, and on elements vs. attributes.

The style guides in this project are licensed under the CC-By 3.0 License, which encourages you to share these documents. See https://creativecommons.org/licenses/by/3.0/ for more details.

The following Google-style guide lives outside of this project: Effective Dart.

Contributing
With few exceptions, these style guides are copies of Google's internal style guides to assist developers working on Google owned and originated open-source projects. Changes to the style guides are made to the internal style guides first and eventually copied into the versions found here. External contributions are not accepted. Pull requests are regularly closed without comment. Issues that raise questions, justify changes on technical merits, or point out obvious mistakes may get some engagement and could in theory lead to changes, but we are primarily optimizing for Google's internal needs.
