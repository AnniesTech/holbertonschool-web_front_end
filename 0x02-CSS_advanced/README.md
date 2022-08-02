# 0x02. Advanced CSS

<html>
<div class="panel panel-default" id="project-description">
 <div class="panel-body">
  <p>
   <img alt="" src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/ce6718f1b55e6c1580c6.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=f23ec6582cce343fde45b70fc40eea1b884faf98bf8fdba1321d9332c2d8f8a5" style=""/>
  </p>
  <h2>
   Resources
  </h2>
  <p>
   <strong>
    Read or watch
   </strong>
  </p>
  <ul>
   <li>
    <a href="https://cssreference.io/" target="_blank" title="CSS Reference - A free visual guide to CSS">
     CSS Reference - A free visual guide to CSS
    </a>
   </li>
   <li>
    <a href="https://caniuse.com/" target="_blank" title="Can I use,,, Support tables for HTML5, CSS3, etc">
     Can I use,,, Support tables for HTML5, CSS3, etc
    </a>
   </li>
   <li>
    <a href="http://ref.openweb.io/CSS/" target="_blank" title="CSS Reference">
     CSS Reference
    </a>
   </li>
   <li>
    <a href="https://htmldog.com/references/css/properties/" target="_blank" title="CSS Properties | HTML Dog">
     CSS Properties | HTML Dog
    </a>
   </li>
   <li>
    <a href="https://css-tricks.com/box-sizing/" target="_blank" title="Box Sizing">
     Box Sizing
    </a>
   </li>
   <li>
    <a href="http://www.standardista.com/wp-content/uploads/2012/01/specificity3.pdf" target="_blank" title="CSS Selectors weight">
     CSS Selectors weight
    </a>
   </li>
   <li>
    <a href="https://www.codecaptain.io/tools/css-specificity-calculator" target="_blank" title="CSS specificity calculator">
     CSS specificity calculator
    </a>
   </li>
   <li>
    <a href="https://frontend30.com/css-selectors-cheatsheet/" target="_blank" title="Play with CSS selector">
     Play with CSS selector
    </a>
   </li>
  </ul>
  <h2>
   Learning Objectives
  </h2>
  <p>
   At the end of this project, you are expected to be able to
   <a href="https://fs.blog/feynman-learning-technique/" target="_blank" title="explain to anyone">
    explain to anyone
   </a>
   ,
   <strong>
    without the help of Google
   </strong>
   :
  </p>
  <ul>
   <li>
    Selectors, properties, and values
   </li>
   <li>
    The difference between block and inline styling
   </li>
   <li>
    How to ensure consistency across all browers (CSS reset)
   </li>
   <li>
    How to setup CSS variables
   </li>
   <li>
    The differences between inline, embeded and external CSS
   </li>
   <li>
    How grid systems work (with floats)
   </li>
   <li>
    The difference between icons webfonts and SVG icons
   </li>
   <li>
    The difference between pseudo-classes and pseudo-elements
   </li>
   <li>
    How to make background gradients
   </li>
   <li>
    How to animate elements in CSS
   </li>
   <li>
    How to transform (2d, 3d) elements
   </li>
   <li>
    What vendor prefixes are
   </li>
  </ul>
  <h2>
   Requirements
  </h2>
  <h3>
   General
  </h3>
  <ul>
   <li>
    Allowed editors:
    <code>
     vi
    </code>
    ,
    <code>
     vim
    </code>
    ,
    <code>
     emacs
    </code>
    ,
    <code>
     VSCode
    </code>
    ,
    <code>
     Atom
    </code>
   </li>
   <li>
    All your files will be interpreted on Chrome (version 78.x)
   </li>
   <li>
    All your files should end with a new line
   </li>
   <li>
    All your files should start by a comment describing the task
   </li>
   <li>
    A
    <code>
     README.md
    </code>
    file, at the root of the folder of the project, is mandatory
   </li>
   <li>
    Your code should be W3C compliant and validate with
    <a href="https://github.com/holbertonschool/W3C-Validator" target="_blank" title="W3C-Validator">
     W3C-Validator
    </a>
   </li>
  </ul>
  <h3>
   Files you need for the project
  </h3>
  <h4>
   <code>
    favicon.jpg
   </code>
  </h4>
  <p>
   <img alt="" src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/2ba3a0d7878316de5aaa.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=10e74360ae2f0003ce844e14772255fd8ea40c4dd93d9ad4914fb802f35f138c" style=""/>
  </p>
  <p>
   <a href="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/2ba3a0d7878316de5aaa.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=345600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=35503a3129b05d2c0c42d8389e605743274f9e045564d403ce0dcaef9f07d0dd" target="_blank" title="download favicon.jpg">
    download favicon.jpg
   </a>
  </p>
  <h4>
   <code>
    logo-black.png
   </code>
  </h4>
  <p>
   <img alt="" src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/06f32e89f2a82582234e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=33691bdacaadef803d6b1e02a616518ef257c95e4693d02c486234d3fd5904f8" style=""/>
  </p>
  <p>
   <a href="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/06f32e89f2a82582234e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=345600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=e0d9cadb29e56744f84bd9f9403b92031604699119709df6b584cbeef4fae335" target="_blank" title="download logo-black.png">
    download logo-black.png
   </a>
  </p>
  <h4>
   <code>
    logo-white.png
   </code>
  </h4>
  <p>
   <img alt="" src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/0fa48a04048a2d050cab.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=5ab81a134ca25298a51ad64405867f7201b829ed726f154897047f33828e1df1" style=""/>
  </p>
  <p>
   <a href="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/0fa48a04048a2d050cab.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=345600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=3019a590c599c2fe3c895af34112039520da30543ab9933ec8f6284d98e97b05" target="_blank" title="download logo-white.png">
    download logo-white.png
   </a>
  </p>
  <p>
   Store all these under a directory named “images”
  </p>
  <h2>
   End goal of the project
  </h2>
  <p>
   <img alt="" src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/10/b9a220ba79af9ede6fc5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220802%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220802T000450Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=b3c6e99fcdda8a207ee7427d6a2442c61c21af6744b1cfb5c4eac64d9c3a358a" style=""/>
  </p>
  <p>
   Important note:
   <strong>
    details are important!
   </strong>
   lowercase vs uppercase / wrong letter… be careful!
  </p>
 </div>
</div>

[--LINK PROJECT--](https://intranet.hbtn.io/projects/583#)
</html>
