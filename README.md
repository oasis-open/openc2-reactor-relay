<div>
<h1>README</h1>

<div>
<h2><a id="readme-general">OASIS TC Open Repository: openc2-reactor-relay</a></h2>

<p>This GitHub public repository ( <b><a href="https://github.com/oasis-open/openc2-reactor-relay">https://github.com/oasis-open/openc2-reactor-relay</a></b> ) was created at the request of the <a href="https://www.oasis-open.org/committees/openc2/">OASIS Open Command and Control (OpenC2) TC</a> as an <a href="https://www.oasis-open.org/resources/open-repositories/">OASIS TC Open Repository</a> to support development of open source resources related to Technical Committee work.</p>

<p>While this TC Open Repository remains associated with the sponsor TC, its development priorities, leadership, intellectual property terms, participation rules, and other matters of governance are <a href="https://github.com/oasis-open/openc2-reactor-relay/blob/master/CONTRIBUTING.md#governance-distinct-from-oasis-tc-process">separate and distinct</a> from the OASIS TC Process and related policies.</p>

<p>All contributions made to this TC Open Repository are subject to open source license terms expressed in the <a href="https://www.oasis-open.org/sites/www.oasis-open.org/files/Apache-LICENSE-2.0.txt">Apache License v 2.0</a>.  That license was selected as the declared <a href="https://www.oasis-open.org/resources/open-repositories/licenses">"Applicable License"</a> when the TC Open Repository was created.</p>

<p>As documented in <a href="https://github.com/oasis-open/openc2-reactor-relay/blob/master/CONTRIBUTING.md#public-participation-invited">"Public Participation Invited</a>", contributions to this OASIS TC Open Repository are invited from all parties, whether affiliated with OASIS or not.  Participants must have a GitHub account, but no fees or OASIS membership obligations are required.  Participation is expected to be consistent with the <a href="https://www.oasis-open.org/policies-guidelines/open-repositories">OASIS TC Open Repository Guidelines and Procedures</a>, the open source <a href="https://github.com/oasis-open/openc2-reactor-relay/blob/master/LICENSE">LICENSE</a> designated for this particular repository, and the requirement for an <a href="https://www.oasis-open.org/resources/open-repositories/cla/individual-cla">Individual Contributor License Agreement</a> that governs intellectual property.</p>

</div>

<div>
<h2><a id="purposeStatement">Statement of Purpose</a></h2>

<p>Statement of Purpose for this OASIS TC Open Repository (openc2-reactor-relay) as <a href="https://drive.google.com/open?id=0B-FunCZrr-vtTUhnbGpPTlBKLTQ">proposed</a> and <a href="https://www.oasis-open.org/committees/ballot.php?id=3115">approved</a> [<a href="https://issues.oasis-open.org/browse/TCADMIN-2748">bis</a>] by the OpenC2 TC:</p>

<p>The purpose of the openc2-reactor-relay repository is to (a) demonstrate how OpenC2 can be deployed as a means to manage and administrate geographically disparate network, and (b) provision a codebase to enable other prototype efforts.</p>

<p>Reactor-relay provides a simple, modular API to accepting OpenC2 commands and converting them into Python actions.  Reactor-relay can be administered by non-technical staff. It allows the end user to link profile code, to OpenC2 commands and actuators, and handles credential storage.</p>

<p>The relay is called by an upstream Orchestrator (see <a href="https://github.com/oasis-open/openc2-reactor-master">reactor-master</a>).  The idea is that an enterprise has multiple sites and clients, with different capabilities and network layouts, buy allowing engineers to create a topology of "Relays" commands can be routed to multiple sites from a central server, without the need for that central server to connect into each actuator directly. (i.e. remote access as root to a web server from the internet).</p>

<p>Relays provide a way for us to define specific use cases and actuators per client, and provide a secure IP-locked TLS channel to execute those actions.</p>

<p>The initial codebase for openc2-reactor-relay is imported from the OpenC2 Forum's Github repository.</p>



</div>

<div><h2><a id="purposeClarifications">Additions to Statement of Purpose</a></h2>

<p>Repository Maintainers may include here any clarifications &mdash; any additional sections, subsections, and paragraphs that the Maintainer(s) wish to add as descriptive text, reflecting (sub-) project status, milestones, releases, modifications to statement of purpose, etc.  The project Maintainers will create and maintain this content on behalf of the participants.</p>
</div>

<div>
<h2><a id="maintainers">Maintainers</a></h2>

<p>TC Open Repository <a href="https://www.oasis-open.org/resources/open-repositories/maintainers-guide">Maintainers</a> are responsible for oversight of this project's community development activities, including evaluation of GitHub <a href="https://github.com/oasis-open/openc2-reactor-relay/blob/master/CONTRIBUTING.md#fork-and-pull-collaboration-model">pull requests</a> and <a href="https://www.oasis-open.org/policies-guidelines/open-repositories#repositoryManagement">preserving</a> open source principles of openness and fairness. Maintainers are recognized and trusted experts who serve to implement community goals and consensus design preferences.</p>

<p>Initially, the associated TC members have designated one or more persons to serve as Maintainer(s); subsequently, participating community members may select additional or substitute Maintainers, per <a href="https://www.oasis-open.org/resources/open-repositories/maintainers-guide#additionalMaintainers">consensus agreements</a>.</p>

<p><b><a id="currentMaintainers">Current Maintainers of this TC Open Repository</a></b></p>

<ul>
<li><a href="mailto:dpkemp@radium.ncsc.mil">Dave Kemp</a>; GitHub ID: <a href="https://github.com/davaya">https://github.com/davaya</a>; WWW: <a href="http://www.nsa.gov/">Department of Defense</a></li>

<li><a href="mailto:adam.bradbury@zepko.com">Adam Bradbury</a>; GitHub ID: <a href="https://github.com/AdamTheAnalyst">https://github.com/AdamTheAnalyst</a>; WWW: <a href="http://www.zepko.com/">Zepko</a></li>

</ul>

</div>

<div><h2><a id="aboutOpenRepos">About OASIS TC Open Repositories</a></h2>

<p><ul>
<li><a href="https://www.oasis-open.org/resources/open-repositories/">TC Open Repositories: Overview and Resources</a></li>
<li><a href="https://www.oasis-open.org/resources/open-repositories/faq">Frequently Asked Questions</a></li>
<li><a href="https://www.oasis-open.org/resources/open-repositories/licenses">Open Source Licenses</a></li>
<li><a href="https://www.oasis-open.org/resources/open-repositories/cla">Contributor License Agreements (CLAs)</a></li>
<li><a href="https://www.oasis-open.org/resources/open-repositories/maintainers-guide">Maintainers' Guidelines and Agreement</a></li>
</ul></p>

</div>

<div><h2><a id="feedback">Feedback</a></h2>

<p>Questions or comments about this TC Open Repository's activities should be composed as GitHub issues or comments. If use of an issue/comment is not possible or appropriate, questions may be directed by email to the Maintainer(s) <a href="#currentMaintainers">listed above</a>.  Please send general questions about TC Open Repository participation to OASIS Staff at <a href="mailto:repository-admin@oasis-open.org">repository-admin@oasis-open.org</a> and any specific CLA-related questions to <a href="mailto:repository-cla@oasis-open.org">repository-cla@oasis-open.org</a>.</p>

</div></div>
