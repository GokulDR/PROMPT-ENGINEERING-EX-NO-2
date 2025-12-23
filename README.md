[Gokul D R (25017732) EX 1.doc](https://github.com/user-attachments/files/24312601/Gokul.D.R.25017732.EX.1.doc)[Gokul D R (25017732) EX 1.doc](https://github.com/user-attachments/files/24312442/Gokul.D.R.25017732.EX.1.doc)# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT
[Uploading G<html xmlns:o='urn:schemas-microsoft-com:office:office' xmlns:w='urn:schemas-microsoft-com:office:word' xmlns='http://www.w3.org/TR/REC-html40'><head><meta charset='utf-8'><title>Text To Word</title></head><body><h2 data-start="293" data-end="322">1. AIM (slight refinement)</h2>
<p data-start="324" data-end="408"><strong data-start="324" data-end="337">Original:</strong><br data-start="337" data-end="340">To evaluate and compare the effectiveness of prompting techniques...</p>
<p data-start="410" data-end="679"><strong data-start="410" data-end="443">Revised (clearer &amp; smoother):</strong><br data-start="443" data-end="446"><strong data-start="446" data-end="679">To evaluate and compare the effectiveness of different prompting techniques (zero-shot, few-shot, chain-of-thought, and role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, and Copilot) for text summarization tasks.</strong></p>
<hr data-start="681" data-end="684">
<h2 data-start="686" data-end="724">2. Scenario (minor language polish)</h2>
<p data-start="726" data-end="1054"><strong data-start="726" data-end="746">Revised Version:</strong><br data-start="746" data-end="749">You are a member of a content curation team for an educational platform that provides concise summaries of technical concepts to undergraduate students.<br data-start="901" data-end="904">Your task is to summarize a 500-word technical article titled <strong data-start="966" data-end="1001">&ldquo;The Basics of Cloud Computing&rdquo;</strong> using various AI platforms and prompting strategies.</p>
<p data-start="1056" data-end="1199">The objective is to identify the most effective combination of <strong data-start="1119" data-end="1158">AI platform and prompting technique</strong> based on predefined evaluation criteria.</p>
<hr data-start="1201" data-end="1204">
<h2 data-start="1206" data-end="1247">3. Algorithm (better flow, same steps)</h2>
<p data-start="1249" data-end="1271"><strong data-start="1249" data-end="1271">Revised Algorithm:</strong></p>
<ol data-start="1273" data-end="1776">
<li data-start="1273" data-end="1375">
<p data-start="1276" data-end="1375">Select a technical article of approximately 500 words titled <strong data-start="1337" data-end="1373">&ldquo;The Basics of Cloud Computing.&rdquo;</strong></p>
</li>
<li data-start="1376" data-end="1495">
<p data-start="1379" data-end="1420">Apply the following prompting techniques:</p>
<ul data-start="1424" data-end="1495">
<li data-start="1424" data-end="1437">
<p data-start="1426" data-end="1437">Zero-shot</p>
</li>
<li data-start="1441" data-end="1453">
<p data-start="1443" data-end="1453">Few-shot</p>
</li>
<li data-start="1457" data-end="1477">
<p data-start="1459" data-end="1477">Chain-of-Thought</p>
</li>
<li data-start="1481" data-end="1495">
<p data-start="1483" data-end="1495">Role-based</p>
</li>
</ul>
</li>
<li data-start="1496" data-end="1587">
<p data-start="1499" data-end="1529">Use the selected AI platforms:</p>
<ul data-start="1533" data-end="1587">
<li data-start="1533" data-end="1544">
<p data-start="1535" data-end="1544">ChatGPT</p>
</li>
<li data-start="1548" data-end="1558">
<p data-start="1550" data-end="1558">Gemini</p>
</li>
<li data-start="1562" data-end="1572">
<p data-start="1564" data-end="1572">Claude</p>
</li>
<li data-start="1576" data-end="1587">
<p data-start="1578" data-end="1587">Copilot</p>
</li>
</ul>
</li>
<li data-start="1588" data-end="1658">
<p data-start="1591" data-end="1658">Generate summaries and record response time for each combination.</p>
</li>
<li data-start="1659" data-end="1711">
<p data-start="1662" data-end="1711">Evaluate the outputs using predefined criteria.</p>
</li>
<li data-start="1712" data-end="1776">
<p data-start="1715" data-end="1776">Compare results and identify the best-performing combination.</p>
</li>
</ol>
<hr data-start="1778" data-end="1781">
<h2 data-start="1783" data-end="1836">4. Prompting Strategies Definition (minor clarity)</h2>
<p data-start="1838" data-end="1982"><strong data-start="1838" data-end="1869">Chain-of-Thought (revised):</strong><br data-start="1869" data-end="1872">Ask the model to first identify key points from the article and then generate a summary based on those points.</p>
<p data-start="1984" data-end="2130"><strong data-start="1984" data-end="2009">Role-based (revised):</strong><br data-start="2009" data-end="2012">Ask the model to act in a specific role (for example, <em data-start="2066" data-end="2128">a cloud computing instructor teaching undergraduate students</em>).</p>
<hr data-start="2132" data-end="2135">
<h2 data-start="2137" data-end="2185">5. Evaluation Criteria (slight academic tone)</h2>
<ul data-start="2187" data-end="2486">
<li data-start="2187" data-end="2243">
<p data-start="2189" data-end="2243"><strong data-start="2189" data-end="2202">Accuracy:</strong> Correctly represents the main concepts</p>
</li>
<li data-start="2244" data-end="2302">
<p data-start="2246" data-end="2302"><strong data-start="2246" data-end="2260">Coherence:</strong> Well-organized and logically structured</p>
</li>
<li data-start="2303" data-end="2370">
<p data-start="2305" data-end="2370"><strong data-start="2305" data-end="2320">Simplicity:</strong> Easily understandable by undergraduate students</p>
</li>
<li data-start="2371" data-end="2421">
<p data-start="2373" data-end="2421"><strong data-start="2373" data-end="2383">Speed:</strong> Time taken to generate the response</p>
</li>
<li data-start="2422" data-end="2486">
<p data-start="2424" data-end="2486"><strong data-start="2424" data-end="2444">User Experience:</strong> Overall clarity and ease of interaction</p>
</li>
</ul>
<hr data-start="2488" data-end="2491">
<h2 data-start="2493" data-end="2548">6. Best Performing Combination (stronger conclusion)</h2>
<p data-start="2550" data-end="2920"><strong data-start="2550" data-end="2573">Revised Conclusion:</strong><br data-start="2573" data-end="2576">The analysis shows that <strong data-start="2600" data-end="2636">Claude with Role-based prompting</strong> and <strong data-start="2641" data-end="2676">ChatGPT with Few-shot prompting</strong> achieved the highest score (24/25). These combinations produced summaries that were accurate, clear, well-structured, and highly suitable for undergraduate learners, making them the most effective choices for educational content summarization.</p></body></html>okul D R (25017732) EX 1.doc…]()


## RESULT
