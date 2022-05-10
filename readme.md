1. Download the node module : npm install
2. Run the Node server: node server.js
3. On a new terminal, Run the Evil server: node evil server.js 

4. Go to [http://localhost:3000] which runs the welcome login for the editor's website.
5. On Console of  the application execute encodeURIComponent :
        mentioned in the project report to get the cookiee information and the keylogger values to be shown on the Evil Server which records the sensitive information and displays it.
6. Mitigation for XSS (cokiee and keyloger) :  change our application/website code to use user input that is the  q parameter strictly as text content. 
7. Implementing Content Security Policy declarations to instruct the browser.