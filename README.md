<h1>Beebs Brute</h1>

<p>**Important Disclaimer:** This tool is intended for educational purposes only and should never be used on systems you don't have explicit permission to access. Brute-force attacks can be illegal and unethical.</p>

<h2>Description</h2>

<p>Beebs Brute is a Python script designed to crack MySQL passwords. It offers two methods:</p>

<ul>
  <li><strong>Dictionary Attack:</strong> This method attempts passwords from a provided dictionary file.</li>
  <li><strong>Brute-Force Attack:</strong> This method systematically tries all possible character combinations within a specified length range.</li>
</ul>

<h2>Usage</h2>
<h3>Prerequisites</h3>

<ul>
  <li>Python 3.x installed</li>
  <li>`mysql.connector` library installed (`pip install mysql.connector`)</li>
  <li>`colorama` library installed (`pip install colorama`)</li>
</ul>

<h3>Running the Script</h3>

1. Download or clone the Beebs Brute script.
2. Open a terminal or command prompt and navigate to the script's directory.
3. Execute the script with the desired options:

   <ul>
     <li><strong>Dictionary Attack:</strong></li>
     <pre>python beebs_brute.py -d &lt;dictionary_file.txt&gt;</pre>
     <p>Replace <code>&lt;dictionary_file.txt&gt;</code> with the path to your dictionary file containing potential passwords.</p>
     <li><strong>Brute-Force Attack:</strong></li>
     <pre>python beebs_brute.py -b --min &lt;min_length&gt; --max &lt;max_length&gt;</pre>
     <p>Replace <code>&lt;min_length&gt;</code> with the minimum password length to try (e.g., 4).</p>
     <p>Replace <code>&lt;max_length&gt;</code> with the maximum password length to try (e.g., 8).</p>
   </ul>

<h3>Output</h3>

<p>The script will display colored output indicating successful password discovery (green) or failed attempts (red).</p>

<h2>Important Notes</h2>

<ul>
  <li>Dictionary attacks are generally faster but less effective if the password isn't in the dictionary.</li>
  <li>Brute-force attacks can be very slow, especially for longer passwords.</li>
  <li>Beebs Brute attempts to connect to a MySQL server on `localhost` (your computer) by default. You may need to modify the connection details in the script if targeting a different server.</li>
</ul>

<h2>Security Considerations</h2>

<ul>
  <li>Brute-force attacks can be time-consuming and resource-intensive on the targeted system.</li>
  <li>Repeated login attempts may trigger security measures like account lockouts.</li>
  <li>Using this script on a system you don't own is illegal and unethical.</li>
</ul>

<h2>Like what you see?</h2>

<p>If you find Beebs Brute useful, consider giving my gig a like! And if you'd like to support my work further, you can buy me a coffee [link to your coffee platform, e.g., Buy Me a Coffee, Ko-fi].</p>
