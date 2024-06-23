# T1A1-Workbook

## Q1 Identify and explain common and important components and concepts of web development markup languages

What are Markup Languages?

Markup languages are the foundation of web pages. They define the structure and content of a webpage, telling web browsers how to display information.
Common Markup Languages:

- HTML (HyperText Markup Language): The most widely used markup language for web pages. It defines the structure, layout, and basic content of a page.

  - Updated HTML to HTML5:  
    HTML5 is the latest version of HTML, introducing new elements and attributes to improve web functionality.

        - Semantic Elements: These elements provide better structure and meaning, like <header, <footer, <article, <section.

        - Multimedia Elements: New tags for bringing in media, like audio, video.

        - Form Elements: Improved form controls with new input types, like <input type="date", <input type="email".

        - Data Storage: Uses SQL, local, and application cache to temporarily store data.

- XML (Extensible Markup Language): Used for data storage and exchange. XML allows you to create custom tags and define structured data.

### Key Components and Concepts:

- Elements: Elements are the building blocks of a webpage. They are represented by tags enclosed in angle brackets (< >). Examples:

  - Headings: Used to structure the page with hierarchical titles (h1, h2, etc.).
  - Paragraphs: Used to create blocks of text (p).
  - Lists: Used to present information in ordered or unordered lists (ol, ul, li).
  - Links: Used to create clickable hyperlinks (a).
  - Images: Used to import images (img).
  - Tables: Used to organise data in rows and columns (table).
  - Forms: Used to collect user input (form).

- Attributes: Attributes provide additional information about an element. They come in key-value pairs within the opening tag. For example, img src="image.jpg" alt="A picture of me" defines an image with a source and an alternative text description.

- Content: The text, images, videos, and other data that appear on a webpage are called content. It's enclosed within the opening and closing tags of an element.

- Data Storage: Uses cookies and browser cache to temporarily store data.

- CSS Styling: CSS is used to style and layout web pages. It controls the design, layout, and visual effects of web content written in HTML. Through the use of selectors, these are used to target HTML elements, like .class, #id, element, etc.

### Key Things to do when writing in a markup language:

- Semantic HTML: Use tags that accurately describe the meaning and purpose of the content, not just for styling. This improves accessibility and optimization.

- Valid Code: Write clean and well-formed code that follows the specifications of the markup language.

- Accessibility: Design web pages to be usable and accessible by everyone, including people with disabilities.

Example of HTML5:

```
<html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <title>Web Page</title>
    </head>
    <body>
        <header>
            <img src="./images/Logo.png" alt="Logo">
            <nav>
                <a class="home" href="#">Home</a>
            </nav>
        </header>
    <main>
        <section>
            <h1>Welcome to My Website</h1>
            <p>This is a simple web page with a heading and paragraph.</p>
            <img src="image.jpg" alt="A picture">
        </section>
    </main>
    <footer>
      <a href="link to socials">Socials</a>
      <p>Contact info</p>
      <h4>Copyright</h4>
    </footer>
  </body>
</html>
```

A few new elements are missing but this is just a basic example.

### References:

- Markup language:

  - Shopify (2023). How Markup Language Works to Format Websites (2023) - Shopify. [online] Shopify. Available at: https://www.shopify.com/blog/markup-language.

- HTML/HTML5:

  - MDN Web Docs (2018). HTML: HyperText Markup Language. [online] MDN Web Docs. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML.

  - VVCS (2024). Important Concepts in HTML | Key Concepts in HTML. [online] Vcube software solutions. Available at: https://www.vcubesoftsolutions.com/key-concepts-in-html/#:~:text=Introduction%3A%20HTML%2C%20which%20stands%20for.

  - W3Schools (2022). Introduction to HTML. [online] W3schools.com. Available at: https://www.w3schools.com/html/html_intro.asp.

  - G, D. (2021). What Is the Difference Between HTML vs HTML5. [online] Hostinger Tutorials. Available at: https://www.hostinger.com/tutorials/difference-between-html-and-html5#:~:text=Both%20HTML%20and%20HTML5%20are.

- XML:

  - developer.mozilla.org. (2023). XML: Extensible Markup Language | MDN. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/XML.

  - Sadok, S.B. (2023). What Is Markup Language? Examples, Types & Definition. [online] Semrush Blog. Available at: https://www.semrush.com/blog/markup-language/#xml:-bridging-data-storage-and-transport.

  - w3schools (2015). XML Introduction. [online] W3schools.com. Available at: https://www.w3schools.com/xml/xml_whatis.asp.

