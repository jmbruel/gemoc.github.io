---
layout: default

---

<!-- Page Heading/Breadcrumbs -->
<div class="row">
    <div class="col-lg-12">
        <h1 class="page-header">CNRS PICS Project MBSAR 
            <small>2013-2015</small>
        </h1>
        <ol class="breadcrumb">
            <li><a href="{{ site.baseurl }}/index.html">Home</a></li>
            <li><a href="{{ site.baseurl }}/projects.html">Projects</a></li>
            <li class="active">MBSAR</li>
        </ol>
    </div>
</div>
<!-- /.row -->



<!-- Content Row -->
<div class="row">
    <div class="col-lg-12">

	        
							
			                        
                        <blockquote>
<h3>MBSAR (<em>Model-Based Security Analysis at Runtime</em>) is a collaboration between the <a href="http://www.cs.colostate.edu/~bieman/SAL/" target="_blank">Software Assurance Lab</a> from <a href="http://www.colostate.edu/" target="_blank">Colorado State University</a> and the <a href="http://www.irisa.fr/triskell" target="_blank">Triskell team</a> at <a href="http://www.irisa.fr/" target="_blank">IRISA</a>. MBSAR is a 3-year project (2013-2015) funded by the <a href="http://www.cnrs.fr/" target="_blank">CNRS</a> in the context of the program <a href="https://dri-dae.cnrs-dir.fr/spip.php?article155" target="_blank">PICS</a>.</h3>
</blockquote>
<p style="text-align: center;"><a href="http://www.irisa.fr" target="_blank"><img class="wp-image-542" style="border: 0px;" alt="logo-IRISA" src="../logo/01/logo-IRISA.png" width="239" height="56" srcset="../logo/01/logo-IRISA.png 553w, ../logo/01/logo-IRISA-300x69.png 300w" sizes="(max-width: 239px) 100vw, 239px" /></a>                    <a style="font-size: 12px; line-height: 18px;" href="http://www.cnrs.fr" target="_blank"><img class="wp-image-543" style="border: 0px;" alt="logocnrs" src="../logo/01/logocnrs.jpg" width="69" height="69" srcset="../logo/01/logocnrs.jpg 709w, ../logo/01/logocnrs-150x150.jpg 150w, ../logo/01/logocnrs-300x300.jpg 300w" sizes="(max-width: 69px) 100vw, 69px" /></a>                    <a style="font-size: 12px; line-height: 18px;" href="http://www.colostate.edu" target="_blank"><img class=" wp-image-541" style="border: 0px;" alt="csulogo" src="../logo/01/csulogo.png" width="129" height="56" /></a></p>
<hr />
<h3>The CNRS PICS project MBSAR finished in December 2015. Please, refer to the activity reports for more information (<a href="../resources/pics-mbsar-activityreport-2013.pdf">2013</a>, <a href="../resources/pics-mbsar-activityreport-2014.pdf">2014</a> and <a href="../resources/pics-mbsar-activityreport-2015.pdf">2015</a>).</h3>
<hr />
<h2>On the Globalization <em>at Runtime</em> of Modeling Languages</h2>
<p>MBSAR will focus on secure software engineering for the Future Internet. Software intensive systems for the Future Internet pervade numerous sectors in our societies (e.g., assisted living, energy). These applications assemble distributed software services and are deployed in dynamically changing and open environments, and thus they need to adapt their behavior at runtime. Developing and evolving these highly-adaptable software systems is very challenging. This, and the fact that many of these systems play critical roles in societies, highlights the need for research that aims to develop scalable runtime analysis and adaptation techniques. MBSAR will leverage the complementary expertise of CSU and IRISA to develop model-based techniques for runtime analysis and enforcement of security policies in adaptive software systems. In particular we will focus on the development of a model typing theory to support rigorous compositional adaptation, and runtime analysis of security properties.</p>
<h2>Principal Investigators</h2>
<ul>
<li><span style="font-size: 12px; line-height: 18px;"><a title="Benoit Combemale" href="http://people.irisa.fr/Benoit.Combemale/" target="_blank">Benoit Combemale</a> (Associate Professor, University of Rennes 1, France)</span></li>
<li><span style="font-size: 12px; line-height: 18px;"><a title="Robert B. France" href="http://www.cs.colostate.edu/~france/" target="_blank">Robert B. France</a> (Professor, Colorado State University, USA)</span></li>
</ul>
<h2>Context</h2>
<p>Software intensive applications for the Future Internet assemble software services distributed over multiple devices. These software applications are deployed in dynamic and open environments. The environments are dynamic because the availability of services and support resources varies in time, and open because new clients and providers can move in and out of the environments over time. These applications are also used in sectors that provide critical services to society, for example, assisted living and energy management. Furthermore, these applications often manipulate data and resources that must be protected from unauthorized access. Model-Driven Software Development provides effective concepts and techniques for modeling and analyzing security and other system integrity concerns at design time. However, in a dynamic and open environment, software systems have to adapt to dynamic environments after deployment. This makes it necessary to analyze the system at runtime to ensure that the system still fulfills security and other integrity requirements.</p>
<p>System monitoring and reflection mechanisms can be used to extract and maintain abstract views (models) of a system at runtime. These models at runtime can serve to reason about runtime adaptation of software systems, as well as to analyze the changes required by an adaptation. MBSAR focuses on extending the applicability of Model-Driven Software Development to adaptive systems. In particular, we investigate the use of models at runtime to support the evolution and analysis at runtime.</p>
<p>The core principle of models at runtime is to include, in the running system, a set of models. Each model presents a perspective that serves specific reasoning and analysis purposes, with respect to software adaptation at runtime. For example, it is possible to embed (1) an architecture model in a running system that captures the deployed structure of the system, (2) a variability model that captures the set of features that can be used to vary behavior at runtime, and (3) a security access control policy model that determines how users access the resources of the system.</p>
<p>Models at runtime raise a number of difficult challenges for the design and deployment of adaptive software. MBSAR focuses on the issues related to runtime analysis. In particular we focus on three related topics:</p>
<ul>
<li><span style="font-size: 12px; line-height: 18px;">Model composition and model typing ;</span></li>
<li><span style="font-size: 12px; line-height: 18px;">Runtime analysis of security properties ;</span></li>
<li><span style="font-size: 12px; line-height: 18px;">Empirical evaluation of proposed solutions.</span></li>
</ul>
<h2>Publications</h2>
<ul>
<li><a href="http://www.springer.com/gp/book/9783319261713">&#8220;Globalizing Domain-Specific Languages&#8221;</a> (Betty H. C. Cheng, Benoît Combemale, Robert B. France, Jean-Marc Jézéquel, Bernhard Rumpe), In Lecture Notes in Computer Science 9400, Springer, 2015</li>
<li><a href="https://hal.inria.fr/hal-01179369">&#8220;Using Slicing to Improve the Performance of Model Invariant Checking&#8221;</a> (Wuliang Sun, Benoît Combemale, Robert B. France, Arnaud Blouin, Benoit Baudry, Indrakshi Ray), In <a href="http://www.jot.fm" target="_blank">Journal of Object Technology</a>, vol.14, no. 4, 2015</li>
<li><a href="https://hal.inria.fr/hal-01141395">&#8220;Towards the use of slicing techniques for an efficient invariant checking&#8221;</a> (Wuliang Sun, Benoît Combemale, Robert B. France). In <a href="http://modularity.info/conference/2015/">MODULARITY 2015</a>, ACM, pp. 23-24, 2015</li>
<li><a href="https://hal.inria.fr/hal-00994551">&#8220;Globalizing Modeling Languages&#8221;</a> (Benoit Combemale, Julien Deantoni, Benoit Baudry, Robert France, Jean-Marc Jézéquel and Jeff Gray), In <a href="http://www.computer.org/csdl/mags/co/2014/06/mco2014060068-abs.html" target="_blank">IEEE Computer</a>, vol.47, no. 6, pp. 68-71, June 2014</li>
<li><a href="http://hal.inria.fr/hal-00850770">&#8220;Reifying Concurrency for Executable Metamodeling&#8221;</a> (Benoît Combemale, Julien Deantoni, Matias Vara Larsen, Frederic Mallet, Olivier Barais, Benoit Baudry and Robert France), In <a href="http://planet-sl.org/sle2013/" target="_blank">6th International Conference on Software Language Engineering</a> (SLE 2013)</li>
<li><a href="http://people.irisa.fr/Benoit.Combemale/wp-publications/models13compofm/">Composing your Compositions of Variability Models</a> (Mathieu Acher, Benoit Combemale, Philippe Collet, Olivier Barais, Philippe Lahire and Robert B. France), In <a href="http://www.modelsconference.org/" target="_blank">ACM/IEEE 16th International Conference on Model Driven Engineering Languages and Systems</a> (MODELS 2013)</li>
<li><a title="Using Model Types to Support Contract-Aware Model Substitutability" href="#" target="_blank">Using Model Types to Support Contract-Aware Model Substitutability</a> (Sun Wuliang, Benoit Combemale, Steven Derrien, Robert France), In <a title="ECMFA 2013" href="http://www.lirmm.fr/ecmfa13/" target="_blank">9th European Conference on Modelling Foundations and Applications</a> (ECMFA 2013, foundation track), Springer, 2013.</li>
</ul>
<h2>Past events</h2>
<ul>
<li><span style="font-size: 12px; line-height: 18px;">September, 2015: One paper accepted in the <a href="http://www.jot.fm" target="_blank">Journal of Object Technology</a></span>, and will be published in open access.</li>
<li>March, 2015: Organization of the workshop <a href="http://sustainability15.inria.fr" target="_blank">Sustainability’15</a> on Next Generation of Modularity Approaches for Multiple Dimensions of Sustainability (co-located with Modularity&#8217;15).</li>
<li><span style="font-size: 12px; line-height: 18px;">February, 2015: It is with considerable sadness that we learned of <a href="http://people.irisa.fr/Benoit.Combemale/tribute-robert-france/">the passing of Prof. Robert B. France</a>, on Sunday, February 15th, 2015 at 19h50</span</li>
<li><span style="font-size: 12px; line-height: 18px;">October-November, 2014: Robert B. France will spend 2 months at IRISA working on model typing and language interfaces</span> (supported by the Inria Intl. Chair)</li>
<li>October, 2014: Organization of the <a href="http://www.dagstuhl.de/14412" target="_blank">Dagstuhl seminar #14412</a> on the globalization of Domain-Specific Languages.</li>
<li><span style="font-size: 12px; line-height: 18px;">June, 2014: One paper accepted in <a title="IEEE Computer" href="http://www.computer.org/portal/web/computingnow/computer" target="_blank">IEEE Computer</a></span>, and will be published in the issue of June.</li>
<li><span style="font-size: 12px; line-height: 18px;">June, 2014: Benoit Combemale and Benoit Baudry will spend 1 week at CSU working on model-based security and testing</span></li>
<li><span style="font-size: 12px; line-height: 18px;">October, 2013: One paper accepted in the foundation track of the <a title="SLE 2013" href="http://www.sleconf.org/2013/" target="_blank">SLE 2013</a> conference</span>, and will be published in Springer’s Lecture Notes in Computer Science series.</li>
<li><span style="font-size: 12px; line-height: 18px;">October, 2013: One paper accepted in the foundation track of the <a title="MODELS 2013" href="http://www.modelsconference.org/" target="_blank">MODELS 2013</a> conference</span>, and will be published in Springer’s Lecture Notes in Computer Science series.</li>
<li><span style="font-size: 12px; line-height: 18px;">June, 2013: One paper accepted in the foundation track of the <a title="ECMFA 2013" href="http://www.lirmm.fr/ecmfa13/" target="_blank">ECMFA 2013</a> conference</span>, and published in Springer’s Lecture Notes in Computer Science series.</li>
<li><span style="font-size: 12px; line-height: 18px;">May, 2013: Benoit Baudry will spend 1 week at CSU working on model-based security and testing</span></li>
<li><span style="font-size: 12px; line-height: 18px;">May, 2013: Benoit Baudry and Benoit Combemale will attend the MiSE&#8217;13 workshop, and meet together with Robert B. France</span></li>
<li>February, 2013: Benoit Combemale spend 2 weeks at CSU working on model typing and variability management in modeling languages</li>
<li>January, 2013: the project is accepted by the CNRS and the website is online!</li>
</ul>

    </div>
    <!-- /.col-lg-12 -->
</div>
<!-- /.row -->
