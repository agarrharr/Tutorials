<h1>
 Julia.jl
</h1>
<p>
 <a href="http://svaksha.github.io/Julia.jl">
  Julia.jl
 </a>
 aggregates and curates decibans of knowledge resources for the
 <a href="https://github.com/JuliaLang">
  Julia language
 </a>
 .
</p>
<ul>
 <li>
  <a href="#index">
   INDEX
  </a>
 </li>
 <li>
  <a href="#license">
   LICENSE
  </a>
  <ul>
   <li>
    <a href="#mirrors">
     Mirrors
    </a>
   </li>
  </ul>
 </li>
 <li>
  <a href="#contribute">
   CONTRIBUTE
  </a>
  <ul>
   <li>
    <a href="#guidelines">
     Guidelines
    </a>
   </li>
   <li>
    <a href="#status">
     Status
    </a>
   </li>
   <li>
    <a href="#bugreport-pullrequest">
     BugReport-PullRequest
    </a>
   </li>
  </ul>
 </li>
</ul>
<hr/>
<h1>
 INDEX
</h1>
<p>
 For Base packages, check if the package you seek is listed in the
 <a href="https://github.com/JuliaLang/METADATA.jl">
  built-in package manager
 </a>
 on github, or check METADATA for
 <a href="http://pkg.julialang.org/">
  registered Julia packages
 </a>
 , then use the built-in package manager to install it after checking the requirements for respective versions and dont forget the Easter eggs!
</p>
<p>
 To create a package, check out the
 <a href="https://github.com/JuliaLang/PkgDev.jl">
  Julia Package Development Kit
 </a>
 and here is a
 <a href="https://github.com/JuliaLang/Example.jl">
  sample Julia package
 </a>
 model. The latest interesting package statistics are available at the
 <a href="http://pkg.julialang.org/pulse.html">
  Julia Package Ecosystem Pulse
 </a>
 webpage which mirrors the current core development on
 <a href="https://github.com/JuliaLang/julia/pulse">
  github
 </a>
 . Abandoned packages that no longer have a maintainer or no longer fit into the Julia oraganization that initially hosted the package are listed in the
 <a href="https://github.com/JuliaArchive">
  Julia Archive
 </a>
 organisation.
</p>
<ul>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/AI.md">
   AI.md
  </a>
  :: Algorithms, DataMining, Data Structures, HMM, ML, NLP, ...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/API.md">
   API.md
  </a>
  :: Language API's - C++, Fortran, Go, Java, JavaScript, MATLAB, Perl, Python, R, ...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Biology.md">
   Biology.md
  </a>
  :: Bioinformatics, genomics, agriculture, food science, medicine, genetic engineering, Neuroscience, et. al...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Build-Automation.md">
   Build-Automation.md
  </a>
  :: Tools for continuous integration (CI),  continuous delivery (CD), Packaging, release engineering (RE), release management (RM), software configuration management (SCM), etc...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Chemistry.md">
   Chemistry.md
  </a>
  :: Analytical chemistry, cheminformatics, crystallography, nanochemistry, nuclear chemistry ...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Community.md">
   Community.md
  </a>
  :: List of community and development links, including events, (un)conferences, forums/ meetup groups, NEWS, etc..
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Computer-Graphics.md">
   Computer-Graphics.md
  </a>
  :: Plotting, Graphics and other Visualization tools.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/DataBase.md">
   DataBase.md
  </a>
  :: NoSQL, RDBMS and Middleware API's.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Earth-Science.md">
   Earth-Science.md
  </a>
  :: software related to the subcategories of cartography, climatology, geobiology, geochemistry, geography, geoinformatics, geology‎, geophysics‎, geoscience/GIS, geomathematics, meteorology, oceanography, etc...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Hardware.md">
   Hardware.md
  </a>
  :: Software for cross-platform hardware, Robotics, and other API libraries.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/i18n-L10n.md">
   i18n-L10n.md
  </a>
  :: Transliteration, Internationalisation (i18n) and Localisation (L10n)
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/IO.md">
   IO.md
  </a>
  :: Input/Output functionality and support for file formats.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Mathematics.md">
   Mathematics.md
  </a>
  :: Algebra, Geometry,... anything Math related.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/OpenData.md">
   OpenData.md
  </a>
  :: OpenData, Free Data Sets.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Physics.md">
   Physics.md
  </a>
  :: Julia software related to Physics.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Programming-Paradigms.md">
   Programming-Paradigms.md
  </a>
  :: Programming Paradigms and language concepts that are used in the type system, data types, etc..
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Publications.md">
   Publications.md
  </a>
  :: Research Papers (journal and conference publications).
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/QA.md">
   QA.md
  </a>
  :: Test Driven Development, Sandbox, Functional/ Unit testing,... Quality-related tools.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Resources.md">
   Resources.md
  </a>
  :: blogs, cookbooks, cheatsheets, IJulia NoteBooks, and other non-standard resources.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Space-Science.md">
   Space-Science.md
  </a>
  :: Astronomy, Imaging, Planetary and
  <a href="https://en.wikipedia.org/wiki/Outline_of_space_science">
   space science
  </a>
  related packages.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Statistics.md">
   Statistics.md
  </a>
  :: Actuarial Science, Finance, economics, stochastic, insurance Statistics, Operations research and Benchmarks and Optimization toolkits....
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Super-Computing.md">
   Super-Computing.md
  </a>
  :: HPC, Distributed Computing, Cloud computing, Cluster computing, Grid computing, Kernels and architectures like ARM, MIPS, GPU, CUDA, etc...
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Utilities.md">
   Utilities.md
  </a>
  :: Handy toolkits and other general utilities for your Desktop.
 </li>
 <li>
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Web-Server.md">
   Web-Server.md
  </a>
  :: HPC, Distributed Computing, Cloud WWW, HTTP, Networking, Servers, etc...
 </li>
