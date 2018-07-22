<h1>SimpleChatRoom</h1>
<p>A simple chat room web app implemented in NodeJS. Simply run server end script and let users connect via provided HTML file.</p>

<h2>The Server End</h2>
<p>You will be needing NodeJS, NPM, module express, module socket.io installed.</br>
The .msi file for installing NodeJS on Windows contains NPM itself.</p>
<pre>
  $ npm install express
  $ npm install socket.io
</pre>

<p>And then call <code>node</code> to run the server script.</p>
<pre>
  $ node main.js
</pre>
<p>3 Files should be at the same location. Server will pass the needed files to the clients when connected.</p>


<h2>The Client End</h2>
<p>Connect to http://SERVERIP:PORT and join the chat!</p>

<h2>To-do</h2>
<p>More details will be added (yeah, as well as files and screen shots) as I continue working on this.</p>
