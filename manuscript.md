<style>
.page {
break-before: page;
position: relative;
width: 500px;
height: 500px;
}
.abspos {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
}
</style>

<h1>Navigation Test</h1>
<nav>
<h2>Table of Contents</h2>
<ul>
    <li><a href="#section1">Section 1</a></li>
    <li><a href="#section2">Section 2</a></li>
    <li><a href="#section3">Section 3</a></li>
</ul>
</nav>
<div class="page">
<div class="abspos">
    <section id="section1">
    <h3>Section 1</h3>
    <p>This is the content of Section 1.</p>
    </section>
</div>
</div>
<div class="page">
<div class="abspos">
    <section id="section2">
    <h3>Section 2</h3>
    <p>This is the content of Section 2.</p>
    </section>
</div>
</div>
<div class="page">
<div class="abspos">
    <section id="section3">
    <h3>Section 3</h3>
    <p>This is the content of Section 3.</p>
    </section>
</div>
</div>
