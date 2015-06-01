# `<sub-article>`

Sub article elements - peer review components published with the articles

## eLife

The decision letter and response from the peer review process are published at the end of the article as sub article components. Can contain figures, tables and videos that are not part of the main article.

```xml
 <sub-article article-type="article-commentary" id="SA1">
        <front-stub>
            <article-id pub-id-type="doi">10.7554/eLife.00013.037</article-id>
            <title-group>
                <article-title>Decision letter</article-title>
            </title-group>
            <contrib-group>
                <contrib contrib-type="editor">
                    <name>
                        <surname>Sneden</surname>
                        <given-names>Christopher</given-names>
                    </name>
                    <role>Reviewing editor</role>
                    <aff>
                        <institution>Pediatric Dengue Vaccine Initiative</institution>,
                            <country>United States</country>
                    </aff>
                </contrib>
            </contrib-group>
            <contrib-group>
                <contrib contrib-type="reviewer" id="author-34">
                    <name>
                        <surname>Harrison</surname>
                        <given-names>Melissa</given-names>
                    </name>
                    <role>Reviewer</role>
                    <aff>
                        <institution>Pediatric Dengue Vaccine Initiative</institution>,
                            <country>United States</country>
                    </aff>
                </contrib>
            </contrib-group>
            <contrib-group>
                <contrib contrib-type="reviewer" id="author-35">
                    <name>
                        <surname>Roderick</surname>
                        <given-names>Sian</given-names>
                    </name>
                    <role>Reviewer</role>
                    <aff>
                        <institution>Pediatric Dengue Vaccine Initiative</institution>,
                            <country>United States</country>
                    </aff>
                </contrib>
            </contrib-group>
        </front-stub>
        <body>
            <boxed-text>
                <p>eLife posts the editorial decision letter and author response on a selection of
                    the published articles (subject to the approval of the authors). An edited
                    version of the letter sent to the authors after peer review is shown, indicating
                    the substantive concerns or comments; minor concerns are not usually shown.
                    Reviewers have the opportunity to discuss the decision before the letter is sent
                    (see <ext-link ext-link-type="uri"
                        xlink:href="http://elifesciences.org/review-process">review
                        process</ext-link>). Similarly, the author response typically shows only
                    responses to the major concerns raised by the reviewers.</p>
            </boxed-text>
            <p>Text text text</p>
        </body>
    </sub-article>
    <sub-article article-type="reply" id="SA2">
        <front-stub>
            <article-id pub-id-type="doi">10.7554/eLife.00013.037</article-id>
            <title-group>
                <article-title>Author response</article-title>
            </title-group>
        </front-stub>
        <body>
            <p>Text text text</p>
                <italic>2) An expanded discussion of the difference in activity between purified
                    RIF-1 vs. the sphingolipid-enriched fraction (<xref ref-type="table" rid="tbl2"
                        >Table 2</xref>). On p. 8, paragraph 1, we clarify that the difference in
                    activity could be due either to delivery issues (i.e. a requirement for RIF-1 to
                    be delivered in the context of the bacterial membrane) or to the absence of
                    other currently unidentified A. machipongonensis molecules that either amplify
                    RIF-1 signaling or might independently induce colony development in S. rosetta
                        (<xref ref-type="fig" rid="fig5">Author response image 1</xref>). In
                    addition, on p. 9 we state that &#x201c;We hypothesize that RIF-1 may be
                    released into the environment in membrane vesicles, which have been described in
                    Gram-negative bacteria and Bacteroidetes (50,51) and that additional membrane
                    constituents might be required for the full potency of RIF-1.</italic>&#x201d;
                    <fig id="fig5" position="float">
                        <object-id pub-id-type="doi">10.7554/eLife.00013.038</object-id>     
                    <label>Author response image 1</label>
                    <caption>
                        <title>Correlation between mean Voxel Number and resulting mean Decoding
                            Accuracy (shown for each ROI (N&#x3d;13) and each of the three pair-wise
                            comparisons for the Plan-Epoch).</title>
                        <p>Pearson correlation between Voxel Number and Hand Plan Epoch decoding
                            accuracies (red diamond symbols): r<sup>2</sup>&#x3d;0.108,
                            p&#x3d;0.272; Pearson Correlation between Voxel Number and Tool Plan
                            Epoch decoding accuracies (blue square symbols):
                            r<sup>2</sup>&#x3d;0.025, p&#x3d;0.602; Pearson Correlation between
                            Voxel Number and Across-Effector Plan Epoch decoding accuracies (purple
                            triangle symbols): r<sup>2</sup>&#x3d;0.026, p&#x3d;0.598.</p>
                        <p>
                            <bold>DOI:</bold>
                            <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.038"
                                >http://dx.doi.org/10.7554/eLife.00013.038</ext-link>
                        </p>
                    </caption>
                    <graphic xlink:href="elife00013f005" xmlns:xlink="http://www.w3.org/1999/xlink"
                    />
                </fig>
            </p>
            <p>
                <italic>3) A more detailed discussion of future directions for this research,
                    including (as pointed out by the reviewers) the need to determine the
                    three-dimensional structure of RIF-1 (p. 9, <xref ref-type="fig" rid="sfig1"
                        >Figure 1&#x2014;figure supplement 1</xref>). Note that defining the
                    stereochemistry will require synthesizing several different possible
                    stereoisomers of RIF-1, and that there are no published total syntheses of any
                    sulfonolipids in the literature (<xref ref-type="table" rid="tbl4">Author
                        response table 1</xref>)</italic>.
                <table-wrap id="tbl4" position="float">
                            <object-id pub-id-type="doi">10.7554/eLife.00013.039</object-id>
                    <label>Author response table 1.</label>
                    <caption>
                        <p>GC-MS analysis of cuticular hydrocarbon extracts from control,
                                <italic>miR-124</italic> mutant, rescued mutants, and
                                <italic>miR-124&#x3e;tra-RNAi</italic> males</p>
                        <p>
                            <bold>DOI:</bold>
                            <ext-link ext-link-type="doi" xlink:href="10.7554/eLife.00013.039"
                                >http://dx.doi.org/10.7554/eLife.00013.039</ext-link>
                        </p>
                    </caption>
                    <table frame="hsides" rules="groups">
                        <thead>
                            <tr>
                                <th>Compound and elemental composition</th>
                                <th>Control (n &#x3d; 3)</th>
                                <th>
                                    <italic>mir-124</italic> mutant (n &#x3d; 3)</th>
                                <th>Rescued mutant (n &#x3d; 3)</th>
                                <th>mir-124&#x3e; tra-RNAi (n &#x3d; 2)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>C21:0 (nC21)</td>
                                <td align="char" char="plusmn">0.28 &#xb1; 0.1</td>
                                <td align="char" char="plusmn">0.21 &#xb1; 0.01</td>
                                <td align="char" char="plusmn">0.51 &#xb1; 0.03</td>
                                <td align="char" char="plusmn">0.35 &#xb1; 0.04</td>
                            </tr>
                            <tr>
                                <td>C22:1</td>
                                <td align="char" char="plusmn">0.22 &#xb1; 0.02</td>
                                <td align="char" char="plusmn">0.24 &#xb1; 0.01</td>
                                <td align="char" char="plusmn">0.31 &#xb1; 0.02</td>
                                <td align="char" char="plusmn">0.34 &#xb1; 0.03</td>
                            </tr>
                            <tr>
                                <td>cVA (cis-vaccenyl acetate)</td>
                                <td align="char" char="plusmn">3.86 &#xb1; 0.43</td>
                                <td align="char" char="plusmn">0.48 &#xb1;
                                    0.04&#x2a;&#x2a;&#x2a;</td>
                                <td align="char" char="plusmn">2.57 &#xb1; 0.47&#x2a;</td>
                                <td align="char" char="plusmn">2.09 &#xb1; 0.23&#x2a;</td>
                            </tr>
                            <tr>
                                <td>C22:0</td>
                                <td align="char" char="plusmn">0.61 &#xb1; 0.03</td>
                                <td align="char" char="plusmn">0.60 &#xb1; 0.01</td>
                                <td align="char" char="plusmn">0.87 &#xb1; 0.05</td>
                                <td align="char" char="plusmn">0.70 &#xb1; 0.05</td>
                            </tr>
                        </tbody>
                    </table>
                </table-wrap>
            </p>
        </body>
    </sub-article>
</article>

```
## F1000Research

