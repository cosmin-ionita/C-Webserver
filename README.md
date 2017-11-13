<html>
<h1>Simple webserver</h1>
<p>This is a webserver that we'll use for research purposes. We'll try different solutions of approaching the client's handling (pthreads / Open MP)</p>
<hr>
<h2>Uses</h2>
<p>If you'd like to see some statistics based on your workstation's configuration, you can use it.</p>
<hr>
<h2>Example</h2>
<p>Run the Makefile</p>
<pre>make</pre>
<p>You run the server like this:</p>
<pre>./server [port] [& - to run in background]</pre>
<p>For example, to run it on port 8080, you'd do something like this:</p>
<pre>./server 8080 &</pre>
</html>
