---
layout: page
title: Ph.D. Genealogy
permalink: /genealogy/
description: My academic genealogy — tracing the chain of PhD advisors.
nav: false
---

<div class="genealogy-tree">

{% assign people = "Friedrich Leibniz (1597–1652)|Moral philosopher|University of Leipzig|leibniz,Jakob Thomasius (1622–1684)|Philosopher|University of Leipzig|thomasius,Otto Mencke (1644–1707)|Philosopher and Mathematician|University of Leipzig|mencke,Johann Christoph Wichmannshausen (1663–1727)|Philosopher|University of Leipzig · University of Wittenberg|wichmannshausen,Christian August Hausen (1693–1743)|Mathematician|University of Wittenberg · University of Leipzig|hausen,Abraham Gotthelf Kästner (1719–1800)|Mathematician and epigrammatist|University of Leipzig · University of Göttingen|kastner,Johann Christian Polycarp Erxleben (1744–1777)|Naturalist|University of Göttingen|erxleben,Christian Ehrenfried Weigel (1748–1831)|Chemist and botanist|University of Göttingen · University of Greifswald|weigel,Karl Asmund Rudolphi (1771–1832)|Naturalist|University of Greifswald · University of Berlin|rudolphi,Johannes Peter Müller (1801–1858)|Physiologist|Rhine University · University of Berlin|muller,Hermann Ludwig Ferdinand von Helmholtz (1821–1894)|Physicist and physician|University of Bonn · University of Heidelberg · Humboldt University|helmholtz,Albert Abraham Michelson (1852–1931)|Physicist|University of Berlin · Case Western Reserve · Clark University · University of Chicago|michelson,Robert Andrews Millikan (1868–1953)|Experimental physicist|Columbia University · University of Chicago · Caltech|millikan,Charles Christian Lauritsen (1892–1968)|Nuclear physicist|Caltech|lauritsen,Horace Richard Crane (1907–2007)|Physicist|Caltech · University of Michigan|crane,David Todd Wilkinson (1935–2002)|Cosmologist|University of Michigan · Princeton University|wilkinson,Peter Timbie (present)|Physicist, cosmologist|Brown University · University of Wisconsin, Madison|timbie,Brian Keating (1971–present)|Cosmologist|Brown University · Stanford University · Caltech · UC San Diego|keating" | split: "," %}