We publish the peer reviewers reports and any author responses to the reports at the end of the article.

```xml

 <sub-article article-type="ref-report" id="report8551">
        <front-stub>
            <article-id pub-id-type="doi">10.5256/f1000research.6388.r8551</article-id>
            <title-group>
                <article-title>Referee response for version 1</article-title>
            </title-group>
            <contrib-group>
                <contrib contrib-type="author">
                    <name>
                        <surname>Patel</surname>
                        <given-names>Rakesh Pravinchandra</given-names>
                    </name>
                    <xref ref-type="aff" rid="r8551a1">1</xref>
                    <role>Referee</role>
                </contrib>
                <aff id="r8551a1">
                    <label>1</label>Department of Pathology and Center for Free Radical Biology and Lung Injury and Repair Center, University of Alabama at Birmingham, Birmingham, AL, USA</aff>
            </contrib-group>
            <author-notes>
                <fn fn-type="conflict">
                    <p>
                        <bold>Competing interests: </bold>No competing interests were disclosed.</p>
                </fn>
            </author-notes>
            <pub-date pub-type="epub">
                <day>1</day>
                <month>5</month><year>2015</year>
            </pub-date>
            <related-article ext-link-type="doi" id="relatedArticleReport8551" related-article-type="peer-reviewed-article" xlink:href="10.12688/f1000research.5971.1"/>
            <custom-meta-group>
                <custom-meta>
                    <meta-name>recommendation</meta-name>
                    <meta-value>approve</meta-value>
                </custom-meta>
            </custom-meta-group>
        </front-stub>
        <body>
            <p>Cytoglobin in regulating redox reactions with H2O2. The study design and methods used are appropriate to address the proposed questions. The data nicely show that distal His residues of this protein play key roles in maintaining heme stability during reactions with H2O2.
                <list list-type="order">
                    <list-item>
                        <p>Details of how many replicates and statistical analyses used to discern differences should be provided.</p>
                    </list-item>
                    <list-item>
                        <p>Is the heme loss observed after reactions with H2O2 and His mutants due to heme release and/ or heme modification that in turn would preclude extraction and measurement by HPLC.  The authors should provide some thoughts on how they think reactions with H2O2 (in the His mutants) is causing the heme to be released or degraded?</p>
                    </list-item>
                    <list-item>
                        <p>Are the effects of the distal His exclusive for reactions with H2O2? Could the authors speculate a little more on whether their results are more generalizable to other biologically relevant peroxides (LOOH, ONOO(H) etc.).</p>
                    </list-item>
                </list>
            </p>
            <p>I have read this submission. I believe that I have an appropriate level of expertise to confirm that it is of an acceptable scientific standard.</p>
        </body>
        <sub-article article-type="response" id="comment1389">
            <front-stub>
                <contrib-group>
                    <contrib contrib-type="author">
                        <name>
                            <surname>Gilad</surname>
                            <given-names>Yoav</given-names>
                        </name>
                        <aff>Human Genetics, University of Chicago, USA</aff>
                    </contrib>
                </contrib-group>
                <author-notes>
                    <fn fn-type="conflict">
                        <p>
                            <bold>Competing interests: </bold>No competing interests were disclosed.</p>
                    </fn>
                </author-notes>
                <pub-date pub-type="epub">
                    <day>26</day>
                    <month>5</month><year>2015</year>
                </pub-date>
            </front-stub>
            <body>
                <p>Dr. Irizarry,</p>
                <p>Thank you for spending the time to provide a review of our work. We agree with you that given the study design used by the mouse ENCODE consortium, applying a batch correction is futile. Indeed, we explicitly explain that in our discussion (you referred to that section of the text in your review).</p>
                <p>We further agree that it would be intellectually interesting to research the extent of the batch effect further – for example, by following your suggestion on how to test for the effect of instrument and lane.</p>
                <p>However, we feel that this additional effort is beyond the scope of our study. The mouse ENCODE consortium papers did not discuss (or account for) the sequencing study design. 
                    <bold>We spent considerable effort tracking the details that allowed us to reconstruct their design</bold>. We pointed out in our paper that given this study design, the unusual biological result reported by the mouse ENCODE consortium might have a technical explanation. We believe it is the responsibility of the mouse ENCODE consortium authors to provide evidence that excludes this technical possibility, rather than us having to prove that it is indeed the likely explanation.</p>
                <p>Which leads us to your third point: Indeed, the mouse ENCODE consortium authors commented that they have now collected additional sequence data, using a different design, and that their results held. In that sense, we believe that this means that the mouse ENCODE consortium authors accepted our claim that their original design was flawed.</p>
                <p>Yet, as mentioned in a few other comments here, there is an additional technical batch effect that was not yet excluded – related to tissue extraction and sample preparation. We plan to discuss this additional technical batch effect in a revised version of the text (we will wait to see additional reviews before we provide a revised version of the paper).</p>
                <p>Again, thank you for your time and thoughts.</p>
            </body>
        </sub-article>
    </sub-article>
