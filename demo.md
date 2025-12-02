---

marp: true
theme: default
paginate: true
title: "Custom Styled Presentation"
transition: slide

---

<style>
  blockquote {
    font-style: italic;
  }
  section {
    background-image: url('images/bg_img.jpg');
    background-repeat: no-repeat;
    background-position: top 20px right 20px;
    background-size: 80px auto;
  }
</style>
<!-- Slide 1 -->
# Product Documentation

Welcome to the product documentation presentation for our software!

---

<!-- Slide 2 -->
## Your Email

For any questions, feel free to reach out to us at:

**23f3000795@ds.study.iitm.ac.in**

---

<!-- Slide 3 -->
## Custom Theme and Styling

In this slide, we will demonstrate custom theme and styling for Marp.

### Example Custom Styling

```css
section {
  font-family: "Arial", sans-serif;
  color: #333;
}

h1 {
  color: #2c3e50;
}

h2 {
  color: #34495e;
}
```

---

<!-- Slide 5 -->
## Algorithmic Complexity
Here is an example of an algorithmic complexity:
$$
O(n \log n) 
$$

This means the time complexity of the algorithm grows at a rate of $n \log n$.

---

<!-- Slide 6 -->

![bg](images/bg_img.jpg)

---

<!-- Slide 6 -->
Core Capabilities
<div class="tiled-content"> <div class="tile"> <div class="icon"><i class="fa-solid fa-shield-halved"></i></div> <h3>Secure</h3> <p>Enterprise-grade encryption (AES-256) at rest and in transit ensures your data never leaks.</p> </div> <div class="tile"> <div class="icon"><i class="fa-solid fa-bolt"></i></div> <h3>Performant</h3> <p>Low-latency data pipelines processing millions of events per second with sub-millisecond overhead.</p> </div> <div class="tile"> <div class="icon"><i class="fa-solid fa-chart-line"></i></div> <h3>Scalable</h3> <p>Auto-scaling infrastructure that grows elastically with your user base and traffic spikes.</p> </div> </div>

---

<!-- Slide 7 -->
Configuration Parameters
<div class="table-container"> <table> <thead> <tr> <th>Parameter</th> <th>Type</th> <th>Default</th> <th>Description</th> </tr> </thead> <tbody> <tr> <td>timeout_ms</td> <td>Integer</td> <td>5000</td> <td>Maximum time to wait for a response before aborting.</td> </tr> <tr> <td>retries</td> <td>Integer</td> <td>3</td> <td>Number of automatic retry attempts for failed requests.</td> </tr> <tr> <td>auth_mode</td> <td>String</td> <td>'bearer'</td> <td>Authentication strategy: 'bearer', 'basic', or 'api_key'.</td> </tr> <tr> <td>debug</td> <td>Boolean</td> <td>false</td> <td>Enable verbose logging for troubleshooting integration issues.</td> </tr> </tbody> </table> </div>