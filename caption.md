# `<caption>`

Figure and table captions.

## PeerJ

```xml
<!-- figure -->
<fig id="fig-1">
  <label>Figure 1</label>
  <caption>
    <title>Illustrating the angles of the H+ model when the hydrogen bond acceptor is sp<sup>2</sup> hybridized.</title>
    <p>Θ is the angle between atoms A and B. Φ<sub>X</sub> is the angle between the hydrogen and […]</p>
  </caption>
  <graphic mimetype="image" mime-subtype="png" xlink:href="http://example.org/fig-1.png"/>
</fig>

<!-- table -->
<table-wrap id="table-1">
  <label>Table 1</label>
  <caption>
    <title>General linear models describing variation in wing pigmentation in <italic>Calopteryx maculata</italic>.</title>
    <p>Parameter estimates from general linear models (weighted by square root of sample size) describing variation in wing pigmentation in <italic>Calopteryx maculata</italic> males. DF = 1 for all parameters.</p>
  </caption>
  <alternatives>
    <graphic mimetype="image" mime-subtype="png" xlink:href="https://example.org/table-1.png"/>
    <table>…</table>
  </alternatives>
</table-wrap>
```

## eLife

```xml
<!-- figure where there are figure supplements we have to use the fig-group container, some figures also have source data -->
<fig-group>
<fig id="fig1" position="float">
<object-id pub-id-type="doi">10.7554/eLife.00013.003</object-id>
<label>Figure 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.003">http://dx.doi.org/10.7554/eLife.00013.003</ext-link>
</p>
p>
<supplementary-material id="SD1-data">
<object-id pub-id-type="doi">10.7554/eLife.00013.004</object-id>
<label>Figure 1&#x2014;source data 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.004">http://dx.doi.org/10.7554/eLife.00013.004</ext-link>
</p>
</caption>
<media mime-subtype="xlsx" mimetype="application" xlink:href="elife00013s001.xlsx"/>
</supplementary-material>
</p>
</caption>
<graphic xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="elife00013f001"/>
</fig>
<fig id="sfig1" position="float" specific-use="child-fig">
<object-id pub-id-type="doi">10.7554/eLife.00013.005</object-id>
<label>Figure 1&#x2014;figure supplement 1.</label>
<caption>
<title>TEXT</title>
<p>TEXT</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.005">http://dx.doi.org/10.7554/eLife.00013.005</ext-link>
</p>
</caption>
<graphic xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="elife00013fs001"/>
</fig>
</fig-group>


<!-- table -->
<table-wrap id="tbl1" position="float">
<object-id pub-id-type="doi">10.7554/eLife.00013.009</object-id>
<label>Table 1.</label>
<caption>
<p>Species tested for colony induction</p>
<p>
<bold>DOI:</bold>
<ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.009">http://dx.doi.org/10.7554/eLife.00013.009</ext-link>
</p>
</caption>
<table frame="hsides" rules="groups">...</table>
<table-wrap-foot>
<fn id="tblfn1">
<label>&#x2a;</label>
<p>No rosette colonies observed, &#x2b; rosette colonies observed</p>
</fn>
</table-wrap-foot>
</table-wrap>

```

## Ubiquity Press

```xml

<!-- figure -->

<fig id="F1">
<label>Figure 1</label>
<caption>
<p>Evolution of CVLI rate in Pernambuco &#8211; 2006 to 2013. Source: GACE/SDS and IBGE.</p>
</caption>
<graphic xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="figures/Fig01_web.jpg"/>
</fig>

<!-- table -->

<table-wrap id="T1">
<label>Table 1</label>
<caption>
<p>Number of schools by socioeconomic level and group. Source: (<xref ref-type="bibr" rid="B12">Correa 2007</xref>).</p>
</caption>
<table>...</table>
</table-wrap>


```



## F1000Research

```xml

<!-- box -->

<boxed-text id="B1">
                    <label>Box 1.</label>
                    <caption>
                        <title>Model code for a reaction sequence (Model #320 at 
                            <ext-link ext-link-type="uri" xlink:href="http://www.physiome.org">www.physiome.org</ext-link>).</title>
                    </caption>
					<p>BOX TEXT!</p>
</boxed-text>

<!-- figure -->

<fig fig-type="figure" id="f1" position="float">
                    <label>Figure 1.</label>
                    <caption>
                        <title>Capillary-tissue exchange unit.</title>
                        <p>Fluid flows with velocity F
                            <sub>cap</sub>*L/V
                            <sub>cap</sub> along the capillary from the entrance at x = 0 to the exit at x = L, and exchanges across the capillary wall into a stagnant extravascular region with conductance PS, the permeability-surface area product. The input is a bolus of solute, C
                            <sub>in</sub>(t), entering the capillary with the flow, F
                            <sub>cap</sub>. Axial gradients along the capillary are diminished by diffusion, D
                            <sub>p</sub> and D
                            <sub>isf</sub>. Tissue consumption occurs at rate G
                            <sub>isf</sub>*C
                            <sub>isf</sub>. This is a simplified version of models used for indicator dilution studies and PET clinical studies (
                            <xref ref-type="bibr" rid="ref-16">Beard &amp; Bassingthwaighte, 2000</xref>; 
                            <xref ref-type="bibr" rid="ref-7">Bassingthwaighte 
                                <italic>et al.</italic>, 1989</xref>; 
                            <xref ref-type="bibr" rid="ref-8">Bassingthwaighte 
                                <italic>et al.</italic>, 1992</xref>; 
                            <xref ref-type="bibr" rid="ref-12">Bassingthwaighte 
                                <italic>et al.</italic>, 2006b</xref>).</p>
                    </caption>
                    <graphic xlink:href="f1000research-2-4716-g0000.eps"/>
                </fig>


<!-- table -->

<table-wrap id="T3" position="anchor">
                    <label>Table 3. </label>
                    <caption>
                        <title>JSim’s optimizers.</title>
                    </caption>
                    <table content-type="article-table" frame="hsides">
                        <tbody>
                            <tr>
                                <td>Simplex</td>
                                <td>A bounded, non-linear steepest-descent algorithm (
                                    <xref ref-type="bibr" rid="ref-28">Dantzig 
                                        <italic>et al.</italic>, 1955</xref>)</td>
                            </tr>
                        </tbody>
                    </table>
                </table-wrap>

```