---

### Q2 Define the features of the following technologies that are essential in terms of the development of the internet:

Packets:

- Features:

  - Data Structure: Packets are small blocks of data that include both the payload (actual data being sent) and control information (headers with destination address, sequencing, and error-checking data).

  - Fragmentation: Larger messages are broken down into packets which can be sent independently across the network and reassembled at the destination.

  - Reliability and Efficiency: Packet-switching ensures efficient use of network resources and provides robustness, as packets can take multiple paths to reach the destination.

- Contribution: Packets enable efficient and reliable data transmission over the internet. By breaking down large messages into packets, they help in optimising bandwidth and facilitate error-handling, allowing for flexibility and improved network utilisation.

IP Addresses (IPv4 and IPv6):

- Features:

  - Unique Identification: Both IPv4 and IPv6 provide unique addresses for devices connected to the internet, facilitating accurate data routing.

  - IPv4: Addresses are designed in a 32-bit binary format, allowing for approximately 4.3 billion (2^32) unique addresses. A complete 32-bit address consists of two main parts:

    - Network Prefix: Hosts within a single network share the same network address.
    - Host Number: Host has a unique address that identifies it within the network.

  - IPv6: The successor to IPv4, was designed to meet the growing demands of the Internet. It enhances routing efficiency with a simplified packet header, supports mobile devices better, enforces data security through IPsec, and offers improved QoS support. IPv6 addresses are 128 bits long and include a scope field to match application type. Unlike IPv4, IPv6 uses multicast addresses for broadcast and introduces the anycast address type.

- Contribution: IP addresses are crucial for identifying devices and routing data correctly across the internet. IPv4 initially supported the internet’s growth, while IPv6 now addresses the limitations of IPv4, ensuring the continued expansion of the internet and the Internet of Things (IoT).

Routers and Routing:

- Features:

  - Path Determination: Routers determine the optimal path for data packets to travel from sender to receiver.

  - Interconnecting Networks: Routers connect multiple networks, directing packet traffic across the internet.

  - Dynamic Routing: Utilises routing algorithms and protocols (like OSPF, BGP) to dynamically adjust routes based on current network conditions, optimising performance and reliability.

- Contribution: Routers and routing protocols are fundamental for the connection of networks, forming the backbone of the internet. They ensure data packets are efficiently and accurately delivered, supporting the scalability and adaptability of the internet.

Domains and DNS:

- Features:

  - Domain Names: Human-readable addresses (e.g., www.example.com) that map to numerical IP addresses.

  - DNS (Domain Name System): A naming system that translates domain names into IP addresses, distributed across various DNS servers worldwide.

  - Efficiency: DNS supports a hierarchical structure (root, TLD, second-level domains) which optimises the address resolution process.

- Contribution: The Domain Name System simplifies internet navigation by allowing users to use memorable and manageable domain names instead of numeric IP addresses. DNS is essential for the usability and accessibility of the internet, ensuring that users can reach websites and services effortlessly.

### References:

- Packets:

  - What is a packet? | Network packet definition | Cloudflare UK. (n.d.). Cloudflare. [online] Available at: https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-packet/.

  - Wikipedia Contributors (2019). Packet switching. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Packet_switching.

- IP Addresses (IPv4 and IPv6):

  - Kapoor, A. (2023). Understand the Difference Between IPv4 and IPv6 | Simplilearn. [online] Simplilearn.com. Available at: https://www.simplilearn.com/tutorials/cyber-security-tutorial/difference-between-ipv4-and-ipv6.

  - Wikipedia Contributors (2019). IP address. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/IP_address.

  - www.juniper.net. (2024). IPv4 and IPv6 Protocol Families | Junos OS | Juniper Networks. [online] Available at: https://www.juniper.net/documentation/us/en/software/junos/interfaces-security-devices/topics/topic-map/security-interface-ipv4-ipv6-protocol.html#:~:text=IPv4%20addresses%20are%2032%2Dbit.

