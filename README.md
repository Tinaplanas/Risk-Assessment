<h1>🧠 Mock Risk Assessment: Point-of-Sale (POS) System</h1>

This mock risk assessment helped me practice thinking like a security analyst. I chose a POS system because I have real-world experience in sales environments and I know firsthand how critical (and vulnerable) these systems can be. I wanted to break it down, step-by-step, just like I would in a real role.

<hr>

<h2>🔍 Risk Identification</h2>

<table>
  <tr>
    <th>Threat</th>
    <th>Vulnerability</th>
    <th>Impact</th>
  </tr>
  <tr>
    <td>Malware via USB</td>
    <td>USB ports not disabled</td>
    <td>Data breach; credit card data exfiltration</td>
  </tr>
  <tr>
    <td>Network sniffing</td>
    <td>Unencrypted traffic</td>
    <td>Customer data compromise</td>
  </tr>
  <tr>
    <td>Insider misuse</td>
    <td>Weak access controls</td>
    <td>Unauthorized transactions</td>
  </tr>
</table>

<hr>

<h2>🔐 Controls I’d Recommend</h2>

<table>
  <tr>
    <th>Control Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Preventive</td>
    <td>Disable USB ports via Group Policy</td>
  </tr>
  <tr>
    <td>Detective</td>
    <td>Antivirus with real-time scanning</td>
  </tr>
  <tr>
    <td>Corrective</td>
    <td>Endpoint reimaging policy</td>
  </tr>
</table>

<hr>

<h2>🧮 Risk Evaluation</h2>

<table>
  <tr>
    <th>Risk</th>
    <th>Likelihood</th>
    <th>Impact</th>
    <th>Risk Score</th>
  </tr>
  <tr>
    <td>Malware via USB</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Network sniffing</td>
    <td>High</td>
    <td>Medium</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Insider misuse</td>
    <td>Medium</td>
    <td>Medium</td>
    <td>Medium</td>
  </tr>
</table>

<hr>

<h2>✅ My Thought Process</h2>

I wanted to build this the way I'd present it to a team. I asked myself: What’s vulnerable? How likely is it to be exploited? What can we do about it? It’s more than theory. It’s critical thinking under pressure, with real systems at stake.

<hr>

<h2>✍️ Mitigation Plan</h2>

<ul>
  <li>Use endpoint protection with centralized USB control</li>
  <li>Encrypt POS network traffic using TLS</li>
  <li>Train employees regularly on security best practices</li>
  <li>Schedule and document monthly vulnerability scans</li>
</ul>
