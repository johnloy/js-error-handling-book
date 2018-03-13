# Table of Contents

* [Cover](README.md)

----

* [Preface][1]
* [Introduction][2]
* [Part 1: The value of thoughtful and thorough error handling][3]
	* [Ch 1:  What exactly is an error?][4]
	* [Ch 2: Errors vs. exceptions vs. maybe bad][5]
	* [Ch 3: When an error is not an Error][6]
	* [Ch 4: Error handling paradigms and schools of thought][7]
	* [Ch 5: Good error handling aids user experience][8]
	* [Ch 6: Good error handling aids developer experience][9]
	* [Ch 7: Good error handling aids testing][10]
	* [Ch 8: Good error handling enhances and protects reputation][11]
* [Part 2: Error handling in the JavaScript language][12]
	* [Ch 9: The Error constructor][13]
	* [Ch 10: Built-in error constructors][14]
	* [Ch 11: try…catch…finally][15]
	* [Ch 12: The call stack][16]
	* [Ch 13: The throw statement][17]
	* [Ch 14: Stack traces][18]
	* [Ch 15: Custom errors][19]
	* [Ch 16: Async error handling][20]
	* [Ch 17: Challenges and language design flaws][21]
* [Part 3: Real world JavaScript error handling in browsers and Node.js][22]
	* [Ch 18: Commonalities between browsers and Node.js][23]
	* [Ch 19: Browser peculiarities][24]
	* [Ch 20: Browser APIs][25]
	* [Ch 21: Node peculiarities][26]
	* [Ch 22: Node APIs][27]
	* [Ch 23: HTTP][28]
* [Part 4: Real world JavaScript error handling in web application architecture][29]
	* [Ch 24: When and where error handling is useful][30]
	* [Ch 25: Design and strategy][31]
	* [Ch 26: Tactics][32]
		* [Missing browser or Node.js feature support][33]
		* [Faulty third-party packages][34]
		* [Faulty third-party dynamic embeds][35]
		* [Code API contract violations][36]
		* [Race conditions][37]
		* [Loss of network connectivity][38]
		* [Request failure][39]
		* [Asset load failure][40]
		* [Critical failure during app loading][41]
		* [UI component render failure][42]
		* [No matching route][43]
		* [Forbidden route][44]
		* [Private browsing mode][45]
		* [Realtime data inconsistency][46]
		* [Too-aggressive caching][47]
		* [Too-fast input][48]
		* [Too-slow processing][49]
		* [Client storage quota exceeded][50]
	* [Ch 27: During development][51]
	* [Ch 28: During automated testing][52]
	* [Ch 29: During staging and QA][53]
	* [Ch 30: During production][54]
* [Part 5: Complementary concepts and techniques][55]

[1]:	preface.md
[2]:    introduction.md
[3]:	part-1/0-intro.md
[4]:	part-1/chapter-1/0-what-exactly-is-an-error.md
[5]:	part-1/chapter-2/0-errors-vs-exceptions-vs-maybe-bad.md
[6]:	part-1/chapter-3/0-when-an-error-is-not-an-error.md
[7]:	part-1/chapter-4/0-error-handling-paradigms-and-schools-of-thought.md
[8]:	part-1/chapter-5/0-good-error-handling-aids-user-experience.md
[9]:	part-1/chapter-6/0-good-error-handling-aids-developer-experience.md
[10]:	part-1/chapter-7/0-good-error-handling-aids-testing.md
[11]:	part-1/chapter-8/0-good-error-handling-enhances-and-protects-reputation.md
[12]:	part-2/0-intro.md
[13]:	part-2/chapter-9/0-the-error-constructor.md
[14]:	part-2/chapter-10/0-built-in-error-constructors.md
[15]:	part-2/chapter-11/0-try-catch-finally.md
[16]:	part-2/chapter-12/0-the-call-stack.md
[17]:	part-2/chapter-13/0-the-throw-statement.md
[18]:	part-2/chapter-14/0-stack-traces.md
[19]:	part-2/chapter-15/0-custom-errors.md
[20]:	part-2/chapter-16/0-async-error-handling.md
[21]:	part-2/chapter-17/0-challenges-and-language-design-flaws.md
[22]:	part-3/0-intro.md
[23]:	part-3/chapter-18/0-commonalities-between-browsers-and-nodejs.md
[24]:	part-3/chapter-19/0-browser-peculiarities.md
[25]:	part-3/chapter-20/0-browser-apis.md
[26]:	part-3/chapter-21/0-node-peculiarities.md
[27]:	part-3/chapter-22/0-node-apis.md
[28]:	part-3/chapter-23/0-http.md
[29]:	part-4/0-intro.md
[30]:   part-4/chapter-24/0-when-and-where-error-handling-is-useful.md
[31]:   part-4/chapter-25/0-design-and-strategy.md
[32]:   part-4/chapter-26/0-tactics.md
[33]:   part-4/chapter-26/missing-browser-node-feature-support.md
[34]:   part-4/chapter-26/faulty-third-party-packages.md
[35]:   part-4/chapter-26/faulty-third-party-dynamic-embeds.md
[36]:   part-4/chapter-26/code-api-contract-violations.md
[37]:   part-4/chapter-26/race-conditions.md
[38]:   part-4/chapter-26/loss-of-network-connectivity.md
[39]:   part-4/chapter-26/request-failure.md
[40]:   part-4/chapter-26/asset-load-failure.md
[41]:   part-4/chapter-26/critical-failure-during-app-loading.md
[42]:   part-4/chapter-26/ui-component-render-failure.md
[43]:   part-4/chapter-26/no-matching-route.md
[44]:   part-4/chapter-26/forbidden-route.md
[45]:   part-4/chapter-26/private-browsing-mode.md
[46]:   part-4/chapter-26/realtime-data-inconsistency.md
[47]:   part-4/chapter-26/too-aggressive-caching.md
[48]:   part-4/chapter-26/too-fast-input.md
[49]:   part-4/chapter-26/too-slow-processing.md
[50]:   part-4/chapter-26/client-storage-quota-exceeded.md
[55]:	part-5/0-intro.md