<style>
.genealogy-tree {
  max-width: 700px;
  margin: 0 auto;
  position: relative;
  padding-left: 20px;
}
.genealogy-tree::before {
  content: "";
  position: absolute;
  left: 60px;
  top: 0;
  bottom: 60px;
  width: 2px;
  background: var(--global-divider-color, #ddd);
}
.genealogy-entry {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 24px;
  position: relative;
}
.genealogy-entry::before {
  content: "";
  position: absolute;
  left: -20px;
  top: 50%;
  width: 20px;
  height: 2px;
  background: var(--global-divider-color, #ddd);
}
.genealogy-portrait {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  border: 2px solid var(--global-divider-color, #ddd);
}
.genealogy-info h3 {
  font-size: 1rem;
  margin: 0 0 2px;
}
.genealogy-info .role {
  font-size: 0.85rem;
  color: var(--global-text-color-light, #888);
}
.genealogy-info .university {
  font-size: 0.8rem;
  color: var(--global-text-color-light, #888);
  font-style: italic;
}
.genealogy-me {
  display: inline-block;
  margin: 8px 0 24px 0;
  padding: 10px 28px;
  border: 2px solid var(--global-theme-color, #333);
  border-radius: 4px;
  font-weight: bold;
  font-size: 1rem;
}
</style>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/leibniz.jpg" alt="Friedrich Leibniz">
  <div class="genealogy-info">
    <h3>Friedrich Leibniz (1597–1652)</h3>
    <div class="role">Moral philosopher</div>
    <div class="university">University of Leipzig</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/thomasius.jpg" alt="Jakob Thomasius">
  <div class="genealogy-info">
    <h3>Jakob Thomasius (1622–1684)</h3>
    <div class="role">Philosopher</div>
    <div class="university">University of Leipzig</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/mencke.jpg" alt="Otto Mencke">
  <div class="genealogy-info">
    <h3>Otto Mencke (1644–1707)</h3>
    <div class="role">Philosopher and Mathematician</div>
    <div class="university">University of Leipzig</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/wichmannshausen.jpg" alt="Johann Christoph Wichmannshausen">
  <div class="genealogy-info">
    <h3>Johann Christoph Wichmannshausen (1663–1727)</h3>
    <div class="role">Philosopher</div>
    <div class="university">University of Leipzig · University of Wittenberg</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/hausen.jpg" alt="Christian August Hausen">
  <div class="genealogy-info">
    <h3>Christian August Hausen (1693–1743)</h3>
    <div class="role">Mathematician</div>
    <div class="university">University of Wittenberg · University of Leipzig</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/kastner.jpg" alt="Abraham Gotthelf Kästner">
  <div class="genealogy-info">
    <h3>Abraham Gotthelf Kästner (1719–1800)</h3>
    <div class="role">Mathematician and epigrammatist</div>
    <div class="university">University of Leipzig · University of Göttingen</div>
    <div class="role" style="font-size:0.78rem;">The crater Kästner on the Moon is named after him.</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/erxleben.jpg" alt="Johann Christian Polycarp Erxleben">
  <div class="genealogy-info">
    <h3>Johann Christian Polycarp Erxleben (1744–1777)</h3>
    <div class="role">Naturalist</div>
    <div class="university">University of Göttingen</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/weigel.jpg" alt="Christian Ehrenfried Weigel">
  <div class="genealogy-info">
    <h3>Christian Ehrenfried Weigel (1748–1831)</h3>
    <div class="role">Chemist and botanist</div>
    <div class="university">University of Göttingen · University of Greifswald</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/rudolphi.jpg" alt="Karl Asmund Rudolphi">
  <div class="genealogy-info">
    <h3>Karl Asmund Rudolphi (1771–1832)</h3>
    <div class="role">Naturalist — "father of helminthology"</div>
    <div class="university">University of Greifswald · University of Berlin</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/muller.jpg" alt="Johannes Peter Müller">
  <div class="genealogy-info">
    <h3>Johannes Peter Müller (1801–1858)</h3>
    <div class="role">Physiologist</div>
    <div class="university">Rhine University · University of Berlin</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/helmholtz.jpg" alt="Hermann von Helmholtz">
  <div class="genealogy-info">
    <h3>Hermann Ludwig Ferdinand von Helmholtz (1821–1894)</h3>
    <div class="role">Physicist and physician</div>
    <div class="university">University of Bonn · University of Heidelberg · Humboldt University</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/michelson.jpg" alt="Albert Abraham Michelson">
  <div class="genealogy-info">
    <h3>Albert Abraham Michelson (1852–1931)</h3>
    <div class="role">Physicist — Nobel Prize in Physics</div>
    <div class="university">United States Naval Academy · University of Berlin · University of Chicago</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/millikan.jpg" alt="Robert Andrews Millikan">
  <div class="genealogy-info">
    <h3>Robert Andrews Millikan (1868–1953)</h3>
    <div class="role">Experimental physicist — Nobel Prize in Physics</div>
    <div class="university">Columbia University · University of Chicago · Caltech</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/lauritsen.jpg" alt="Charles Christian Lauritsen">
  <div class="genealogy-info">
    <h3>Charles Christian Lauritsen (1892–1968)</h3>
    <div class="role">Nuclear physicist</div>
    <div class="university">Caltech</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/crane.jpg" alt="Horace Richard Crane">
  <div class="genealogy-info">
    <h3>Horace Richard Crane (1907–2007)</h3>
    <div class="role">Physicist — National Medal of Science</div>
    <div class="university">Caltech · University of Michigan</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/wilkinson.jpg" alt="David Todd Wilkinson">
  <div class="genealogy-info">
    <h3>David Todd Wilkinson (1935–2002)</h3>
    <div class="role">Cosmologist — NASA's WMAP named after him</div>
    <div class="university">University of Michigan · Princeton University</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/timbie.jpg" alt="Peter Timbie">
  <div class="genealogy-info">
    <h3>Peter Timbie</h3>
    <div class="role">Physicist, cosmologist</div>
    <div class="university">Brown University · University of Wisconsin, Madison</div>
  </div>
</div>

<div class="genealogy-entry">
  <img class="genealogy-portrait" src="/assets/img/genealogy/keating.jpg" alt="Brian Keating">
  <div class="genealogy-info">
    <h3>Brian Keating (1971–present)</h3>
    <div class="role">Cosmologist</div>
    <div class="university">Brown University · Stanford University · Caltech · UC San Diego</div>
  </div>
</div>

<div class="genealogy-me">ME</div>

<p class="text-muted mt-3" style="font-size:0.85rem;">
  Find your own academic genealogy at <a href="https://academictree.org/" target="_blank">academictree.org</a>
</p>

</div>