- Routers and Routing:

  - Cloudflare. (n.d.). What is a router? [online] Available at: https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-router/.

  - What is routing? | IP routing | Cloudflare UK. (n.d.). Cloudflare. [online] Available at: https://www.cloudflare.com/en-gb/learning/network-layer/what-is-routing/.

  - Wikipedia Contributors (2019). Router (computing). [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Router_(computing).

- Domains and DNS:

  - Cloudflare (2022). What Is DNS? | How DNS Works | Cloudflare UK. Cloudflare. [online] Available at: https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/.

  - Wikipedia Contributors (2019). Domain Name System. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/Domain_Name_System.

---

### Q3 Define the features of the following technologies that are essential in terms of the development of the internet:

TCP (Transmission Control Protocol):

- Features:

  - Reliability: TCP ensures reliable data transmission by establishing connections, acknowledging received data, and retransmitting lost packets.

  - Flow Control: Regulates data flow between sender and receiver, preventing data overflow and ensuring efficient delivery.

  - Sequencing: Orders data packets to be reassembled correctly at the receiving end.

- Contribution: TCP forms the backbone of client-server communication on the internet. Its reliable, connection-oriented nature allows for error-free data transmission, making it crucial for services like email, file transfer, and web browsing.

HTTP and HTTPS:

- Features:

  - HTTP (Hypertext Transfer Protocol): Facilitates the transfer of web content from servers to clients via a request-response model.

  - HTTPS (Hypertext Transfer Protocol Secure): Encrypts data transmitted over HTTP using SSL/TLS, ensuring secure communication.

- Contribution: HTTP enables seamless data exchange between web servers and clients, forming the basis of web browsing. HTTPS enhances security by encrypting data, safeguarding sensitive information like login credentials and payment details during online transactions.

Web Browsers:

- Features:

  - Requests: Browsers send HTTP requests to web servers, fetching web resources like HTML, CSS, and scripts to render pages.

  - Rendering: Browsers interpret HTML, CSS, and JavaScript to display web content visually for users.

  - Developer Tools: Provide functionalities for debugging, profiling, and inspecting web elements during development.

- Contribution: Web browsers act as user interfaces for accessing web content, handling client-side processing, and presenting information in a readable format. Developer tools aid in creating and optimising web applications, ensuring a smooth user experience and efficient web development.

### References:

- TCP:

  - Lutkevich, B. (2021). What is TCP (Transmission Control Protocol)? [online] TechTarget. Available at: https://www.techtarget.com/searchnetworking/definition/TCP.

  - MDN Web Docs. (2019). TCP. [online] Available at: https://developer.mozilla.org/en-US/docs/Glossary/TCP.

- HTTP and HTTPS:

  - Cloudflare (n.d.). What is HTTPS? | Cloudflare UK. Cloudflare. [online] Available at: https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/.

  - MDN Contributors (2019). HTTP. [online] MDN Web Docs. Available at: https://developer.mozilla.org/en-US/docs/Web/HTTP.

  - MDN Web Docs. (2019). An overview of HTTP. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview.

  - Wikipedia Contributors (2018). HTTPS. [online] Wikipedia. Available at: https://en.wikipedia.org/wiki/HTTPS.

- Web Browsers:

  - GeeksforGeeks. (2023). Functions and Features of a Web Browser. [online] Available at: https://www.geeksforgeeks.org/functions-and-features-of-a-web-browser/.

  - Khaliszikrul (2024). What is a Web Browser? Features and Benefits - Khaliszikrul - Medium. [online] Medium. Available at: https://medium.com/@khaliszikrul/what-is-a-web-browser-features-and-benefits-aa23de12a0a0.

---

### Q4 Describe the features of interpreters and compilers and how they are different.

Interpreters:

- Translating Source Code: Interpreters translate source code into machine code line by line, executing each line as it's translated.

- Suitability: They are suitable for languages like Python and JavaScript, as they allow for quick prototyping and easier debugging.

- Performance: Interpreted code generally runs slower compared to compiled code due to the real-time translation process.

- Error Handling: Errors are reported as soon as they are encountered during interpretation.

- Examples: Python interpreter, Node.js for JavaScript.

Compilers:

- Transforming Source Code: Compilers transform entire source code into machine code before execution, creating an executable file.

- Suitability: Commonly used for languages like C, C++, and Java, which require compilation before execution.

- Performance: Compiled code tends to be faster and more efficient as it's directly converted to machine code.

- Error Handling: Errors are reported after the compilation process, which can make debugging more challenging.

- Examples: GCC for C/C++, Java Compiler for Java programs.

Differences:

- Execution Method:

  - Interpreters: Execute code line-by-line. The interpreter reads the source code and executes it immediately each time it is run.

  - Compilers: Translate the entire source code into machine code in one go, creating an executable file.

- Performance:

  - Interpreters: Can be slower due to line-by-line execution, especially for repetitive tasks.

  - Compilers: Compiled programs tend to run faster because the entire source code is optimised into machine code.

- Memory Usage:

  - Interpreters: Does not produce object code, resulting in lower memory usage.

  - Compilers: Creates object code, leading to higher memory consumption.

- Usage:

  - Interpreters: Used by languages such as JavaScript, Python, and Ruby.

  - Compilers: Used by languages like C, C++, and Java.

### References:

- Interpreters:

  - Wikipedia. (2020). Interpreter (computing). [online] Available at: https://en.wikipedia.org/wiki/Interpreter_(computing).

- Compilers:

  - Wikipedia. (2020). Compiler. [online] Available at: https://en.wikipedia.org/wiki/Compiler.

- Both:

  - Sassi, R.B. (2023). Compiler vs. Interpreter in Programming | Built in. [online] builtin.com. Available at: https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter.

  - Simplilearn (2023). Key Differences Between Compiler and Interpreter. [online] Simplilearn.com. Available at: https://www.simplilearn.com/difference-between-compiler-and-interpreter-article.

---

### Q5 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

Two commonly used programming languages are Python and JavaScript

Python:

- Benefits:

  - Ease of Learning and Readability: Python's syntax is clear and intuitive, making it an excellent choice for beginners. Its readability means that code written in Python is easy to understand and maintain.

  - Versatility: Python is a general-purpose language that can be used for writing scripts to automate system administration tasks, perform file operations, creating apps, and more.

  - Strong Community Support: Python has a large, active community that contributes to a wealth of resources, tutorials, and third-party modules. This community support can be invaluable when solving problems or learning the language.

- Drawbacks:

  - Performance: Python is an interpreted language, which generally makes it slower than compiled languages like C++ or Java. This can be a drawback for performance-critical applications.

  - Mobile and Game Development: Python is not as strong a choice for mobile app and game development compared to languages like Swift for iOS or C++ for game development. While there are frameworks available, they are not as established as those in other languages.

JavaScript:

- Benefits:

  - Web Development: JavaScript is the language of the web. It runs natively in web browsers, making it essential for front-end development. With the advent of Node.js, it can also be used for back-end server-side development, providing a full-stack development capability.

  - Dynamic and Flexible: JavaScript is a highly flexible language that supports object-oriented, imperative, and functional programming styles. This allows developers to choose the paradigm that best suits their project.

  - Large System: JavaScript has an extensive system, including numerous frameworks and libraries like React, Angular, and Vue.js for front-end development, and Express for server-side development. This makes it easier to build complex applications efficiently.

- Drawbacks:

  - Security Issues: It's presence in web development makes JavaScript a target for security vulnerabilities and attacks, such as cross-site scripting (XSS). It requires careful handling of user inputs and other potential security threats.

  - Browser Compatibility: Despite significant improvements over the years, ensuring compatibility across different browsers can still be a challenge due to differing implementations of JavaScript standards.

  - Performance: While JavaScript can perform well, particularly with modern engines like Chrome, it can be less performant for CPU-intensive applications compared to languages like C++.

### References:

- Python:

  - Python (2010). BeginnersGuide - Python Wiki. [online] Python.org. Available at: https://wiki.python.org/moin/BeginnersGuide.

  - Shalu (2024). Versatility of Python: A Comprehensive Guide to the Language and its Applications. [online] Medium. Available at: https://medium.com/@shalum620/versatility-of-python-a-comprehensive-guide-to-the-language-and-its-applications-2e5cb31f9db6.

  - Sunbul (2024). Exploring The Advantages And Disadvantages Of Python. [online] www.redswitches.com. Available at: https://www.redswitches.com/blog/advantages-and-disadvantages-of-python/.

- JavaScript:

  - GeeksforGeeks. (2024). JavaScript. [online] Available at: https://www.geeksforgeeks.org/javascript/?ref=ghm.

  - Introduction, A. (2019). An Introduction to JavaScript. [online] Javascript.info. Available at: https://javascript.info/intro.

  - MDN Contributors (2023). JavaScript. [online] MDN Web Docs. Available at: https://developer.mozilla.org/en-US/docs/Web/javascript.

---

### Q6 A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.

Dear Alex,

Thank you for reaching out to me regarding the website for the Super Awesome Museum (SAM). I'm glad to hear about the exciting displays at SAM and to help connect visitors through the development of a website.

To touch base about the requirements for the website, which include showcasing the museum's exhibits and artefacts, providing directions to the museum, and offering a means for visitors to contact the museum. I have thought of some ideas that aligns with these requests.

I propose incorporating features like an interactive map for directions, a blog for all of SAM’s artefacts and exhibits, and a contact form for users to send enquiries, this will help keep engagement on the website and improve accessibility for everyone.

I would be more than happy to discuss further details and collaborate closely with you to bring SAM's online presence to life. Please feel free to share any specific preferences or additional requirements you may have for the website.
Looking forward to the opportunity to work together.

Kind regards,
Luke H

---

### Q7 Think back to a scenario or situation in your own software development projects or work.

Reflecting on my portfolio project involving HTML/CSS using the Gibbs Reflective Cycle

- Description:

  - Our first significant assignment involved creating a portfolio website with HTML and CSS. The website needed to adhere to semantic guidelines, incorporate either flexbox or grid for layout, and consist of 5 connected pages. I included a Home page, About Me page, Blog page, Projects page, and Contact Me page. Additionally, there were 2 subpages for a blog post and a thank you page within my portfolio.

- Feelings:

  - I feel as though I did pretty well for my first attempt at making a website. I certainly was stressed about it and thought I was going to fail, but I kept pushing myself and adding more and more to my website and I’m happy with what it turned out like. I would make a few improvements given I had more coding experience:

    - Improvements:

      - Responsive Design: I would also improve the responsiveness of the website. I would have implemented more media types and different layouts like Grid on some pages and flexbox on the others.

      - Accessibility: I would pay more attention to ensure the website is more accessible and easy to use for all users, including those with disabilities.

      - Styling: Lastly, I would focus on adding more styling through the use of JavaScript. (Like a side Nav bar that you click to open).

- Evaluation of the Experience:

  - The good aspects were successfully creating a functional and visually appealing website from scratch, which helped in building my confidence and technical skills. The bad aspects were the initial stress and challenges in understanding some new language I had never written in before, and deciding how I want my website to look, which slowed down my progress initially.

- Analysis:

  - The stressful moments made a significant impact. They pushed me to problem-solve and learn, requiring me to re-watch the class videos and search for design ideas.

- Conclusion:

  - What I learned is the importance of planning and breaking down the work into manageable tasks, which helped in making the process less overwhelming.

- Action Plan:

  - In the future, I would:

    - Plan More Effectively: Create a better detailed plan with clear objectives to track progress better and reduce the amount of stress.

    - Seek Feedback: Talk with the teachers early in the process to get feedback (as i didnt).

    - Enhance Responsiveness: Prioritise testing on various devices and screen sizes to ensure a responsive design.

    - Advanced Styling: Use JavaScript for dynamic elements and interactivity to enhance the design of my webpage.

### References:

- Gibbs relfection

  - Main, P. (2023). Gibbs’ Reflective Cycle. [online] Structural Learning. Available at: https://www.structural-learning.com/post/gibbs-reflective-cycle.

  - The University of Edinburgh (2020). Gibbs’ Reflective Cycle. [online] The University of Edinburgh. Available at: https://www.ed.ac.uk/reflection/reflectors-toolkit/reflecting-on-experience/gibbs-reflective-cycle

---

### Q8 A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops.

- Meetup Groups: Join IT-related meetup groups in your area or online. Meetup.com has a variety of tech-focused groups where you can talk with professionals, share knowledge, and build connections within the tech community.

- Online Training Platforms: Enrol in online training platforms like Udemy, or LinkedIn Learning to improve skills and connect with instructors and peers in the IT industry. Participate in discussion forums, live Q&A sessions, and networking events.

- LinkedIn Networking: Participate in IT-related discussions on LinkedIn groups, connect with professionals, and engage with industry leaders. Utilise LinkedIn Events to find virtual networking opportunities such as webinars, panel discussions, and online workshops.

- Social Media Platforms: Create social accounts for my coding journey to showcase what I'm learning and how I am progressing. For instance, the 100-day coding challenge.

- Coder Academy Discord: Talk with other students and teachers, go to events that have been sent in the chat, or organise meet-ups.

### References to different outlined websites above:

- https://au.linkedin.com/

- https://www.meetup.com/

- https://www.udemy.com/

---

### Q9 Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.

- Generating Content: These models can assist in generating written content for reports by providing suggestions, summaries, or even full paragraphs based on the input provided. This can save time and help in generating more diverse content efficiently.

- Proofreading and Editing: Language models can also help in proofreading and editing written work by identifying grammar mistakes, suggesting alternative word choices, and improving overall readability, which is crucial for technical reports and documentation.

- Technical Assistance: For software projects, language models can aid in explaining complex technical concepts in simpler terms, assisting in writing clean and concise code documentation, and even providing solutions or troubleshooting tips for coding issues.

- Enhancing Communication: These technologies can improve communication within a team by assisting in generating responses to queries, clarifying technical jargon, and facilitating smoother collaboration on projects.

- Research and Information Retrieval: ChatGPT and similar models can fetch relevant information quickly, aiding in research for reports or finding solutions to technical problems in software projects by parsing through vast amounts of data.

### References:

- Eurotechconseil (2023). What is Chatgpt ? Unlock New Ways of Language Learning! [online] Eurotechconseil. Available at: https://www.eurotechconseil.com/en/blog/benefits-of-using-chatgpt/.

- Kanade, V. (2023). ChatGPT Characteristics, Uses, and Alternatives | Spiceworks. [online] Spiceworks. Available at: https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-chatgpt/.

---

### Q10 Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.

Legal Impacts:

- Intellectual Property Rights: Concerns about intellectual property rights if the generated content infringes on copyrighted material.

- Data Privacy: Storing and processing data using such models may raise privacy concerns, especially if confidential or sensitive information is involved.

- Liability: There may be liability issues if the output generated by the model is inaccurate or causes harm in any way.

Ethical Impacts:

- Bias: Language models can produce biased answers based on the data they are trained on, leading to potential issues of discrimination in written works or software projects.

- Misinformation: These models can generate false information, leading to ethical concerns if not validated and fact-checked.

- Transparency: Ensuring transparency in the use of these technologies is crucial to maintain trust and ethical standards in reporting and software development.

### References:

- Hua, S., Jin, S. and Jiang, S. (2023). The Limitations and Ethical Considerations of ChatGPT. Data intelligence, 6(1), pp.1–38. doi:https://doi.org/10.1162/dint_a_00243.

- Khurram, M. (2023). Ethical Considerations of Using ChatGPT in Software Development. [online] Tech Lead Hub. Available at: https://medium.com/tech-lead-hub/ethical-considerations-of-using-chatgpt-in-software-development-cff577427867.

- Podrecki, T.K., Wachowska, P.-A. and Ręgorowicz, M. (2023). ChatGPT in practice - major legal issues. [online] Lexology. Available at: https://www.lexology.com/library/detail.aspx?g=33bf4b4f-ffd9-4bf1-bfc1-7c790d86a22f.

---

### Q11 Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

Soft Skills:

- Communication:

  - Verbal and Written Communication: Clear and concise communication is essential for ideas, discussing requirements, and collaborating with team members and stakeholders. Effective communication helps in avoiding misunderstandings and ensures everyone is on the same page.

  - Active Listening: Actively listening to colleagues, clients, and users ensures that all perspectives are considered, leading to better decision-making and problem resolution.

- Teamwork and Collaboration:

  - Collaboration: Working well with others is critical in software development, which often involves working in cross-functional teams. Collaborating can lead to more solutions and a more well functioning work environment.

  - Conflict Resolution: The ability to manage and resolve conflicts is vital for maintaining a productive and positive working environment.

- Problem-Solving:

  - Analytical Thinking: Breaking down complex problems into manageable parts and systematically addressing each part, leads to more efficient solutions.

  - Creativity: Thinking outside the box can lead to innovative solutions that might not be obvious.

- Adaptability:

  - Flexibility: Being able to adjust to new tools, technologies, and methodologies is important in the fast-paced tech industry.

  - Resilience: The ability to bounce back from setbacks and continue working towards a goal is crucial, as development projects often encounter unexpected challenges.

Hard Skills:

- Programming Languages:

  - Proficiency in Languages such as Python, JavaScript, or C++: Learning one or more of these programming languages is fundamental for developing software. Each language has its strengths and is suited to different types of projects.

  - Proficient in Markup languages such as HTML, HTML5 or XML to handle back-end web development, and the use of CSS for front-end

- Software Development Methodologies:

  - Agile and Scrum: Understanding and implementing Agile methodologies can improve productivity and team collaboration. Scrum, a subset of Agile, focuses on iterative progress through sprints, allowing teams to deliver functional segments of the software frequently.

- Version Control Systems:

  - Git: Knowledge of version control systems like Git is essential for managing code changes, collaborating with other developers, and maintaining the history of codebase modifications.

- Development Tools:

  - IDEs and Editors: Proficiency in using Integrated Development Environments (IDEs) like Visual Studio Code or Jetbrains can improve productivity and code quality.

  - Debugging Tools: Using debugging tools effectively to identify and fix issues in the codebase is crucial for maintaining high-quality software.

- Database Management:
  - SQL and NoSQL Databases: Understanding how to design, implement, and query databases is fundamental for developing applications that handle data. Proficiency in both SQL (e.g., MySQL, PostgreSQL) and NoSQL (e.g., MongoDB, Cassandra) databases can be particularly valuable.

### Reference:

- Codemotion (2023). Trending Hard Skills and Soft Skills In Software Development. [online] Codemotion Magazine. Available at: https://www.codemotion.com/magazine/it-careers/trending-hard-skills-and-soft-skills-in-software-development/.

- Jennifer Herrity (2021). Adaptability Skills: Definition and Examples | Indeed.com. [online] www.indeed.com. Available at: https://www.indeed.com/career-advice/career-development/adaptability-skills.

- Phoenix, U. of (2023). Hard skills vs. soft skills: What they are and why both matter. [online] Professional Development Blog | University of Phoenix. Available at: https://www.phoenix.edu/professional-development/blog/hard-skills-vs-soft-skills-what-they-are-and-why-both-matter/.

- www.ironhack.com. (2023). Soft Skills vs Hard Skills: What Do Tech Recruiters Want? [online] Available at: https://www.ironhack.com/us/blog/soft-skills-vs-hard-skills-what-do-tech-recruiters-want.

---

### Q12 Explain multiple roles or job positions that would be found in a medium-sized software development company.

- Software Developer/Engineer:

  - Software developers are responsible for designing, coding, testing, and maintaining software applications. They work closely with the development team to understand project requirements and deliver high-quality code to meet those requirements.

- Project Manager:

  - Project managers oversee the planning, execution, and delivery of software projects. They are responsible for coordinating tasks, managing resources, and ensuring that projects are completed on time and within budget. Project managers also act as a liaison between the development team and stakeholders.

- Quality Assurance (QA):

  - QA engineers focus on testing software applications to identify bugs, issues, and areas for improvement. They develop test plans, execute test cases, and work to ensure that software products meet quality standards before release.

- UX/UI Designer:

  - UX/UI designers are responsible for creating intuitive and visually appealing user interfaces for software applications. They focus on enhancing the user experience by designing interfaces that are easy to navigate, visually pleasing, and functional.

- Systems Architect:

  - Systems architects design the overall structure of software systems, including hardware and software components. They work to create scalable and efficient systems that meet the needs of the software projects being developed.

- Database Administrator:

  - Database administrators are responsible for managing and maintaining databases that support software applications. They ensure data integrity, security, and performance within the database system.

- DevOps Engineer:

  - DevOps engineers focus on streamlining the development and deployment process through automation, collaboration, and communication between development and operations teams. They work to improve the speed and quality of software delivery.

- Technical Support Specialist:
  - Technical support specialists provide assistance to end-users of software applications. They troubleshoot issues, provide technical guidance, and ensure that users can effectively use the software products.

### References:

- CA and States (2021). Software Development Roles and Responsibilities in Outsourcing | QArea. [online] Software Development Company. Available at: https://qarea.com/blog/software-development-roles-and-responsibilities-in-outsourcing.

- Ivanova, A. (2023). 11 Key Roles in a Software Development Team ᐈ StaffingPartner. [online] StaffingPartner. Available at: https://staffingpartner.net/blog/key-roles-in-a-software-development-team/.

- Ovcharenko, S. (2022). 10 Key Roles in Software Development Team & Their Responsibilities. [online] Alcor BPO. Available at: https://alcor-bpo.com/10-key-roles-in-a-software-development-team-who-is-responsible-for-what/.

- Shashkina, V. (2022). Software Development Team Structure: Roles & Responsibilities. [online] ITRex. Available at: https://itrexgroup.com/blog/software-development-team-structure/.

---

### Extra References

https://www.grammarly.com/ (To help with grammar, spell checks and formatting)

https://www.mybib.com/ (To help with creating harvard style refrences)
