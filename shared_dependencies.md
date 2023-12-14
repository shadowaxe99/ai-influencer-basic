```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Agent Hierarchical Structure</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div id="hierarchy">
        <section id="executive-layer">
            <h1>Executive Layer</h1>
            <article id="cio">
                <h2>Chief Influencer Officer (CIO)</h2>
                <ul>
                    <li>Sets overall strategy for influencer growth and branding.</li>
                    <li>Makes high-level decisions regarding partnerships and deals.</li>
                </ul>
            </article>
            <article id="ai-legal-advisor">
                <h2>AI Legal Advisor</h2>
                <ul>
                    <li>Ensures all contracts and deals abide by legal standards.</li>
                    <li>Provides advice on intellectual property and usage rights.</li>
                </ul>
            </article>
        </section>
        <section id="management-layer">
            <!-- Similar structure for other roles -->
        </section>
        <!-- Additional sections for other layers -->
    </div>
    <script src="js/script.js"></script>
</body>
</html>
```

```css
/* css/style.css */
body {
    font-family: Arial, sans-serif;
}

#hierarchy {
    width: 80%;
    margin: 0 auto;
}

section {
    margin-bottom: 20px;
}

h1, h2 {
    color: #333;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background-color: #f0f0f0;
    margin: 5px 0;
    padding: 10px;
    border-radius: 5px;
}
```

```javascript
// js/script.js
document.addEventListener('DOMContentLoaded', function() {
    // Code to manipulate the DOM or handle events can go here
});
```