moodle-save-all-resources
=========================

<h1>Purpose</h1>
This Greasemonkey user script is meant to facilitate the downloads on a Moodle Class by adding a Download All button to every Session.

<h1>Features</h1>
<ul>
    <li>Single file download just by clicking on its link (default behavior is opening a new window)</li>
    <li>Download all files (trigger one by one) by clicking on the link <code>Download all</code></li>
    <li>Download all files zipped in an archive with folder useful structure  by clicking on the link <code>Download all zipped</code><br/>
    This option first fetches all the files an then creates the Zip archive. It marks with a green check sign the files successfully fetched. Marks with a red sign the files that are not downloadable which you should check out by yourself.
    </li>
    <li>Avoids the browser to open and render PDF files instead of downloading them.</li>
</ul>

<h1>Supported browsers</h1>
<ul>
    <li>Chrome 14+</li>
    <li>Firefox 20+</li>
</ul>

<h1>Notes:</h1>
<ul>
    <li>When using the <code>Download all</code> link the browser may popup an alert saying <em>This site is downloading multiple files</em> which you have to <em>Allow</em> otherwise the files are not downloaded.</li>
    <li>On PDF files the some browsers asky you to <em>Keep</em> or <em>Discard</em> before actually downloading.</li>
    <li>Only INCAE Moodle url was added to the @match definition, to be able to use this script in other Moodle installation you will have to add a @match tag with your installation base url.</li>
</ul>

<b>Version:<b>1.0rc1

<b>License:<b>GNU General Public License (GPL)