</ul>
<p>
 <strong>
  DISCLAIMER :
 </strong>
 As a new language in the scientific computing scene it is frequently in a state of flux due to the addition of new libraries, resulting in frequent changes and page reordering. Since the
 <strong>
  Julia.jl
 </strong>
 repo only provides a list (of links) of Julia packages out in the wild, it should not be considered an endorsment of any particular package for software quality, technical features, coding style/organization, etc...
</p>
<hr/>
<h1>
 LICENSE
</h1>
<ul>
 <li>
  COPYRIGHT © 2012-Now
  <a href="http://svaksha.com/pages/Bio">
   SVAKSHA
  </a>
  , All Rights Reserved.
 </li>
 <li>
  This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License - (CC BY-NC-SA 4.0) as detailed in the
  <a href="LICENSE.md">
   LICENSE.md
  </a>
  file and ALL references, citations, copies and forks of this work must retain the Copyright, Licence (LICENSE.md file), this permission notice and must
  <a href="https://en.wikipedia.org/wiki/Creative_Commons_license#Attribution">
   attribute credit
  </a>
  .
 </li>
</ul>
<h2>
 Mirrors
</h2>
<ul>
 <li>
  <a href="https://bitbucket.org/svaksha/Julia.jl">
   Bitbucket
  </a>
  :: git clone git@bitbucket.org:svaksha/Julia.jl.git
 </li>
 <li>
  <a href="https://gitlab.com/svaksha/Julia.jl">
   GitLab
  </a>
  :: git clone git@gitlab.com:svaksha/Julia.jl.git
 </li>
 <li>
  <a href="https://notabug.org/svaksha/julia.jl">
   NotABug
  </a>
  :: git clone git@notabug.org:svaksha/julia.jl.git
 </li>
</ul>
<h1>
 CONTRIBUTE
</h1>
<p>
 <a href="https://github.com/svaksha/Julia.jl/graphs/contributors">
  Contributions
 </a>
 to
 <code>
  Julia.jl
 </code>
 are welcome in the form of pull requests (PR). Here are some guidelines and tips on how to submit a Bug Report (BR) and/or
 <a href="https://github.com/svaksha/Julia.jl/pulls">
  PR
 </a>
 :
</p>
<h2>
 Guidelines
</h2>
<p>
 The Julia community has
 <a href="http://julialang.org/community/standards/">
  ethical guidelines
 </a>
 aimed at respecting Copyright, Licenses and attribution standards
 <sup>
  {1} and {2}
 </sup>
 which you are requested to follow while submitting materials to be listed. Additionally, if you find any material (or code repos) that violates these ethical standards, please file a bug report for their removal from
 <code>
  Julia.jl
 </code>
 .
+ References :
   + {1} https://github.com/JuliaLang/julialang.github.com/issues/200
   + {2} https://github.com/JuliaLang/julialang.github.com/issues/194
</p>
<h2>
 Status
</h2>
<p>
 These
 <a href="https://github.com/svaksha/Julia.jl/commit/a884fe9e921d57b87d85e970c2f57b8f21025641#commitcomment-15802037">
  comments
 </a>
 led to a
 <a href="https://github.com/svaksha/Julia.jl/issues/55">
  BR discussing
 </a>
 the addition of metadata tags that will enable programmers and package users to easily distinguish the status of various Julia packages that are under various stages of development. Currently, METADATA has a tag system but not all package authors use it, making it harder for lay users to know if the package maintenance is active or not.
</p>
<p>
 Lets experiment with asking package authors and core-commiters to tag their Julia packages on the following criteria :
</p>
<p>
 On a scale of 1 to 5 (1=lowest,..5=highest), please rank your package for,
</p>
<ul>
 <li>
  <code>
   Usability
  </code>
  : Does the package do what it says it does? is it easy to figure out? Is the package production-ready and actively maintained (issues/PRs are responded and resolved in a timely manner, and maintenance and testing is at par with Julia release cycles).
 </li>
 <li>
  <code>
   Quality
  </code>
  : Does the package have tests? are there lots of bugs? Do you have good documentation? Can it be used in production environments that expect prompt security patches?
 </li>
 <li>
  <code>
   Activity
  </code>
  : Should a 3rd party user bother to use your library, or is it really only intended to be used by the package author? Let's say, an experimental "throw-away toy repo" whose development has now been abandoned.
 </li>
 <li>
  <code>
   License
  </code>
  : Which software license do you use? If you dont have a license, please state
  <code>
   None
  </code>
  .
 </li>
</ul>
<h2>
 BugReport-PullRequest
</h2>
<ol>
 <li>
  Add your link as per the top-level Category page within the topic sub-section(s), in
  <em>
   alphabetical order
  </em>
  , with notes (if any) in the markdown files.
 </li>
 <li>
  For broken links or outdated information, submit a bug report (BR), or make the necessary changes and submit a PR. Both are welcome. Please submit separate PR's for each link or change added.
 </li>
 <li>
  For Documentation and cookbooks, check if it matches the categories listed, else, list it on the
  <a href="https://github.com/svaksha/Julia.jl/blob/master/Resources.md">
   Resources.md
  </a>
  page.
 </li>
 <li>
  For those unable to use git, create a github account, then fork the
  <code>
   Julia.jl
  </code>
  repo on the user interface. Then edit the page by
  <a href="https://help.github.com/articles/editing-files-in-your-repository">
   clicking on the "pencil" icon on the markdown page
  </a>
  , then click on save and submit a PR. Github does this
  <a href="https://help.github.com/articles/editing-files-in-another-user-s-repository">
   automatically in 8 steps
  </a>
  .
 </li>
</ol>
