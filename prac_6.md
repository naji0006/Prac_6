<div class=WordSection1>

<h1><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;color:windowtext'>Introduction<o:p></o:p></span></h1>

<p class=MsoNormal>Baggage Handling System (BHS) is one the most complex
conveyor systems currently in practical use. This system is ranged from semi to
fully-automated. A single flaw in this system can result in chaotic
consequences as experienced in several major airports around the globe.</p>

<h1><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;color:windowtext'>Initial Stage<o:p></o:p></span></h1>

<p class=MsoNormal>At the very first stage where different various potential
systems are discussed, a set of major factors must be taken into consideration.</p>

<p class=MsoNormal>Time and budget constraints: this indicates if the system
can be developed in a test-driven (agile) manner, then every aspect of the
design can be pre-tested before any physical implementation. This is usually
achievable via developing a simulator to simulate the kind of functionality,
general or specific, that is expected from a BHS.</p>

<p class=MsoNormal>Recovery plan: a sophisticated system, in this case BHS,
would deliberately seek for potential threats to simulate a total failure
scenario to execute extreme test on the design stage. This should result in
designing a secondary mechanism (most likely fully-manual) in an event of
failure in BHS in order to keep an airport in an operational state.</p>

<h1><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;color:windowtext'>Operational Risks<o:p></o:p></span></h1>

<p class=MsoNormal>BHS consists of many sub-systems and parts that are fully
integrated into one main framework that executes the major functionality
expected from the whole system (baggage handling). Based on circumstances and
level of failure, system can cause different impacts on an airport operations.
This could range from hardware failure caused by physical symptoms in the
mechanical sections of BHS to more soft type of issues, such as failure in
verification/identification process that could potentially result in
non-programmed and system caused path changes results in baggage loss.</p>

<h1><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;color:windowtext'>System Decomposition<o:p></o:p></span></h1>

<p class=MsoNormal>As previously mentioned, BHS consists of various sub-systems
and parts that are fully integrated into it, but there are only a few of them
that could have a catastrophic impact on the whole system, and thereby on the
whole operation of an airport. These are:</p>

<p class=MsoNormal>X-Ray Screening: this is the most important part of a BHS as
the possible failure in operating a fully functional and accurate state could
potentially endanger human lives. For instance, failure of detecting explosive
devices can result in a major catastrophic event, such that lives are lost, and
therefore recovery from it would not go beyond a less important (finical)
factors.</p>

<p class=MsoNormal>Sorting: this part of BHS is normally full-automated, and as
a result is less prone to human-caused errors. A failure in this section brings
a massive liability an airport, as any misplacement of baggage into a wrong
plane or a passenger would critically endanger personal property/belongings, and
consequently put them at a risk of permanent loss.</p>

<p class=MsoNormal><span style='mso-bidi-font-family:Helvetica;background:white'>Carrousel:
this part of a BHS is more involved in the mechanical process of system, and
generally is easier to fix in the event of a malfunction/failure. If in place,
secondary mechanisms involving manual labour (non-automated) can mitigate the
impact of failure, but if not in place, then the impact I just as severe as it
is in the above part.<o:p></o:p></span></p>

<p class=MsoNormal>Check-in: this is perhaps the least important part (when
considering BHS as an automated system, as this part mostly involves human
factors). As such, failure is not necessary system-based. But, there is still a
narrow probability that a system failure in this section could be rather
catastrophic as the down-time could be considerably long (with the standards
followed by major airports).</p>

<h1><span style='color:windowtext'>Essential Testings<o:p></o:p></span></h1>

<p class=MsoNormal>Unit <span class=GramE>Testing</span>: as per the
information provided in the system decomposition section, there are several
major parts that are exited in a BHS system. Each one this part is a considered
a module of BHS and need to be separately tested with various testing inputs to
capture and eliminate any possible risks that could occur during the course of
each systems’ operation. </p>

<p class=MsoNormal>Integration Testing: this testing has to be applied on the
system after each individual modules are combined and integrated to form a BHS,
and its ultimate goal is to make sure that BHS as a whole works the way it was
planned. Bottom-up approach is more preferable in this system as it starts
testings from lowest integrated levels which is more robust in terms of finding
bugs.</p>

<p class=MsoNormal>Prototype Testing: considering the size of an airport, BHS
system must be prototyped and fully-tested for any design flaws prior to any
implementation. A good indication as to how an implemented system that had
bypassed prototyping is the Denver international airport. Considering that they
could predict and observed design flows in early prototype, could save them an
enormous amount of time and resources.</p>

<h1><span style='color:windowtext'>Trivial Testings<o:p></o:p></span></h1>

<p class=MsoNormal>Acceptance Testing: this test would be trivial as a BHS
system must undergo major reviews and planning phases that generates extensive
documentation on both functionality and formality of the system. </p>

<p class=MsoNormal>Usability Testing: prototype testing is capable of
demonstrating how a final system operates, therefore having usability on the
final phase is redundant. Although this test can, at times when enough
resources are available be executed on a prototype.</p>

<p class=MsoNormal>Compatibility Testing: this is perhaps the least important
test in the context of BHS. A system with the magnitude and size of BHS has to
have a major pre-planning phase in which compatibility is extensively examined
and the development phase is totally reliant on, therefore upon finalising a
BHS system, there has to be a confidence in place that it developed BHS has
full compatibility with existing and future-planned base structures (as per
planning and design documentation instructions).</p>

</div>
